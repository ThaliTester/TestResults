#### Test 832760828839a22_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-31 11:29:05.377  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 11:29:05.377  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:29:05.377  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:29:05.377  1015  1027 D BatteryService: stay LED for fully charged
08-31 11:29:05.377  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 11:29:05.377  1015  1015 I MotionRecognitionService: Plugged
08-31 11:29:05.387  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
08-31 11:29:05.387  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 11:29:05.387  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 11:29:05.387  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 11:29:05.387  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-31 11:29:05.397  3181  3181 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:29:05.397  3181  3283 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:29:05.407  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 11:29:05.407  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 11:29:05.407  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 11:29:05.407  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 11:29:05.417  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-31 11:29:06.227  6725  6725 D AndroidRuntime: 
08-31 11:29:06.227  6725  6725 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 11:29:06.237  6725  6725 D AndroidRuntime: CheckJNI is OFF
08-31 11:29:06.237  6725  6725 D AndroidRuntime: readGMSProperty: start
08-31 11:29:06.237  6725  6725 D AndroidRuntime: readGMSProperty: already setted!!
08-31 11:29:06.237  6725  6725 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 11:29:06.237  6725  6725 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 11:29:06.237  6725  6725 D AndroidRuntime: readGMSProperty: end
08-31 11:29:06.237  6725  6725 D AndroidRuntime: addProductProperty: start
08-31 11:29:06.317   290   290 E SMD     : DCD OFF
08-31 11:29:06.377  6725  6725 E AffinityControl: AffinityControl: registerfunction enter
08-31 11:29:06.407  6725  6725 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 11:29:06.427  1015  1709 E PersonaManagerService: inState():  stateMachine is null !!
08-31 11:29:06.427  1015  1709 I PersonaManagerService: PersonaId don't exist
08-31 11:29:06.427  1015  1709 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 11:29:06.427  1015  1709 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 11:29:06.447  1015  1709 W ActivityManager: mDVFSHelper.acquire()
08-31 11:29:06.447   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-31 11:29:06.447   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-31 11:29:06.457  1015  1709 D FocusedStackFrame: Set to : 0
08-31 11:29:06.467  1015  1709 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:06.467  1015  1709 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:06.467  1015  1709 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:06.467  1015  1709 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:06.477  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 11:29:06.477  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 11:29:06.477  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 11:29:06.477  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 11:29:06.477   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-31 11:29:06.477  6736  6736 E Zygote  : MountEmulatedStorage()
08-31 11:29:06.477  6736  6736 E Zygote  : v2
08-31 11:29:06.477  6736  6736 I libpersona: KNOX_SDCARD checking this for 10171
08-31 11:29:06.487  6736  6736 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:06.487  6736  6736 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:06.487  1015  1709 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6736 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:29:06.487  1015  1709 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 11:29:06.487  1015  1709 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 11:29:06.487  6736  6736 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:06.487  6736  6736 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 11:29:06.497  1015  1709 D InputDispatcher: Focused application set to: xxxx
08-31 11:29:06.497  1015  1709 D InputDispatcher: Focus left window: 1482
08-31 11:29:06.497  6725  6725 D AndroidRuntime: Shutting down VM
08-31 11:29:06.517  6736  6736 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:06.517  6736  6736 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:06.527  1015  1499 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-31 11:29:06.527  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 11:29:06.527  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 11:29:06.527  1015  1015 V ActivityManager: Display changed displayId=0
08-31 11:29:06.527  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 11:29:06.547  1015  1499 D PersonaManager: isKioskContainerExistOnDevice
08-31 11:29:06.567  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-31 11:29:06.577   257  1037 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-31 11:29:06.577   257   442 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-31 11:29:06.587  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{147816fe token=android.os.BinderProxy@1fbc2e65 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 11:29:06.587  1482  1482 D Launcher: onTrimMemory. Level: 20
08-31 11:29:06.697  6736  6736 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-31 11:29:06.707  6725  6725 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 11:29:06.737  6736  6736 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 7506-7509)
,08-31 11:29:06.737  6736  6736 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 11:29:06.757  6736  6736 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19830a16}
,08-31 11:29:06.757  6736  6736 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 11:29:06.757  6736  6736 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:29:06.797  6736  6736 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-31 11:29:06.797  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:29:06.807  6736  6736 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 11:29:06.837  6736  6736 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 11:29:06.837  6736  6736 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 11:29:06.837  6736  6736 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 11:29:06.837  6736  6736 I Adreno-EGL: Local Branch: 
08-31 11:29:06.837  6736  6736 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 11:29:06.837  6736  6736 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 11:29:06.837  6736  6736 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 11:29:06.907  6736  6736 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:29:06.927  6736  6736 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-31 11:29:06.927  6736  6736 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-31 11:29:06.927  6736  6736 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-31 11:29:06.927  6736  6736 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-31 11:29:07.047  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:29:07.057  1015  1041 W ActivityManager: Activity pause timeout for ActivityRecord{4b93638 u0 com.test.thalitest/.MainActivity t2},
,08-31 11:29:07.057  6736  6736 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 11:29:07.067  6736  6736 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-31 11:29:07.067  6736  6736 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-31 11:29:07.077  6736  6736 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 11:29:07.087  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:29:07.087  6736  6736 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:29:07.177  6736  6777 D OpenGLRenderer: Render dirty regions requested: true
,08-31 11:29:07.177  1015  1510 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-31 11:29:07.177  1015  1510 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 11:29:07.177  1015  1510 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-31 11:29:07.177  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 11:29:07.177  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 11:29:07.187  6736  6764 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-31 11:29:07.187  6736  6736 V ActivityThread: updateVisibility : ActivityRecord{3df14b76 token=android.os.BinderProxy@d8b9a9b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 11:29:07.197  6736  6736 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-31 11:29:07.197  6736  6736 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-31 11:29:07.217   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-31 11:29:07.227  1015  1592 D InputDispatcher: Focus entered window: 6736,
08-31 11:29:07.227  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 11:29:07.227  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 11:29:07.227  6736  6736 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-31 11:29:07.227  6736  6777 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 11:29:07.237  6736  6777 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-31 11:29:07.237  6736  6777 D OpenGLRenderer: Enabling debug mode 0
,08-31 11:29:07.257  1015  1028 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 11:29:07.257  1177  1177 I StatusBar: Icon Only
,08-31 11:29:07.257  1177  1177 D PanelView: There is/are notification(s) 
,08-31 11:29:07.267  1015  6781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 11:29:07.267  1015  1046 I ActivityManager: Displayed Component not be shown by security: +715ms (total +808ms)
,08-31 11:29:07.267  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4b93638 u0 com.test.thalitest/.MainActivity t2} time:108049
08-31 11:29:07.267  1015  1046 W ActivityManager: mDVFSHelper.release()
,08-31 11:29:07.277  6736  6736 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
08-31 11:29:07.277  6736  6736 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d8b9a9b time:108055
,08-31 11:29:07.277   257  1975 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-31 11:29:07.277   257  1037 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-31 11:29:07.287  1878  1878 I SamsungIME: getCurrentCandidateView
,08-31 11:29:07.387  6736  6736 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6736
,08-31 11:29:07.407  1878  1878 D SamsungIME: Dismiss ExpandCandiate
,08-31 11:29:07.557  1878  1878 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 11:29:07.577  1015  1309 E Watchdog: !@Sync 3
,08-31 11:29:07.587  6736  6736 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 11:29:07.597  1878  1878 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 11:29:07.607  1878  1878 I SamsungIME: KeybaordView init() : load resources
,08-31 11:29:07.627  1878  1878 I SamsungIME: getCurrentKeyboard
,08-31 11:29:07.627  1878  1878 I SamsungIME: getTextKeyboard
,08-31 11:29:07.647  1878  1878 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 11:29:07.677  6736  6783 D jxcore_app_log: JniHelper::setJavaVM(0xb84782b0), pthread_self() = -1197455208
,08-31 11:29:07.677  6736  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 11:29:07.677  6736  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 11:29:07.677  6736  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 11:29:07.677  6736  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 11:29:07.677  6736  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 11:29:07.677  6736  6783 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b992d7c added. We now have 1 listener(s)
,08-31 11:29:07.687  6736  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-31 11:29:07.687  6736  6783 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 11:29:07.687  6736  6783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:29:07.687  6736  6783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 11:29:07.697  6736  6783 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d44608b added. We now have 1 listener(s)
,08-31 11:29:07.697  6736  6783 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:07.697  6736  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:29:07.697  6736  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 11:29:07.697  6736  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 11:29:07.697  6736  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 11:29:07.697  6736  6783 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 11:29:07.697  6736  6783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:07.707  6736  6783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-31 11:29:07.717  6736  6783 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 11:29:07.717  6736  6783 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:07.717  6736  6783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:07.717  6736  6783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:07.717  6736  6783 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:07.717  6736  6783 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:07.717  6736  6783 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:07.717  6736  6783 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:07.717  6736  6783 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:07.717  6736  6783 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 11:29:07.717  6736  6783 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:07.717  6736  6783 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 11:29:07.717  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:07.717  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:07.747  6736  6736 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 11:29:08.247  6736  6790 W jxcore-log: Initializing JXcore engine
08-31 11:29:08.257  6736  6790 W jxcore-log: JXcore engine is ready
,08-31 11:29:08.317  1981  1981 E audit   : type=1400 msg=audit(1472635748.317:205): avc:  denied  { ioctl } for  pid=6790 comm="Thread-1245" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2069 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-31 11:29:08.317  1981  1981 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:08.317  1981  1981 E audit   : type=1300 msg=audit(1472635748.317:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9fc448f8 items=0 ppid=308 ppcomm=main pid=6790 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1245" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 11:29:08.317  1981  1981 E audit   : type=1320 msg=audit(1472635748.317:205): 
,08-31 11:29:08.327  6736  6790 W jxcore-log: Starting JXcore engine
,08-31 11:29:08.337   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-31 11:29:08.337   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-31 11:29:08.437  6736  6790 W jxcore-log: Platform android
08-31 11:29:08.437  6736  6790 W jxcore-log: 
08-31 11:29:08.437  6736  6790 W jxcore-log: Process ARCH arm
08-31 11:29:08.437  6736  6790 W jxcore-log: 
,08-31 11:29:08.637  6736  6790 I jxcore-log: JXcore Cordova bridge is ready!
08-31 11:29:08.637  6736  6790 I jxcore-log: 
,08-31 11:29:08.637  6736  6790 W jxcore-log: JXcore engine is started
,08-31 11:29:08.647  6736  6783 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 11:29:08.647  6736  6736 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 11:29:09.317   290   290 E SMD     : DCD OFF
,08-31 11:29:11.507  1015  1048 I PowerManagerService: [PWL] Off : 50s ago,
,08-31 11:29:11.597  1015  3371 D SSRM:n  : SIOP:: AP = 330
,08-31 11:29:12.317   290   290 E SMD     : DCD OFF
,08-31 11:29:13.337   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:14.337   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:15.207  5634  5634 D FactoryTest: Not factory mode
,08-31 11:29:15.207  5634  5634 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-31 11:29:15.207  5634  5634 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-31 11:29:15.207  5634  5634 D MTPRx   : still no open session command from host, so toast
,08-31 11:29:15.217  5634  5634 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-31 11:29:15.217  5634  5634 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-31 11:29:15.217  5634  5634 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115995
,08-31 11:29:15.217  1015  1490 E PersonaManagerService: inState():  stateMachine is null !!
,08-31 11:29:15.217  1015  1490 I PersonaManagerService: PersonaId don't exist
08-31 11:29:15.217  1015  1490 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-31 11:29:15.227  1015  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 11:29:15.227  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:15.227  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:15.227  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-31 11:29:15.227  1015  1490 W ActivityManager: mDVFSHelper.acquire()
,08-31 11:29:15.247  1015  1490 D PersonaManager: isKioskContainerExistOnDevice
,08-31 11:29:15.247  1015  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 11:29:15.247  1015  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 11:29:15.247  1015  1490 D InputDispatcher: Focused application set to: xxxx
,08-31 11:29:15.247  1015  1490 D InputDispatcher: Focus left window: 6736
,08-31 11:29:15.257  5634  5634 E MTPRx   : started activity for popup
,08-31 11:29:15.257  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 11:29:15.257  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 11:29:15.287  5634  5634 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-31 11:29:15.287  5634  5634 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-31 11:29:15.287  5634  5634 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-31 11:29:15.287  5634  5634 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:29:15.287  5634  5634 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 11:29:15.287  5634  5634 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:29:15.307  5634  5634 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-31 11:29:15.317  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 11:29:15.317  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 11:29:15.317  1015  1027 D InputDispatcher: Focused application set to: xxxx
,08-31 11:29:15.317  1015  1027 D InputDispatcher: Focus entered window: 6736
,08-31 11:29:15.317   290   290 E SMD     : DCD OFF
,08-31 11:29:15.327  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 11:29:15.327  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 11:29:15.327  1015  1499 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 11:29:15.327  1015  1499 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@4d2d86b attribute=null, token = android.os.BinderProxy@3a7a5a7b
,08-31 11:29:15.337   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:15.367  5634  5634 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-31 11:29:15.377  5634  5634 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-31 11:29:15.377  5634  5634 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-31 11:29:15.407  6736  6736 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 11:29:15.407  6736  6736 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-31 11:29:15.407  6736  6736 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 11:29:15.407  6736  6736 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-31 11:29:15.407  1015  1594 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-31 11:29:15.407  1015  1594 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 11:29:15.407  1015  1594 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-31 11:29:15.407  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 11:29:15.407  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 11:29:15.417  6736  6736 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 11:29:15.417  6736  6736 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-31 11:29:15.427  6736  6736 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@182c87 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@16eec51c, 16908290=android.view.AbsSavedState$1@16eec51c}, android:focusedViewId=100}]}]
,08-31 11:29:15.427  6736  6736 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-31 11:29:15.427  6736  6736 V ActivityThread: updateVisibility : ActivityRecord{3df14b76 token=android.os.BinderProxy@d8b9a9b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 11:29:15.427  6736  6736 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 11:29:15.427  6736  6736 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-31 11:29:15.427  6736  6736 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d8b9a9b time:116203
,08-31 11:29:15.447  1015  1480 D PersonaManager: isKioskContainerExistOnDevice
,08-31 11:29:15.447  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 11:29:15.447  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 11:29:15.447  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:29:15.447  1015  1028 D BatteryService: stay LED for fully charged
,08-31 11:29:15.447  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:29:15.457  1015  1015 I MotionRecognitionService: Plugged
,08-31 11:29:15.457  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:29:15.457  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 11:29:15.457  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:29:15.467  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 11:29:15.467  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:29:15.477  3181  3181 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 11:29:15.477  3181  3283 D HeadsetStateMachine: Disconnected process message: 10
,08-31 11:29:15.487  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 11:29:15.487  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 11:29:15.487  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 11:29:15.487  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 11:29:15.487  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-31 11:29:16.337   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:16.517  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 11:29:17.337   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:18.237  1015  1041 W ActivityManager: mDVFSHelper.release()
,08-31 11:29:18.327   290   290 E SMD     : DCD OFF,
,08-31 11:29:18.337   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-31 11:29:19.227  1015  1094 V AlarmManager: waitForAlarm result :4
,08-31 11:29:19.237  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-31 11:29:19.257  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-31 11:29:19.257  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-31 11:29:19.257  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-31 11:29:19.267  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-31 11:29:19.267  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 11:29:19.277  2006  2006 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-31 11:29:19.277  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-31 11:29:19.287  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,08-31 11:29:19.297  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:29:19.297  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-31 11:29:19.297  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,08-31 11:29:19.327  1015  1709 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:19.327  1015  1709 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-31 11:29:19.327  1015  1709 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:19.327  1015  1709 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:19.327  1015  1709 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:19.327  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:29:19.337  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:29:19.347  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:29:19.357  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-31 11:29:19.367  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 11:29:19.407  4779  4779 D ConnectivityManager: CallingUid : 10011, CallingPid : 4779
,08-31 11:29:19.407  1015  1709 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 11:29:19.407  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-31 11:29:19.407  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-31 11:29:19.407  1015  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-31 11:29:19.417  4779  6800 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 11:29:19.467  4779  6801 W DriveInitializer: Background init thread started
,08-31 11:29:19.497   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-31 11:29:19.497   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:19.497  4779  6801 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-31 11:29:19.597  4779  6801 W DriveInitializer: Background init thread ended
,08-31 11:29:19.607  2006  2006 I art     : Explicit concurrent mark sweep GC freed 57656(3MB) AllocSpace objects, 16(256KB) LOS objects, 39% free, 10MB/17MB, paused 1.240ms total 69.586ms
,08-31 11:29:19.627  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:19.627  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-31 11:29:19.627  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:19.627  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:19.627  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:19.647  1015  1379 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-31 11:29:19.647  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-31 11:29:19.667  1015  1213 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:19.667  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-31 11:29:19.667  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:19.667  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:19.667  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:19.697  4779  6809 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-31 11:29:19.697  4779  6809 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-31 11:29:19.717  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 11:29:19.757  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:19.757  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:29:19.757  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:19.957  1015  1448 I art     : Explicit concurrent mark sweep GC freed 35038(1866KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.402ms total 146.272ms
,08-31 11:29:19.967  1015  1213 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:19.967  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-31 11:29:19.967  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:19.967  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:19.967  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.007  1015  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:20.007  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-31 11:29:20.007  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:20.007  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.007  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.057  1015  1448 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:20.057  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.057  1015  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.057  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.117  1015  1592 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:20.127  1015  1592 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.127  1015  1592 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.127  1015  1592 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.197  1015  1510 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:20.197  1015  1510 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.197  1015  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.197  1015  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.207  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:20.207  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:20.207  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:20.207  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:20.217  6814  6814 E Zygote  : MountEmulatedStorage()
,08-31 11:29:20.217  6814  6814 E Zygote  : v2
08-31 11:29:20.217  6814  6814 I libpersona: KNOX_SDCARD checking this for 10011,
08-31 11:29:20.217  6814  6814 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:20.217  1015  1510 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6814 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-31 11:29:20.227  6814  6814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:20.227  6814  6814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:20.227  6814  6814 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:29:20.247  6814  6814 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:20.247  6814  6814 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:20.267  6814  6814 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-31 11:29:20.267  6814  6814 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 11:29:20.307  6814  6814 I MultiDex: VM with version 2.1.0 has multidex support
08-31 11:29:20.307  6814  6814 I MultiDex: install
08-31 11:29:20.307  6814  6814 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 11:29:20.337  6814  6814 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 11:29:20.407  6814  6814 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 11:29:20.407  6814  6814 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@121756b2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-31 11:29:20.407  6814  6814 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-31 11:29:20.417  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-31 11:29:20.417  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:20.427  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.427  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.427  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.437  6814  6814 D ChimeraCfgMgr: Reading stored module config
,08-31 11:29:20.447  1015  1448 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:20.447  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.457  1015  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.457  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.497  2006  2006 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=452b5dce-5a9b-416a-99e8-45fdae14e669
,08-31 11:29:20.547  6814  6833 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-31 11:29:20.547  1015  1480 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-31 11:29:20.547  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 11:29:20.547  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.547  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.547  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:20.547  6814  6814 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 11:29:20.547  6814  6814 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 11:29:20.547  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 11:29:20.547  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 11:29:20.567  1015  1213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:20.567  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.567  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.567  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.647   282   282 D WVCdm   : Instantiating CDM.
,08-31 11:29:20.647   282   686 I WVCdm   : CdmEngine::OpenSession
08-31 11:29:20.647   282   686 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-31 11:29:20.677   282   686 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-31 11:29:20.697   282   686 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-31 11:29:20.747  4224  5040 I art     : Explicit concurrent mark sweep GC freed 1421(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 684us total 20.845ms
,08-31 11:29:20.747   282   686 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-31 11:29:20.747   282   282 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-31 11:29:20.747   282   282 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-31 11:29:20.747   282   282 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-31 11:29:20.757   282   282 D WVCdm   : PrepareKeyRequest: nonce=1975337009
,08-31 11:29:20.777  6814  6825 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-31 11:29:20.777  6814  6825 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 11:29:20.777  6814  6825 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 11:29:20.777  6814  6825 I System.out: (HTTPLog)-Thread-1224-631032663: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 11:29:20.777  6814  6825 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 11:29:20.777   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:20.777   277  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 11:29:20.817  2006  2154 W GCoreFlp: No location to return for getLastLocation()
,08-31 11:29:20.827  6814  6825 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 11:29:20.827  6814  6825 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6814, getuid(): 10011
,08-31 11:29:20.857  1015  1593 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:20.857  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.867  1015  1593 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.867  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.867  1015  1510 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:20.867  1015  1510 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.867  1015  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.867  1015  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.877  1015  1213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:20.877  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.877  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:20.877  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:20.887  4779  6810 D UdcContextInitService: registered all accounts: true
,08-31 11:29:20.897  2006  2157 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 11:29:20.907  2006  2176 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-31 11:29:21.027  1015  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:21.027  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-31 11:29:21.027  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:21.027  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:29:21.027  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.127  6814  6825 I qtaguid : Untagging socket 30
,08-31 11:29:21.147  1015  1448 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:21.147  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:21.147  1015  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:29:21.147  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.207  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:21.207  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:21.207  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:21.207  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.307  1015  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:21.307  1015  1499 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:21.307  1015  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:21.307  1015  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.307  2006  6844 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-31 11:29:21.307  2006  6842 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-31 11:29:21.307  1015  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:21.307  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:21.307  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:21.307  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.327   290   290 E SMD     : DCD OFF,
,08-31 11:29:21.377  2006  2176 I art     : Explicit concurrent mark sweep GC freed 48381(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 11MB/18MB, paused 1.419ms total 87.810ms
,08-31 11:29:21.387  1015  1592 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:21.387  1015  1592 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:21.387  1015  1592 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:21.387  1015  1592 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.387  2006  6844 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-31 11:29:21.387  2006  6842 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-31 11:29:21.387  1015  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:21.397  1015  1499 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:21.397  1015  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:21.397  1015  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.397  1015  1379 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-31 11:29:21.397  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 11:29:21.407  1015  1379 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:21.407  1015  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:21.407  1015  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.417  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:21.417  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:21.417  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:21.417  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.417  2006  6844 E CommitToConfigurationOperation: Malformed snapshot token (size): ,
,08-31 11:29:21.417  2006  6842 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-31 11:29:21.417  2006  6842 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-31 11:29:21.427  2006  6842 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 11:29:21.487  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 11:29:21.487  6736  6790 I jxcore-log: 
,08-31 11:29:21.487  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 11:29:21.487  6736  6790 I jxcore-log: 
,08-31 11:29:21.497  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:21.497  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:21.497  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:21.497  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:21.497  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:21.497  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:21.497  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:21.497  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:21.507  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:21.507  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 11:29:21.507  6736  6790 I jxcore-log: 
,08-31 11:29:21.507  1015  1499 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 11:29:21.507  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 11:29:21.507  6736  6790 I jxcore-log: 
,08-31 11:29:21.567  6845  6845 I dex2oat : ----------------------------------------------------
08-31 11:29:21.567  6845  6845 I dex2oat : <SS>: S T A R T I N G . . .
08-31 11:29:21.567  6845  6845 I dex2oat : <SS>: Zip is absent. Canceled.
,08-31 11:29:21.567  6845  6845 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 11:29:21.577  1015  1712 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-31 11:29:21.587  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 11:29:21.587  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:21.587  1015  1712 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:21.587  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:21.637  1015  3371 D SSRM:n  : SIOP:: AP = 360,
,08-31 11:29:21.637  6845  6845 I dex2oat : dex2oat took 66.444ms (threads: 4),
08-31 11:29:21.637  2006  6842 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-31 11:29:21.637  2006  6842 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 11:29:21.637  2006  6842 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 11:29:21.637  2006  6842 I System.out: (HTTPLog)-Thread-277-931203565: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-31 11:29:21.647  2006  6842 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,08-31 11:29:21.647   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-31 11:29:21.647   277  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 11:29:21.647  6814  6825 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 11:29:21.647  6814  6825 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 11:29:21.647  6814  6825 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 11:29:21.647  6814  6825 I Adreno-EGL: Local Branch: 
08-31 11:29:21.647  6814  6825 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 11:29:21.647  6814  6825 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 11:29:21.647  6814  6825 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 11:29:21.657  2006  6842 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 11:29:21.657  2006  6842 I qtaguid : Tagging socket 69 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2006, getuid(): 10011
,08-31 11:29:21.707  2006  6842 I qtaguid : Tagging socket 72 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2006, getuid(): 10011
,08-31 11:29:21.757  1015  3388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 11:29:21.767  6814  6825 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 11:29:21.767  6814  6825 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 11:29:21.767  6814  6825 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 11:29:21.767  6814  6825 I Adreno-EGL: Local Branch: 
08-31 11:29:21.767  6814  6825 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 11:29:21.767  6814  6825 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 11:29:21.767  6814  6825 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 11:29:21.807  6814  6825 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 11:29:21.807  6814  6825 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 11:29:21.807  6814  6825 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 11:29:21.807  6814  6825 I Adreno-EGL: Local Branch: 
08-31 11:29:21.807  6814  6825 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 11:29:21.807  6814  6825 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 11:29:21.807  6814  6825 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 11:29:21.987  1015  1213 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 11:29:21.997  2006  6842 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 11:29:21.997  2006  6842 I qtaguid : Tagging socket 69 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2006, getuid(): 10011
,08-31 11:29:22.117  1015  1480 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 11:29:22.117  2006  6842 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 11:29:22.117  2006  6842 I qtaguid : Tagging socket 69 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 2006, getuid(): 10011
,08-31 11:29:22.177  2006  6812 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 11:29:22.187   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:22.187   277  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-31 11:29:22.187  2006  6812 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 11:29:22.187  2006  6812 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2006, getuid(): 10011
,08-31 11:29:22.217  2006  6812 I qtaguid : Tagging socket 75 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2006, getuid(): 10011
,08-31 11:29:22.267  1015  1379 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 11:29:22.267  6736  6790 I jxcore-log: Unit Test app is loaded
08-31 11:29:22.267  6736  6790 I jxcore-log: 
,08-31 11:29:22.277  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:22.277  6736  6790 I jxcore-log: 
,08-31 11:29:22.277  2006  6842 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 11:29:22.277  2006  6842 I qtaguid : Tagging socket 69 with tag 11065b5800000000{285629272,0} for uid -1, pid: 2006, getuid(): 10011
,08-31 11:29:22.277  6736  6736 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 11:29:22.287  6736  6790 D executeNativeTests: Running unit tests
,08-31 11:29:22.317   282   704 I WVCdm   : CdmEngine::CloseSession
,08-31 11:29:22.317   282   704 I WVCdm   : L3 Terminate.
,08-31 11:29:22.387  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:22.387  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 added. We now have 2 listener(s)
,08-31 11:29:22.387  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 11:29:22.387  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:22.387  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:22.387  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:22.387  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa added. We now have 2 listener(s)
08-31 11:29:22.387  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:22.387  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:29:22.397  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:22.397  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:22.397  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:22.397  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:22.397  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:22.397  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:22.397  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:22.397  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:22.397  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:22.397  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:22.397  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:22.397  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:22.397  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:29:22.397  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:22.397  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:22.407  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:22.407  6736  6790 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-31 11:29:22.407  6736  6790 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:29:22.407  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:29:22.407  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:22.407  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:22.407  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.407  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.407  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.407  2006  2176 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-31 11:29:22.407  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.407  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.407  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:22.407  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:22.407  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 removed from the list
08-31 11:29:22.407  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.407  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa removed from the list
08-31 11:29:22.407  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.407  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.407  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.407  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.407  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.407  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.407  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.407  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.407  6736  6790 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 11:29:22.407  2006  2176 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-31 11:29:22.417  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.417  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.417  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.417  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.417  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.417  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.417  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.417  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.417  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.417  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.417  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.417  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.417  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.417  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.417  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.417  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.417  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:29:22.417  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.417  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.417  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.417  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.417  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.417  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.417  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.417  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.417  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.417  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.417  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.417  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.417  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.417  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.427  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.427  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.427  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.427  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.427  6736  6790 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:29:22.427  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:22.427  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:22.427  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:22.427  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:22.427  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:22.427  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:22.427  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:22.427  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:22.427  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:22.437  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:22.437  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:22.437  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:22.437  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:22.437  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:22.437  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:22.437  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:29:22.437  2006  2176 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-31 11:29:21.096+0200, stopTime=2016-08-31 11:29:22.449+0200, duration=1353ms
08-31 11:29:22.437  2006  6859 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 11:29:22.437  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:29:22.437  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:22.447   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:22.447   277  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-31 11:29:22.447  2006  6859 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-31 11:29:22.447  2006  6859 I qtaguid : Tagging socket 76 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2006, getuid(): 10011
08-31 11:29:22.447  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:22.457  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:29:22.457  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:29:22.457  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-31 11:29:22.467  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage,
08-31 11:29:22.467  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:29:22.467  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 11:29:22.467  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:22.487  2006  6859 I qtaguid : Tagging socket 81 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2006, getuid(): 10011
,08-31 11:29:22.497  3181  3361 D BtGatt.GattService: registerClient() - UUID=892463db-ca1a-48db-937e-2bff3340f8ae
,08-31 11:29:22.547  3181  3275 D BtGatt.GattService: onClientRegistered() - UUID=892463db-ca1a-48db-937e-2bff3340f8ae, clientIf=6
,08-31 11:29:22.547  6736  6750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 11:29:22.547  3181  3189 D BtGatt.GattService: start scan with filters
,08-31 11:29:22.547  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:22.547  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 11:29:22.547  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:22.547  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:22.547  3181  3282 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:22.557  3181  3282 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:22.557  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:22.557  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:22.557  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:29:22.557  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:22.567  3181  3275 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:29:22.567  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.567  3181  3282 D BtGatt.ScanManager: allow scan with filters
08-31 11:29:22.567  3181  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:29:22.567  3181  3282 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6,
,08-31 11:29:22.567  3181  3275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 11:29:22.567  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.567  3181  3282 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 11:29:22.567  3181  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:29:22.567  3181  3275 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 11:29:22.567  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.567  6736  6790 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:29:22.567  3181  3275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 11:29:22.567  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.577  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:22.577  6736  6790 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:29:22.577  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.577  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:22.577  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.577  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:22.577  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:22.577  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:22.577  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:22.577  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:29:22.577  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:29:22.577  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:22.577  3181  3191 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:22.577  3181  3361 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:29:22.587  3181  3282 D BtGatt.ScanManager: filter size is 1
08-31 11:29:22.587  3181  3282 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 11:29:22.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 11:29:22.587  3181  3275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:29:22.587  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:22.587  3181  3282 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:29:22.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:22.587  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 11:29:22.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:22.587  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:22.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:22.587  3181  3275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 11:29:22.587  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:22.587  3181  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:29:22.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:22.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:22.587  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:29:22.597  3181  3275 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:29:22.597  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.597  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:22.597  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:29:22.597  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:22.597  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:22.597  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.597  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.597  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:22.597  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.597  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.597  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.597  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.597  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.597  6736  6790 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 11:29:22.597  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:22.607  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:22.607  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:22.607  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:22.607  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:22.607  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:22.607  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:22.607  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:22.607  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:22.607  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:22.607  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:22.607  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:22.607  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:22.607  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:29:22.607  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:22.607  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 11:29:22.607  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:22.607  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:22.617  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:29:22.617  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:22.617  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:22.617  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:22.617  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 11:29:22.617  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:22.627  3181  3189 D BtGatt.GattService: registerClient() - UUID=252804a8-60f3-4752-997b-aa5658ba0ba2
,08-31 11:29:22.677  3181  3275 D BtGatt.GattService: onClientRegistered() - UUID=252804a8-60f3-4752-997b-aa5658ba0ba2, clientIf=6
,08-31 11:29:22.677  6736  6750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 11:29:22.677  3181  3191 D BtGatt.GattService: start scan with filters
08-31 11:29:22.677  3181  3282 D BtGatt.ScanManager: handling starting scan,
08-31 11:29:22.677  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-31 11:29:22.677  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-31 11:29:22.677  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:22.677  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:29:22.677  3181  3275 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:29:22.677  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:22.677  3181  3282 D BtGatt.ScanManager: allow scan with filters
08-31 11:29:22.677  3181  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:29:22.677  3181  3282 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 11:29:22.677  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:22.677  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:22.677  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:22.677  3181  3275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 11:29:22.677  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.677  3181  3282 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:22.677  3181  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-31 11:29:22.677  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:22.677  3181  3275 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 11:29:22.677  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.677  6736  6790 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:29:22.687  3181  3275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:29:22.687  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.687  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.687  6736  6790 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:29:22.687  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.687  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:22.687  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.687  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:29:22.687  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:22.687  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:22.687  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:29:22.687  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:22.687  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:22.687  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:22.687  3181  3361 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:22.687  3181  3282 D BtGatt.ScanManager: filter size is 1
,08-31 11:29:22.687  3181  3282 D BtGatt.ScanManager: delete FilterIndex - 4
,08-31 11:29:22.697  3181  3189 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-31 11:29:22.697  3181  3275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:29:22.697  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.697  3181  3282 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:29:22.697  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:22.697  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 11:29:22.697  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:22.697  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 11:29:22.697  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:22.697  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:22.697  3181  3275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 11:29:22.697  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.707  3181  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:29:22.707  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 11:29:22.707  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:22.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:29:22.707  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:22.707  3181  3275 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:29:22.707  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:22.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.707  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.707  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:22.707  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:22.707  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.707  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.707  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.707  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.707  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:22.707  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:22.707  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.707  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:22.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.707  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
,08-31 11:29:22.707  6736  6790 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 11:29:22.717  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:22.717  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:22.717  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:22.717  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:22.717  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:22.717  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:22.717  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:22.717  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:22.717  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:22.717  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:22.717  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:22.717  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:22.727  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:22.727  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:22.727  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:22.727  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:22.727  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:22.727  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:22.727  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:29:22.727  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:22.737  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:22.737  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:22.737  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:22.737  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:22.737  3181  3361 D BtGatt.GattService: registerClient() - UUID=ea7ef3b5-2a3c-4f3d-a0e3-bd61eeb48d16
,08-31 11:29:22.787  3181  3275 D BtGatt.GattService: onClientRegistered() - UUID=ea7ef3b5-2a3c-4f3d-a0e3-bd61eeb48d16, clientIf=6
,08-31 11:29:22.787  6736  6750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-31 11:29:22.787  3181  3189 D BtGatt.GattService: start scan with filters
,08-31 11:29:22.787  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:22.787  3181  3282 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:22.787  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 11:29:22.787  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 11:29:22.787  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:29:22.787  3181  3275 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 11:29:22.787  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:22.787  3181  3282 D BtGatt.ScanManager: allow scan with filters
,08-31 11:29:22.787  3181  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:29:22.787  3181  3282 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-31 11:29:22.787  3181  3275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:29:22.787  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.787  3181  3282 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:22.787  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:22.787  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:22.787  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:29:22.787  3181  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:29:22.797  3181  3275 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:29:22.797  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:22.797  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:22.797  3181  3275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:29:22.797  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.807  6736  6790 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:29:22.807  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:22.807  6736  6790 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 11:29:22.807  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:22.807  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:22.807  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:22.807  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:22.807  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 11:29:22.807  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 11:29:22.807  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:22.807  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:29:22.807  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:29:22.807  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:22.807  3181  3191 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:22.817  3181  3282 D BtGatt.ScanManager: filter size is 1
,08-31 11:29:22.817  3181  3282 D BtGatt.ScanManager: delete FilterIndex - 5
,08-31 11:29:22.817  3181  3275 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:29:22.817  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:22.817  3181  3361 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:29:22.817  3181  3282 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:29:22.817  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:22.817  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:22.817  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:22.817  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:22.817  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:22.817  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:22.827  2006  6859 I qtaguid : Untagging socket 76
,08-31 11:29:22.827  3181  3275 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:29:22.827  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:22.827  3181  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:29:22.827  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:22.827  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:22.827  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:29:22.827  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:22.827  3181  3275 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:29:22.827  3181  3275 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:22.837  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:22.837  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:22.837  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:22.837  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:22.837  6736  6790 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:29:22.837  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.837  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:22.837  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.837  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.837  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:22.837  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.837  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.837  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.837  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.837  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.837  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.837  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.837  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:22.837  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.837  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.837  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
,08-31 11:29:22.837  6736  6790 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-31 11:29:22.837  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.837  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.837  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.837  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:22.837  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.837  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.837  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.837  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.837  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.837  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.837  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.837  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.837  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.837  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.837  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:22.847  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.847  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.847  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
,08-31 11:29:22.847  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-31 11:29:22.847  2006  2176 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-31 11:29:22.847  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.847  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.847  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.847  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.847  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.847  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.847  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.847  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.847  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.847  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.847  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.847  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.847  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.847  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.847  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.847  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.847  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.847  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
,08-31 11:29:22.847  6736  6790 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-31 11:29:22.857  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:22.857  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.857  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.857  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.857  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.857  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.857  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.857  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.857  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.857  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.857  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.857  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.857  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.857  6736  6790 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 11:29:22.857  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.857  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.857  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.857  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.857  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.857  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:22.857  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.857  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.857  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.857  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.857  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.857  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.857  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:29:22.857  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:29:22.857  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:29:22.857  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:22.857  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.857  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.857  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.857  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.857  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.857  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 11:29:22.857  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.857  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.857  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.857  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-31 11:29:22.857  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.857  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:29:22.857  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 11:29:22.857  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.857  6736  6790 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:22.857  6736  6790 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:29:22.857  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:29:22.867  6736  6790 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:22.867  6736  6790 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,0:2010:2010:2010:2010:2010]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:29:22.867  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:29:22.867  6736  6790 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 11:29:22.867  6736  6790 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:29:22.867  6736  6790 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 11:29:22.867  6736  6790 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:22.867  6736  6790 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:29:22.867  6736  6790 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 11:29:22.867  6736  6790 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:22.867  6736  6790 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:29:22.867  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 11:29:22.877  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 11:29:22.877  6736  6790 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 11:29:22.877  6736  6790 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:22.877  6736  6790 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 11:29:22.877  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.877  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation:, Should start/stop everything
08-31 11:29:22.877  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.877  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.877  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.877  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 11:29:22.877  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.877  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.877  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.877  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.877  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.877  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.877  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.877  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.877  6736  6790 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 11:29:22.877  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.877  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.877  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.877  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.877  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.877  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.877  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.877  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.877  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.877  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.877  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.877  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.877  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.877  6736  6790 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 11:29:22.877  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.877  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.877  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.877  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.877  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.877  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.877  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.887  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.887  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.887  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.887  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.887  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.887  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.887  6736  6869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1309
08-31 11:29:22.887  6736  6868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1309)
08-31 11:29:22.887  6736  6868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1309)
08-31 11:29:22.887  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.887  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.887  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.887  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.887  6736  6790 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 11:29:22.887  6736  6790 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 11:29:22.887  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:29:22.887  6736  6790 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 11:29:22.887  6736  6790 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:29:22.887  6736  6790 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 11:29:22.887  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:29:22.887  6736  6790 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 11:29:22.887  6736  6790 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:29:22.887  6736  6790 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:29:22.887  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:29:22.887  6736  6790 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 11:29:22.887  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.887  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.887  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.887  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.887  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.887  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.887  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.887  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.887  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.887  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.887  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.887  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.887  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.887  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.897  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.897  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.897  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.897  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.897  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.897  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.897  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.897  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.897  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.897  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.897  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.897  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.897  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.897  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.897  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.897  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.897  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.897  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.897  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:22.897  6736  6736 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:29:22.897  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.897  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:22.897  6736  6736 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:22.897  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.897  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.907  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:22.907  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:22.907  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:22.907  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:22.907  6736  6870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:29:22.907  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.907  6736  6870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:29:22.907  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.907  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.907  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.907  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.907  6736  6736 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 11:29:22.907  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.907  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.907  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.907  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.907  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.907  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.907  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.907  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.907  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.907  6736  6790 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 11:29:22.907  6736  6790 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:29:22.907  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:22.907  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.907  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.907  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.907  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.907  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.907  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.907  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.907  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.907  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.907  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.907  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.907  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.907  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.907  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.917  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.917  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.917  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.917  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.917  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.917  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.917  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.917  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.917  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.917  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.917  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.917  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.917  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:22.917  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:22.917  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:22.917  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.917  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.917  6736  6790 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e2195 not in the list
08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.917  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:22.917  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.917  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:22.917  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:22.917  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:22.917  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:22.917  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3aede2aa not in the list
08-31 11:29:22.917  6736  6790 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:29:22.917  6736  6790 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:29:22.917  6736  6790 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 11:29:22.917  6736  6790 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:29:22.917  6736  6790 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:29:22.917  6736  6790 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 11:29:22.917  6736  6790 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 11:29:22.927  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:22.927  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38eb017c added. We now have 2 listener(s)
08-31 11:29:22.927  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:22.927  6736  6790 D BluetoothAdapter: enable()
08-31 11:29:22.927  6736  6790 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 11:29:22.927  1015  1510 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 11:29:22.927  1015  1510 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:29:22.927  1015  1510 D SecContentProvider2: mCursor = null
08-31 11:29:22.927  1015  1510 D WifiService: setWifiEnabled: true pid=6736, uid=10171
08-31 11:29:22.927  1015  1510 W ActivityManager: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:22.937  1015  1510 W WifiService: Failed getting userId using ActivityManagerNative
08-31 11:29:22.937  1015  1510 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:22.937  1015  1510 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:22.937  1015  1510 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 11:29:22.937  1015  1510 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 11:29:22.937  1015  1510 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 11:29:22.937  1015  1510 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 11:29:22.937  1015  1510 D SettingsProvider: name = wifi_on
08-31 11:29:22.937  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:22.937  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@386b9a05 added. We now have 3 listener(s)
08-31 11:29:22.937  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:22.937  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:22.937  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@339c4a5a added. We now have 4 listener(s)
08-31 11:29:22.937  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:22.937  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:22.947  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33cf448b added. We now have 5 listener(s)
08-31 11:29:22.947  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:22.947  1015  1709 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 11:29:22.947  1015  1709 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:29:22.947  1015  1709 D SecContentProvider2: mCursor = null
08-31 11:29:22.947  1015  1709 D WifiService: setWifiEnabled: false pid=6736, uid=10171
08-31 11:29:22.947  1015  1709 D SettingsProvider: name = wifi_on
08-31 11:29:22.947  1015  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 11:29:22.957  1370  1370 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 11:29:22.957  1370  1370 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-31 11:29:22.957  1370  1370 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 11:29:22.957  1370  1370 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-31 11:29:22.957  6736  6790 D BluetoothAdapter: disable()
08-31 11:29:22.957  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:29:22.957  1015  1448 D SettingsProvider: name = bluetooth_on
,08-31 11:29:22.967  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:22.967  3181  3272 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-31 11:29:22.967  3181  3272 D BluetoothAdapterProperties: Setting state to 13
08-31 11:29:22.967  3181  3272 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:29:22.967  3181  3272 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:22.967  3181  3272 D BluetoothAdapterService: updateAdapterState state is 13
,08-31 11:29:22.967  1015  1379 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:22.967  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:22.977  1015  1379 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:22.977  1015  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:22.977  1015  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:22.977  3181  3272 D BluetoothAdapterService: Autoconnection is available ,
08-31 11:29:22.977  3181  3272 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 11:29:22.977  3181  3272 D BluetoothAdapterService: terminating service from this receiver
08-31 11:29:22.977  3181  3181 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-31 11:29:22.977  3181  3181 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d2798f1, channel: 19, state: LISTENING
08-31 11:29:22.977  1015  1593 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 11:29:22.977  3181  3181 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d2798f1, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a39b980, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@259ccb57mSocket: android.net.LocalSocket@26014644 impl:android.net.LocalSocketImpl@2daed062 fd:FileDescriptor[74]
08-31 11:29:22.977  3181  3181 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@26014644 impl:android.net.LocalSocketImpl@2daed062 fd:FileDescriptor[74]
08-31 11:29:22.977  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:22.977  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 11:29:22.977  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-31 11:29:22.977  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:22.977  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:22.977  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:22.977  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:22.977  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:22.977  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:22.977  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:22.977  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:22.977  1015  1593 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:22.977  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-31 11:29:22.977  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:22.977  3181  3272 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:29:22.977  3181  3272 D BluetoothAdapterProperties: mDiscovering is false
08-31 11:29:22.977  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:22.977  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:22.977  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:22.977  1015  1213 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 11:29:22.977  3181  3272 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 11:29:22.987  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:22.987  1015  1125 E WifiNative-wlan0: do suspend true
,08-31 11:29:22.987  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:22.987  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:29:22.987  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:22.987  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:29:22.987  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-31 11:29:22.997  1878  1878 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 11:29:22.997  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:22.997  1015  1594 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 11:29:22.997  1015  1510 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 11:29:22.997  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-31 11:29:22.997  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:22.997  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-31 11:29:22.997  3067  3067 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:23.007  1015  1594 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:23.007  1015  1594 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.007  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:23.007  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:23.007  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:23.007  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:23.007  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:23.007  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:23.007  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:23.007  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:23.007  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:23.007  3181  3275 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-31 11:29:23.007  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:23.007  3181  3275 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:29:23.007  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:23.007  1015  1594 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.007  1015  1594 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:23.007  1015  1594 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:23.007  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:23.007  3067  3067 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:23.007  1015  1709 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:29:23.007  1015  1709 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-31 11:29:23.017  1015  1709 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.017  1015  1709 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:23.017  1015  1709 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:23.017  3067  3067 D BluetoothPbap: Proxy object disconnected
08-31 11:29:23.017  3067  3067 D PbapServerProfile: Bluetooth service disconnected
08-31 11:29:23.017  3181  3272 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 11:29:23.017  3181  3272 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-31 11:29:23.017  3181  3272 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-31 11:29:23.017  3181  3272 E bt-btif : cmd socket is not created
,08-31 11:29:23.017  3181  3272 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 11:29:23.027  3181  5198 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 11:29:23.027  3181  3296 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-31 11:29:23.027  3181  3296 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 11:29:23.027  3067  3067 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:23.027  3181  3181 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4b8c5f3, channel: 5, state: LISTENING
08-31 11:29:23.027  3181  3181 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@4b8c5f3, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a192bb9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1bee82b0mSocket: android.net.LocalSocket@147f7529 impl:android.net.LocalSocketImpl@16ad90ae fd:FileDescriptor[76]
08-31 11:29:23.027  3181  3181 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@147f7529 impl:android.net.LocalSocketImpl@16ad90ae fd:FileDescriptor[76]
08-31 11:29:23.027  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:23.027  3181  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:23.027  3181  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:23.027  3181  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 11:29:23.037  3067  3067 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:23.037  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:23.037  3181  3181 I BtOppRfcommListener: stopping Accept Thread
08-31 11:29:23.037  3181  3181 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e8fce4f, channel: 12, state: LISTENING
08-31 11:29:23.037  3181  3181 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e8fce4f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1072827b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@343119dcmSocket: android.net.LocalSocket@af13ae5 impl:android.net.LocalSocketImpl@1ac609ba fd:FileDescriptor[81]
08-31 11:29:23.037  3181  3181 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@af13ae5 impl:android.net.LocalSocketImpl@1ac609ba fd:FileDescriptor[81]
,08-31 11:29:23.037  3181  5198 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 11:29:23.037  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:23.037  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 11:29:23.047  3181  3181 V BluetoothOppManager: cleanUp...
,08-31 11:29:23.047  1015  1592 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 11:29:23.047  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:23.047  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:23.047  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:23.047  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:23.067  6877  6877 E Zygote  : MountEmulatedStorage()
,08-31 11:29:23.067  6877  6877 E Zygote  : v2
08-31 11:29:23.067  6877  6877 I libpersona: KNOX_SDCARD checking this for 10055,
08-31 11:29:23.067  6877  6877 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:23.067  1015  1592 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6877 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,08-31 11:29:23.067  6877  6877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:23.077  6877  6877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:23.077  6877  6877 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:23.107  6877  6877 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:23.117  6877  6877 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:23.137  6877  6877 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 11:29:23.177  6877  6877 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 11:29:23.177  6877  6877 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
08-31 11:29:23.177  6877  6877 D UserAnalysis: Create SecureDbHelper
,08-31 11:29:23.187  6877  6877 D IntelligenceServiceApplication: onCreate()
,08-31 11:29:23.187  1015  1510 I ActivityManager: Killing 6441:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-31 11:29:23.197  1015  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 11:29:23.197  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:23.197  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:23.197  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:23.197  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:23.207  6877  6877 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 11:29:23.217  6895  6895 E Zygote  : MountEmulatedStorage(),
,08-31 11:29:23.217  6895  6895 E Zygote  : v2
,08-31 11:29:23.217  6895  6895 I libpersona: KNOX_SDCARD checking this for 10105
08-31 11:29:23.217  6895  6895 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:23.217  1015  1480 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6895 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,08-31 11:29:23.217  6895  6895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:23.217  1015  1594 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-31 11:29:23.217  6877  6877 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 11:29:23.227  6895  6895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:23.227  6895  6895 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 11:29:23.227  3181  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:23.227  3181  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:23.227  3181  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:29:23.227  3181  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:23.227  3181  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:23.227  3181  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:29:23.227  3181  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:23.227  3181  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:23.227  3181  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:29:23.227  3181  3296 W bt-btif : ag scb idx 1 not allocated
08-31 11:29:23.227  3181  3296 W bt-btif : ag scb idx 2 not allocated
08-31 11:29:23.227  3181  3296 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 11:29:23.227  3181  3331 I bt_userial_mct: exiting userial_read_thread
08-31 11:29:23.227  3181  3331 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 11:29:23.227  3181  3275 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 11:29:23.227  3181  3298 I bt_vendor: hw_epilog_process
08-31 11:29:23.227  3181  3275 D bt_userial_mct: userial_close
08-31 11:29:23.227  3181  3275 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-31 11:29:23.227  6877  6877 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 11:29:23.237  6895  6895 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:23.237  6895  6895 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:23.337   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:23.347   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:29:23.347   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:23.347  6895  6915 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:29:23.357   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:29:23.357   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:23.357  6895  6915 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:29:23.407  6736  6736 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:23.487  3181  3275 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-31 11:29:23.487  3181  3275 I bt_vendor: bluetooth satus is on
08-31 11:29:23.487  3181  3275 I bt_vendor: bt-vendor : resetting BT status
,08-31 11:29:23.487  3181  3275 I bt_vendor: Starting hciattach daemon
08-31 11:29:23.487  3181  3275 I bt_vendor: try to set false
,08-31 11:29:23.487  3181  3275 I bt_vendor: Starting hciattach daemon
,08-31 11:29:23.487  3181  3275 I bt_vendor: try to set false
,08-31 11:29:23.487  3181  3275 I bt_vendor: cleanup
,08-31 11:29:23.487  3181  3296 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
08-31 11:29:23.487  3181  3275 I GKI_LINUX: GKI_exit_task 0 done
,08-31 11:29:23.487  3181  3275 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-31 11:29:23.487  3181  3272 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 11:29:23.487  3181  3272 D BtConfig.SecureMode: isSecureModeOn:false
08-31 11:29:23.487  3181  3272 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 11:29:23.487  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 11:29:23.487  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 11:29:23.487  3181  3272 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 11:29:23.487  1015  1713 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:23.487  1015  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.487  1015  1713 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.487  1015  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:23.487  1015  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:23.497  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 11:29:23.497  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:23.497  3181  3181 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:29:23.497  3181  3272 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:23.497  3181  3181 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 11:29:23.497  3181  3181 D BtGatt.GattService: stop()
08-31 11:29:23.497  3181  3181 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 11:29:23.497  1015  1712 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:23.497  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.497  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.497  1015  1712 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:23.497  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:23.497  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:23.497  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 11:29:23.497  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:23.497  3181  3272 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:23.497  3181  3181 D HeadsetService: Received stop request...Stopping profile...
08-31 11:29:23.497  1015  1709 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:23.497  1015  1709 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.497  1015  1709 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:23.497  1015  1709 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:23.497  1015  1709 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:23.507  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 11:29:23.507  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 11:29:23.507  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:23.507  3181  3272 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 11:29:23.507  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 11:29:23.507  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:23.507  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.507  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.507  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:23.507  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:23.507  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:29:23.507  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 11:29:23.507  3067  3067 D HeadsetProfile: Bluetooth service disconnected
,08-31 11:29:23.507  3181  3272 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:29:23.507  1015  1510 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:23.507  1015  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.507  1015  1510 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.507  1015  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:23.507  1015  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:23.507  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-31 11:29:23.517  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 11:29:23.517  3181  3272 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:29:23.517  1015  1712 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:23.517  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 11:29:23.517  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.517  1015  1712 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:23.517  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:23.517  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 11:29:23.517  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:23.517  3181  3272 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:23.517  1015  1213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:23.517  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.517  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:23.517  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:23.517  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:23.517  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-31 11:29:23.517  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 11:29:23.527  3181  3272 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 11:29:23.527  1015  1592 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:23.527  1015  1592 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.527  1015  1592 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:23.527  1015  1592 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:23.527  1015  1592 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:23.527  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:23.527  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:29:23.527  3181  3272 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:23.527  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:23.527  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 11:29:23.527  3181  3272 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-31 11:29:23.527  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:29:23.527  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 11:29:23.527  3181  3272 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-31 11:29:23.527  3181  3272 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:29:23.527  3181  3272 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 11:29:23.527  3181  3272 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-31 11:29:23.527  3181  3181 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-31 11:29:23.527  3181  3181 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-31 11:29:23.527  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:23.537  3181  3272 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-31 11:29:23.537  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-31 11:29:23.537  3181  3181 D A2dpService: Received stop request...Stopping profile...
,08-31 11:29:23.537  3181  3287 D A2dpStateMachine: Exit Disconnected: -1
,08-31 11:29:23.537  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:23.537  3067  3067 D BluetoothA2dp: Proxy object disconnected
08-31 11:29:23.537  3067  3067 D A2dpProfile: Bluetooth service disconnected
,08-31 11:29:23.537  1015  1015 D BluetoothA2dp: Proxy object disconnected
,08-31 11:29:23.537  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 11:29:23.547  3181  3181 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 11:29:23.547  3181  3181 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 11:29:23.547  3181  3181 D HidService: Received stop request...Stopping profile...
,08-31 11:29:23.547  3181  3181 D HidService: Stopping Bluetooth HidService
,08-31 11:29:23.547  3181  3181 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:29:23.547  3181  3181 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 11:29:23.547  3181  3181 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-31 11:29:23.547  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:23.547  3181  3181 D HealthService: Received stop request...Stopping profile...
,08-31 11:29:23.547  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:23.547  3181  3181 D PanService: Received stop request...Stopping profile...
08-31 11:29:23.547  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:23.557  3067  3067 D BluetoothInputDevice: Proxy object disconnected
08-31 11:29:23.557  3067  3067 D HidProfile: Bluetooth service disconnected
08-31 11:29:23.557  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 11:29:23.557  3067  3067 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:29:23.557  3067  3067 D PanProfile: Bluetooth service disconnected
,08-31 11:29:23.557  6895  6895 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:23.557  6895  6895 D StrictMode: StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:23.557  6895  6895 D StrictMode: StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:23.557  6895  6895 D StrictMode: StrictMode policy violation; ~duration=182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:23.557  6895  6895 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:23.557  6895  6895 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:23.557  6895  6895 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:23.557  6895  6895 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:23.557  6895  6895 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:23.557  3181  3181 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:29:23.557  1015  1480 I ActivityManager: Killing 6337:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-31 11:29:23.567  2006  2006 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 11:29:23.567  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
08-31 11:29:23.567  3181  3181 D SapService: Received stop request...Stopping profile...
08-31 11:29:23.567  3181  3181 D SapService: Stopping Bluetooth SapService
08-31 11:29:23.567  3181  3181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
08-31 11:29:23.567  3067  3067 D BluetoothMap: Proxy object disconnected
08-31 11:29:23.567  3067  3067 D MapProfile: Bluetooth service disconnected
08-31 11:29:23.567  3067  3067 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 11:29:23.567  3067  3067 D SapProfile: Bluetooth service disconnected
08-31 11:29:23.567  2006  2006 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 11:29:23.567  3181  3181 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 11:29:23.577  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:23.577  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 11:29:23.577  3181  3181 D BluetoothA2dp: Proxy object disconnected
08-31 11:29:23.577  3181  3181 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-31 11:29:23.577  3181  3289 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 11:29:23.577  3181  3181 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:29:23.577  3181  3181 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 11:29:23.577  3181  3181 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 11:29:23.577  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:23.577  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:23.577  3181  3181 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-31 11:29:23.577  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:23.577  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:23.577  3181  3181 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:29:23.577  3181  3181 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:29:23.577  3181  3181 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 11:29:23.577  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:23.577  3181  3181 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:23.577  3181  3181 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:29:23.577  3181  3181 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:29:23.577  3181  3181 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 11:29:23.577  3181  3181 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:23.577  3181  3181 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-31 11:29:23.577  3181  3181 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-31 11:29:23.577  3181  3181 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 11:29:23.577  3181  3181 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-31 11:29:23.587  3181  3272 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:29:23.587  3181  3272 D BluetoothAdapterProperties: Setting state to 10
08-31 11:29:23.587  3181  3272 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:29:23.587  3181  3272 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:23.587  3181  3272 D BluetoothAdapterService: updateAdapterState state is 10
08-31 11:29:23.587  3181  3272 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:23.587  3067  6873 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:29:23.587  3181  3272 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 11:29:23.587  3181  3272 I BluetoothAdapterState: Entering OffState
08-31 11:29:23.587  1450  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:23.587  1450  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:23.587  3067  3071 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 11:29:23.587  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:29:23.587  1440  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:23.587  1440  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:23.597  3067  3077 D Bluetoothsap: onBluetoothStateChange: up=false
08-31 11:29:23.597  3067  3077 D Bluetoothsap: Unbinding service...
08-31 11:29:23.597  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:23.597  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:23.597  3067  3071 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:23.597  3067  3071 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:23.597  3181  3191 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:29:23.597  3067  6873 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:29:23.597  2006  2161 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:23.597  2006  2161 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:23.597  3181  3189 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:23.597  3181  3189 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:23.597  3067  3077 D BluetoothMap: onBluetoothStateChange: up=false
08-31 11:29:23.597  1177  1186 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:23.597  1177  1186 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:23.597  6736  6746 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:23.597  6736  6746 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:23.597  6736  6746 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-31 11:29:23.607  6736  6746 D BluetoothLeAdvertiser: Exit stop advertising
08-31 11:29:23.607  6736  6746 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 11:29:23.607  6736  6746 D BluetoothLeScanner: Exiting stopAllScan
08-31 11:29:23.607  1428  1463 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:23.607  1428  1463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:23.607  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-31 11:29:23.607  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-31 11:29:23.617  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:23.617  6895  6916 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-31 11:29:23.617  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-31 11:29:23.617  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-31 11:29:23.617  1177  1177 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
08-31 11:29:23.617  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:29:23.617  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:23.617  1177  1628 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
08-31 11:29:23.627  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-31 11:29:23.627  1177  1628 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
08-31 11:29:23.627  1177  1177 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
08-31 11:29:23.627  1177  1177 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
08-31 11:29:23.627  1015  1709 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 11:29:23.627  1015  1713 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 11:29:23.627  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-31 11:29:23.627  1878  1878 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 11:29:23.627  2006  2163 D BluetoothAdapter: 806912991: getState() :  mService = null. Returning STATE_OFF
08-31 11:29:23.627  2006  2163 D BluetoothAdapter: 806912991: getState() :  mService = null. Returning STATE_OFF
08-31 11:29:23.627  3067  3067 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:23.637  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:23.637  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.637  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:23.637  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.637  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:23.637  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:23.637  3181  3275 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 11:29:23.637  3067  3067 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:23.637  1015  1490 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 11:29:23.637  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:23.637  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-31 11:29:23.637  3181  3181 I GKI_LINUX: GKI_exit_task 1 done
08-31 11:29:23.637  3181  3181 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-31 11:29:23.637  3181  3181 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 11:29:23.647  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.647  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:23.647  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:23.647  1015  1713 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:23.647  1015  1713 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.647  1015  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:23.647  1015  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 11:29:23.647  3181  3181 I art     : System.exit called, status: 0
,08-31 11:29:23.647  3181  3181 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 11:29:23.647  1370  1370 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
,08-31 11:29:23.647  1015  1124 D WifiP2pService: InactiveState{ what=147461 }
,08-31 11:29:23.657  1015  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-31 11:29:23.657  1015  1124 D WifiP2pService: DefaultState{ what=147461 }
08-31 11:29:23.657  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
08-31 11:29:23.657  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:29:23.657   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:23.657  2006  3018 V NativeCrypto: Read error: ssl=0xb896f928: I/O error during system call, Connection timed out
,08-31 11:29:23.657  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:23.657  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:29:23.667  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:23.667  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-31 11:29:23.667  2006  3018 V NativeCrypto: SSL shutdown failed: ssl=0xb896f928: I/O error during system call, Broken pipe
,08-31 11:29:23.667  2006  3018 E GCM     : Wifi connection closed with errorCode 20
,08-31 11:29:23.667  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:23.667  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 11:29:23.667  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.667  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.667  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.667  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:23.667  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 11:29:23.667  1015  1593 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-31 11:29:23.667  3067  3067 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:23.667  3067  3067 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:23.677  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:23.677  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:23.677  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:23.677  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
,08-31 11:29:23.677  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,08-31 11:29:23.677  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:23.677  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-31 11:29:23.677  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.677  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 11:29:23.677  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.677  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:23.677  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-31 11:29:23.677  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:29:23.687  1015  1704 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-10ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:23.687  1015  1704 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-10ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:23.687  1015  1704 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 11:29:23.687  1015  1704 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:23.687  1015  1704 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-31 11:29:23.687  1015  1704 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 11:29:23.687  1015  1704 I qtaguid : Tagging socket 346 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,08-31 11:29:23.687  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:29:23.687  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-31 11:29:23.687  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 11:29:23.697  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-31 11:29:23.697  1015  1704 I qtaguid : Untagging socket 346
08-31 11:29:23.697  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 11:29:23.697  1015  1704 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 11:29:23.697  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:23.697  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 11:29:23.697  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 11:29:23.697  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 11:29:23.697  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-31 11:29:23.697  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:23.697  1015  1046 D WifiDisplayController: disconnect
08-31 11:29:23.697  1015  1046 D WifiDisplayController: updateConnection
08-31 11:29:23.697  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:23.697  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:23.707  1015  1124 D WifiP2pService: P2pDisablingState
08-31 11:29:23.707  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 11:29:23.707  1015  1124 D WifiP2pService: p2p socket connection lost
08-31 11:29:23.717  1015  1124 D WifiP2pService: P2pDisabledState
,08-31 11:29:23.717  1015  1125 E WifiNative-wlan0: do suspend true
,08-31 11:29:23.717  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-31 11:29:23.717  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-31 11:29:23.717  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:23.717  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:29:23.727  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 11:29:23.727  1015  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:23.727  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 11:29:23.727  1015  1379 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-31 11:29:23.727  1015  1379 W BroadcastQueue: android.os.DeadObjectException
08-31 11:29:23.727  1015  1379 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:29:23.727  1015  1379 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:29:23.727  1015  1379 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-31 11:29:23.727  1015  1379 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-31 11:29:23.727  1015  1379 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284),
08-31 11:29:23.727  1015  1379 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-31 11:29:23.727  1015  1379 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-31 11:29:23.727  1015  1379 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-31 11:29:23.727  1015  1379 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 11:29:23.727  1015  1379 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-31 11:29:23.727  1015  1379 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:23.727  1015  1379 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:23.727  1015  1379 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:23.727  1015  1379 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:23.747  6938  6938 E Zygote  : MountEmulatedStorage(),
,08-31 11:29:23.747  6938  6938 E Zygote  : v2
08-31 11:29:23.747  6938  6938 I libpersona: KNOX_SDCARD checking this for 1002
08-31 11:29:23.747  6938  6938 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:23.747  6938  6938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:23.747  1015  1379 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6938 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
08-31 11:29:23.747  1015  1593 W ActivityManager: Spurious death for ProcessRecord{2483b85b 6938:com.android.bluetooth/1002}, curProc for 3181: null
08-31 11:29:23.747  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-31 11:29:23.747  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-31 11:29:23.747  6938  6938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 11:29:23.757  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:23.757  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 11:29:23.757  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.757  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.757  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.757  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.757  6938  6938 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:23.767   277  1014 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:29:23.767   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:23.767   277  1010 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 11:29:23.777  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 11:29:23.777  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 11:29:23.777  1015  1127 V NetworkStats: updateIfacesLocked()
08-31 11:29:23.777  1015  1704 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-31 11:29:23.777  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:23.777  1015  1704 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-31 11:29:23.777  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:23.777  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:23.777  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 11:29:23.777  1370  1370 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-31 11:29:23.777  1015  1127 V NetworkStats: performPollLocked() took 5ms
08-31 11:29:23.777  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:23.787  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:23.787  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:23.787  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.787  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.787  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.787  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:23.787  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:23.787  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:23.787  6938  6938 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:23.787  6938  6938 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:23.787  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-31 11:29:23.787  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:23.787  1015  1125 D SecContentProvider2: mCursor = null
08-31 11:29:23.787  1177  1605 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 11:29:23.787  4779  6800 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-31 11:29:23.787  1015  1704 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:23.787  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-31 11:29:23.797  1015  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:29:23.797  1450  1450 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 11:29:23.797  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-31 11:29:23.797  1450  1450 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:29:23.797  1015  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-31 11:29:23.797  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 11:29:23.797  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:23.797  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:29:23.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.797  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.797  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:23.797  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:23.797  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-31 11:29:23.797  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 11:29:23.797  3067  3067 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:23.807  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:23.807  1177  1177 D HotspotTile: onReceive : 0, 0
,08-31 11:29:23.807  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:23.807  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:23.807  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:23.807  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:23.807  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:23.807  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:23.807  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:23.807  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:23.807  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:23.807  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:23.807  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:23.807  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 11:29:23.817  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-31 11:29:23.817  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,08-31 11:29:23.817  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:23.817  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:23.817  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:23.817  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:23.817  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:23.817  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:23.817  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:23.817  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:23.817  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:23.817  1015  1122 V NetworkStats: updateIfacesLocked()
08-31 11:29:23.817  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:23.817  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:23.817  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:23.817  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:23.817  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:23.817  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:29:23.817  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 11:29:23.817  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 11:29:23.817  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:23.817  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:23.817  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:23.817  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 11:29:23.817  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-31 11:29:23.817  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 11:29:23.817  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 11:29:23.817  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-31 11:29:23.817  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 11:29:23.817  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 11:29:23.817  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:23.817  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:23.817  1015  1122 V NetworkStats: performPollLocked() took 6ms
,08-31 11:29:23.817  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:23.817  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 11:29:23.817  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:23.817  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:23.827  6938  6938 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 11:29:23.827  6938  6938 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 11:29:23.827  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 11:29:23.827  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 11:29:23.827  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-31 11:29:23.827  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:23.827  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:29:23.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:23.827  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:23.827  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:23.827  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:23.857  6938  6938 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 11:29:23.877  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:23.877  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:23.877  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:23.887  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:23.887  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:23.887  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:23.887  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding GattService
,08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding HeadsetService
08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding HidService
08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding HealthService
08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding PanService
,08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding SapService
,08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-31 11:29:23.887  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding SapClientService
08-31 11:29:23.887  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:23.887  6938  6938 D BtSettings.ProfileConfig: Adding HidDevService
,08-31 11:29:23.887  6938  6938 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 11:29:23.897  1015  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-31 11:29:23.897  1015  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.897  1015  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.897  1015  1499 D SettingsProvider: selectionArgs: false
08-31 11:29:23.897  1015  1499 D SettingsProvider: selectionArgs: 1002
08-31 11:29:23.897  1015  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.897  1015  1499 D SettingsProvider: ret = -1
,08-31 11:29:23.897  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:23.897  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:23.897  1015  1712 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:23.897  1015  1712 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.897  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:23.897  1015  1712 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.897  1015  1712 D SettingsProvider: selectionArgs: false
08-31 11:29:23.897  1015  1712 D SettingsProvider: selectionArgs: 1002,
08-31 11:29:23.897  1015  1712 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.897  1015  1712 D SettingsProvider: ret = -1
,08-31 11:29:23.897  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:23.897  1015  1593 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 11:29:23.897  1015  1593 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.897  1015  1593 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.897  1015  1593 D SettingsProvider: selectionArgs: false
08-31 11:29:23.897  1015  1593 D SettingsProvider: selectionArgs: 1002
08-31 11:29:23.897  1015  1593 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.897  1015  1593 D SettingsProvider: ret = -1
,08-31 11:29:23.897  1015  1592 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 11:29:23.897  1015  1592 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.897  1015  1592 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.897  1015  1592 D SettingsProvider: selectionArgs: false
08-31 11:29:23.897  1015  1592 D SettingsProvider: selectionArgs: 1002
08-31 11:29:23.897  1015  1592 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.897  1015  1592 D SettingsProvider: ret = -1
08-31 11:29:23.897  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:23.897  1015  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 11:29:23.897  1015  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.897  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:23.897  1015  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.897  1015  1490 D SettingsProvider: selectionArgs: false
08-31 11:29:23.897  1015  1490 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:23.897  1015  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.897  1015  1490 D SettingsProvider: ret = -1
,08-31 11:29:23.897  1015  1594 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 11:29:23.897  1015  1594 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.897  1015  1594 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.897  1015  1594 D SettingsProvider: selectionArgs: false
,08-31 11:29:23.897  1015  1594 D SettingsProvider: selectionArgs: 1002
08-31 11:29:23.897  1015  1594 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.897  1015  1594 D SettingsProvider: ret = -1
08-31 11:29:23.897  1370  1370 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:29:23.907  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 11:29:23.907  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:23.907  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:23.907  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.907  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.907  1015  1028 D SettingsProvider: selectionArgs: false
08-31 11:29:23.907  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:23.907  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.907  1015  1028 D SettingsProvider: ret = -1
,08-31 11:29:23.907  1015  1133 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-31 11:29:23.907  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.907  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.907  1015  1133 D SettingsProvider: selectionArgs: false
08-31 11:29:23.907  1015  1133 D SettingsProvider: selectionArgs: 1002
08-31 11:29:23.907  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.907  1015  1133 D SettingsProvider: ret = -1
,08-31 11:29:23.907  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:23.907  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.907  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.907  1015  1027 D SettingsProvider: selectionArgs: false
08-31 11:29:23.907  1015  1027 D SettingsProvider: selectionArgs: 1002
08-31 11:29:23.907  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.907  1015  1027 D SettingsProvider: ret = -1
,08-31 11:29:23.907  1015  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:23.907  1015  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.907  1015  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.907  1015  1499 D SettingsProvider: selectionArgs: false
08-31 11:29:23.907  1015  1499 D SettingsProvider: selectionArgs: 1002
08-31 11:29:23.907  1015  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.907  1015  1499 D SettingsProvider: ret = -1
08-31 11:29:23.907  1015  1213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-31 11:29:23.907  1015  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.907  1015  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.907  1015  1213 D SettingsProvider: selectionArgs: false
08-31 11:29:23.907  1015  1213 D SettingsProvider: selectionArgs: 1002
08-31 11:29:23.907  1015  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.907  1015  1213 D SettingsProvider: ret = -1
08-31 11:29:23.907  1015  1713 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-31 11:29:23.907  1015  1713 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:23.907  1015  1713 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:23.907  1015  1713 D SettingsProvider: selectionArgs: false
08-31 11:29:23.907  1015  1713 D SettingsProvider: selectionArgs: 1002
08-31 11:29:23.907  1015  1713 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:23.907  1015  1713 D SettingsProvider: ret = -1
08-31 11:29:23.907  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:23.907  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:23.907  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:23.907  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:23.907  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:23.907  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:23.917  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:23.917  1015  1448 I ActivityManager: Killing 6470:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-31 11:29:23.917  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:23.917  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:23.917  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:23.917  2006  2006 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:23.927  1015  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:23.927  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 11:29:23.927  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:23.927  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:23.927  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.927  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:23.927  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:23.927  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:23.937  2006  6971 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 11:29:23.937  2006  2006 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 11:29:23.947  1015  1510 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:23.947  1015  1510 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.947  1015  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:23.947  1015  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:23.947  1015  1594 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-31 11:29:23.947  1015  1594 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:23.947  1015  1594 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:23.947  1015  1594 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:23.947  1015  1594 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:23.957  1638  1638 I Hs20UtilService: Starting #8
08-31 11:29:23.957  1638  1717 I Hs20UtilService: Message received 5007
,08-31 11:29:23.957  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:23.967  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:29:23.967  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:23.967  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:29:23.967  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:23.967  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:23.967  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:23.977  1370  1370 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 11:29:23.977  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:23.977  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:23.977  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:23.977  2006  6971 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-31 11:29:23.977  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:23.977  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:23.977  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:29:23.977  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:23.987  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 11:29:23.987  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:23.987  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:23.987  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:23.987  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:23.987  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:29:23.987  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:23.997  1015  1713 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 11:29:23.997  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:23.997  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:23.997  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:23.997  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:23.997  1370  1370 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-31 11:29:23.997  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:23.997  1370  1370 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 11:29:23.997  1370  1370 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 11:29:23.997  1370  1370 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:23.997  1370  1370 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 11:29:23.997  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:23.997  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:24.007  1015  1128 D Tethering: InitialState.processMessage what=4
08-31 11:29:24.007  1015  1128 E Tethering: No numeric data
08-31 11:29:24.007  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:24.007  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:24.007  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:24.007  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:29:24.007  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:24.007  6973  6973 E Zygote  : MountEmulatedStorage()
08-31 11:29:24.007  6973  6973 E Zygote  : v2
08-31 11:29:24.007  6973  6973 I libpersona: KNOX_SDCARD checking this for 10064
08-31 11:29:24.007  6973  6973 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:24.007  1015  1043 D Tethering: interfaceStatusChanged wlan0, false,
08-31 11:29:24.007  6973  6973 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:24.007  1015  1713 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6973 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:24.017  6973  6973 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:24.017  6973  6973 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:24.017  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:29:24.017  1015  1128 D Tethering: clearTetheredNotification(),
,08-31 11:29:24.017  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:24.017  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:24.017  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:24.017  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:24.017  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:24.017  1177  1177 D HotspotTile: updateTetherState():false, false,
,08-31 11:29:24.027  1015  1122 V NetworkStats: performPollLocked() took 4ms
,08-31 11:29:24.027  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:24.027  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 11:29:24.027  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:24.037  6973  6973 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:24.037  6973  6973 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:24.057  6973  6973 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 11:29:24.057   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb85837c8
08-31 11:29:24.057   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-31 11:29:24.057   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 11:29:24.057   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1202178760)
,08-31 11:29:24.087  6973  6973 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:24.087  6973  6973 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 11:29:24.097  1015  1709 I art     : Explicit concurrent mark sweep GC freed 46407(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.921ms total 162.188ms
,08-31 11:29:24.117   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-31 11:29:24.117   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 11:29:24.117   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1202178760) wakelock released: 1, error no: 0
08-31 11:29:24.117   272   338 I rmt_storage: 
,08-31 11:29:24.117   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb85837c8
,08-31 11:29:24.127  6973  6973 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:29:24.127  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 11:29:24.127  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:24.127  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.127  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.127  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:24.137  6989  6989 E Zygote  : MountEmulatedStorage()
08-31 11:29:24.137  6989  6989 E Zygote  : v2
08-31 11:29:24.137  1015  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6989 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:24.137  6989  6989 I libpersona: KNOX_SDCARD checking this for 10065
08-31 11:29:24.137  6989  6989 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:24.137  6989  6989 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:24.147  6989  6989 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 11:29:24.147  6989  6989 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:24.157  6989  6989 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:24.157  6989  6989 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:24.177  6989  6989 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:24.187  1015  1713 I ActivityManager: Killing 6501:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-31 11:29:24.187  1015  1713 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.187  1015  1713 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-31 11:29:24.187  1015  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:24.187  1015  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-31 11:29:24.197  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.197  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.197  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.197  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:24.207  7004  7004 E Zygote  : MountEmulatedStorage(),
08-31 11:29:24.207  1015  1713 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7004 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-31 11:29:24.207  7004  7004 E Zygote  : v2
08-31 11:29:24.207  7004  7004 I libpersona: KNOX_SDCARD checking this for 10102,
08-31 11:29:24.207  7004  7004 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:24.207  7004  7004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:24.207  7004  7004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:24.217  7004  7004 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-31 11:29:24.257  1370  1370 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:29:24.257  7004  7004 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:24.257  7004  7004 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:24.277  7004  7004 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 11:29:24.307  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:24.307  1370  1370 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 11:29:24.317  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:24.317  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:24.317  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:24.317  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-31 11:29:24.327   290   290 E SMD     : DCD OFF
,08-31 11:29:24.327  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:24.337  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:24.337  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:24.337  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:24.337  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:24.337  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:24.337  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:24.337  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:24.337  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:24.337  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:24.347   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:24.347  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:24.347  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:24.347  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:24.347  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:24.347  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:24.347  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:24.347  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:24.347  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:24.347  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:24.417  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-31 11:29:24.417  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:29:24.427  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:24.427  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:29:24.427  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:24.427  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:24.427  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:24.427  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:24.427  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:24.427  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-31 11:29:24.427  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:29:24.427  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:24.437  1177  1177 D HotspotTile: onReceive : 1, 0
,08-31 11:29:24.437  2006  2163 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:29:24.437  3067  3067 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:24.437  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:24.437  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:24.497  7004  7024 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-31 11:29:24.497  7004  7024 I Babel_SMS: MmsConfig.loadMmsSettings
08-31 11:29:24.497  7004  7024 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-31 11:29:24.497  7004  7024 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 11:29:24.507  7004  7024 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-31 11:29:24.507  7004  7024 I Babel_SMS: MmsConfig.loadFromResources
,08-31 11:29:24.507  7004  7024 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 11:29:24.507  7004  7024 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 11:29:24.577  1015  1379 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-31 11:29:24.577  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 11:29:24.577  1015  1379 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:24.577  1015  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,08-31 11:29:24.577  1015  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 11:29:24.607  7004  7004 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:29:24.627  7004  7004 I Babel_Crash: startup - clean
,08-31 11:29:24.667  1015  1593 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:24.667  1015  1593 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:24.667  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:24.667  1015  1593 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.667  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:24.677  1638  1638 I Hs20UtilService: Starting #9
,08-31 11:29:24.677  2006  2176 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-31 11:29:24.677  1638  1717 I Hs20UtilService: Message received 5007
,08-31 11:29:24.677  2006  2176 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
08-31 11:29:24.677  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:29:24.677  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:24.677  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:24.677  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:24.677  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:24.677  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:29:24.677  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:24.687  7004  7004 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:24.697  7004  7004 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 11:29:24.697  1015  1448 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:24.697  1015  1448 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:24.697  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:24.697  1015  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.697  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:24.697  7004  7004 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 11:29:24.697  1638  1638 I Hs20UtilService: Starting #10
,08-31 11:29:24.707  1638  1717 I Hs20UtilService: Message received 5011
,08-31 11:29:24.707  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 11:29:24.707  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:24.707  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 11:29:24.707  7004  7004 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-31 11:29:24.707  7004  7004 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-31 11:29:24.707  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:29:24.717  7004  7004 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-31 11:29:24.717  7004  7004 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 11:29:24.717  7004  7004 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 11:29:24.727  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.727  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.727  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.727  7004  7004 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 11:29:24.727  7004  7004 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 11:29:24.737  7004  7004 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 11:29:24.737  7004  7004 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 11:29:24.747  7004  7004 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 11:29:24.747  7004  7004 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 11:29:24.747  7004  7004 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 11:29:24.747  7004  7004 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 11:29:24.747  7004  7004 W VideoCapabilities: Unsupported mime video/mp43
,08-31 11:29:24.757  7004  7004 W VideoCapabilities: Unsupported mime video/sorenson
,08-31 11:29:24.757  7004  7004 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 11:29:24.777  7004  7004 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 11:29:24.797  7004  7004 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:24.797  7004  7004 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:24.797  7004  7004 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:24.807  7004  7004 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:24.807  1015  1592 I ActivityManager: Killing 6521:com.samsung.android.sm/1000 (adj 15): empty #21
,08-31 11:29:24.807  7004  7004 I vclib   : onServiceConnected
,08-31 11:29:24.817  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.817  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.817  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.827  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.827  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.827  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.827  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.827  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.827  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.827  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.827  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.827  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.827  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.827  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.827  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.837  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.837  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.837  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.837  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.837  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.837  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.837  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.837  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.837  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.837  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.837  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.837  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.847  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.847  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.847  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.847  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.847  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.847  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.847  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.847  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.847  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.847  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.847  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.847  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.857  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:24.857  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:24.857  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:24.857  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 11:29:24.857  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.857  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.857  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.857  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:24.877  7028  7028 E Zygote  : MountEmulatedStorage(),
08-31 11:29:24.877  7028  7028 E Zygote  : v2
08-31 11:29:24.877  7028  7028 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:24.877  7028  7028 I libpersona: KNOX_SDCARD not a persona,
08-31 11:29:24.877  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:24.877  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7028 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 11:29:24.877  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 11:29:24.877  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:24.897  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:24.907  7028  7028 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:24.937  7028  7028 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-31 11:29:24.937  7028  7028 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 11:29:24.937  7028  7028 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 11:29:24.947  7028  7028 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 11:29:24.947  7028  7028 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-31 11:29:24.947  7028  7028 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-31 11:29:24.947  7028  7028 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:24.957  1015  1712 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-31 11:29:24.957  1015  1712 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-31 11:29:24.957  1015  1712 I ActivityManager: Killing 6571:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-31 11:29:24.957  7028  7043 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-31 11:29:24.967  1015  1043 D Tethering: interfaceRemoved wlan0
08-31 11:29:24.967  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 11:29:24.977  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 11:29:24.977  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:24.977  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.977  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:24.977  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:24.987  7045  7045 E Zygote  : MountEmulatedStorage()
08-31 11:29:24.987  7045  7045 E Zygote  : v2
08-31 11:29:24.987  7045  7045 I libpersona: KNOX_SDCARD checking this for 10031
08-31 11:29:24.987  7045  7045 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:24.987  7045  7045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:24.997  7045  7045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 11:29:24.997  1015  1027 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7045 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-31 11:29:24.997  7045  7045 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:25.007  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-31 11:29:25.007  1817  1817 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 11:29:25.007  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.007  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.007  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.007  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.017  7058  7058 E Zygote  : MountEmulatedStorage()
08-31 11:29:25.017  7058  7058 E Zygote  : v2
08-31 11:29:25.017  7058  7058 I libpersona: KNOX_SDCARD checking this for 10121
08-31 11:29:25.017  7058  7058 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:25.017  7058  7058 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:25.027  7045  7045 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:25.027  7045  7045 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:25.027  1015  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7058 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-31 11:29:25.027  7058  7058 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:25.027  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 11:29:25.027  7058  7058 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:25.027  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.027  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.027  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.027  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.047  7058  7058 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:25.047  7058  7058 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:25.057   308   308 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 721us total 28.366ms,
,08-31 11:29:25.077   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.319ms total 19.850ms
,08-31 11:29:25.097   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 812us total 20.031ms
,08-31 11:29:25.117  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7075 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 11:29:25.117  7075  7075 E Zygote  : MountEmulatedStorage()
08-31 11:29:25.117  7075  7075 E Zygote  : v2
08-31 11:29:25.117  7075  7075 I libpersona: KNOX_SDCARD checking this for 10001
08-31 11:29:25.117  7075  7075 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:25.127  7075  7075 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:25.127  7075  7075 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 11:29:25.127  7075  7075 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:25.157  2605  2614 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-31 11:29:25.167  1817  1817 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-31 11:29:25.167  1817  1817 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-31 11:29:25.167  1817  1817 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-31 11:29:25.167  7058  7058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:29:25.167  1817  1817 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
08-31 11:29:25.167  7058  7058 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 11:29:25.167  7058  7058 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:29:25.167  1015  1043 D Tethering: interfaceRemoved p2p0
08-31 11:29:25.167  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 11:29:25.167  7075  7075 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:25.167  7075  7075 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:25.177  1817  1817 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 11:29:25.177  1817  1817 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-31 11:29:25.177  1015  1592 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-31 11:29:25.187  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.187  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.187  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.187  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.187  7058  7058 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:25.197  7090  7090 E Zygote  : MountEmulatedStorage()
08-31 11:29:25.197  7090  7090 E Zygote  : v2
08-31 11:29:25.197  7090  7090 I libpersona: KNOX_SDCARD checking this for 10077
08-31 11:29:25.197  7090  7090 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:25.207  7090  7090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:25.207  7090  7090 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:25.207  1015  1592 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7090 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 11:29:25.207  7090  7090 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-31 11:29:25.217  7058  7058 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 11:29:25.217  7058  7058 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 11:29:25.227  1015  1593 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-31 11:29:25.227  1015  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.227  1015  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.227  1015  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.227  1015  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.237  7045  7045 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-31 11:29:25.247  7104  7104 E Zygote  : MountEmulatedStorage(),
08-31 11:29:25.247  7104  7104 E Zygote  : v2
08-31 11:29:25.247  7104  7104 I libpersona: KNOX_SDCARD checking this for 10141
,08-31 11:29:25.247  7104  7104 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:25.247  7104  7104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:25.247  7104  7104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:25.257  1015  1593 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7104 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-31 11:29:25.257  1015  1593 I ActivityManager: Killing 6585:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-31 11:29:25.257  1015  1593 I ActivityManager: Killing 6603:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
08-31 11:29:25.257  7104  7104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:25.257  7090  7090 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:25.257  7090  7090 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:25.277  1015  1594 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-31 11:29:25.287  1015  1594 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.287  1015  1594 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.287  1015  1594 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.287  1015  1594 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.287  2783  7119 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-31 11:29:25.287  2783  7119 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-31 11:29:25.287  7104  7104 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:25.287  7104  7104 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:25.287  2783  7119 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-31 11:29:25.297  2783  7119 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-31 11:29:25.297  2783  7119 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-31 11:29:25.297  7123  7123 E Zygote  : MountEmulatedStorage()
,08-31 11:29:25.297  7123  7123 E Zygote  : v2
08-31 11:29:25.297  7123  7123 I libpersona: KNOX_SDCARD checking this for 10032
08-31 11:29:25.297  7123  7123 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:25.307  7123  7123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:25.307  1015  1594 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7123 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:25.307  7123  7123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:25.307  7123  7123 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 11:29:25.327  1015  1592 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 11:29:25.327  7104  7104 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-31 11:29:25.327  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.327  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.327  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.327  1015  1592 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.327  7104  7104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:29:25.327  7104  7104 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 11:29:25.327  7104  7104 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 11:29:25.337  7123  7123 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:25.337  7123  7123 D ActivityThread: Added TimaKeyStore provider,
,08-31 11:29:25.347  7137  7137 E Zygote  : MountEmulatedStorage()
,08-31 11:29:25.347  7137  7137 E Zygote  : v2
08-31 11:29:25.347  7137  7137 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:25.347  7137  7137 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:25.347   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
08-31 11:29:25.347  7137  7137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:25.347  7137  7137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 11:29:25.347  1015  1592 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7137 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 11:29:25.347  7137  7137 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:25.347  1015  1592 I ActivityManager: Killing 6539:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-31 11:29:25.377  7137  7137 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:25.377  7137  7137 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:25.397  1015  1594 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:25.417  1015  1712 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:25.437  7123  7156 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-31 11:29:25.437  7123  7156 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-31 11:29:25.457  7123  7156 D SPPClientService: PushLog.txt file is not deleted.
,08-31 11:29:25.457  7123  7156 D SPPClientService: PushLog.txt file is not deleted.
08-31 11:29:25.457  7123  7156 D SPPClientService: ============PushLog. stop!
,08-31 11:29:25.457  7137  7137 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 11:29:25.467  1015  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:25.487  7123  7123 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-31 11:29:25.487  1015  1448 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-31 11:29:25.487  1015  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.487  1015  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.487  1015  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.487  1015  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.497  1015  1592 D RCPManagerService: exchangeData() failure , invalid userId,
,08-31 11:29:25.507  7162  7162 E Zygote  : MountEmulatedStorage()
08-31 11:29:25.507  7162  7162 E Zygote  : v2
08-31 11:29:25.507  7162  7162 I libpersona: KNOX_SDCARD checking this for 10036
08-31 11:29:25.507  7162  7162 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:25.507  7162  7162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:25.507  1015  1448 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7162 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 11:29:25.507  1015  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 11:29:25.507  1015  1499 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:29:25.507  1015  1499 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:29:25.507  1015  1499 D BatteryService: stay LED for fully charged
08-31 11:29:25.507  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 11:29:25.507  1015  1448 I ActivityManager: Killing 6625:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-31 11:29:25.517  1015  1213 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-31 11:29:25.517  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-31 11:29:25.517  7162  7162 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:25.517  7162  7162 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,08-31 11:29:25.517  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:25.517  1015  1213 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 11:29:25.517  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-31 11:29:25.527  1015  1015 I MotionRecognitionService: Plugged
08-31 11:29:25.527  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:29:25.527  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 11:29:25.537  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:29:25.537  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-31 11:29:25.537  7162  7162 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:25.537  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-31 11:29:25.537  7162  7162 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:25.557  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 11:29:25.557  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 11:29:25.557  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 11:29:25.557  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 11:29:25.557  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-31 11:29:25.587  1015  1510 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-31 11:29:25.587  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.587  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.587  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.587  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.597  7123  7171 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-31 11:29:25.607  7162  7162 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@15d8113e
,08-31 11:29:25.617  7162  7162 I SA      : [SSP] onCreated
,08-31 11:29:25.627  7181  7181 E Zygote  : MountEmulatedStorage()
08-31 11:29:25.627  7181  7181 E Zygote  : v2
08-31 11:29:25.627  7181  7181 I libpersona: KNOX_SDCARD checking this for 10068
08-31 11:29:25.627  7181  7181 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:25.627  7181  7181 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:25.627  1015  1510 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7181 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-31 11:29:25.627  7181  7181 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:25.627  7181  7181 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 11:29:25.647  7181  7181 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:25.647  7162  7162 I SA      : [TPM] There is no property file
,08-31 11:29:25.657  7181  7181 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:25.657  7162  7162 I SA      : [SCU] isHaveSA() - false
,08-31 11:29:25.657  7162  7162 I SA      : [TPM] getModelProperty : null
08-31 11:29:25.667  7162  7162 I SA      : [TPM] getCSCProperty : null
,08-31 11:29:25.667  7162  7162 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-31 11:29:25.667  7162  7162 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-31 11:29:25.667  7162  7162 I SA      : [DM] TFT FEATURE: false
,08-31 11:29:25.667  1015  1594 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-31 11:29:25.667  1015  1594 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 11:29:25.667  1015  1499 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:25.667  1015  1594 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:25.667  1015  1594 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:25.667  1015  1594 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-31 11:29:25.667  7162  7162 I SA      : [DM] init START
,08-31 11:29:25.677  1015  1594 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:25.677  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
08-31 11:29:25.677  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.677  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.677  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.677  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.697  7162  7162 I SA      : [DM] This device is not a Vodafone
,08-31 11:29:25.697  7202  7202 E Zygote  : MountEmulatedStorage()
08-31 11:29:25.697  7202  7202 E Zygote  : v2
08-31 11:29:25.697  7202  7202 I libpersona: KNOX_SDCARD checking this for 10110
08-31 11:29:25.697  7202  7202 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:25.697  7202  7202 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:25.697  7137  7137 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 11:29:25.697  7202  7202 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:25.707  7202  7202 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 11:29:25.707  1015  1027 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7202 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:25.707  7181  7181 D BadgeProvider: onCreate
08-31 11:29:25.707  1015  1592 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-31 11:29:25.707  1015  1592 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-31 11:29:25.707  1015  1592 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:25.707  7181  7181 D BadgeProvider: DatabaseHelper
,08-31 11:29:25.707  1015  1592 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:25.707  1015  1592 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 11:29:25.707  7137  7137 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-31 11:29:25.717  7137  7137 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:25.717  7137  7137 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 11:29:25.717  7137  7137 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-31 11:29:25.717  7137  7137 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 11:29:25.717  1015  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-31 11:29:25.717  7004  7201 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-31 11:29:25.717  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.717  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.717  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.717  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.727  1015  1709 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:25.727  7202  7202 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-31 11:29:25.727  7202  7202 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:25.727  7181  7198 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-31 11:29:25.737  7162  7162 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-31 11:29:25.737  7217  7217 E Zygote  : MountEmulatedStorage()
08-31 11:29:25.737  7217  7217 I libpersona: KNOX_SDCARD checking this for 10008
08-31 11:29:25.737  7217  7217 E Zygote  : v2
08-31 11:29:25.737  7217  7217 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:25.737  7217  7217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:25.737  7217  7217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:25.737  1015  1480 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7217 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:25.737  7217  7217 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-31 11:29:25.737  1015  1480 I ActivityManager: Killing 6049:com.android.mms/u0a41 (adj 15): empty #21
,08-31 11:29:25.737  7162  7162 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-31 11:29:25.737  7162  7162 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-31 11:29:25.737  7162  7162 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-31 11:29:25.747  7162  7162 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-31 11:29:25.747  7162  7162 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-31 11:29:25.747  1015  1510 D RCPManagerService: exchangeData() failure , invalid userId
08-31 11:29:25.747  7162  7162 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 11:29:25.757  7162  7162 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-31 11:29:25.757  1015  1379 I ActivityManager: Killing 6646:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-31 11:29:25.757  7162  7162 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
08-31 11:29:25.767  7217  7217 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:25.767  1015  1379 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-31 11:29:25.767  1015  1379 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.767  7217  7217 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:25.767  1015  1379 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:25.767  1015  1379 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.767  1015  1379 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:25.767  7181  7198 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-31 11:29:25.767  7181  7198 D BadgeProvider: sendNotify, [notify] : null
08-31 11:29:25.767  7181  7198 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-31 11:29:25.767  7181  7198 D BadgeProvider: update, [BadgeCount] : badgecount=0
,08-31 11:29:25.767  7181  7198 D BadgeProvider: update, [UpdateCount] : 1
,08-31 11:29:25.777  1482  1482 D Launcher.Model: reloadBadges entered.
,08-31 11:29:25.777  7233  7233 E Zygote  : MountEmulatedStorage(),
08-31 11:29:25.787  7233  7233 I libpersona: KNOX_SDCARD checking this for 10009
08-31 11:29:25.777  7233  7233 E Zygote  : v2
08-31 11:29:25.787  7233  7233 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:25.787  7233  7233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:25.787  1015  1379 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7233 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-31 11:29:25.787  7233  7233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:25.787  7162  7162 I SA      : [SCU] isHaveSA() - false
08-31 11:29:25.787  7162  7162 I SA      : support phone number id : false
08-31 11:29:25.787  7162  7162 I SA      : [DM] Supports Ref Jpn : true
,08-31 11:29:25.787  7162  7162 I SA      : [DM] init END
08-31 11:29:25.787  7162  7162 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
08-31 11:29:25.787  7233  7233 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 11:29:25.787  1015  1379 I ActivityManager: Killing 6480:com.android.calendar/u0a131 (adj 15): empty #21,
08-31 11:29:25.787  1015  1379 I ActivityManager: Killing 6664:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #22
,08-31 11:29:25.797  7162  7162 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-31 11:29:25.797  7162  7162 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 11:29:25.817  7233  7233 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:25.817  7233  7233 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:25.817  7162  7162 I SA      : [SLFUCHKMGR] constructor called
,08-31 11:29:25.837  1015  1592 D CountryDetector: No listener is left
,08-31 11:29:25.837  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
08-31 11:29:25.837  7162  7162 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-31 11:29:25.837  7162  7162 I SA      : [OR] == isSIMCardReady false ==
,08-31 11:29:25.877  7162  7162 I SA      : [SCU] == networkStateCheck == false
,08-31 11:29:25.877  7162  7162 I SA      : [OR] onReceive END
,08-31 11:29:25.887  1015  1448 I ActivityManager: Killing 6680:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-31 11:29:25.897  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:25.907  1015  1594 I ActivityManager: Killing 6010:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-31 11:29:25.917  2911  2911 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 11:29:25 GMT+02:00 2016
,08-31 11:29:25.917  1015  1480 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 11:29:25.917  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 11:29:25.917  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:25.917  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:25.917  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 11:29:25.927  2911  2911 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 11:29:25.927  2911  2911 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 11:29:25.927  2911  2911 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 11:29:25.937  2911  2911 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 11:29:25.937  2911  7250 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 11:29:25.937  2911  7250 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 11:29:25.937  2911  7250 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-31 11:29:25.947  2911  7250 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-31 11:29:25.947  2911  2911 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 11:29:25.967  1015  1593 I ActivityManager: Killing 5812:com.android.vending/u0a26 (adj 15): empty #21
,08-31 11:29:25.967  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-31 11:29:25.967  1015  1490 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-31 11:29:25.967  1015  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 11:29:25.967  1015  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 11:29:25.977  1015  1594 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:25.977  1015  1594 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 11:29:25.977  1015  1594 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:25.977  1015  1594 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:25.977  1015  1594 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:25.987  1015  1709 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:29:25.987  1015  1709 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:29:25.987  1015  1709 D SecContentProvider2: mCursor = null
,08-31 11:29:25.987  1015  1709 D WifiService: setWifiEnabled: true pid=6736, uid=10171
,08-31 11:29:25.987  1015  1709 W ActivityManager: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:29:25.987  1015  1709 W WifiService: Failed getting userId using ActivityManagerNative
08-31 11:29:25.987  1015  1709 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:25.987  1015  1709 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:25.987  1015  1709 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 11:29:25.987  1015  1709 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 11:29:25.987  1015  1709 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 11:29:25.987  1015  1709 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:29:25.987  1015  1709 D SettingsProvider: name = wifi_on
,08-31 11:29:25.997  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 11:29:26.007  4779  7252 I iu.SyncManager: SYNC; picasa accounts
,08-31 11:29:26.007  4779  4779 D NetworkLogImpl: Loaded NetworkSpeedPredictor,
,08-31 11:29:26.057  1015  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:29:26.147   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 11:29:26.147   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:26.147  7202  7257 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 11:29:26.157   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 11:29:26.157   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:26.157  7202  7257 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 11:29:26.177   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 11:29:26.177   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:26.177  7202  7258 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 11:29:26.187   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 11:29:26.187   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:26.187  7202  7258 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 11:29:26.207  7202  7202 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 11:29:26.207  7202  7202 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 11:29:26.207  7202  7202 I GAv4    :   adb logcat -s GAv4
,08-31 11:29:26.227  7202  7202 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:29:26.227  1015  1499 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:29:26.237  7202  7202 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:29:26.247  7202  7266 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:29:26.347   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:26.347  1015  1043 D Tethering: interfaceAdded wlan0
,08-31 11:29:26.357  1015  1128 E Tethering: No numeric data
,08-31 11:29:26.357  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:26.357  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:29:26.357  1015  1128 D Tethering: clearTetheredNotification()
08-31 11:29:26.357  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:26.357  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:26.357  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:26.367  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:26.367  1015  1122 V NetworkStats: performPollLocked() took 7ms
,08-31 11:29:26.367  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:26.367  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 11:29:26.367  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:29:26.367  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:26.367  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:26.367  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 11:29:26.367  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:26.367  1015  1128 D Tethering: InitialState.processMessage what=4
,08-31 11:29:26.367  1015  1043 D Tethering: interfaceAdded p2p0
,08-31 11:29:26.367  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 11:29:26.367  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:29:26.377  1015  1128 E Tethering: No numeric data
08-31 11:29:26.377   277  1014 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 11:29:26.377  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:29:26.377  1015  1128 D Tethering: clearTetheredNotification()
08-31 11:29:26.377  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:26.377  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-31 11:29:26.377   277  1014 D SoftapController: Softap fwReload - Ok
,08-31 11:29:26.377  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:26.377  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:26.377  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:26.377  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:26.377  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:26.377  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 11:29:26.377  1015  1122 V NetworkStats: performPollLocked() took 6ms
08-31 11:29:26.377  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:26.377   277  1014 D CommandListener: Setting iface cfg
08-31 11:29:26.377   277  1014 D CommandListener: Trying to bring down wlan0
,08-31 11:29:26.377  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:26.377  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:26.387   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:26.387  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 11:29:26.387  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 11:29:26.397  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:26.397  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:29:26.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:26.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:26.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:26.397  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:26.407  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:26.407  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-31 11:29:26.407  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:26.407  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:26.407  1177  1177 D HotspotTile: onReceive : 2, 0,
,08-31 11:29:26.407  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:26.407  3067  3067 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:26.407  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:26.437  7271  7271 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 11:29:26.437  7271  7271 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 11:29:26.437  7271  7271 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 11:29:26.457  7271  7271 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-31 11:29:26.457   380   380 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7271
08-31 11:29:26.457   380   380 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-31 11:29:26.457  7271  7271 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 11:29:26.457  7271  7271 I wpa_supplicant: ssSupport state is = 1
,08-31 11:29:26.457  7271  7271 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 11:29:26.467  7271  7271 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-31 11:29:26.467   380   380 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7271
08-31 11:29:26.467   380   380 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-31 11:29:26.527  1015  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:26.527  1015  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:26.527  1015  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:26.527  1015  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 11:29:26.557  7202  7202 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-31 11:29:26.597  7202  7202 I cr.library_loader: Time to load native libraries: 5 ms (timestamps 7362-7367)
08-31 11:29:26.597  7202  7202 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 11:29:26.607  7202  7202 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d2798f1}
08-31 11:29:26.607  7202  7202 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 11:29:26.607  7202  7202 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:29:26.627  7202  7202 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,08-31 11:29:26.627  7202  7202 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:29:26.627  7202  7202 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-31 11:29:26.637   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-31 11:29:26.637  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-31 11:29:26.637  7202  7202 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 11:29:26.637  7202  7202 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 11:29:26.637  7202  7202 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 11:29:26.637  7202  7202 I Adreno-EGL: Local Branch: 
08-31 11:29:26.637  7202  7202 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 11:29:26.637  7202  7202 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 11:29:26.637  7202  7202 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 11:29:26.687  7271  7271 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 11:29:26.687  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 11:29:26.697  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 11:29:26.697   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7271
08-31 11:29:26.697   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 11:29:26.697  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 11:29:26.697  7271  7271 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:26.697  7271  7271 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 11:29:26.697  7271  7271 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:26.697  7271  7271 E wpa_supplicant: SIM READ ERROR
08-31 11:29:26.697  7271  7271 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:26.697  7271  7271 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:26.697  7271  7271 E wpa_supplicant: SIM READ ERROR
08-31 11:29:26.697  7271  7271 I wpa_supplicant: Blacklist: Clear (all) 
08-31 11:29:26.697  7271  7271 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:29:26.697  7271  7271 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-31 11:29:26.697  7271  7271 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:26.707  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:26.697  7271  7271 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 11:29:26.697  7271  7271 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:26.697  7271  7271 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:26.697  7271  7271 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 11:29:26.707  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:26.707  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:26.707  7202  7202 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:29:26.717  7202  7299 W cr.media: Requires BLUETOOTH permission
,08-31 11:29:26.717  7202  7202 I NSApplication: Starting up...
,08-31 11:29:26.717  1015  1593 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:29:26.727  1015  1499 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:29:26.727  1015  1712 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-31 11:29:26.727  1015  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:26.727  1015  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:26.727  1015  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:26.727  1015  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:26.747  7304  7304 E Zygote  : MountEmulatedStorage()
,08-31 11:29:26.747  7304  7304 E Zygote  : v2
08-31 11:29:26.747  7304  7304 I libpersona: KNOX_SDCARD checking this for 10117
08-31 11:29:26.747  7304  7304 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:26.747  1015  1712 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7304 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:26.747  1015  1712 I ActivityManager: Killing 6877:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21,
08-31 11:29:26.747  7304  7304 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:26.757  7304  7304 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:26.757  7304  7304 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:29:26.757  7271  7271 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 11:29:26.767   308   308 I art     : Explicit concurrent mark sweep GC freed 8684(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 21.560ms
,08-31 11:29:26.777  7304  7304 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:26.777  7304  7304 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:26.787   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 17.463ms
,08-31 11:29:26.797  7304  7304 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:29:26.807   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.442ms
,08-31 11:29:26.897  7271  7271 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 11:29:26.897  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 11:29:26.917  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-31 11:29:26.917   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7271
08-31 11:29:26.917   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 11:29:26.917  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-31 11:29:26.917  7271  7271 I wpa_supplicant: ssSupport state is = 1
,08-31 11:29:26.917  7271  7271 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-31 11:29:26.917  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 11:29:26.927  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-31 11:29:26.927   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7271
08-31 11:29:26.927   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-31 11:29:26.927  7271  7271 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 11:29:26.927  7271  7271 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:26.927  7271  7271 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:26.927  7271  7271 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:26.927  7271  7271 E wpa_supplicant: SIM READ ERROR
08-31 11:29:26.927  7271  7271 I wpa_supplicant: wpa_default_ap_write_once,
08-31 11:29:26.927  7271  7271 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 11:29:26.927  7271  7271 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:29:26.927  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:26.927  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:26.937  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:26.937  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:29:26.937  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:26.937  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:27.047  7271  7271 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 11:29:27.047  7271  7271 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 11:29:27.127  1015  1448 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-31 11:29:27.127  1015  1448 I ActivityManager: Killing 6938:com.android.bluetooth/1002 (adj 15): empty #21
,08-31 11:29:27.137  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:27.137  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:27.137  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:27.137  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:27.137  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:27.137  1638  1638 I Hs20UtilService: Starting #11
,08-31 11:29:27.137  1638  1717 I Hs20UtilService: Message received 5011
,08-31 11:29:27.147  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:27.147  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:27.147  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:27.147  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:29:27.157  1015  1593 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:27.157  1015  1593 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:27.157  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:27.157  1015  1593 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:27.157  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:27.157  1638  1638 I Hs20UtilService: Starting #12
,08-31 11:29:27.157  1638  1717 I Hs20UtilService: Message received 5011
,08-31 11:29:27.167  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:27.167  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:27.167  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:27.167  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:29:27.177  7271  7271 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-31 11:29:27.177  7271  7271 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 11:29:27.177  7271  7271 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 11:29:27.177  1015  1028 I ActivityManager: Killing 6895:com.google.android.apps.maps/u0a105 (adj 15): empty #21,
,08-31 11:29:27.177  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 11:29:27.187  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-31 11:29:27.187  7271  7271 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 11:29:27.187  7271  7271 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:27.187  7271  7271 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 11:29:27.187  7271  7271 E wpa_supplicant: SIM READ ERROR
08-31 11:29:27.187  7271  7271 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:29:27.227  7271  7271 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 11:29:27.237  7271  7271 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 11:29:27.237  1015  1125 D WifiConfigStore: Loading config and enabling all networks ,
,08-31 11:29:27.237  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:27.237  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:27.237  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:27.237  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:27.237  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:27.237  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:27.237  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:27.237  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-31 11:29:27.237  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:27.237  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:29:27.247  1177  1177 D HotspotTile: onReceive : 3, 0
,08-31 11:29:27.247  3067  3067 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-31 11:29:27.247  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:27.247  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:27.247  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-31 11:29:27.247  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:27.247  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:27.247  1015  1712 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:27.247  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:27.247  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:27.247  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:27.247  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:27.247  1015  1712 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:27.247  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:27.257  1015  1125 E WifiConfigStore: Not a HS20
08-31 11:29:27.257  1638  1638 I Hs20UtilService: Starting #13
08-31 11:29:27.257  1638  1717 I Hs20UtilService: Message received 5011
08-31 11:29:27.257  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 11:29:27.257  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:27.257  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 11:29:27.257  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 11:29:27.257  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:27.257  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-31 11:29:27.257  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 11:29:27.257  7271  7271 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 11:29:27.257  7271  7271 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 11:29:27.257  7271  7271 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 11:29:27.257  7271  7271 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 11:29:27.257  7271  7271 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 11:29:27.257  7271  7271 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 11:29:27.257  7271  7271 I wpa_supplicant: First Scan Start
08-31 11:29:27.257  7271  7271 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 11:29:27.257  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-31 11:29:27.257  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19,
08-31 11:29:27.267  1015  1125 I WifiNative-HAL: startHal,
08-31 11:29:27.267  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9ed4488c
08-31 11:29:27.267  1015  1125 I WifiNative-HAL: Could not start hal
,08-31 11:29:27.267  7004  7004 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:29:27.267  1015  1125 E WifiNative-wlan0: do suspend true
,08-31 11:29:27.267  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 11:29:27.267   277  1014 D CommandListener: Setting iface cfg
08-31 11:29:27.267   277  1014 D CommandListener: Trying to bring up p2p0
,08-31 11:29:27.267  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
08-31 11:29:27.267  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:29:27.267  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 11:29:27.267  1015  1124 D WifiP2pService: P2pEnablingState,
08-31 11:29:27.267  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:27.267  1015  1148 I WifiNative-HAL: startHal
08-31 11:29:27.267  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9d8039bc
08-31 11:29:27.267  1015  1148 I WifiNative-HAL: Could not start hal
,08-31 11:29:27.267  1015  1148 E WifiScanningService: could not start HAL,
08-31 11:29:27.277  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:29:27.277  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:29:27.277  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-31 11:29:27.277  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-31 11:29:27.277  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:29:27.277  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:29:27.277  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 11:29:27.277  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-31 11:29:27.277  1015  1124 D WifiP2pService: P2p socket connection successful
08-31 11:29:27.277  1015  1124 D WifiP2pService: P2pEnabledState
08-31 11:29:27.277  1015  1149 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:29:27.277  7271  7271 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:29:27.277  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 11:29:27.277  7271  7271 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:29:27.277  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:27.277  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 11:29:27.277  7271  7271 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-31 11:29:27.277  1015  1125 E WifiStateMachine: Failed to set frequency band 0
08-31 11:29:27.277  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-31 11:29:27.277  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:27.277  1015  1046 D WifiDisplayController: disconnect
,08-31 11:29:27.277  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:27.277  1015  1046 D WifiDisplayController: updateConnection
08-31 11:29:27.277  1015  1125 D SecContentProvider2: mCursor = null
08-31 11:29:27.277  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-31 11:29:27.277  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:27.287  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-31 11:29:27.287  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-31 11:29:27.287  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:29:27.287  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:29:27.287  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:27.287  1015  1125 D SecContentProvider2: mCursor = null
08-31 11:29:27.287  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
08-31 11:29:27.287  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-31 11:29:27.287  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 11:29:27.287  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:29:27.287  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:27.287  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 11:29:27.287  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-31 11:29:27.287  1015  1593 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 11:29:27.287  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 11:29:27.287  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  secondary type: null
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  wps: 0
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  grpcapab: 0
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  devcapab: 0
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  status: 3
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  wfdInfo: null
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-31 11:29:27.287  1015  1046 D WifiDisplayController:  SConnectInfo : null
,08-31 11:29:27.297  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:27.297  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:27.297  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:27.297  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:27.297  6973  6973 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:27.297  6973  6973 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 11:29:27.297  6973  6973 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:29:27.307  6989  6989 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:27.317  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 11:29:27.317  1015  1124 D WifiP2pService: InactiveState
,08-31 11:29:27.317  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-31 11:29:27.317  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:29:27.317  7271  7271 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-31 11:29:27.317  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-31 11:29:27.317  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:29:27.327   290   290 E SMD     : DCD OFF,
,08-31 11:29:27.347   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:27.357  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 11:29:27.357  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:27.357  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:28.347   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-31 11:29:28.457  7271  7271 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
08-31 11:29:28.457  7271  7271 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 11:29:28.457  7271  7271 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-31 11:29:28.457  7271  7271 I wpa_supplicant: Trying to associate with  'G700'
08-31 11:29:28.457  7271  7271 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-31 11:29:28.457  7271  7271 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 11:29:28.457  1015  7327 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 11:29:28.467  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:28.467  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:28.567  7271  7271 E wpa_supplicant: Cmd 35605 not handled
,08-31 11:29:28.567  7271  7271 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:29:28.567  7271  7271 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00),
08-31 11:29:28.567  7271  7271 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 11:29:28.567  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:28.567  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 11:29:28.567  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:28.567  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:28.567  7271  7271 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 11:29:28.567  7271  7271 I wpa_supplicant: Associated with F4.99.3E
08-31 11:29:28.567  7271  7271 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:29:28.567  7271  7271 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 11:29:28.567  7271  7271 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:28.567  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:28.567  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:28.577  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 11:29:28.577  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 11:29:28.577  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:28.577  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 11:29:28.577  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 11:29:28.577  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-31 11:29:28.577  7271  7271 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-31 11:29:28.577  7271  7271 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 11:29:28.577  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:28.577  1015  1125 D SecContentProvider2: mCursor = null
08-31 11:29:28.577  7271  7271 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-31 11:29:28.577  7271  7271 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:28.577  1015  1128 E Tethering: No numeric data
08-31 11:29:28.587  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:28.587  1015  1125 D SecContentProvider2: mCursor = null
08-31 11:29:28.587  7271  7271 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 11:29:28.587  7271  7271 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 11:29:28.587  7271  7271 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
,08-31 11:29:28.587  7271  7271 I wpa_supplicant: Blacklist: Clear (temp) 
,08-31 11:29:28.587  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:29:28.587  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 11:29:28.587  7271  7271 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-31 11:29:28.587  1015  1128 D Tethering: clearTetheredNotification()
08-31 11:29:28.587  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 11:29:28.597  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:28.587  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-31 11:29:28.597  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:28.597  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-31 11:29:28.597  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:28.597  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:28.597  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 11:29:28.597  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:28.597  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 11:29:28.597  1015  1122 V NetworkStats: performPollLocked() took 9ms
08-31 11:29:28.597  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:28.607  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 11:29:28.607  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 11:29:28.607  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-31 11:29:28.607  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 11:29:28.607  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:28.607  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:28.607  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:28.607  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:28.607  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:28.607  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:28.617  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:29:28.617  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:28.617  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:28.617  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:28.617  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:28.617  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:28.617  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:28.617  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:28.617  1638  1638 I Hs20UtilService: Starting #14
,08-31 11:29:28.617  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:29:28.617  1638  1717 I Hs20UtilService: Message received 5007
08-31 11:29:28.617  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:28.617  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:28.627  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:28.627  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:28.627  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:28.627  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:29:28.627  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:28.637   277  1014 D CommandListener: Setting iface cfg,
,08-31 11:29:28.637  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,08-31 11:29:28.647  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:28.647  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:28.647  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:28.647  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 11:29:28.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:28.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:28.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:28.657  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:28.657  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:28.657  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:28.667  1015  1125 E WifiNative-wlan0: do suspend false
,08-31 11:29:28.667  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:29:28.667  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:29:28.877  7335  7335 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 11:29:28.887  7335  7335 I dhcpcd  : version 5.5.6 starting,
,08-31 11:29:28.887  7335  7335 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 11:29:28.947  7335  7335 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-31 11:29:28.947  7335  7335 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 11:29:28.947  7335  7335 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,08-31 11:29:28.947  7335  7335 I dhcpcd  : bssid match
,08-31 11:29:28.947  7335  7335 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-31 11:29:28.987  1015  1499 I ActivityManager: Killing 7028:com.sec.pcw.device/1000 (adj 15): empty #21,
,08-31 11:29:28.997  1015  1213 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 11:29:28.997  1015  1213 D WifiService: setWifiEnabled: false pid=6736, uid=10171
08-31 11:29:28.997  1015  1213 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:29:28.997  1015  1213 D SecContentProvider2: mCursor = null
08-31 11:29:28.997  1015  1213 D SettingsProvider: name = wifi_on
08-31 11:29:28.997  7335  7335 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-31 11:29:29.007  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:29.027  1015  1125 E WifiNative-wlan0: do suspend true,
,08-31 11:29:29.047  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
08-31 11:29:29.047  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:29:29.047   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:29.057  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:29.057  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:29:29.057  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:29.057  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-31 11:29:29.057   277  1014 E Netd    : no such netId 503
,08-31 11:29:29.067  7335  7335 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-31 11:29:29.067  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:29.067  1015  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-31 11:29:29.067  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:29.067  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 11:29:29.067  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:29.067  1015  1127 V NetworkStats: updateIfacesLocked()
08-31 11:29:29.067  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:29.067  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:29.067  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.067  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.067  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.077  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 11:29:29.077  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
,08-31 11:29:29.077  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:29.077  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-31 11:29:29.077  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:29.077  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 11:29:29.077  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 11:29:29.087  1015  1127 V NetworkStats: performPollLocked() took 15ms
,08-31 11:29:29.087  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:29.097  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:29.097  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:29.097  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.097  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.097  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.097  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:29.097  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,08-31 11:29:29.097  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:29.097  1015  1015 D RttService: SCAN_AVAILABLE : 1
,08-31 11:29:29.097  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:29:29.107  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503],
08-31 11:29:29.107  1015  7333 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:29.107  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 11:29:29.107  1015  7333 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 11:29:29.107  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 11:29:29.107  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 11:29:29.107  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-31 11:29:29.107  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:29:29.107  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:29:29.107  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:29.107  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:29.107  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 11:29:29.107  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:29.107  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-31 11:29:29.117  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:29.117  1015  1713 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:29.117  1015  1713 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:29.117  1015  1713 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:29.117  1015  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:29.117  1015  1124 D WifiP2pService: P2pDisablingState
08-31 11:29:29.117  1015  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:29.117  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 11:29:29.117  1015  1124 D WifiP2pService: p2p socket connection lost
,08-31 11:29:29.117  1015  1125 E WifiNative-wlan0: do suspend true
08-31 11:29:29.117  1015  1124 D WifiP2pService: P2pDisabledState
08-31 11:29:29.117  1638  1638 I Hs20UtilService: Starting #15
08-31 11:29:29.117  1638  1717 I Hs20UtilService: Message received 5007
,08-31 11:29:29.117  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 11:29:29.117  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 11:29:29.117  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:29.117  1015  1046 D WifiDisplayController: disconnect
08-31 11:29:29.117  1015  1046 D WifiDisplayController: updateConnection
08-31 11:29:29.117  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:29.117  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:29.127  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-31 11:29:29.127  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
08-31 11:29:29.127  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:29:29.127  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:29:29.127  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-31 11:29:29.127  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:29.127  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:29:29.127  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 11:29:29.127  1015  1133 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 11:29:29.127  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:29.127  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-31 11:29:29.127  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 11:29:29.127  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:29:29.137  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:29.137  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:29:29.137  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:29.137  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:29.137  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:29.137  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 11:29:29.137  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:29.137  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:29.147  6973  6973 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:29.147  6973  6973 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 11:29:29.147  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
08-31 11:29:29.147  6973  6973 D FileShare-Client: Outbound.stopDelayTimer - 
08-31 11:29:29.147  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-31 11:29:29.157  6989  6989 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:29.157   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:29.157  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:29.157  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:29.157  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.157  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.157  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.157  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.157  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 11:29:29.157  7271  7271 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-31 11:29:29.167  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:29.167  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:29.167  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.167  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.167  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.167  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:29.167  1015  1592 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:29.167  1015  1592 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:29.167  1015  1592 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:29.167  1015  1592 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:29.167  1015  1592 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:29.177  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:29.177  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:29.177  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:29.177  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:29:29.177  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.177  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.177  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:29.177  1638  1638 I Hs20UtilService: Starting #16
08-31 11:29:29.177  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:29.177  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,08-31 11:29:29.177  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-31 11:29:29.177  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:29.187  1638  1717 I Hs20UtilService: Message received 5007
08-31 11:29:29.187  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:29.187  1177  1177 D HotspotTile: onReceive : 0, 0
,08-31 11:29:29.187  3067  3067 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:29.197  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:29.197  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:29.197  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:29.197  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:29.197  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:29.197  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:29.197  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:29.197  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:29:29.197  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:29.197  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 11:29:29.197  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:29.207  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:29.207  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:29.207  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:29.217  1015  1379 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-31 11:29:29.217  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:29.227  1015  1379 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:29.227  1015  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:29.227  1015  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
08-31 11:29:29.227  1638  1638 I Hs20UtilService: Starting #17
08-31 11:29:29.227  1638  1717 I Hs20UtilService: Message received 5011
08-31 11:29:29.227  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-31 11:29:29.227  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:29.227  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:29.227  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1,
,08-31 11:29:29.337  7271  7271 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:29:29.457  7271  7271 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
08-31 11:29:29.457  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:29.457  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:29.457  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:29.477  7271  7271 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-31 11:29:29.487  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:29.487  7271  7271 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 11:29:29.487  7271  7271 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e,
08-31 11:29:29.487  7271  7271 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-31 11:29:29.487  7271  7271 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 11:29:29.487  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:29.487  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:29.487  1015  1128 D Tethering: InitialState.processMessage what=4
,08-31 11:29:29.487  1015  1128 E Tethering: No numeric data
,08-31 11:29:29.487  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:29.487  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:29.487  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:29.487  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:29:29.487  1015  1128 D Tethering: clearTetheredNotification()
08-31 11:29:29.497  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:29.497  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:29.497  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 11:29:29.497  1177  1177 D HotspotTile: updateTetherState():false, false
,08-31 11:29:29.497  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 11:29:29.497  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:29.497  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 11:29:29.497  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:29.497  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:29.497  1015  1122 V NetworkStats: performPollLocked() took 7ms
,08-31 11:29:29.507  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:29.507  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:29.507  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:29.567  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 11:29:29.567  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:29.567  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:29.817  7271  7271 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:29:29.977  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 11:29:29.977  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:29.977  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:29.977  7271  7271 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-31 11:29:30.097  7004  7004 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-31 11:29:30.097  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-31 11:29:30.097  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:29:30.097  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:30.097  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:29:30.097  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:30.097  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:30.097  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:30.097  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:30.097  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:30.097  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-31 11:29:30.097  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:29:30.097  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,08-31 11:29:30.097  2006  2163 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:29:30.107  1177  1177 D HotspotTile: onReceive : 1, 0
,08-31 11:29:30.107  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 11:29:30.107  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 11:29:30.117  3067  3067 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:30.117  1015  1712 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:30.117  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:30.117  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:30.117  1015  1712 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:30.117  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:30.127  1638  1638 I Hs20UtilService: Starting #18
,08-31 11:29:30.127  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:30.127  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:30.127  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:30.127  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-31 11:29:30.127  1638  1717 I Hs20UtilService: Message received 5011
,08-31 11:29:30.327   290   290 E SMD     : DCD OFF
,08-31 11:29:30.697  1015  1043 D Tethering: interfaceRemoved wlan0
,08-31 11:29:30.697  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 11:29:30.847  1015  1043 D Tethering: interfaceRemoved p2p0
,08-31 11:29:30.847  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 11:29:31.647  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-31 11:29:31.677  1015  3371 D SSRM:n  : SIOP:: AP = 360,
,08-31 11:29:32.017  6736  6790 D BluetoothAdapter: enable()
,08-31 11:29:32.017  1015  1593 W ActivityManager: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:29:32.017  1015  1593 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 11:29:32.017  1015  1593 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:32.017  1015  1593 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:32.017  1015  1593 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 11:29:32.017  1015  1593 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 11:29:32.017  1015  1593 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 11:29:32.017  1015  1593 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 11:29:32.017  1015  1593 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-31 11:29:32.017  1015  1593 D SettingsProvider: name = bluetooth_on
08-31 11:29:32.017  1015  1593 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:32.027  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-31 11:29:32.027  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:32.027  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-31 11:29:32.027  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-31 11:29:32.027  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 11:29:32.027  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:32.027  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 11:29:32.027  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:32.047  1015  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7367 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-31 11:29:32.047  7367  7367 E Zygote  : MountEmulatedStorage()
08-31 11:29:32.047  7367  7367 E Zygote  : v2,
08-31 11:29:32.047  7367  7367 I libpersona: KNOX_SDCARD checking this for 1002
08-31 11:29:32.047  7367  7367 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:32.057  7367  7367 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:32.057  7367  7367 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 11:29:32.057  7367  7367 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 11:29:32.087  7367  7367 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:32.087  7367  7367 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:32.107  7367  7367 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 11:29:32.107  7367  7367 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:29:32.137  7367  7367 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 11:29:32.167  7367  7367 D BtSettings.ProfileConfig: Adding GattService
,08-31 11:29:32.167  7367  7367 D BtSettings.ProfileConfig: Adding HeadsetService
,08-31 11:29:32.167  7367  7367 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 11:29:32.167  7367  7367 D BtSettings.ProfileConfig: Adding HidService
,08-31 11:29:32.167  7367  7367 D BtSettings.ProfileConfig: Adding HealthService
,08-31 11:29:32.167  7367  7367 D BtSettings.ProfileConfig: Adding PanService
08-31 11:29:32.177  7367  7367 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-31 11:29:32.177  7367  7367 D BtSettings.ProfileConfig: Adding SapService
,08-31 11:29:32.177  7367  7367 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-31 11:29:32.177  7367  7367 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-31 11:29:32.177  7367  7367 D BtSettings.ProfileConfig: Adding SapClientService
08-31 11:29:32.177  7367  7367 D BtSettings.ProfileConfig: Adding HidDevService
,08-31 11:29:32.177  7367  7367 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 11:29:32.187  1015  1709 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 11:29:32.187  1015  1709 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.187  1015  1709 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.187  1015  1709 D SettingsProvider: selectionArgs: false
08-31 11:29:32.187  1015  1709 D SettingsProvider: selectionArgs: 1002
08-31 11:29:32.187  1015  1709 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.187  1015  1709 D SettingsProvider: ret = -1
,08-31 11:29:32.187  1015  1510 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:32.187  1015  1510 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.187  1015  1510 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.187  1015  1510 D SettingsProvider: selectionArgs: false
08-31 11:29:32.187  1015  1510 D SettingsProvider: selectionArgs: 1002
08-31 11:29:32.187  1015  1510 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.187  1015  1510 D SettingsProvider: ret = -1
,08-31 11:29:32.187  1015  1592 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 11:29:32.187  1015  1592 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.187  1015  1592 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.187  1015  1592 D SettingsProvider: selectionArgs: false
08-31 11:29:32.187  1015  1592 D SettingsProvider: selectionArgs: 1002
08-31 11:29:32.187  1015  1592 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.187  1015  1592 D SettingsProvider: ret = -1
,08-31 11:29:32.187  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 11:29:32.187  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.187  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.187  1015  1028 D SettingsProvider: selectionArgs: false
08-31 11:29:32.187  1015  1028 D SettingsProvider: selectionArgs: 1002
08-31 11:29:32.187  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.187  1015  1028 D SettingsProvider: ret = -1
,08-31 11:29:32.187  1015  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-31 11:29:32.187  1015  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.187  1015  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.187  1015  1499 D SettingsProvider: selectionArgs: false
08-31 11:29:32.187  1015  1499 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:32.187  1015  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.187  1015  1499 D SettingsProvider: ret = -1
,08-31 11:29:32.187  1015  1448 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 11:29:32.187  1015  1448 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.187  1015  1448 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.187  1015  1448 D SettingsProvider: selectionArgs: false
,08-31 11:29:32.187  1015  1448 D SettingsProvider: selectionArgs: 1002
08-31 11:29:32.187  1015  1448 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.187  1015  1448 D SettingsProvider: ret = -1
,08-31 11:29:32.187  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 11:29:32.187  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.187  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.187  1015  1133 D SettingsProvider: selectionArgs: false
,08-31 11:29:32.187  1015  1133 D SettingsProvider: selectionArgs: 1002
08-31 11:29:32.187  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.187  1015  1133 D SettingsProvider: ret = -1
,08-31 11:29:32.187  1015  1213 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-31 11:29:32.187  1015  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 11:29:32.187  1015  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.187  1015  1213 D SettingsProvider: selectionArgs: false
08-31 11:29:32.187  1015  1213 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:32.187  1015  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.187  1015  1213 D SettingsProvider: ret = -1
,08-31 11:29:32.197  1015  1379 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService,
,08-31 11:29:32.197  1015  1379 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.197  1015  1379 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.197  1015  1379 D SettingsProvider: selectionArgs: false
08-31 11:29:32.197  1015  1379 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:32.197  1015  1379 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.197  1015  1379 D SettingsProvider: ret = -1
08-31 11:29:32.197  1015  1594 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:32.197  1015  1594 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 11:29:32.197  1015  1594 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-31 11:29:32.197  1015  1594 D SettingsProvider: selectionArgs: false
08-31 11:29:32.197  1015  1594 D SettingsProvider: selectionArgs: 1002,
08-31 11:29:32.197  1015  1594 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.197  1015  1594 D SettingsProvider: ret = -1
,08-31 11:29:32.197  1015  1713 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-31 11:29:32.197  1015  1713 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.197  1015  1713 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-31 11:29:32.197  1015  1713 D SettingsProvider: selectionArgs: false,
08-31 11:29:32.197  1015  1713 D SettingsProvider: selectionArgs: 1002
08-31 11:29:32.197  1015  1713 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 11:29:32.197  1015  1713 D SettingsProvider: ret = -1
08-31 11:29:32.197  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-31 11:29:32.197  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.197  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:32.197  1015  1027 D SettingsProvider: selectionArgs: false,
08-31 11:29:32.197  1015  1027 D SettingsProvider: selectionArgs: 1002
08-31 11:29:32.197  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 11:29:32.197  1015  1027 D SettingsProvider: ret = -1
,08-31 11:29:32.227  7367  7367 D BluetoothAdapterState: make,
,08-31 11:29:32.227  7367  7367 I bluedroid: init,
,08-31 11:29:32.227  7367  7382 I BluetoothAdapterState: Entering OffState,
,08-31 11:29:32.227  7367  7367 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-31 11:29:32.227  7367  7367 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 11:29:32.227  7367  7367 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:29:32.227  7367  7367 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 11:29:32.237  7367  7367 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-31 11:29:32.237  7367  7367 I bluedroid: get_profile_interface socket
08-31 11:29:32.237  7367  7367 I bluedroid: get_profile_interface map_client
08-31 11:29:32.237  7367  7385 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 11:29:32.237  7367  7367 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 11:29:32.237  7367  7385 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-31 11:29:32.237  7367  7385 E BluetoothServiceJni: populateRssiValuesNative
,08-31 11:29:32.237  7367  7385 I bluedroid: getModelRssiValues
,08-31 11:29:32.237  7367  7385 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 11:29:32.237  7367  7385 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 11:29:32.247  1015  1015 D SettingsProvider: name = bluetooth_name
,08-31 11:29:32.247  7367  7385 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 11:29:32.247  7367  7367 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:32.247  1015  1213 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 11:29:32.247  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.257  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.257  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.257  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:32.257  7367  7379 I bluedroid: config_hci_snoop_log
,08-31 11:29:32.257  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-31 11:29:32.257  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-31 11:29:32.267  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-31 11:29:32.267  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 11:29:32.267  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 11:29:32.267  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:32.267  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:32.267  7367  7367 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-31 11:29:32.277  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 11:29:32.277  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 11:29:32.277  7367  7382 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-31 11:29:32.277  7367  7382 D BluetoothAdapterProperties: Setting state to 11
08-31 11:29:32.277  7367  7382 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:29:32.277  7367  7382 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:32.277  7367  7382 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 11:29:32.277  7367  7382 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:32.277  7367  7382 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 11:29:32.277  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:32.277  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-31 11:29:32.287  7367  7382 D BluetoothSecureManager: getInstant: null
,08-31 11:29:32.287  7367  7382 D BluetoothSecureManager: calling getMethod for getService
,08-31 11:29:32.287  7367  7382 D BluetoothSecureManager: calling getService
,08-31 11:29:32.287  7367  7382 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3bc945ee
,08-31 11:29:32.287  1015  1709 D BluetoothSecureManagerService: isSecureModeEnabled
,08-31 11:29:32.287  1015  1709 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-31 11:29:32.287  7367  7382 D BtConfig.SecureMode: isSecureModeOn:false
08-31 11:29:32.287  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 11:29:32.287  7367  7382 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-31 11:29:32.297  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:32.297  7367  7382 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:32.297  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:32.297  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:32.297  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:29:32.297  1177  1177 D BluetoothTile:  getBluetoothState : 11,
,08-31 11:29:32.297  7367  7382 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 11:29:32.297  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:32.297  3067  3067 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:32.297  7367  7382 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 11:29:32.297  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 11:29:32.297  7367  7382 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 11:29:32.297  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 11:29:32.307  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:32.307  1878  1878 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:32.307  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:32.307  3067  3067 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:32.317  7367  7382 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 11:29:32.317  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:32.317  7367  7382 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 11:29:32.317  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 11:29:32.317  7367  7382 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 11:29:32.317  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:29:32.317  7367  7382 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:32.317  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 11:29:32.317  7367  7382 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:32.317  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 11:29:32.317  7367  7382 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:32.317  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 11:29:32.317  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
08-31 11:29:32.317  7367  7382 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-31 11:29:32.317  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:29:32.317  1015  1594 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:32.317  1015  1133 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:29:32.317  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:29:32.327  7367  7382 D BluetoothBondStateMachine: make
,08-31 11:29:32.327  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-31 11:29:32.327  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 11:29:32.327  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 11:29:32.327  7367  7388 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 11:29:32.467  1015  1490 I art     : Explicit concurrent mark sweep GC freed 71141(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.544ms total 155.949ms
,08-31 11:29:32.467  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:32.467  1015  1712 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:32.467  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 11:29:32.467  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.467  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.467  1015  1712 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.467  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:32.467  1015  1593 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:32.467  1015  1593 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.467  7367  7367 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:29:32.467  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 11:29:32.467  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:29:32.467  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:32.467  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.467  7367  7367 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:29:32.467  7367  7367 D BtGatt.GattService: start()
08-31 11:29:32.467  7367  7367 D BtGatt.GattService: start()
08-31 11:29:32.467  7367  7367 I bluedroid: get_profile_interface gatt
08-31 11:29:32.467  1015  1593 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:32.467  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:32.467  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
08-31 11:29:32.467  7367  7367 D BtGatt.AdvertiseManager: advertise manager created
,08-31 11:29:32.477  1015  1713 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:32.477  1015  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.477  1015  1713 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:32.477  1015  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.477  1015  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:32.477  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 11:29:32.477  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:29:32.477  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:32.477  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 11:29:32.487  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:32.487  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:32.487  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:32.487  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:32.497  7391  7391 E Zygote  : MountEmulatedStorage(),
08-31 11:29:32.497  7391  7391 I libpersona: KNOX_SDCARD checking this for 10055
08-31 11:29:32.497  7391  7391 E Zygote  : v2
08-31 11:29:32.497  7391  7391 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:32.497  7391  7391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:32.497  7391  7391 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:32.497  7391  7391 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:32.497  1015  1028 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7391 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-31 11:29:32.497  1015  1379 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:32.497  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.497  1015  1379 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.497  1015  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.497  1015  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:32.507  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-31 11:29:32.507  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:32.507  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService,
,08-31 11:29:32.507  1015  1592 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:32.517  7367  7367 D BtGatt.GattService: mStartError = false
08-31 11:29:32.507  1015  1592 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 11:29:32.517  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:32.517  7367  7367 D HeadsetService: Received start request. Starting profile...
08-31 11:29:32.517  7367  7367 D HeadsetService: start()
,08-31 11:29:32.517  1015  1592 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:32.517  1015  1592 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.517  1015  1592 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:32.517  7367  7367 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 11:29:32.517  7367  7367 D HeadsetStateMachine: make
,08-31 11:29:32.517  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:29:32.517  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:29:32.517  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:29:32.517  1015  1448 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:32.517  1015  1448 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.527  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.527  1015  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.527  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:32.527  7367  7367 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 11:29:32.527  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 11:29:32.527  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:29:32.527  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:29:32.527  1015  1593 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:32.527  1015  1593 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.527  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.527  1015  1593 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.527  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:32.537  1015  1713 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-31 11:29:32.537  1015  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.537  1015  1713 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.537  1015  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.537  1015  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 11:29:32.537  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:32.537  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:32.537  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 11:29:32.537  7391  7391 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:32.537  1015  1593 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:32.537  7391  7391 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:32.537  1015  1593 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.537  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.537  1015  1593 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.537  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:32.537  1015  1594 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 11:29:32.537  1015  1594 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.537  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 11:29:32.537  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:32.537  7367  7382 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 11:29:32.537  1015  1594 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.537  1015  1594 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.537  1015  1594 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 11:29:32.537  7367  7367 I bluedroid: get_profile_interface handsfree
,08-31 11:29:32.547  1015  1709 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:32.547  1015  1709 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:32.547  1015  1709 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:32.547  1015  1709 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:32.547  1015  1709 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:32.547  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:29:32.547  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:29:32.547  7367  7382 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:32.547  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:32.547  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:32.547  7367  7382 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:32.547  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:29:32.547  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:32.547  7367  7382 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:29:32.547  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:29:32.547  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:29:32.547  7367  7382 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:29:32.557  7367  7382 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 11:29:32.567  7367  7367 I DualScoManager: Instantiating Dual Sco Manager
08-31 11:29:32.567  7367  7367 I DualScoManager: Set HeadsetServiceHelper
,08-31 11:29:32.567  7367  7367 D BluetoothAtMessage: createCMTIContentObservers
,08-31 11:29:32.567  1015  1028 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-31 11:29:32.567  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:32.567  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 11:29:32.567  1015  1028 D SettingsProvider: selectionArgs: false
08-31 11:29:32.567  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:32.567  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:32.567  1015  1028 D SettingsProvider: ret = -1
,08-31 11:29:32.567  7367  7402 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 11:29:32.567  7367  7367 D HeadsetService: mStartError = false
08-31 11:29:32.567  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:32.577  7367  7367 D A2dpService: Received start request. Starting profile...
08-31 11:29:32.577  7367  7367 D A2dpService: start()
,08-31 11:29:32.577  7367  7367 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 11:29:32.577  7367  7367 I bluedroid: get_profile_interface avrcp
,08-31 11:29:32.577  7367  7402 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 11:29:32.577  7367  7402 D HeadsetStateMachine: map size, before remove : 0
08-31 11:29:32.577  7367  7402 D HeadsetStateMachine: map size, after remove: 0
,08-31 11:29:32.577  7391  7391 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 11:29:32.587  7367  7367 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:29:32.587  7367  7367 D Avrcp   : Initialize Media Controller
,08-31 11:29:32.587  7367  7367 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 11:29:32.587  7367  7367 E Avrcp   : getActiveSessions
,08-31 11:29:32.587  7367  7367 D Avrcp   : pick active media Controller
08-31 11:29:32.587  7367  7367 D Avrcp   : Get the active Media Controller 
,08-31 11:29:32.597  7367  7367 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 11:29:32.607  7367  7411 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 11:29:32.607  7367  7367 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:29:32.607  7367  7367 D A2dpStateMachine: make
,08-31 11:29:32.617  7367  7367 I bluedroid: get_profile_interface a2dp
,08-31 11:29:32.617  7367  7411 D BluetoothMediaBrowser: no now playing list
08-31 11:29:32.617  7367  7411 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-31 11:29:32.617  7391  7391 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-31 11:29:32.617  7367  7413 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:29:32.617  7367  7367 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 11:29:32.617  7391  7391 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 11:29:32.617  7391  7391 D UserAnalysis: Create SecureDbHelper
,08-31 11:29:32.617  7367  7367 D A2dpService: mStartError = false
08-31 11:29:32.617  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:32.617  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-31 11:29:32.617  7367  7412 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:29:32.617  7367  7367 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 11:29:32.617  7367  7367 D HidService: Received start request. Starting profile...
08-31 11:29:32.617  7367  7367 D HidService: start()
08-31 11:29:32.617  7367  7367 I bluedroid: get_profile_interface hidhost
08-31 11:29:32.617  7367  7367 D HidService: setHidService(): set to: null
08-31 11:29:32.617  7367  7367 D HidService: mStartError = false
08-31 11:29:32.617  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:32.627  7367  7367 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 11:29:32.627  7391  7391 D IntelligenceServiceApplication: onCreate()
,08-31 11:29:32.627  7367  7367 D HealthService: Received start request. Starting profile...
,08-31 11:29:32.627  7367  7367 D HealthService: start()
,08-31 11:29:32.627  1015  1480 I ActivityManager: Killing 7045:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-31 11:29:32.627  7367  7367 I bluedroid: get_profile_interface health
,08-31 11:29:32.627  7367  7367 D HealthService: mStartError = false
08-31 11:29:32.627  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:32.627  7367  7367 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 11:29:32.637  7367  7367 D PanService: Received start request. Starting profile...
08-31 11:29:32.637  7367  7367 D PanService: start()
08-31 11:29:32.637  7367  7367 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:29:32.637  7367  7367 I bluedroid: get_profile_interface pan
,08-31 11:29:32.637  7367  7367 D PanService: mStartError = false
08-31 11:29:32.637  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:32.637  7367  7367 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 11:29:32.637  7391  7391 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 11:29:32.637  1428  1463 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 11:29:32.637  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-31 11:29:32.637  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 11:29:32.637  1428  1463 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 11:29:32.637  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-31 11:29:32.637  7391  7391 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 11:29:32.637  7367  7367 D BluetoothMapService: Received start request. Starting profile...
,08-31 11:29:32.637  7367  7367 D BluetoothMapService: start()
,08-31 11:29:32.647  7367  7367 D BluetoothMapService: mStartError = false
08-31 11:29:32.647  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:32.647  7367  7367 D HeadsetStateMachine: Proxy object connected
08-31 11:29:32.647  7367  7367 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 11:29:32.647  7367  7402 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:29:32.647  7367  7367 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-31 11:29:32.647  7367  7367 D SapService: Received start request. Starting profile...
08-31 11:29:32.647  7367  7367 D SapService: start()
08-31 11:29:32.647  7367  7367 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 11:29:32.647  7367  7367 I bluedroid: get_profile_interface sap
08-31 11:29:32.647  7367  7367 D SapService: mStartError = false
08-31 11:29:32.647  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
08-31 11:29:32.647  7367  7367 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-31 11:29:32.647  7367  7367 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 11:29:32.647  7367  7402 D HeadsetStateMachine: Disconnected process message: 18
08-31 11:29:32.647  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 11:29:32.647  7367  7367 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:29:32.647  7367  7367 D BluetoothA2dp: Proxy object connected
08-31 11:29:32.647  7367  7367 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-31 11:29:32.647  7367  7402 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:29:32.647  7367  7402 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:29:32.647  7367  7402 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:29:32.647  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 11:29:32.647  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-31 11:29:32.647  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-31 11:29:32.647  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-31 11:29:32.647  1015  1593 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 11:29:32.657  7391  7391 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 11:29:32.657  1015  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:32.657  1015  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:32.657  1015  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:32.657  1015  1593 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:32.667  7418  7418 E Zygote  : MountEmulatedStorage(),
08-31 11:29:32.667  7418  7418 I libpersona: KNOX_SDCARD checking this for 10105
08-31 11:29:32.667  7418  7418 E Zygote  : v2
08-31 11:29:32.667  7418  7418 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:32.667  7418  7418 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 11:29:32.667  1015  1593 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7418 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-31 11:29:32.677  7418  7418 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 11:29:32.677  7418  7418 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:29:32.697  7418  7418 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:32.697  7418  7418 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:32.697  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-31 11:29:32.697  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 11:29:32.707  7367  7382 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-31 11:29:32.707  7367  7382 I bluedroid: enable
,08-31 11:29:32.707  7367  7431 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-31 11:29:32.707  7367  7382 I bt_hci_bdroid: init
,08-31 11:29:32.717  7367  7382 I bt_vendor: bt-vendor : init
08-31 11:29:32.717  7367  7382 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 11:29:32.717  7367  7382 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 11:29:32.717  7367  7382 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-31 11:29:32.717  7367  7382 D bt_userial_mct: userial_init
,08-31 11:29:32.717  7367  7382 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 11:29:32.717  7367  7382 I bt_vendor: Starting hciattach daemon
08-31 11:29:32.717  7367  7382 I bt_vendor: try to set false
,08-31 11:29:32.717  7367  7382 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-31 11:29:32.717  7367  7382 I bt_vendor: Starting hciattach daemon
08-31 11:29:32.717  7367  7382 I bt_vendor: try to set true
,08-31 11:29:32.737  7438  7438 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 11:29:32.797  7444  7444 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-31 11:29:32.807  7447  7447 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:29:32.827  7449  7449 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 11:29:32.837  7450  7450 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 11:29:32.847  7451  7451 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 11:29:32.847  7452  7452 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-31 11:29:32.877   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:29:32.877   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:32.877  7418  7455 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:29:32.887   256   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:29:32.887   256   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:32.887  7418  7455 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:29:33.057  7418  7418 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:33.057  7418  7418 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:33.057  7418  7418 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:33.057  7418  7418 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:33.057  7418  7418 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:33.057  7418  7418 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:33.057  7418  7418 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:33.057  7418  7418 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:33.057  7418  7418 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:33.067  1015  1133 I ActivityManager: Killing 7058:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-31 11:29:33.067  2006  2006 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 11:29:33.067  2006  2006 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 11:29:33.117  7418  7466 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 11:29:33.137  7468  7468 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-31 11:29:33.147  7469  7469 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 11:29:33.147  1015  1593 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:33.157  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.157  1015  1593 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:33.157  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 11:29:33.167  7367  7382 I bt_vendor: bluetooth satus is on
,08-31 11:29:33.177  7367  7433 D bt_userial_mct: userial_open(port:0)
08-31 11:29:33.177  7367  7433 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 11:29:33.177  7367  7433 I bt_vendor: Done intiailizing UART
,08-31 11:29:33.177  7367  7433 I bt_vendor: Done intiailizing UART
,08-31 11:29:33.177  7367  7433 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-31 11:29:33.177  7367  7433 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_SAP
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 11:29:33.187  7367  7431 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 11:29:33.187  7367  7472 D bt_userial_mct: Entering userial_read_thread(),
,08-31 11:29:33.277  7367  7431 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-31 11:29:33.287  7367  7431 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4247ed1 
,08-31 11:29:33.287  7367  7431 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4247ed1 
,08-31 11:29:33.297  7367  7385 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 11:29:33.307  7367  7385 E bt-btif : Calling BTA_HhEnable
,08-31 11:29:33.307  7367  7385 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 11:29:33.307  7367  7385 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-31 11:29:33.307  7367  7385 E BluetoothServiceJni: populateRssiValuesNative
,08-31 11:29:33.307  7367  7385 I bluedroid: getModelRssiValues
08-31 11:29:33.307  7367  7385 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-31 11:29:33.307  7367  7385 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 11:29:33.307  1015  1015 D SettingsProvider: name = bluetooth_name
,08-31 11:29:33.307  7367  7385 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 11:29:33.317  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.317  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.327  7367  7385 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 11:29:33.327  7367  7385 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:29:33.327  7367  7385 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:29:33.327  7367  7385 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-31 11:29:33.327  7367  7385 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-31 11:29:33.327  7367  7385 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-31 11:29:33.327  7367  7385 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 11:29:33.327  7367  7385 E bt-btif : btif_sock_init: !vhci_init
08-31 11:29:33.327  7367  7385 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 11:29:33.327  7367  7385 D IOP_DB_BT: db_open: db_open : handle 2963218448l, read 13894 bytes onto local cache
,08-31 11:29:33.327  7367  7385 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-31 11:29:33.327  7367  7472 E bt_mct  : hci lib postload completed
,08-31 11:29:33.327   290   290 E SMD     : DCD OFF
,08-31 11:29:33.337  7367  7385 D IOP_DB_BT: db_query: result 1
08-31 11:29:33.337  7367  7385 I         : iop_db_open: iop_db_open status 0
,08-31 11:29:33.337  7367  7385 D bte_conf: Device ID record 1 : primary
08-31 11:29:33.337  7367  7385 D bte_conf:   vendorId            = 0075
08-31 11:29:33.337  7367  7385 D bte_conf:   vendorIdSource      = 0001
,08-31 11:29:33.337  7367  7385 D bte_conf:   product             = 0100
08-31 11:29:33.337  7367  7385 D bte_conf:   version             = 0200
08-31 11:29:33.337  7367  7385 D bte_conf:   clientExecutableURL = ,
08-31 11:29:33.337  7367  7385 D bte_conf:   serviceDescription  = 
08-31 11:29:33.337  7367  7385 D bte_conf:   documentationURL    = 
08-31 11:29:33.337  7367  7385 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 11:29:33.337  7367  7385 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:29:33.337  7367  7382 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 11:29:33.337  7367  7382 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:29:33.337  7367  7382 D BluetoothAdapterProperties: State =  11
,08-31 11:29:33.337  1015  1379 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 11:29:33.337  7367  7382 D BluetoothAdapterProperties: Setting state to 12
08-31 11:29:33.337  7367  7382 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 11:29:33.337  1015  1499 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-31 11:29:33.347  1015  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:33.347  1015  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:33.347  1015  1499 D SettingsProvider: selectionArgs: false
,08-31 11:29:33.347  1015  1499 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:33.347  1015  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:33.347  1015  1499 D SettingsProvider: ret = -1
,08-31 11:29:33.347  7367  7385 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 11:29:33.347  7367  7382 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:33.347  7367  7385 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:29:33.347  7367  7385 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:29:33.347  7367  7382 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 11:29:33.347  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:33.347  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.347  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.347  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:33.357  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.357  7367  7382 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:33.357  7367  7382 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 11:29:33.357  7367  7382 D BluetoothAdapterService: starting service from this receiver
08-31 11:29:33.357  3067  3077 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:29:33.357  1015  1712 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:33.357  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.367  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.367  1015  1712 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.367  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.367  7367  7382 I BluetoothAdapterState: Entering On State from state = 11
,08-31 11:29:33.367  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:33.367  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.367  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.367  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:33.367  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:33.367  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:33.367  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:33.367  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:33.367  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-31 11:29:33.377  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.377  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:33.377  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.377  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.377  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.377  1450  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:33.377  1450  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:33.377  3067  6873 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:33.377  7367  7367 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 11:29:33.377  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 11:29:33.377  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:33.377  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.377  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.377  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.387  3067  6873 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:33.387  3067  3071 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:29:33.387  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:33.387  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.387  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.387  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:33.387  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:33.387  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:33.387  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:33.387  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:33.387  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-31 11:29:33.387  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.387  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.387  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.387  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.387  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:29:33.387  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-31 11:29:33.387  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:33.387  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:29:33.387  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.387  1015  1015 D BluetoothA2dp: Proxy object connected
08-31 11:29:33.387  1440  1455 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:33.387  1440  1455 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:33.387  3067  3077 D BluetoothPan: Binding service...
,08-31 11:29:33.397  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:29:33.397  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.397  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.397  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:33.397  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.397  3067  6873 D Bluetoothsap: onBluetoothStateChange: up=true
08-31 11:29:33.397  3067  6873 D Bluetoothsap: Binding service...
,08-31 11:29:33.397  3067  3067 D BluetoothPbap: Proxy object connected
08-31 11:29:33.397  7367  7367 I BluetoothPbapService: Handler(): got msg=1
08-31 11:29:33.397  3067  3067 D PbapServerProfile: Bluetooth service connected
,08-31 11:29:33.407  1015  1713 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 11:29:33.407  3067  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 11:29:33.407  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-31 11:29:33.407  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.407  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.407  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.407  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.407  3067  6873 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-31 11:29:33.407  1015  1045 D BluetoothPan: Binding service...
,08-31 11:29:33.407  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:29:33.407  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 11:29:33.407  7367  7379 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:33.407  7367  7379 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:33.407  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:29:33.407  3067  3067 D HeadsetProfile: Bluetooth service connected
,08-31 11:29:33.417  1428  6926 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:33.417  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:33.417  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:33.417  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.417  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.417  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.417  1428  6926 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:33.417  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:33.417  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:33.417  3067  3077 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:33.417  3067  3077 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:33.417  3067  6873 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:33.417  7367  7476 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 11:29:33.417  3067  3067 D BluetoothInputDevice: Proxy object connected
,08-31 11:29:33.417  3067  3067 D HidProfile: Bluetooth service connected
08-31 11:29:33.417  3067  6873 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:33.417  7367  7476 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 11:29:33.417  7367  7476 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:33.417  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:29:33.417  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.417  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.417  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.417  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.427  2006  2015 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:33.427  2006  2015 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:33.427  7367  7476 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-31 11:29:33.427  7367  7476 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:33.427  7367  7476 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:33.427  7367  7476 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10065603
08-31 11:29:33.427  7367  7476 D BluetoothSocket: channel: 19
08-31 11:29:33.427  3067  3067 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:29:33.427  3067  3067 D PanProfile: Bluetooth service connected
,08-31 11:29:33.427  7367  7476 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-31 11:29:33.427  1428  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:33.427  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 11:29:33.427  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:33.427  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.427  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.427  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.427  1428  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:33.427  7418  7426 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:33.427  3067  3067 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 11:29:33.427  3067  3067 D SapProfile: Bluetooth service connected
08-31 11:29:33.427  3067  3067 D Bluetoothsap: getConnectedDevices()
08-31 11:29:33.427  7418  7426 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:33.427  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:33.427  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:33.427  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 11:29:33.427  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:33.437  3067  3067 D BluetoothA2dp: Proxy object connected
,08-31 11:29:33.437  3067  3067 D A2dpProfile: Bluetooth service connected
08-31 11:29:33.437  1450  1700 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:33.437  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:33.437  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:33.437  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.437  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.437  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.437  1450  1700 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 11:29:33.437  3067  3071 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:29:33.437  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-31 11:29:33.437  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.437  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.437  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.437  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.437  1428  6926 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:33.447  3067  3067 D BluetoothMap: Proxy object connected
,08-31 11:29:33.447  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:33.447  3067  3067 D MapProfile: Bluetooth service connected
08-31 11:29:33.447  3067  3067 D BluetoothMap: getConnectedDevices()
08-31 11:29:33.447  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:33.447  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.447  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.447  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.447  1428  6926 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:33.447  1177  6516 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:33.447  1177  6516 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:33.447  7367  7381 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:33.447  6736  6988 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:33.447  6736  6988 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:33.447  1428  1463 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:33.447  1428  1463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:33.447  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 11:29:33.447  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 11:29:33.447  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:33.447  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
,08-31 11:29:33.447  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:29:33.457  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@13436c6f, true
,08-31 11:29:33.457  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:29:33.457  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:29:33.457  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:33.457  1878  1878 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:33.457  1428  1428 D BluetoothHeadset: registerMessageListener
,08-31 11:29:33.457  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-31 11:29:33.457  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:33.467  3067  3067 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:33.467  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:33.467  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.467  1015  1480 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:33.467  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.467  1015  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 11:29:33.477  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 11:29:33.477  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:33.477  1015  1448 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:33.477  7367  7379 D HeadsetService: registerMessageListener
08-31 11:29:33.477  1015  1448 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.477  7367  7379 D HeadsetService: registerMessageListener
08-31 11:29:33.477  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.477  1015  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:33.477  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:33.477  7367  7402 D HeadsetStateMachine: Disconnected process message: 70
08-31 11:29:33.477  7367  7402 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@a39b980
,08-31 11:29:33.477  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-31 11:29:33.477  3067  3067 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-31 11:29:33.477  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 11:29:33.477  3067  3067 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-31 11:29:33.477  3067  3067 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 11:29:33.477  3067  3067 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 11:29:33.487  7367  7478 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 11:29:33.487  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-31 11:29:33.487  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 11:29:33.487  7367  7478 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:29:33.487  7367  7478 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:33.487  7367  7478 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-31 11:29:33.487  7367  7478 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:33.487  7367  7478 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:33.487  7367  7478 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a192bb9
,08-31 11:29:33.487  7367  7478 D BluetoothSocket: channel: 5
,08-31 11:29:33.487  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 11:29:33.487  3067  3067 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:33.497  1015  1499 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:29:33.497  1015  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.497  1015  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.497  1015  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-31 11:29:33.497  1015  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:33.497  7367  7402 D HeadsetStateMachine: Disconnected process message: 9
,08-31 11:29:33.497  7367  7402 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 11:29:33.507  3067  3067 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:33.507  3067  3067 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:33.507   282   704 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-31 11:29:33.507   282   704 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 11:29:33.507   282   704 V voice   : voice_set_parameters: exit with code(-2)
08-31 11:29:33.507   282   704 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 11:29:33.507   282   704 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 11:29:33.507   282   704 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 11:29:33.507   282   704 V audio_hw_primary: adev_set_parameters: exit
08-31 11:29:33.507  7367  7402 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 11:29:33.517  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:33.517  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 11:29:33.527  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
08-31 11:29:33.527  7367  7367 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 11:29:33.527  1015  1510 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:33.527  1015  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.527  1015  1510 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.527  1015  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.527  1015  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.537  2006  2006 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:33.537  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:33.537  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.537  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.537  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:33.537  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:33.547  2006  7484 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 11:29:33.547  2006  2006 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 11:29:33.547  1015  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:33.557  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.557  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:33.557  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:33.567  1015  1510 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 11:29:33.567  1015  1593 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:33.577  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.577  1015  1593 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:29:33.577  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:33.587  7367  7488 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 11:29:33.587  7367  7488 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:33.587  2006  7484 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 11:29:33.587  7367  7488 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-31 11:29:33.587  7367  7488 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:33.587  7367  7488 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:33.587  7367  7488 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1072827b
,08-31 11:29:33.587  7367  7488 D BluetoothSocket: channel: 12
,08-31 11:29:33.587  7367  7488 I BtOppRfcommListener: Accept thread started.
,08-31 11:29:35.027  6736  6790 D BluetoothAdapter: disable()
,08-31 11:29:35.027  1015  1593 D SettingsProvider: name = bluetooth_on
,08-31 11:29:35.037  7367  7382 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-31 11:29:35.037  7367  7382 D BluetoothAdapterProperties: Setting state to 13
,08-31 11:29:35.037  7367  7382 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 11:29:35.037  7367  7382 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 11:29:35.037  7367  7382 D BluetoothAdapterService: updateAdapterState state is 13
,08-31 11:29:35.037  1015  1379 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:35.037  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
,08-31 11:29:35.047  1015  1379 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.047  1015  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.047  1015  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:35.047  7367  7367 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-31 11:29:35.047  7367  7367 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@aa53898, channel: 19, state: LISTENING
,08-31 11:29:35.047  7367  7367 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@aa53898, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10065603, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d2798f1mSocket: android.net.LocalSocket@15dbbcd6 impl:android.net.LocalSocketImpl@259ccb57 fd:FileDescriptor[74]
08-31 11:29:35.047  7367  7367 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15dbbcd6 impl:android.net.LocalSocketImpl@259ccb57 fd:FileDescriptor[74]
,08-31 11:29:35.047  7367  7382 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:35.047  7367  7382 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 11:29:35.047  7367  7382 D BluetoothAdapterService: terminating service from this receiver
,08-31 11:29:35.047  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-31 11:29:35.047  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.047  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.047  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:35.057  3067  3067 D BluetoothPbap: Proxy object disconnected
08-31 11:29:35.057  3067  3067 D PbapServerProfile: Bluetooth service disconnected
,08-31 11:29:35.057  7367  7382 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 11:29:35.057  7367  7382 D BluetoothAdapterProperties: mDiscovering is false
,08-31 11:29:35.057  1015  1712 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 11:29:35.057  7367  7382 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 11:29:35.057  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:35.067  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
08-31 11:29:35.067  7367  7385 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-31 11:29:35.067  7367  7385 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:29:35.077  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:29:35.077  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:29:35.077  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:35.077  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:35.077  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-31 11:29:35.077  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:35.087  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:29:35.087  1015  1448 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:35.087  1015  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:29:35.087  1878  1878 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:35.087  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:29:35.097  3067  3067 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:35.097  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:35.097  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:35.097  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:35.097  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:35.097  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:35.097  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:35.097  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:35.097  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:35.097  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:35.097  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:35.097  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:35.107  1015  1592 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:35.107  1015  1592 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.107  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:35.107  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:35.107  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:35.107  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:35.107  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:35.107  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:35.107  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:35.107  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:35.107  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:35.107  7367  7382 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 11:29:35.107  7367  7382 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-31 11:29:35.107  1015  1592 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:35.107  1015  1592 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:35.107  1015  1592 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:35.107  6736  6736 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:35.107  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:35.107  7367  7382 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-31 11:29:35.107  7367  7382 E bt-btif : cmd socket is not created
,08-31 11:29:35.107  7367  7382 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 11:29:35.117  7367  7431 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-31 11:29:35.117  7367  7431 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 11:29:35.117  7367  7431 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:35.117  7367  7431 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:35.117  7367  7431 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:29:35.117  7367  7488 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 11:29:35.117  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:35.117  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:35.117  3067  3067 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:35.117  1015  1593 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:29:35.117  1015  1593 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.127  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.127  1015  1593 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.127  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:35.137  3067  3067 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:35.137  3067  3067 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:35.137  7367  7367 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e8bd32d, channel: 5, state: LISTENING
08-31 11:29:35.137  7367  7367 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e8bd32d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a192bb9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2daed062mSocket: android.net.LocalSocket@4b8c5f3 impl:android.net.LocalSocketImpl@1bee82b0 fd:FileDescriptor[76]
08-31 11:29:35.137  7367  7367 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4b8c5f3 impl:android.net.LocalSocketImpl@1bee82b0 fd:FileDescriptor[76]
,08-31 11:29:35.147  7367  7367 I BtOppRfcommListener: stopping Accept Thread
08-31 11:29:35.147  7367  7367 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@147f7529, channel: 12, state: LISTENING
08-31 11:29:35.147  7367  7367 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@147f7529, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1072827b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16ad90aemSocket: android.net.LocalSocket@1e8fce4f impl:android.net.LocalSocketImpl@343119dc fd:FileDescriptor[80]
08-31 11:29:35.147  7367  7367 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e8fce4f impl:android.net.LocalSocketImpl@343119dc fd:FileDescriptor[80]
,08-31 11:29:35.147  7367  7488 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 11:29:35.147  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:35.147  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 11:29:35.147  7367  7367 V BluetoothOppManager: cleanUp...
,08-31 11:29:35.177  2006  2006 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:35.177  2006  2006 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 11:29:35.317  7367  7431 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 11:29:35.317  7367  7431 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:35.317  7367  7431 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
08-31 11:29:35.317  7367  7431 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:35.317  7367  7431 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 11:29:35.317  7367  7431 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:29:35.317  7367  7431 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 11:29:35.317  7367  7431 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:35.317  7367  7431 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 11:29:35.317  7367  7431 W bt-btif : ag scb idx 1 not allocated
08-31 11:29:35.317  7367  7431 W bt-btif : ag scb idx 2 not allocated
,08-31 11:29:35.317  7367  7431 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 11:29:35.317  7367  7472 I bt_userial_mct: exiting userial_read_thread
,08-31 11:29:35.317  7367  7472 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 11:29:35.317  7367  7385 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-31 11:29:35.317  7367  7433 I bt_vendor: hw_epilog_process
08-31 11:29:35.317  7367  7385 D bt_userial_mct: userial_close
,08-31 11:29:35.317  7367  7385 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-31 11:29:35.577  1015  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 11:29:35.577  1015  1133 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-31 11:29:35.577  1015  1133 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-31 11:29:35.577  1015  1133 D BatteryService: stay LED for fully charged
,08-31 11:29:35.577  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:29:35.587  1015  1015 I MotionRecognitionService: Plugged
,08-31 11:29:35.587  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:29:35.587  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-31 11:29:35.587  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 11:29:35.587  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 11:29:35.587  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:29:35.607  7367  7367 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:29:35.607  7367  7402 D HeadsetStateMachine: Disconnected process message: 10
,08-31 11:29:35.607  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 11:29:35.617  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 11:29:35.617  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 11:29:35.617  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 11:29:35.617  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-31 11:29:35.657  7367  7385 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-31 11:29:35.657  7367  7385 I bt_vendor: bluetooth satus is on
,08-31 11:29:35.657  7367  7385 I bt_vendor: bt-vendor : resetting BT status
,08-31 11:29:35.657  7367  7385 I bt_vendor: Starting hciattach daemon
08-31 11:29:35.657  7367  7385 I bt_vendor: try to set false,
,08-31 11:29:35.657  7367  7385 I bt_vendor: Starting hciattach daemon
,08-31 11:29:35.657  7367  7385 I bt_vendor: try to set false
,08-31 11:29:35.657  7367  7385 I bt_vendor: cleanup
,08-31 11:29:35.667  7367  7431 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-31 11:29:35.667  7367  7385 I GKI_LINUX: GKI_exit_task 0 done
08-31 11:29:35.667  7367  7385 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-31 11:29:35.667  7367  7382 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-31 11:29:35.667  1015  1713 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:35.667  7367  7382 D BtConfig.SecureMode: isSecureModeOn:false
08-31 11:29:35.667  1015  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-31 11:29:35.667  7367  7382 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 11:29:35.667  1015  1448 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:35.667  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-31 11:29:35.667  1015  1448 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 11:29:35.667  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 11:29:35.667  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-31 11:29:35.667  1015  1713 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.667  1015  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.667  1015  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:35.667  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-31 11:29:35.667  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:29:35.677  1015  1712 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:35.667  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 11:29:35.677  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 11:29:35.667  7367  7367 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 11:29:35.677  1015  1213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:35.667  7367  7367 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 11:29:35.677  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 11:29:35.667  7367  7367 D BtGatt.GattService: stop()
08-31 11:29:35.667  7367  7367 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 11:29:35.667  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.667  1015  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.667  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:35.677  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 11:29:35.677  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:29:35.677  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 11:29:35.677  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
08-31 11:29:35.677  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.677  1015  1712 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.677  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:35.677  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 11:29:35.677  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:35.677  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-31 11:29:35.677  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.677  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.677  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:35.677  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:29:35.677  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:29:35.677  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:29:35.677  1015  1594 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:35.687  1015  1594 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.677  1015  1594 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-31 11:29:35.687  1015  1594 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.687  1015  1594 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:35.687  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 11:29:35.687  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:29:35.687  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-31 11:29:35.687  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:35.687  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.687  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.687  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:35.687  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:35.687  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 11:29:35.687  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:35.687  1015  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:35.687  7367  7382 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 11:29:35.687  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.697  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.697  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:35.697  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 11:29:35.697  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 11:29:35.697  1015  1592 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:35.697  1015  1592 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.697  1015  1592 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.697  1015  1592 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.697  1015  1592 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:35.697  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:35.697  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:29:35.697  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:29:35.697  7367  7382 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:29:35.697  7367  7382 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:29:35.697  7367  7382 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 11:29:35.697  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-31 11:29:35.697  7367  7367 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:29:35.697  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
08-31 11:29:35.697  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 11:29:35.707  3067  3067 D HeadsetProfile: Bluetooth service disconnected
,08-31 11:29:35.707  7367  7367 D A2dpService: Received stop request...Stopping profile...
,08-31 11:29:35.707  7367  7412 D A2dpStateMachine: Exit Disconnected: -1
,08-31 11:29:35.707  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:35.707  1015  1015 D BluetoothA2dp: Proxy object disconnected
,08-31 11:29:35.707  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 11:29:35.707  7367  7367 D HidService: Received stop request...Stopping profile...
08-31 11:29:35.707  7367  7367 D HidService: Stopping Bluetooth HidService
08-31 11:29:35.707  7367  7367 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:29:35.707  7367  7367 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 11:29:35.707  7367  7367 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:29:35.707  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:35.707  3067  3067 D BluetoothA2dp: Proxy object disconnected
08-31 11:29:35.707  3067  3067 D A2dpProfile: Bluetooth service disconnected
08-31 11:29:35.717  3067  3067 D BluetoothInputDevice: Proxy object disconnected
08-31 11:29:35.717  3067  3067 D HidProfile: Bluetooth service disconnected
,08-31 11:29:35.717  7367  7367 D HealthService: Received stop request...Stopping profile...
08-31 11:29:35.717  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:35.717  7367  7367 D PanService: Received stop request...Stopping profile...,
,08-31 11:29:35.717  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:35.717  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 11:29:35.717  7367  7367 D BluetoothMapService: Received stop request...Stopping profile...
08-31 11:29:35.717  3067  3067 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:29:35.717  3067  3067 D PanProfile: Bluetooth service disconnected
,08-31 11:29:35.717  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
,08-31 11:29:35.717  7367  7367 D SapService: Received stop request...Stopping profile...,
08-31 11:29:35.727  7367  7367 D SapService: Stopping Bluetooth SapService
08-31 11:29:35.727  7367  7367 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1552d331
08-31 11:29:35.727  3067  3067 D BluetoothMap: Proxy object disconnected
,08-31 11:29:35.727  3067  3067 D MapProfile: Bluetooth service disconnected
,08-31 11:29:35.727  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 11:29:35.727  7367  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:35.727  7367  7367 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-31 11:29:35.727  3067  3067 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 11:29:35.727  3067  3067 D SapProfile: Bluetooth service disconnected
,08-31 11:29:35.727  7367  7367 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 11:29:35.727  7367  7367 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 11:29:35.727  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-31 11:29:35.727  7367  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:35.727  7367  7367 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 11:29:35.727  7367  7367 D BluetoothA2dp: Proxy object disconnected,
08-31 11:29:35.727  7367  7367 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-31 11:29:35.727  7367  7413 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-31 11:29:35.727  7367  7367 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:29:35.727  7367  7367 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated,
08-31 11:29:35.727  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 11:29:35.727  7367  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:35.727  7367  7367 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:35.727  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true,
,08-31 11:29:35.727  7367  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:35.727  7367  7367 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:35.727  7367  7367 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:29:35.727  7367  7367 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:29:35.727  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true,
08-31 11:29:35.727  7367  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:35.727  7367  7367 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:35.727  7367  7367 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...,
08-31 11:29:35.727  7367  7367 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 11:29:35.727  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-31 11:29:35.727  7367  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:35.727  7367  7367 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-31 11:29:35.727  7367  7367 E BluetoothAdapterService(357749553): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-31 11:29:35.727  7367  7367 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 11:29:35.727  7367  7367 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-31 11:29:35.727  7367  7382 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:29:35.727  7367  7382 D BluetoothAdapterProperties: Setting state to 10
,08-31 11:29:35.727  7367  7382 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:29:35.727  7367  7382 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:35.727  7367  7382 D BluetoothAdapterService: updateAdapterState state is 10
08-31 11:29:35.737  7367  7382 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:35.737  7367  7382 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-31 11:29:35.737  7367  7382 I BluetoothAdapterState: Entering OffState
08-31 11:29:35.737  3067  3077 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 11:29:35.737  1450  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:35.737  1450  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:35.737  3067  6873 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 11:29:35.737  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:29:35.737  1440  1455 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:35.737  1440  1455 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:35.737  3067  3071 D Bluetoothsap: onBluetoothStateChange: up=false
,08-31 11:29:35.737  3067  3071 D Bluetoothsap: Unbinding service...
,08-31 11:29:35.737  7367  7386 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:35.737  7367  7386 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:35.747  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:35.747  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:35.747  3067  6873 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:35.747  3067  6873 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:35.747  3067  3077 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:29:35.747  2006  2015 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:35.747  2006  2015 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:35.747  7418  7428 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:35.747  7418  7428 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:35.747  3067  3071 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 11:29:35.747  1177  1964 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:35.747  1177  1964 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:35.747  7367  7387 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:29:35.747  6736  6750 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:35.747  6736  6750 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:35.747  6736  6750 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-31 11:29:35.757  6736  6750 D BluetoothLeAdvertiser: Exit stop advertising
,08-31 11:29:35.757  6736  6750 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 11:29:35.757  6736  6750 D BluetoothLeScanner: Exiting stopAllScan
,08-31 11:29:35.757  1428  1463 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:35.757  1428  1463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:35.757  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 11:29:35.757  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 11:29:35.767  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:35.767  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-31 11:29:35.767  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:29:35.767  1177  1177 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
,08-31 11:29:35.767  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:29:35.777  1177  1628 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
08-31 11:29:35.777  7367  7385 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 11:29:35.777  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:35.777  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-31 11:29:35.777  7367  7367 I GKI_LINUX: GKI_exit_task 1 done
08-31 11:29:35.777  7367  7367 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-31 11:29:35.777  7367  7367 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 11:29:35.777  1177  1628 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
,08-31 11:29:35.777  1177  1177 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
,08-31 11:29:35.777  1878  1878 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:35.777  1177  1177 D BluetoothAdapter: 684883832: getState() :  mService = null. Returning STATE_OFF
,08-31 11:29:35.777  1015  1713 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:35.777  2006  2163 D BluetoothAdapter: 806912991: getState() :  mService = null. Returning STATE_OFF
08-31 11:29:35.777  2006  2163 D BluetoothAdapter: 806912991: getState() :  mService = null. Returning STATE_OFF
,08-31 11:29:35.777  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:35.777  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:35.787  1015  1593 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:29:35.787  3067  3067 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:35.787  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:35.787  1015  1510 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:35.787  1015  1510 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.787  3067  3067 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 11:29:35.787  7367  7367 I art     : System.exit called, status: 0
08-31 11:29:35.787  7367  7367 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 11:29:35.787  1015  1510 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.787  1015  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:35.787  1015  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:35.787  1015  1480 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 11:29:35.787  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.797  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.797  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.797  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:35.797  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:29:35.807  3067  3067 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:35.807  3067  3067 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:35.817  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:35.817  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 11:29:35.827  1015  1713 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 11:29:35.827  1015  1713 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-31 11:29:35.827  1015  1713 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-31 11:29:35.827  1015  1713 W BroadcastQueue: android.os.TransactionTooLargeException
08-31 11:29:35.827  1015  1713 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:29:35.827  1015  1713 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:29:35.827  1015  1713 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-31 11:29:35.827  1015  1713 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-31 11:29:35.827  1015  1713 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-31 11:29:35.827  1015  1713 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-31 11:29:35.827  1015  1713 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-31 11:29:35.827  1015  1713 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-31 11:29:35.827  1015  1713 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:29:35.827  1015  1713 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-31 11:29:35.837  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.837  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.837  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.837  1015  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.847  7504  7504 E Zygote  : MountEmulatedStorage()
08-31 11:29:35.847  1015  1713 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7504 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-31 11:29:35.847  7504  7504 E Zygote  : v2
08-31 11:29:35.847  7504  7504 I libpersona: KNOX_SDCARD checking this for 1002
08-31 11:29:35.847  7504  7504 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:35.847  7504  7504 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:35.857  7504  7504 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:35.857  7504  7504 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:35.877  7504  7504 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:35.877  7504  7504 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:35.887  7504  7504 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 11:29:35.887  7504  7504 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:29:35.917  7504  7504 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding GattService
,08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding HeadsetService
08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding HidService
08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding HealthService
08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding PanService
,08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding SapService
08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding SapClientService
,08-31 11:29:35.957  7504  7504 D BtSettings.ProfileConfig: Adding HidDevService
08-31 11:29:35.957  7504  7504 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 11:29:35.957  1015  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 11:29:35.957  1015  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.957  1015  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.957  1015  1480 D SettingsProvider: selectionArgs: false,
08-31 11:29:35.957  1015  1480 D SettingsProvider: selectionArgs: 1002
08-31 11:29:35.957  1015  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:35.957  1015  1480 D SettingsProvider: ret = -1
,08-31 11:29:35.957  1015  1712 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 11:29:35.957  1015  1712 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.957  1015  1712 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.957  1015  1712 D SettingsProvider: selectionArgs: false
08-31 11:29:35.957  1015  1712 D SettingsProvider: selectionArgs: 1002,
08-31 11:29:35.957  1015  1712 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 11:29:35.957  1015  1712 D SettingsProvider: ret = -1
08-31 11:29:35.967  1015  1594 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:35.967  1015  1594 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.967  1015  1594 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.967  1015  1594 D SettingsProvider: selectionArgs: false
,08-31 11:29:35.967  1015  1594 D SettingsProvider: selectionArgs: 1002
08-31 11:29:35.967  1015  1594 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:35.967  1015  1594 D SettingsProvider: ret = -1,
08-31 11:29:35.967  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 11:29:35.967  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.967  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 11:29:35.967  1015  1133 D SettingsProvider: selectionArgs: false
08-31 11:29:35.967  1015  1133 D SettingsProvider: selectionArgs: 1002
08-31 11:29:35.967  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:35.967  1015  1133 D SettingsProvider: ret = -1
,08-31 11:29:35.967  1015  1593 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 11:29:35.967  1015  1593 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.967  1015  1593 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.967  1015  1593 D SettingsProvider: selectionArgs: false
08-31 11:29:35.967  1015  1593 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:35.967  1015  1593 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:35.967  1015  1593 D SettingsProvider: ret = -1
08-31 11:29:35.967  1015  1592 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 11:29:35.967  1015  1592 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 11:29:35.967  1015  1592 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.967  1015  1592 D SettingsProvider: selectionArgs: false
08-31 11:29:35.967  1015  1592 D SettingsProvider: selectionArgs: 1002
08-31 11:29:35.967  1015  1592 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 11:29:35.967  1015  1592 D SettingsProvider: ret = -1
08-31 11:29:35.967  1015  1448 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 11:29:35.967  1015  1448 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.967  1015  1448 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.967  1015  1448 D SettingsProvider: selectionArgs: false
08-31 11:29:35.967  1015  1448 D SettingsProvider: selectionArgs: 1002
08-31 11:29:35.967  1015  1448 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:35.967  1015  1448 D SettingsProvider: ret = -1
08-31 11:29:35.967  1015  1213 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-31 11:29:35.967  1015  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.967  1015  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.967  1015  1213 D SettingsProvider: selectionArgs: false
08-31 11:29:35.967  1015  1213 D SettingsProvider: selectionArgs: 1002
08-31 11:29:35.967  1015  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 11:29:35.967  1015  1213 D SettingsProvider: ret = -1
,08-31 11:29:35.967  1015  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:35.967  1015  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 11:29:35.967  1015  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.967  1015  1490 D SettingsProvider: selectionArgs: false
08-31 11:29:35.967  1015  1490 D SettingsProvider: selectionArgs: 1002
08-31 11:29:35.967  1015  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:35.967  1015  1490 D SettingsProvider: ret = -1
,08-31 11:29:35.967  1015  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:35.967  1015  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.967  1015  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.967  1015  1499 D SettingsProvider: selectionArgs: false
08-31 11:29:35.967  1015  1499 D SettingsProvider: selectionArgs: 1002
08-31 11:29:35.977  1015  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:35.977  1015  1499 D SettingsProvider: ret = -1
,08-31 11:29:35.977  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-31 11:29:35.977  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.977  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 11:29:35.977  1015  1028 D SettingsProvider: selectionArgs: false
08-31 11:29:35.977  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:35.977  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 11:29:35.977  1015  1028 D SettingsProvider: ret = -1
,08-31 11:29:35.977  1015  1379 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-31 11:29:35.977  1015  1379 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:35.977  1015  1379 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:35.977  1015  1379 D SettingsProvider: selectionArgs: false
08-31 11:29:35.977  1015  1379 D SettingsProvider: selectionArgs: 1002
08-31 11:29:35.977  1015  1379 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:35.977  1015  1379 D SettingsProvider: ret = -1
,08-31 11:29:35.987  2006  2006 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:35.997  1015  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:35.997  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.997  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:35.997  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:35.997  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:36.007  2006  7520 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 11:29:36.007  2006  2006 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 11:29:36.007  1015  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:36.017  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:36.017  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:36.017  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:36.017  2006  7520 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-31 11:29:36.337   290   290 E SMD     : DCD OFF
,08-31 11:29:36.517  1015  1048 I PowerManagerService: [PWL] Off : 75s ago
,08-31 11:29:36.517  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-31 11:29:36.517  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1,
08-31 11:29:36.517  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=12687)
,08-31 11:29:36.517  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2994)
08-31 11:29:36.517  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2993)
,08-31 11:29:37.577  1015  1309 E Watchdog: !@Sync 4
,08-31 11:29:38.047  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:29:38.047  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:38.357   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:39.347   290   290 E SMD     : DCD OFF
,08-31 11:29:39.357   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:40.347   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:41.037  1015  1712 I ActivityManager: Killing 7075:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-31 11:29:41.037  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:41.037  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3910d181 added. We now have 6 listener(s)
08-31 11:29:41.037  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:41.037  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:41.037  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36c4b226 added. We now have 7 listener(s)
08-31 11:29:41.037  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:41.047  6736  6790 I System.out: IsBluetoothEnabled
,08-31 11:29:41.047  6736  6790 D BluetoothAdapter: disable()
,08-31 11:29:41.047  1015  1213 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-31 11:29:41.047  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:41.047  6736  6790 D BluetoothAdapter: enable()
,08-31 11:29:41.057  1015  1480 W ActivityManager: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:29:41.057  1015  1480 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-31 11:29:41.057  1015  1480 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:41.057  1015  1480 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:41.057  1015  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 11:29:41.057  1015  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 11:29:41.057  1015  1480 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
,08-31 11:29:41.057  1015  1480 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 11:29:41.057  1015  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 11:29:41.057  1015  1480 D SettingsProvider: name = bluetooth_on
08-31 11:29:41.057  1015  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:41.067  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 11:29:41.067  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:41.067  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-31 11:29:41.067  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-31 11:29:41.087  7504  7504 D BluetoothAdapterState: make
,08-31 11:29:41.087  7504  7504 I bluedroid: init
,08-31 11:29:41.087  7504  7526 I BluetoothAdapterState: Entering OffState
,08-31 11:29:41.097  7504  7504 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 11:29:41.097  7504  7504 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 11:29:41.097  7504  7504 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 11:29:41.097  7504  7504 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 11:29:41.097  7504  7504 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-31 11:29:41.097  7504  7504 I bluedroid: get_profile_interface socket
08-31 11:29:41.097  7504  7504 I bluedroid: get_profile_interface map_client
,08-31 11:29:41.097  7504  7529 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 11:29:41.097  7504  7504 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-31 11:29:41.107  7504  7529 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-31 11:29:41.107  7504  7529 E BluetoothServiceJni: populateRssiValuesNative
08-31 11:29:41.107  7504  7529 I bluedroid: getModelRssiValues
08-31 11:29:41.107  7504  7529 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 11:29:41.107  7504  7529 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 11:29:41.107  7504  7504 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:41.107  7504  7529 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 11:29:41.107  1015  1015 D SettingsProvider: name = bluetooth_name
,08-31 11:29:41.107  1015  1213 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 11:29:41.107  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.117  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:41.117  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:41.117  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:41.117  7504  7512 I bluedroid: config_hci_snoop_log
,08-31 11:29:41.117  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 11:29:41.117  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
08-31 11:29:41.127  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-31 11:29:41.127  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 11:29:41.127  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 11:29:41.127  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:41.127  7504  7504 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-31 11:29:41.127  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:41.127  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 11:29:41.137  7504  7526 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-31 11:29:41.137  7504  7526 D BluetoothAdapterProperties: Setting state to 11
,08-31 11:29:41.137  7504  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-31 11:29:41.137  7504  7526 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:41.137  7504  7526 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 11:29:41.137  7504  7526 D BluetoothAdapterService: Autoconnection is available ,
08-31 11:29:41.137  7504  7526 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 11:29:41.137  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 11:29:41.147  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:41.147  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-31 11:29:41.147  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:29:41.147  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:41.147  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-31 11:29:41.157  7504  7526 D BluetoothSecureManager: getInstant: null
08-31 11:29:41.157  7504  7526 D BluetoothSecureManager: calling getMethod for getService
08-31 11:29:41.157  7504  7526 D BluetoothSecureManager: calling getService
,08-31 11:29:41.157  7504  7526 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@20e36125
,08-31 11:29:41.157  1015  1592 D BluetoothSecureManagerService: isSecureModeEnabled
08-31 11:29:41.157  1015  1592 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-31 11:29:41.157  7504  7526 D BtConfig.SecureMode: isSecureModeOn:false
08-31 11:29:41.157  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 11:29:41.157  7504  7526 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 11:29:41.157  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:41.157  7504  7526 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 11:29:41.157  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:41.157  7504  7526 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 11:29:41.157  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 11:29:41.157  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
08-31 11:29:41.157  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:29:41.157  7504  7526 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 11:29:41.157  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 11:29:41.157  7504  7526 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 11:29:41.157  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 11:29:41.157  7504  7526 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 11:29:41.157  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:41.157  1878  1878 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:41.167  1015  1594 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:41.167  7504  7526 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 11:29:41.167  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 11:29:41.167  7504  7526 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-31 11:29:41.167  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:29:41.167  1015  1379 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:29:41.167  7504  7526 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:29:41.167  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 11:29:41.167  3067  3067 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:41.167  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:29:41.167  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:41.167  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.167  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:41.167  7504  7526 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:41.167  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 11:29:41.167  7504  7526 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:41.167  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:29:41.177  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:41.177  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:41.177  7504  7526 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-31 11:29:41.177  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:41.177  7504  7526 D BluetoothBondStateMachine: make
,08-31 11:29:41.177  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-31 11:29:41.177  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 11:29:41.177  7504  7526 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-31 11:29:41.177  7504  7531 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 11:29:41.187  3067  3067 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:41.187  1015  1448 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:41.187  1015  1448 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.187  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:41.187  1015  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:41.187  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:41.187  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 11:29:41.187  1015  1379 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:41.187  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:29:41.197  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 11:29:41.187  7504  7526 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 11:29:41.197  7504  7504 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 11:29:41.197  7504  7504 D BtGatt.GattService: Received start request. Starting profile...
08-31 11:29:41.197  7504  7504 D BtGatt.GattService: start()
08-31 11:29:41.197  7504  7504 D BtGatt.GattService: start()
08-31 11:29:41.197  7504  7504 I bluedroid: get_profile_interface gatt,
08-31 11:29:41.197  1015  1379 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:41.197  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
08-31 11:29:41.197  7504  7504 D BtGatt.AdvertiseManager: advertise manager created
,08-31 11:29:41.197  1015  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:41.197  1015  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:41.207  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 11:29:41.207  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:29:41.207  7504  7526 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:41.207  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-31 11:29:41.207  1015  1713 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:41.207  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 11:29:41.207  1015  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 11:29:41.207  1015  1713 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:41.207  1015  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:41.207  1015  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:41.207  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-31 11:29:41.207  7504  7504 D BtGatt.GattService: mStartError = false,
08-31 11:29:41.207  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
08-31 11:29:41.217  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:41.217  7504  7526 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 11:29:41.217  1015  1593 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:41.217  1015  1593 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.217  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:41.217  1015  1593 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:41.217  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:41.217  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:29:41.217  7504  7504 D HeadsetService: Received start request. Starting profile...
08-31 11:29:41.217  7504  7504 D HeadsetService: start()
08-31 11:29:41.217  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:29:41.217  7504  7526 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:29:41.217  7504  7504 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 11:29:41.217  7504  7504 D HeadsetStateMachine: make
,08-31 11:29:41.217  1015  1592 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:41.217  1015  1592 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.217  1015  1592 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:41.217  1015  1592 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:41.217  1015  1592 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:41.227  7504  7504 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 11:29:41.227  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-31 11:29:41.227  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:29:41.227  7504  7526 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:29:41.227  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:41.227  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.227  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:41.227  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:41.227  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:41.237  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:41.237  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:41.237  7504  7526 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 11:29:41.237  1015  1709 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:41.237  1015  1709 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.237  1015  1709 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:41.237  1015  1709 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:41.237  1015  1709 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:41.237  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-31 11:29:41.237  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:41.237  7504  7526 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 11:29:41.237  1015  1713 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-31 11:29:41.237  1015  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.237  1015  1713 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:41.237  1015  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:41.237  1015  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 11:29:41.237  1015  1712 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:41.237  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.247  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:41.247  1015  1712 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:41.247  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:41.247  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 11:29:41.247  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 11:29:41.247  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:41.247  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:41.247  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:41.247  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-31 11:29:41.247  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:41.247  7504  7526 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:41.247  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:41.247  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:41.247  7504  7526 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:41.247  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:29:41.247  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:41.247  7504  7526 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:29:41.247  7504  7526 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:29:41.247  7504  7526 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:29:41.247  7504  7504 I bluedroid: get_profile_interface handsfree
08-31 11:29:41.247  7504  7526 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:29:41.247  7504  7526 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 11:29:41.257  7504  7504 I DualScoManager: Instantiating Dual Sco Manager
08-31 11:29:41.257  7504  7504 I DualScoManager: Set HeadsetServiceHelper
,08-31 11:29:41.267  7504  7504 D BluetoothAtMessage: createCMTIContentObservers
,08-31 11:29:41.267  1015  1379 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-31 11:29:41.267  1015  1379 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:41.267  1015  1379 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:41.267  1015  1379 D SettingsProvider: selectionArgs: false
08-31 11:29:41.267  1015  1379 D SettingsProvider: selectionArgs: 1002
08-31 11:29:41.267  1015  1379 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:41.267  1015  1379 D SettingsProvider: ret = -1
,08-31 11:29:41.267  7504  7535 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 11:29:41.267  7504  7504 D HeadsetService: mStartError = false
08-31 11:29:41.267  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
,08-31 11:29:41.277  7504  7504 D A2dpService: Received start request. Starting profile...,
08-31 11:29:41.277  7504  7504 D A2dpService: start()
,08-31 11:29:41.277  7504  7504 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 11:29:41.277  7504  7535 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 11:29:41.277  7504  7504 I bluedroid: get_profile_interface avrcp
,08-31 11:29:41.277  7504  7535 D HeadsetStateMachine: map size, before remove : 0
,08-31 11:29:41.277  7504  7535 D HeadsetStateMachine: map size, after remove: 0
,08-31 11:29:41.287  7504  7504 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:29:41.287  7504  7504 D Avrcp   : Initialize Media Controller
,08-31 11:29:41.287  7504  7504 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 11:29:41.287  7504  7504 E Avrcp   : getActiveSessions
,08-31 11:29:41.287  7504  7504 D Avrcp   : pick active media Controller
,08-31 11:29:41.287  7504  7504 D Avrcp   : Get the active Media Controller 
,08-31 11:29:41.307  7504  7504 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 11:29:41.307  7504  7539 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 11:29:41.307  7504  7504 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 11:29:41.307  7504  7504 D A2dpStateMachine: make
,08-31 11:29:41.317  7504  7504 I bluedroid: get_profile_interface a2dp
,08-31 11:29:41.317  7504  7541 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-31 11:29:41.317  7504  7504 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 11:29:41.317  7504  7504 D A2dpService: mStartError = false
08-31 11:29:41.317  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
,08-31 11:29:41.317  7504  7504 E BluetoothAdapterService(753020823): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-31 11:29:41.317  7504  7504 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 11:29:41.317  7504  7540 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:29:41.317  7504  7504 D HidService: Received start request. Starting profile...
08-31 11:29:41.317  7504  7504 D HidService: start()
08-31 11:29:41.317  7504  7504 I bluedroid: get_profile_interface hidhost
08-31 11:29:41.327  7504  7504 D HidService: setHidService(): set to: null
08-31 11:29:41.327  7504  7504 D HidService: mStartError = false
08-31 11:29:41.327  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
,08-31 11:29:41.327  7504  7504 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 11:29:41.327  7504  7504 D HealthService: Received start request. Starting profile...
08-31 11:29:41.327  7504  7504 D HealthService: start()
,08-31 11:29:41.327  7504  7539 D BluetoothMediaBrowser: no now playing list
,08-31 11:29:41.327  7504  7539 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1,
08-31 11:29:41.327  7504  7504 I bluedroid: get_profile_interface health
08-31 11:29:41.327  7504  7504 D HealthService: mStartError = false
08-31 11:29:41.327  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
,08-31 11:29:41.337  7504  7504 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 11:29:41.337  7504  7504 D PanService: Received start request. Starting profile...
08-31 11:29:41.337  7504  7504 D PanService: start()
08-31 11:29:41.337  7504  7504 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:29:41.337  7504  7504 I bluedroid: get_profile_interface pan
,08-31 11:29:41.337  7504  7504 D PanService: mStartError = false
08-31 11:29:41.337  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
,08-31 11:29:41.337  2006  2006 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:41.337  7504  7504 D BluetoothMapService: Received start request. Starting profile...
08-31 11:29:41.337  7504  7504 D BluetoothMapService: start()
,08-31 11:29:41.347  7504  7504 D BluetoothMapService: mStartError = false
,08-31 11:29:41.347  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
08-31 11:29:41.347  2006  2006 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 11:29:41.347  7504  7504 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 11:29:41.347  1428  6926 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 11:29:41.347  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-31 11:29:41.347  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 11:29:41.347  1428  6926 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 11:29:41.347  7504  7504 I BluetoothSAPServiceJni: classInitNative(L204): succeeds,
,08-31 11:29:41.347  7504  7504 D SapService: Received start request. Starting profile...
08-31 11:29:41.347  7504  7504 D SapService: start()
08-31 11:29:41.347  7504  7504 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 11:29:41.347  7504  7504 I bluedroid: get_profile_interface sap
08-31 11:29:41.347  7504  7504 D SapService: mStartError = false
08-31 11:29:41.347   316   316 I ServiceManager: Waiting for service AtCmdFwd...
08-31 11:29:41.347  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
08-31 11:29:41.347  7504  7504 D HeadsetStateMachine: Proxy object connected
08-31 11:29:41.347  7504  7504 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 11:29:41.347  7504  7504 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-31 11:29:41.347  7504  7535 D HeadsetStateMachine: Disconnected process message: 11
08-31 11:29:41.347  7504  7535 D HeadsetStateMachine: Disconnected process message: 18
,08-31 11:29:41.347  7504  7504 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 11:29:41.357  7504  7504 E BluetoothAdapterService(753020823): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 11:29:41.357  7504  7504 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:29:41.357  7504  7504 D BluetoothA2dp: Proxy object connected
08-31 11:29:41.357  7504  7504 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-31 11:29:41.357  7504  7504 E BluetoothAdapterService(753020823): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 11:29:41.357  7504  7535 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:29:41.357  7504  7504 E BluetoothAdapterService(753020823): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-31 11:29:41.357  7504  7535 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:29:41.357  7504  7535 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:29:41.357  7504  7504 E BluetoothAdapterService(753020823): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 11:29:41.357  7504  7504 E BluetoothAdapterService(753020823): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-31 11:29:41.377  7504  7504 E BluetoothAdapterService(753020823): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-31 11:29:41.377  7504  7504 E BluetoothAdapterService(753020823): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 11:29:41.377  7504  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-31 11:29:41.377  7504  7526 I bluedroid: enable
,08-31 11:29:41.377  7504  7526 I bt_hci_bdroid: init
08-31 11:29:41.377  7504  7545 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-31 11:29:41.387  7504  7526 I bt_vendor: bt-vendor : init
,08-31 11:29:41.387  7504  7526 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 11:29:41.387  7504  7526 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 11:29:41.387  7504  7526 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-31 11:29:41.387  7504  7526 D bt_userial_mct: userial_init
,08-31 11:29:41.387  7504  7526 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 11:29:41.387  7504  7526 I bt_vendor: Starting hciattach daemon
08-31 11:29:41.387  7504  7526 I bt_vendor: try to set false
,08-31 11:29:41.387  7504  7526 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 11:29:41.387  7504  7526 I bt_vendor: Starting hciattach daemon
08-31 11:29:41.387  7504  7526 I bt_vendor: try to set true
,08-31 11:29:41.407  7550  7550 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-31 11:29:41.447  7556  7556 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-31 11:29:41.457  7557  7557 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 11:29:41.477  7559  7559 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 11:29:41.487  7560  7560 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-31 11:29:41.497  7561  7561 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 11:29:41.507  7562  7562 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-31 11:29:41.697  1015  3371 D SSRM:n  : SIOP:: AP = 330
,08-31 11:29:41.737  7565  7565 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-31 11:29:41.747  7566  7566 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 11:29:41.767  1015  3388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 11:29:41.797  7504  7526 I bt_vendor: bluetooth satus is on,
08-31 11:29:41.797  7504  7547 D bt_userial_mct: userial_open(port:0)
08-31 11:29:41.797  7504  7547 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 11:29:41.797  7504  7547 I bt_vendor: Done intiailizing UART
08-31 11:29:41.797  7504  7547 I bt_vendor: Done intiailizing UART
08-31 11:29:41.797  7504  7547 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 11:29:41.797  7504  7547 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 11:29:41.807  7504  7568 D bt_userial_mct: Entering userial_read_thread()
,08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_GAP,
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_SAP
,08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 11:29:41.807  7504  7545 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 11:29:41.907  7504  7545 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-31 11:29:41.907  7504  7545 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4149ed1 
,08-31 11:29:41.907  7504  7545 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4149ed1 
,08-31 11:29:41.927  7504  7529 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 11:29:41.927  7504  7529 E bt-btif : Calling BTA_HhEnable
,08-31 11:29:41.927  7504  7529 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 11:29:41.927  7504  7529 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-31 11:29:41.927  7504  7529 E BluetoothServiceJni: populateRssiValuesNative
,08-31 11:29:41.927  7504  7529 I bluedroid: getModelRssiValues
08-31 11:29:41.927  7504  7529 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-31 11:29:41.927  7504  7529 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 11:29:41.937  7504  7529 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-31 11:29:41.937  1015  1015 D SettingsProvider: name = bluetooth_name
,08-31 11:29:41.937  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:41.937  7504  7529 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 11:29:41.937  7504  7529 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:29:41.937  7504  7529 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 11:29:41.937  7504  7529 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-31 11:29:41.937  7504  7529 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-31 11:29:41.937  7504  7529 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-31 11:29:41.937  7504  7529 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 11:29:41.937  7504  7529 E bt-btif : btif_sock_init: !vhci_init
,08-31 11:29:41.937  7504  7529 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 11:29:41.937  7504  7529 D IOP_DB_BT: db_open: db_open : handle 3027800080l, read 13894 bytes onto local cache
,08-31 11:29:41.937  7504  7529 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-31 11:29:41.947  7504  7529 D IOP_DB_BT: db_query: result 1
08-31 11:29:41.947  7504  7529 I         : iop_db_open: iop_db_open status 0
,08-31 11:29:41.947  7504  7568 E bt_mct  : hci lib postload completed
,08-31 11:29:41.947  7504  7529 D bte_conf: Device ID record 1 : primary
,08-31 11:29:41.947  7504  7529 D bte_conf:   vendorId            = 0075
,08-31 11:29:41.947  7504  7529 D bte_conf:   vendorIdSource      = 0001
,08-31 11:29:41.947  7504  7529 D bte_conf:   product             = 0100
,08-31 11:29:41.947  7504  7529 D bte_conf:   version             = 0200
08-31 11:29:41.947  7504  7529 D bte_conf:   clientExecutableURL = 
,08-31 11:29:41.947  7504  7529 D bte_conf:   serviceDescription  = 
08-31 11:29:41.947  7504  7529 D bte_conf:   documentationURL    = 
,08-31 11:29:41.947  7504  7529 D bte_conf: bte_load_did_conf no section named DID2.,
08-31 11:29:41.947  7504  7529 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 11:29:41.957  7504  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 11:29:41.957  7504  7526 D BluetoothAdapterProperties: ScanMode =  20
,08-31 11:29:41.957  7504  7526 D BluetoothAdapterProperties: State =  11
,08-31 11:29:41.957  1015  1510 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 11:29:41.957  7504  7526 D BluetoothAdapterProperties: Setting state to 12
,08-31 11:29:41.957  7504  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 11:29:41.967  7504  7529 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 11:29:41.967  7504  7529 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:29:41.967  7504  7529 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:29:41.967  1015  1490 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-31 11:29:41.967  1015  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:41.967  1015  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:41.967  1015  1490 D SettingsProvider: selectionArgs: false
08-31 11:29:41.967  1015  1490 D SettingsProvider: selectionArgs: 1002
08-31 11:29:41.967  1015  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:41.967  1015  1490 D SettingsProvider: ret = -1
,08-31 11:29:41.967  7504  7526 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:41.967  7504  7526 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 11:29:41.967  1015  2055 V SAMP_SPCM_test: CSC File load.. 
,08-31 11:29:41.977  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:41.977  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:41.977  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:41.977  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:41.977  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:41.977  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:41.977  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:41.977  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:41.987  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-31 11:29:41.987  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-31 11:29:42.027  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-31 11:29:42.027  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-31 11:29:42.027  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-31 11:29:42.027  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-31 11:29:42.027  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-31 11:29:42.027  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-31 11:29:42.037  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
,08-31 11:29:42.047  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAd,minReceiver}: mdm-enterprise-vpn
08-31 11:29:42.057  1015  2055 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-31 11:29:42.057  1015  1379 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:42.057  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.057  1015  1379 W ActivityManager: userId = 0, bbcId = -10000,
,08-31 11:29:42.057  1015  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.057  1015  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.057  1015  2055 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-31 11:29:42.067  7504  7526 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:42.067  7504  7526 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 11:29:42.067  7504  7526 D BluetoothAdapterService: starting service from this receiver
08-31 11:29:42.067  1015  2055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:42.067  1015  2055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:42.067  1015  2055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:42.067  1015  2055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:42.067  3067  3071 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:29:42.077  7572  7572 E Zygote  : MountEmulatedStorage()
,08-31 11:29:42.077  7572  7572 E Zygote  : v2
08-31 11:29:42.077  7572  7572 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:42.077  7572  7572 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:42.077  7572  7572 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:42.087  7504  7504 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 11:29:42.087  7504  7504 I BluetoothPbapService: Handler(): got msg=1
,08-31 11:29:42.087  7572  7572 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:42.087  7572  7572 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:42.087  1015  2055 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7572 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 11:29:42.087  1015  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:42.087  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-31 11:29:42.097  1015  1490 W ActivityManager: userId = 0, bbcId = -10000,
08-31 11:29:42.097  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.097  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.097  7504  7526 I BluetoothAdapterState: Entering On State from state = 11
,08-31 11:29:42.097  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:42.097  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:42.097  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:42.097  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:42.097  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:42.097  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:42.097  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:42.097  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:42.107  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:42.107  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:42.107  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f6b9e67 added. We now have 8 listener(s)
08-31 11:29:42.107  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:42.107  1015  1593 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 11:29:42.107  1015  1593 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:29:42.107  1015  1593 D SecContentProvider2: mCursor = null
08-31 11:29:42.107  1015  1593 D WifiService: setWifiEnabled: false pid=6736, uid=10171
08-31 11:29:42.107  1015  1593 D SettingsProvider: name = wifi_on
,08-31 11:29:42.117  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.117  1015  1499 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 11:29:42.117  1015  1499 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:29:42.117  1015  1499 D SecContentProvider2: mCursor = null
,08-31 11:29:42.117  1015  1499 D WifiService: setWifiEnabled: true pid=6736, uid=10171
,08-31 11:29:42.117  1015  1499 W ActivityManager: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:29:42.117  1015  1499 W WifiService: Failed getting userId using ActivityManagerNative
08-31 11:29:42.117  1015  1499 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6736, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:42.117  1015  1499 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:42.117  1015  1499 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 11:29:42.117  1015  1499 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 11:29:42.117  1015  1499 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 11:29:42.117  1015  1499 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:29:42.117  1015  1499 D SettingsProvider: name = wifi_on
,08-31 11:29:42.127  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 11:29:42.137  7572  7572 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:42.137  7572  7572 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:42.237  1015  1045 I art     : Explicit concurrent mark sweep GC freed 30530(1762KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.579ms total 169.238ms
08-31 11:29:42.237  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 11:29:42.237  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.237  1015  1713 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-31 11:29:42.237  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.237  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.237  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.247  1450  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:42.247  1450  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.247  3067  6873 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:42.247  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:42.247  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:42.247  7504  7590 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 11:29:42.247  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.247  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.247  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.257  3067  6873 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:42.257  3067  3071 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:29:42.257  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-31 11:29:42.257  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.257  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.257  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.257  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.257  7504  7590 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:29:42.257  3067  3067 D BluetoothPbap: Proxy object connected
08-31 11:29:42.257  3067  3067 D PbapServerProfile: Bluetooth service connected
08-31 11:29:42.257  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:29:42.257  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:42.257  3067  3067 D HeadsetProfile: Bluetooth service connected
08-31 11:29:42.257  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:29:42.257  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 11:29:42.257  1015  1015 D BluetoothA2dp: Proxy object connected
,08-31 11:29:42.257  7504  7590 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:42.267  1440  1465 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:42.267  1440  1465 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.267  7504  7590 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-31 11:29:42.267  7504  7590 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:42.267  7504  7590 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:42.267  7504  7590 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a192bb9
,08-31 11:29:42.267  7504  7512 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:42.267  7504  7512 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:42.267  7504  7590 D BluetoothSocket: channel: 19
08-31 11:29:42.267  7504  7590 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 11:29:42.267  3067  3077 D BluetoothPan: Binding service...
,08-31 11:29:42.267  7572  7572 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 11:29:42.267  3067  3067 D BluetoothInputDevice: Proxy object connected
08-31 11:29:42.267  3067  3067 D HidProfile: Bluetooth service connected
,08-31 11:29:42.267  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:29:42.267  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.267  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.267  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.267  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.267  3067  6873 D Bluetoothsap: onBluetoothStateChange: up=true
,08-31 11:29:42.267  3067  6873 D Bluetoothsap: Binding service...
,08-31 11:29:42.277  3067  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 11:29:42.277  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-31 11:29:42.277  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.277  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.277  3067  3067 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:29:42.277  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.277  3067  3067 D PanProfile: Bluetooth service connected
08-31 11:29:42.277  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.277  3067  6873 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 11:29:42.277  1015  1045 D BluetoothPan: Binding service...
,08-31 11:29:42.277  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:29:42.277  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.277  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:29:42.277  3067  3067 D Bluetoothsap: BluetoothSAP Proxy object connected
08-31 11:29:42.277  3067  3067 D SapProfile: Bluetooth service connected
08-31 11:29:42.277  3067  3067 D Bluetoothsap: getConnectedDevices()
,08-31 11:29:42.287  1428  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:42.287  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 11:29:42.287  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:42.287  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.287  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.287  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.287  1428  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:42.287  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:42.287  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.287  3067  3071 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:42.287  3067  3071 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.287  7504  7530 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:42.287  3067  6873 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:29:42.287  3067  6873 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
08-31 11:29:42.287  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:29:42.287  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.287  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.287  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.297  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.297  3067  3067 D BluetoothA2dp: Proxy object connected
08-31 11:29:42.297  3067  3067 D A2dpProfile: Bluetooth service connected
,08-31 11:29:42.297  2006  2014 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:42.297  2006  2014 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.297  1428  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:42.297  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:42.297  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:42.297  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.297  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.297  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.297  1428  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:42.297  7418  7426 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:42.297  7418  7426 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.297  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 11:29:42.297  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:42.297  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 11:29:42.297  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:42.297  1450  1700 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:42.297  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:42.297  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:42.297  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.307  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.307  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.307  1450  1700 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:42.307  3067  3071 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:29:42.307  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 11:29:42.307  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.307  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.307  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.307  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.307  1428  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 11:29:42.307  3067  3067 D BluetoothMap: Proxy object connected
08-31 11:29:42.307  3067  3067 D MapProfile: Bluetooth service connected
08-31 11:29:42.307  3067  3067 D BluetoothMap: getConnectedDevices()
08-31 11:29:42.307  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:42.307  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:42.307  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.307  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.307  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.317  1428  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:42.317  1177  4349 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:42.317  1177  4349 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.317  6736  6746 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:42.317  6736  6746 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.317  1428  1463 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:42.317  1428  1463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:42.317  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 11:29:42.317  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 11:29:42.317  1015  2055 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-31 11:29:42.327  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@b992d7c, true
,08-31 11:29:42.327  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:42.327  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-31 11:29:42.327  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:29:42.327  1428  1428 D BluetoothHeadset: registerMessageListener,
,08-31 11:29:42.327  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:29:42.327  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:29:42.327  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:42.327  1177  1177 D BluetoothTile:  getBluetoothState : 12
08-31 11:29:42.327  1878  1878 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:42.337  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null,
08-31 11:29:42.337  3067  3067 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:42.337   290   290 E SMD     : DCD OFF,
,08-31 11:29:42.337  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:42.337  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.347  1177  1628 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:42.347  7504  7512 D HeadsetService: registerMessageListener
,08-31 11:29:42.347  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:42.347  7504  7512 D HeadsetService: registerMessageListener
08-31 11:29:42.347  7504  7535 D HeadsetStateMachine: Disconnected process message: 70
08-31 11:29:42.347  7504  7535 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@22202bfe
,08-31 11:29:42.347  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-31 11:29:42.347  1015  1490 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-31 11:29:42.347  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 11:29:42.347  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:42.347  1015  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:42.347  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.357   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:42.357  3067  3067 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-31 11:29:42.357  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 11:29:42.357  3067  3067 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 11:29:42.357  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-31 11:29:42.357  3067  3067 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 11:29:42.357  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-31 11:29:42.357  3067  3067 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 11:29:42.357  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.357  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:42.357  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:42.357  7504  7593 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 11:29:42.357  7504  7535 D HeadsetStateMachine: Disconnected process message: 9
,08-31 11:29:42.357  7504  7535 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 11:29:42.367  7504  7593 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 11:29:42.367   282   704 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 11:29:42.367  7504  7593 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:42.367   282   704 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-31 11:29:42.367   282   704 V voice   : voice_set_parameters: exit with code(-2)
,08-31 11:29:42.367   282   704 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 11:29:42.367   282   704 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 11:29:42.367   282   704 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 11:29:42.367   282   704 V audio_hw_primary: adev_set_parameters: exit
08-31 11:29:42.367  7504  7535 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 11:29:42.377  7504  7593 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-31 11:29:42.377  7504  7593 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:42.377  7504  7593 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:42.377  7504  7593 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@198e4f5f
,08-31 11:29:42.377  7504  7593 D BluetoothSocket: channel: 5
,08-31 11:29:42.377  3067  3067 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:42.377  1015  1133 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 11:29:42.377  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.377  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.377  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.377  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:42.397  3067  3067 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:42.397  3067  3067 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:42.397  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:42.397  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 11:29:42.407  7504  7504 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
,08-31 11:29:42.407  7504  7504 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 11:29:42.407  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:42.407  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.407  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.407  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.407  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.427  2006  2006 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:42.427  1015  1448 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:42.427  1015  1448 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.427  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.427  1015  1448 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:42.427  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:42.437  1015  1510 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 11:29:42.437  2006  7605 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 11:29:42.437  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:42.437  2006  2006 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 11:29:42.437  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.437  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:42.437  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:42.447  7504  7608 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:29:42.447  7504  7608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:42.447  7504  7608 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-31 11:29:42.447  7504  7608 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:42.447  7504  7608 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:42.447  7504  7608 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1072827b
,08-31 11:29:42.447  7504  7608 D BluetoothSocket: channel: 12
08-31 11:29:42.447  7504  7608 I BtOppRfcommListener: Accept thread started.
,08-31 11:29:42.457  1015  1593 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:42.457  1015  1593 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.457  1015  1593 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:42.457  1015  1593 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:42.467  2006  7605 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 11:29:42.487  1015  1043 D Tethering: interfaceAdded wlan0
,08-31 11:29:42.487  1015  1128 E Tethering: No numeric data
,08-31 11:29:42.487  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:42.487  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 11:29:42.487  1177  1177 D HotspotTile: updateTetherState():false, false
08-31 11:29:42.487  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:42.487  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 11:29:42.487  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:42.497  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:42.497  1015  1122 V NetworkStats: performPollLocked() took 4ms
08-31 11:29:42.497  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:42.497  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:42.497  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:42.497  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:29:42.497  1015  1128 D Tethering: clearTetheredNotification()
,08-31 11:29:42.497  1015  1128 D Tethering: InitialState.processMessage what=4
,08-31 11:29:42.497  1015  1128 E Tethering: No numeric data
,08-31 11:29:42.497  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-31 11:29:42.497  1015  1128 D Tethering: clearTetheredNotification()
,08-31 11:29:42.497  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-31 11:29:42.497  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:42.497  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:42.497  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:42.497  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:42.497  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:42.497  1177  1177 D HotspotTile: updateTetherState():false, false
08-31 11:29:42.497  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:42.507  1015  1043 D Tethering: interfaceAdded p2p0
08-31 11:29:42.507  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 11:29:42.507  1015  1122 V NetworkStats: performPollLocked() took 6ms
,08-31 11:29:42.507  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:42.507  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:42.507  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:42.507  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:42.507  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:42.507  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:42.507   277  1014 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-31 11:29:42.507   277  1014 D SoftapController: Softap fwReload - Ok
,08-31 11:29:42.517   277  1014 D CommandListener: Setting iface cfg
08-31 11:29:42.517   277  1014 D CommandListener: Trying to bring down wlan0
,08-31 11:29:42.517   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:42.517  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 11:29:42.517  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-31 11:29:42.517  1015  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-31 11:29:42.527  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:42.527  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
08-31 11:29:42.527  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:42.527  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:42.527  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:42.527  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-31 11:29:42.527  3067  3067 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-31 11:29:42.527  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:42.527  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-31 11:29:42.527  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-31 11:29:42.527  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:42.527  1177  1177 D HotspotTile: onReceive : 2, 0
08-31 11:29:42.537  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.537  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:42.537  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:42.547  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.547  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.547  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:42.547  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 11:29:42.547  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 11:29:42.547  1638  1638 I Hs20UtilService: Starting #19
08-31 11:29:42.547  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 11:29:42.547  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:29:42.547  1638  1717 I Hs20UtilService: Message received 5011
,08-31 11:29:42.557  7610  7610 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 11:29:42.557  7610  7610 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 11:29:42.557  7610  7610 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 11:29:42.567  7610  7610 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-31 11:29:42.567   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7610,
08-31 11:29:42.567   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 11:29:42.567  7610  7610 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 11:29:42.567  7610  7610 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:42.567  7610  7610 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-31 11:29:42.567  7610  7610 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 11:29:42.577   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7610
08-31 11:29:42.577   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-31 11:29:42.707   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
08-31 11:29:42.717  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
08-31 11:29:42.767  7610  7610 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 11:29:42.767  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 11:29:42.777  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-31 11:29:42.777   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7610,
08-31 11:29:42.777   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 11:29:42.777  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 11:29:42.777  7610  7610 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:42.777  7610  7610 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 11:29:42.777  7610  7610 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:42.777  7610  7610 E wpa_supplicant: SIM READ ERROR
08-31 11:29:42.777  7610  7610 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-31 11:29:42.777  7610  7610 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:42.777  7610  7610 E wpa_supplicant: SIM READ ERROR
08-31 11:29:42.777  7610  7610 I wpa_supplicant: Blacklist: Clear (all) 
08-31 11:29:42.777  7610  7610 I wpa_supplicant: wpa_default_ap_write_once
,08-31 11:29:42.777  7610  7610 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 11:29:42.777  7610  7610 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:42.777  7610  7610 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 11:29:42.777  7610  7610 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:42.777  7610  7610 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 11:29:42.777  7610  7610 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 11:29:42.777  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:42.777  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:42.777  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:42.857  7610  7610 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-31 11:29:43.097  7610  7610 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-31 11:29:43.097  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-31 11:29:43.107  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 11:29:43.107   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7610,
08-31 11:29:43.107   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 11:29:43.117  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-31 11:29:43.117  7610  7610 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:43.117  7610  7610 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 11:29:43.117  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 11:29:43.127  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-31 11:29:43.127   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7610
08-31 11:29:43.127   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 11:29:43.127  7610  7610 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 11:29:43.127  7610  7610 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:43.127  7610  7610 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:43.127  7610  7610 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:43.127  7610  7610 E wpa_supplicant: SIM READ ERROR
08-31 11:29:43.127  7610  7610 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:29:43.127  7610  7610 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 11:29:43.127  7610  7610 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:29:43.127  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 11:29:43.127  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:43.127  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:43.137  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:43.137  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:43.137  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:43.177  7610  7610 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 11:29:43.177  7610  7610 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 11:29:43.237  7610  7610 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-31 11:29:43.237  7610  7610 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-31 11:29:43.237  7610  7610 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 11:29:43.367   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-31 11:29:43.497  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 11:29:43.497  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:43.497  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:43.527  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 11:29:43.527  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:29:43.527  7610  7610 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 11:29:43.527  7610  7610 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:43.527  7610  7610 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 11:29:43.527  7610  7610 E wpa_supplicant: SIM READ ERROR
08-31 11:29:43.527  7610  7610 I wpa_supplicant: Blacklist: Clear (all) ,
,08-31 11:29:43.547  7610  7610 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-31 11:29:43.557  7610  7610 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 11:29:43.557  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:43.557  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:43.557  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:43.557  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:43.557  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:43.557  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
08-31 11:29:43.557  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:43.567  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:43.567  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-31 11:29:43.567  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:43.567  1177  1628 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:29:43.567  3067  3067 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:43.567  1177  1177 D HotspotTile: onReceive : 3, 0
,08-31 11:29:43.577  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:43.577  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:43.577  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:43.577  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:43.577  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:43.577  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:43.577  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:43.577  6736  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:43.577  1015  1125 E WifiConfigStore: Not a HS20
,08-31 11:29:43.577  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 11:29:43.577  6736  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:43.587  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 11:29:43.587  1015  1499 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:43.587  1015  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:43.587  1015  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:43.587  1015  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:43.587  1015  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:43.597  1638  1638 I Hs20UtilService: Starting #20
,08-31 11:29:43.597  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 11:29:43.597  7610  7610 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 11:29:43.597  7610  7610 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 11:29:43.597  1638  1717 I Hs20UtilService: Message received 5011
,08-31 11:29:43.597  7610  7610 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 11:29:43.597  7610  7610 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 11:29:43.597  7610  7610 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 11:29:43.597  7610  7610 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 11:29:43.597  7610  7610 I wpa_supplicant: First Scan Start
,08-31 11:29:43.597  7610  7610 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 11:29:43.597  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:43.597  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:43.597  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:43.597  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:29:43.597  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-31 11:29:43.597  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:29:43.597  1015  1125 I WifiNative-HAL: startHal
08-31 11:29:43.597  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9ed4488c
08-31 11:29:43.597  1015  1125 I WifiNative-HAL: Could not start hal
,08-31 11:29:43.607  7004  7004 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:29:43.607  1015  1125 E WifiNative-wlan0: do suspend true
,08-31 11:29:43.607  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 11:29:43.607   277  1014 D CommandListener: Setting iface cfg
,08-31 11:29:43.607   277  1014 D CommandListener: Trying to bring up p2p0
08-31 11:29:43.607  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:29:43.607  1015  1124 D WifiP2pService: P2pEnablingState
,08-31 11:29:43.607  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 11:29:43.607  1015  1124 D WifiP2pService: P2p socket connection successful
08-31 11:29:43.617  1015  1124 D WifiP2pService: P2pEnabledState
,08-31 11:29:43.617  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
,08-31 11:29:43.617  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-31 11:29:43.617  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:43.617  1015  1148 I WifiNative-HAL: startHal
08-31 11:29:43.617  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9d8039bc
,08-31 11:29:43.617  1015  1148 I WifiNative-HAL: Could not start hal
08-31 11:29:43.617  1015  1148 E WifiScanningService: could not start HAL
,08-31 11:29:43.617  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-31 11:29:43.617  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:29:43.617  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:29:43.617  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-31 11:29:43.617  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:43.617  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:29:43.617  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:29:43.617  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-31 11:29:43.627  7610  7610 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:29:43.627  7610  7610 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 11:29:43.627  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-31 11:29:43.627  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:43.627  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 11:29:43.627  7610  7610 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-31 11:29:43.627  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 11:29:43.627  1015  1125 E WifiStateMachine: Failed to set frequency band 0
08-31 11:29:43.627  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:43.627  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:43.627  1015  1046 D WifiDisplayController: disconnect
08-31 11:29:43.627  1015  1125 D SecContentProvider2: mCursor = null
08-31 11:29:43.627  1015  1046 D WifiDisplayController: updateConnection
08-31 11:29:43.627  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-31 11:29:43.627  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:43.637  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-31 11:29:43.637  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-31 11:29:43.637  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:29:43.637  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:43.637  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 11:29:43.637  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:29:43.637  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:43.637  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:29:43.637  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 11:29:43.637  1015  1712 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:43.637  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 11:29:43.637  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-31 11:29:43.637  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:43.637  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  secondary type: null
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  wps: 0
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  grpcapab: 0
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  devcapab: 0
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  status: 3
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  wfdInfo: null
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-31 11:29:43.637  1015  1046 D WifiDisplayController:  SConnectInfo : null,
,08-31 11:29:43.647  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:43.647  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:43.647  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:43.647  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:43.647  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:29:43.647  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:43.647  6973  6973 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:43.647  6973  6973 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 11:29:43.657  6973  6973 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:29:43.657  6989  6989 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:43.667  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 11:29:43.667  1015  1124 D WifiP2pService: InactiveState
,08-31 11:29:43.667  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-31 11:29:43.667  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:29:43.667  7610  7610 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:29:43.667  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-31 11:29:43.667  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:29:44.137  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:44.137  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:44.137  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:44.137  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:44.137  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:44.137  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:44.137  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:44.137  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:44.137  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:44.147  6736  6790 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 11:29:44.147  6736  6790 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 11:29:44.147  6736  6790 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@182c87 Bundle[{}]
,08-31 11:29:44.157  6736  6790 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 11:29:44.157  6736  6790 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 11:29:44.157  6736  6790 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 11:29:44.157  6736  6790 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 11:29:44.157  6736  6790 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 11:29:44.157  6736  6790 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 11:29:44.167  6736  6790 I System.out: Running OutgoingSocketThread
,08-31 11:29:44.167  6736  7618 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1340)
,08-31 11:29:44.167  6736  7618 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35873
,08-31 11:29:44.167  6736  7618 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 11:29:44.797  7610  7610 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
08-31 11:29:44.797  7610  7610 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 11:29:44.797  7610  7610 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-31 11:29:44.797  7610  7610 I wpa_supplicant: Trying to associate with  'G700'
08-31 11:29:44.797  7610  7610 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-31 11:29:44.797  7610  7610 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 11:29:44.807  1015  7616 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 11:29:44.817  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:44.817  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:44.917  7610  7610 E wpa_supplicant: Cmd 35605 not handled
,08-31 11:29:44.917  7610  7610 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:29:44.917  7610  7610 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-31 11:29:44.917  7610  7610 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 11:29:44.917  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:44.917  7610  7610 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 11:29:44.917  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:44.917  7610  7610 I wpa_supplicant: Associated with F4.99.3E
08-31 11:29:44.917  7610  7610 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:29:44.917  7610  7610 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 11:29:44.917  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:44.917  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:44.917  7610  7610 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:44.917  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:44.917  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:44.917  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 11:29:44.917  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 11:29:44.917  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-31 11:29:44.917  1015  1128 E Tethering: No numeric data
08-31 11:29:44.917  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:44.917  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:29:44.927  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:44.917  1015  1128 D Tethering: clearTetheredNotification()
08-31 11:29:44.927  1177  1177 D HotspotTile: updateTetherState():false, false
08-31 11:29:44.917  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:44.927  7610  7610 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-31 11:29:44.927  7610  7610 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-31 11:29:44.927  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:44.927  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:44.927  7610  7610 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 11:29:44.927  7610  7610 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:44.927  7610  7610 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:29:44.927  7610  7610 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 11:29:44.927  7610  7610 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-31 11:29:44.927  7610  7610 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 11:29:44.927  7610  7610 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-31 11:29:44.927  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:44.927  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:44.927  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 11:29:44.927  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 11:29:44.927  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-31 11:29:44.937  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:44.937  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:44.937  1015  1122 V NetworkStats: performPollLocked() took 16ms
08-31 11:29:44.937  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:44.937  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:44.937  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:44.947  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-31 11:29:44.947  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 11:29:44.947  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 11:29:44.947  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 11:29:44.947  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:44.947  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 11:29:44.957  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:44.957  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 11:29:44.957  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:44.957  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:44.957  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:44.957  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:44.967  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-31 11:29:44.967  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,08-31 11:29:44.967  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:44.967  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:44.967  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-31 11:29:44.967  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:44.967  1638  1638 I Hs20UtilService: Starting #21
,08-31 11:29:44.967  1638  1717 I Hs20UtilService: Message received 5007
,08-31 11:29:44.977  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:29:44.977  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:44.977  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:44.977  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:44.987  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:44.987  3067  3067 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:44.987  3067  3876 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:44.987  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:44.997   277  1014 D CommandListener: Setting iface cfg,
,08-31 11:29:44.997  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,08-31 11:29:45.007  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:45.007  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:45.007  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:45.007  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:45.007  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.007  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.007  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.007  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:45.017  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:45.017  1015  1125 D SecContentProvider2: mCursor = null
,08-31 11:29:45.027  1015  1125 E WifiNative-wlan0: do suspend false
,08-31 11:29:45.027  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:29:45.027  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:29:45.167  6736  6790 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1341)
,08-31 11:29:45.167  6736  6790 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1341)
,08-31 11:29:45.167  6736  6790 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1346)
,08-31 11:29:45.177  6736  6790 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-31 11:29:45.177  6736  6790 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1347)
,08-31 11:29:45.177  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:45.177  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25c00414 added. We now have 2 listener(s)
,08-31 11:29:45.177  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 11:29:45.187  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:29:45.187  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:29:45.187  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:45.187  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7804bd added. We now have 9 listener(s)
,08-31 11:29:45.187  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:45.187  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:45.187  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:45.197  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:45.197  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:45.197  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:45.197  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:45.197  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:45.197  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:45.197  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:45.197  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:45.197  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:45.197  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:45.197  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:45.197  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1889ba03 added. We now have 3 listener(s)
,08-31 11:29:45.207  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.207  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 11:29:45.207  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:45.207  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:45.207  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:45.207  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa34d80 added. We now have 10 listener(s)
08-31 11:29:45.207  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:45.207  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:45.207  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:45.207  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:45.207  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:45.207  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.207  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:45.207  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:45.207  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25c00414 removed from the list
08-31 11:29:45.207  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.207  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7804bd removed from the list
,08-31 11:29:45.207  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.207  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:29:45.207  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:45.207  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:45.207  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:45.207  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:45.207  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:45.207  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.207  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7804bd not in the list
08-31 11:29:45.207  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.207  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:45.217  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:29:45.217  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:45.217  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.217  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa34d80 removed from the list
08-31 11:29:45.217  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:45.217  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.217  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:45.217  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:45.217  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1889ba03 removed from the list
,08-31 11:29:45.217  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:45.217  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a252fb9 added. We now have 2 listener(s)
,08-31 11:29:45.217  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 11:29:45.217  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:29:45.217  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:29:45.217  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:45.217  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3875dffe added. We now have 9 listener(s)
,08-31 11:29:45.217  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:45.217  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:45.227  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:45.227  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:45.227  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:45.227  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:45.227  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:45.227  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:45.227  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:45.227  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:45.227  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:45.227  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:45.227  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:45.227  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:45.227  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fafc1ac added. We now have 3 listener(s)
,08-31 11:29:45.237  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 11:29:45.237  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:45.237  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:45.237  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:45.237  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e00e75 added. We now have 10 listener(s)
08-31 11:29:45.237  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:45.237  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:45.237  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:45.237  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:45.237  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:45.237  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:45.237  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.237  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.247  7622  7622 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 11:29:45.247  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:29:45.247  7622  7622 I dhcpcd  : version 5.5.6 starting
,08-31 11:29:45.257  7622  7622 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 11:29:45.257  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:45.257  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:45.267  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:45.267  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:45.267  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:45.267  7504  7512 D BtGatt.GattService: registerClient() - UUID=20769ba0-034e-4222-8a57-9e9b6724ea33,
,08-31 11:29:45.307  7622  7622 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-31 11:29:45.307  7622  7622 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 11:29:45.307  7622  7622 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 11:29:45.307  7622  7622 I dhcpcd  : bssid match,
08-31 11:29:45.307  7622  7622 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-31 11:29:45.307  7504  7529 D BtGatt.GattService: onClientRegistered() - UUID=20769ba0-034e-4222-8a57-9e9b6724ea33, clientIf=6,
08-31 11:29:45.307  6736  6746 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 11:29:45.317  7504  7591 D BtGatt.GattService: start scan with filters
,08-31 11:29:45.317  7504  7534 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:45.317  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:45.317  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:45.317  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:45.317  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:45.317  7504  7534 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ce22f97
,08-31 11:29:45.317  7504  7529 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 11:29:45.317  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.317  7504  7534 D BtGatt.ScanManager: allow scan with filters
08-31 11:29:45.317  7504  7534 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 11:29:45.317  7504  7534 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-31 11:29:45.317  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:45.317  7504  7529 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 11:29:45.317  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.327  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:45.327  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:45.327  7504  7534 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:45.327  7504  7534 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:29:45.327  7504  7529 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:29:45.327  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:45.327  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:45.327  7504  7529 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:29:45.327  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:45.337  6736  6790 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:29:45.337  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:45.337  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:45.337  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.337  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:45.337  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:45.337  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:45.337  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:45.337  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:45.337  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:45.337  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:45.337  7504  7591 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:45.337  7504  7534 D BtGatt.ScanManager: filter size is 1,
08-31 11:29:45.337   290   290 E SMD     : DCD OFF
08-31 11:29:45.337  7504  7534 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 11:29:45.337  7504  7530 D BtGatt.GattService: unregisterClient() - clientIf=6
08-31 11:29:45.337  7504  7529 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-31 11:29:45.337  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.337  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:45.337  7504  7534 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:29:45.337  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 11:29:45.337  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:45.337  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:45.337  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:29:45.347  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:45.347  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:45.347  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 11:29:45.347  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:29:45.347  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:45.347  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-31 11:29:45.347  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-31 11:29:45.347  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:45.347  7504  7529 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 11:29:45.347  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.347  7504  7534 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:29:45.347  7504  7529 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:29:45.347  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:45.347  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:45.357  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:45.357  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:45.357  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.357  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:45.357  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a252fb9 removed from the list
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.357  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3875dffe removed from the list
08-31 11:29:45.357  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:45.357  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:45.357  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.357  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:45.357  7622  7622 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.357  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3875dffe not in the list
08-31 11:29:45.357  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.357  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:45.357  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e00e75 removed from the list
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:45.357  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:45.357  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:45.357  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fafc1ac removed from the list
,08-31 11:29:45.357  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-31 11:29:45.357  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a301cf1 added. We now have 2 listener(s)
,08-31 11:29:45.357  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 11:29:45.357  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:45.357  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:45.357  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-31 11:29:45.357  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b3f0d6 added. We now have 9 listener(s)
08-31 11:29:45.357  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:45.357  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:45.367  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:45.367  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:45.367  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:45.367  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:45.367  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:45.367  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:45.367  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:45.367  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:45.367  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:45.367  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:45.367  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:45.377  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:45.377  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f69a44 added. We now have 3 listener(s)
,08-31 11:29:45.377  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.377  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 11:29:45.377  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:45.377  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:45.377  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:45.377  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d98972d added. We now have 10 listener(s)
08-31 11:29:45.377  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:45.377  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:45.377  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:45.377  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:45.377  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:45.377  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:45.377  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:45.377  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.377  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:29:45.387  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:45.387  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:45.387  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:45.387  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 11:29:45.387  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:45.397  7504  7530 D BtGatt.GattService: registerClient() - UUID=ffac3add-ee28-46ca-8af0-761e983a7d7c
,08-31 11:29:45.437  7504  7529 D BtGatt.GattService: onClientRegistered() - UUID=ffac3add-ee28-46ca-8af0-761e983a7d7c, clientIf=6
,08-31 11:29:45.437  6736  6746 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 11:29:45.437  7504  7512 D BtGatt.GattService: start scan with filters
,08-31 11:29:45.437  7504  7534 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:45.437  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:29:45.437  7504  7529 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:29:45.437  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.437  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:45.447  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:45.447  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 11:29:45.447  7504  7534 D BtGatt.ScanManager: allow scan with filters
08-31 11:29:45.447  7504  7534 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:29:45.447  7504  7534 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 11:29:45.447  7504  7529 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:29:45.447  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:45.447  7504  7534 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 11:29:45.447  7504  7534 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:29:45.447  7504  7529 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:29:45.447  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:45.457  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:45.457  7504  7529 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:29:45.457  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:45.457  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:45.457  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:29:45.467  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:45.467  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:29:45.467  6736  6790 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 11:29:45.467  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:45.467  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:45.467  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:45.467  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:45.467  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.467  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:29:45.467  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:45.467  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a301cf1 removed from the list
08-31 11:29:45.467  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:45.467  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b3f0d6 removed from the list
08-31 11:29:45.467  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:29:45.467  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:45.477  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:45.477  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 11:29:45.477  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.477  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:45.477  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:45.477  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:45.477  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:45.477  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b3f0d6 not in the list
08-31 11:29:45.477  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:45.477  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:45.477  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:29:45.477  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:45.477  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:45.477  7504  7512 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:45.477  7504  7534 D BtGatt.ScanManager: filter size is 1
08-31 11:29:45.477  7504  7534 D BtGatt.ScanManager: delete FilterIndex - 4
,08-31 11:29:45.477  7504  7517 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:29:45.477  7504  7529 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 11:29:45.477  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.477  7504  7534 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:29:45.487  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:45.487  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:45.487  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:45.487  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:45.487  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:45.487  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:45.487  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-31 11:29:45.487  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:45.487  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:29:45.487  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:45.487  7504  7529 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 11:29:45.487  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.487  7504  7534 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 11:29:45.487  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:45.487  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:45.487  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.487  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d98972d removed from the list
08-31 11:29:45.487  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-31 11:29:45.487  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.487  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:45.487  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:45.487  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f69a44 removed from the list
08-31 11:29:45.487  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:29:45.487  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:45.487  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:45.487  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:45.487  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11947929 added. We now have 2 listener(s)
08-31 11:29:45.487  7504  7529 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 11:29:45.487  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:45.497  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 11:29:45.497  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:45.497  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:29:45.497  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:45.497  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d844ae added. We now have 9 listener(s)
08-31 11:29:45.497  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:45.497  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:45.497  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:45.507  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:45.507  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:45.507  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:45.507  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:45.507  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:45.507  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:45.507  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:45.507  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:45.507  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:45.507  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:45.507  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.507  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.507  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:45.507  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fceddc added. We now have 3 listener(s)
,08-31 11:29:45.517  7622  7622 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
08-31 11:29:45.517  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 11:29:45.517  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:45.517  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:29:45.517  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:45.517  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e527ee5 added. We now have 10 listener(s)
08-31 11:29:45.517  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:45.517  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:45.517  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 11:29:45.517  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:45.517  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:45.517  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:45.527  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:29:45.527  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:45.527  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:45.537  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-31 11:29:45.537  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:45.537  6736  6790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 11:29:45.537  7504  7591 D BtGatt.GattService: registerClient() - UUID=ff8736df-d608-4716-b4b9-b29cce8183c8
,08-31 11:29:45.577  7504  7529 D BtGatt.GattService: onClientRegistered() - UUID=ff8736df-d608-4716-b4b9-b29cce8183c8, clientIf=6
,08-31 11:29:45.587  6736  6746 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-31 11:29:45.587  7504  7517 D BtGatt.GattService: start scan with filters,
08-31 11:29:45.587  7504  7534 D BtGatt.ScanManager: handling starting scan
08-31 11:29:45.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-31 11:29:45.587  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:45.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 11:29:45.587  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:45.587  7504  7529 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 11:29:45.587  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-31 11:29:45.587  7504  7534 D BtGatt.ScanManager: allow scan with filters
08-31 11:29:45.587  7504  7534 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:29:45.587  7504  7534 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-31 11:29:45.587  7504  7529 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-31 11:29:45.587  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.587  7504  7534 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:45.587  7504  7534 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-31 11:29:45.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:45.587  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:29:45.597  7504  7529 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:29:45.597  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.597  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:45.597  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:45.597  7504  7529 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:29:45.597  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:45.607  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:45.607  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:45.607  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:45.607  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:45.607  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.607  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:45.607  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 11:29:45.607  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11947929 removed from the list
08-31 11:29:45.607  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.607  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d844ae removed from the list
08-31 11:29:45.607  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:45.607  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-31 11:29:45.607  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.607  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 11:29:45.607  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.607  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:45.617  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:45.617  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:45.617  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.617  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d844ae not in the list
08-31 11:29:45.617  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:45.617  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:45.617  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:45.617  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:45.617  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:45.617  7504  7591 D BtGatt.GattService: stopScan() - queue size =1,
,08-31 11:29:45.617  7504  7517 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:29:45.627  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:45.627  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:45.627  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:45.627  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:45.627  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:45.627  7504  7534 D BtGatt.ScanManager: filter size is 1
,08-31 11:29:45.627  7504  7534 D BtGatt.ScanManager: delete FilterIndex - 5
,08-31 11:29:45.627  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:45.627  7504  7529 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:29:45.627  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.627  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:45.627  6736  6790 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:45.627  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:29:45.627  7504  7534 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:29:45.627  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:45.637  7504  7529 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:29:45.637  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:45.637  7504  7534 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 11:29:45.637  7504  7529 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 11:29:45.637  7504  7529 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:45.637  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:29:45.637  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:45.637  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.637  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e527ee5 removed from the list
08-31 11:29:45.637  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:45.637  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.637  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:45.637  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:45.637  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fceddc removed from the list
08-31 11:29:45.637  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:45.637  6736  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:45.637  6736  6736 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:45.637  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:45.637  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26312461 added. We now have 2 listener(s)
,08-31 11:29:45.647  1015  1213 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 11:29:45.647  1015  1213 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:29:45.647  1015  1213 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:29:45.647  1015  1213 D BatteryService: stay LED for fully charged
,08-31 11:29:45.647  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:29:45.647  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-31 11:29:45.647  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:45.647  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:45.647  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:45.647  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83b86 added. We now have 9 listener(s)
08-31 11:29:45.647  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:45.647  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-31 11:29:45.657  1015  1015 I MotionRecognitionService: Plugged
08-31 11:29:45.657  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:29:45.657  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 11:29:45.657  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:29:45.657  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 11:29:45.657  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:29:45.667  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-31 11:29:45.667  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 11:29:45.667  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-31 11:29:45.667  7504  7504 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-31 11:29:45.667  7504  7535 D HeadsetStateMachine: Disconnected process message: 10
,08-31 11:29:45.677  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:45.677  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 11:29:45.677  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-31 11:29:45.687  6736  6790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:45.687  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:45.687  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:45.687  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:45.687  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:45.687  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:45.687  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:45.687  6736  6790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:45.687  6736  6790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:45.687  6736  6790 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:45.687  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:45.687  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d71c74 added. We now have 3 listener(s)
,08-31 11:29:45.687  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-31 11:29:45.687  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:45.687  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:45.697  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:45.697  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8faa59d added. We now have 10 listener(s)
,08-31 11:29:45.697  6736  6790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:45.697  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.697  6736  6790 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:45.697  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-31 11:29:45.697  6736  6790 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:45.697  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:45.697  6736  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:45.697  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.697  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:45.697  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:45.697  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26312461 removed from the list
08-31 11:29:45.697  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.697  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83b86 removed from the list
08-31 11:29:45.697  6736  6790 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:45.697  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:45.697  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.697  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-31 11:29:45.697  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:45.697  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:45.697  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.697  6736  6790 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83b86 not in the list
08-31 11:29:45.697  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.697  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:45.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:45.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:45.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:45.707  6736  6790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8faa59d removed from the list
08-31 11:29:45.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:45.707  6736  6790 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:45.707  6736  6790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:45.707  6736  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:45.707  6736  6790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d71c74 removed from the list
08-31 11:29:45.707  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 11:29:45.707  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:29:45.707  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 11:29:45.707  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:45.707  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 11:29:45.707  6736  6790 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:45.717  6736  7652 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1354, name: My test thread name)
08-31 11:29:45.717  6736  7652 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1354, thread name: My test thread name),
08-31 11:29:45.717  6736  7652 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1354, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 11:29:45.717  6736  7654 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1356, name: My test thread name)
08-31 11:29:45.717  6736  7654 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1356, thread name: My test thread name)
08-31 11:29:45.717  6736  7654 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1356, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 11:29:45.717  6736  6790 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 11:29:45.717  6736  6790 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80,
08-31 11:29:45.717  6736  6790 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 11:29:45.717  6736  6790 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 11:29:45.717  6736  6790 D com.test.thalitest.ThaliTestRunner: Total duration: 23338 ms
,08-31 11:29:45.727  6736  6790 I jxcore-log: Total number of executed tests:  80,
08-31 11:29:45.727  6736  6790 I jxcore-log: 
08-31 11:29:45.727  6736  6790 I jxcore-log: Number of passed tests:  80
08-31 11:29:45.727  6736  6790 I jxcore-log: 
08-31 11:29:45.727  6736  6790 I jxcore-log: Number of failed tests:  0
08-31 11:29:45.727  6736  6790 I jxcore-log: ,
08-31 11:29:45.727  6736  6790 I jxcore-log: Number of ignored tests:  0
08-31 11:29:45.727  6736  6790 I jxcore-log: 
08-31 11:29:45.727  6736  6790 I jxcore-log: Total duration:  23338
,08-31 11:29:45.727  6736  6790 I jxcore-log: 
,08-31 11:29:45.727  6736  6790 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
08-31 11:29:45.727  6736  6790 I jxcore-log: 
08-31 11:29:45.727  6736  6790 I jxcore-log: My device name is: samsung-SM-A300FU
08-31 11:29:45.727  6736  6790 I jxcore-log: 
08-31 11:29:45.727  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:45.727  6736  6790 I jxcore-log: 
08-31 11:29:45.737  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:45.737  6736  6790 I jxcore-log: 
08-31 11:29:45.737  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:45.737  6736  6790 I jxcore-log: 
08-31 11:29:45.737  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:45.737  6736  6790 I jxcore-log: 
08-31 11:29:45.737  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:45.737  6736  6790 I jxcore-log: 
08-31 11:29:45.737  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:45.737  6736  6790 I jxcore-log: 
08-31 11:29:45.737  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:29:45.737  6736  6790 I jxcore-log: 
08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-31 11:29:45.747  6736  6790 I jxcore-log: 
08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
,08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
,08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
,08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
08-31 11:29:45.747  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:45.747  6736  6790 I jxcore-log: 
08-31 11:29:45.757  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:45.757  6736  6790 I jxcore-log: 
08-31 11:29:45.757  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:45.757  6736  6790 I jxcore-log: 
08-31 11:29:45.757  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:45.757  6736  6790 I jxcore-log: 
,08-31 11:29:45.757  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:45.757  6736  6790 I jxcore-log: 
08-31 11:29:45.757  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:45.757  6736  6790 I jxcore-log: 
08-31 11:29:45.757  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:45.757  6736  6790 I jxcore-log: 
,08-31 11:29:45.757  6736  6790 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:45.757  6736  6790 I jxcore-log: 
,08-31 11:29:45.837  1015  1125 E WifiNative-wlan0: do suspend true
,08-31 11:29:45.847  6736  6736 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:45.867  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:29:45.867  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:29:45.877  1015  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-31 11:29:45.877  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:45.877  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:45.877  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:45.877  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.877  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:45.877  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:45.877  1015  1125 E WifiStateMachine: VerifyingLinkState enter
,08-31 11:29:45.887  1015  1127 E ConnectivityService: updateNetworkInfo(),
,08-31 11:29:45.887  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-31 11:29:45.887  1015  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-31 11:29:45.897  1015  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
08-31 11:29:45.897  1015  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 11:29:45.897  1015  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 11:29:45.897  1015  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 11:29:45.897  1015  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 11:29:45.897  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:45.897  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:45.897  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.897  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:45.897  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.897  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:45.917  1015  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-31 11:29:45.927  1015  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-31 11:29:45.927  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:45.927  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:45.927  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:45.927  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:45.927  1638  1638 I Hs20UtilService: Starting #22
08-31 11:29:45.927  1638  1717 I Hs20UtilService: Message received 5007
,08-31 11:29:45.927  1015  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-31 11:29:45.937  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 11:29:45.937  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 11:29:45.937  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:45.937  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:45.937  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.937  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.937  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.937  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:45.947  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:29:45.947  1015  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-31 11:29:45.947  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 11:29:45.947  3067  3067 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 11:29:45.947  1015  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-31 11:29:45.947  1015  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:29:45.947  1015  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-31 11:29:45.947  1015  1127 D ConnectivityService: LTETest block dns file not exists
,08-31 11:29:45.947  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 11:29:45.947  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
,08-31 11:29:45.947  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-31 11:29:45.957  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:45.957  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-31 11:29:45.957  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:45.957  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.957  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:45.957  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:45.957  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:45.957  1015  1127 V NetworkStats: updateIfacesLocked()
08-31 11:29:45.957  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:45.957  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:45.957  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:45.967  1015  1127 V NetworkStats: performPollLocked() took 4ms
,08-31 11:29:45.967  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:45.977  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:45.977  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-31 11:29:45.977  1015  1127 E ConnectivityService: updateNetworkInfo()
08-31 11:29:45.977  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:29:45.977  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:45.977  1015  1127 V NetworkStats: updateIfacesLocked()
08-31 11:29:45.977  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:45.977  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:45.977  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:45.977  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:45.987  1015  1127 V NetworkStats: performPollLocked() took 6ms
08-31 11:29:45.977  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:45.987  1015  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-31 11:29:45.987  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:45.987  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-31 11:29:45.987  1015  7619 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:45.987  1015  1127 D ConnectivityService:    accepting network in place of null
08-31 11:29:45.987  1015  7619 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-31 11:29:45.997  1015  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-31 11:29:45.987  1015  7619 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:45.997  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:29:45.987  1015  7619 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-31 11:29:45.987  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:45.987  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:45.987  1015  7619 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 11:29:45.987  6736  6736 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-31 11:29:45.987   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:45.987   277  1010 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-31 11:29:45.987  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 11:29:45.987  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 11:29:45.987  1450  1450 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 11:29:45.987  1450  1450 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:29:45.997  1015  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-31 11:29:45.997  1015  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-31 11:29:45.997  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
08-31 11:29:45.997  1015  1128 D Tethering: MasterInitialState.processMessage what=3
08-31 11:29:45.997  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 11:29:45.997  1015  1122 V NetworkStats: updateIfacesLocked()
08-31 11:29:45.997  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:45.997  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-31 11:29:45.997  1015  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:45.997  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:45.997  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:45.997  1177  1177 D StatusBar.NetworkController: EthernetConnected: false,
,08-31 11:29:45.997  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-31 11:29:45.997  1177  1605 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:29:46.007  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152,
08-31 11:29:45.997  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:46.007  1015  1122 V NetworkStats: performPollLocked() took 13ms
08-31 11:29:45.997  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:45.997  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:46.007  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 11:29:46.007  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 11:29:46.007  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-31 11:29:46.007  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 11:29:46.007  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-31 11:29:46.007  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:46.007  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:46.007  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:46.007  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:46.007  4779  6800 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:29:46.007  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:46.017  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:29:46.017  1638  1638 I Hs20UtilService: Starting #23
,08-31 11:29:46.017  3067  3067 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:46.017  1638  1717 I Hs20UtilService: Message received 5007
,08-31 11:29:46.017  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:46.017  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:46.017  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-31 11:29:46.017  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:46.017  3067  3067 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-31 11:29:46.017  3067  3067 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 11:29:46.017  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 11:29:46.017  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 11:29:46.017  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-31 11:29:46.017  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:46.017  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 11:29:46.017  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:46.017  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:46.017  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:46.017  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:46.027  1015  1379 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:46.027  1015  1379 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:46.027  1015  1379 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:46.027  1015  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:46.027  1015  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:46.037  1638  1638 I Hs20UtilService: Starting #24,
08-31 11:29:46.037  1638  1717 I Hs20UtilService: Message received 5007
,08-31 11:29:46.037  7655  7655 D AndroidRuntime: 
08-31 11:29:46.037  7655  7655 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 11:29:46.037  7655  7655 D AndroidRuntime: CheckJNI is OFF
08-31 11:29:46.037  7655  7655 D AndroidRuntime: readGMSProperty: start
08-31 11:29:46.037  7655  7655 D AndroidRuntime: readGMSProperty: already setted!!
08-31 11:29:46.037  7655  7655 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 11:29:46.037  7655  7655 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 11:29:46.037  7655  7655 D AndroidRuntime: readGMSProperty: end
08-31 11:29:46.037  7655  7655 D AndroidRuntime: addProductProperty: start
,08-31 11:29:46.037  3067  3067 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:29:46.037  3067  3067 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 11:29:46.047  1015  1213 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-31 11:29:46.047  1015  1448 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-31 11:29:46.047  1015  1448 D SecContentProvider2: mCursor = null
,08-31 11:29:46.057  1015  1510 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-31 11:29:46.057  1015  1510 D SecContentProvider2: mCursor = null
,08-31 11:29:46.057  1015  1713 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-31 11:29:46.057  1015  1713 D SecContentProvider2: mCursor = null
,08-31 11:29:46.057  1015  1490 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-31 11:29:46.057  1015  1490 D SecContentProvider2: mCursor = null
,08-31 11:29:46.067  1015  1028 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
,08-31 11:29:46.067  1015  1028 D SecContentProvider2: mCursor = null
08-31 11:29:46.067  1015  1379 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-31 11:29:46.067  1015  1379 D SecContentProvider2: mCursor = null
,08-31 11:29:46.087  1015  7619 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-31 11:29:46.097   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-31 11:29:46.107  1015  1027 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015,
,08-31 11:29:46.117  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 11:29:46.137  6736  6736 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:46.137  1015  7619 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:29:46 GMT], X-Android-Received-Millis=[1472635786154], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472635786129]}
08-31 11:29:46.137  1015  7619 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 11:29:46.137  1015  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-31 11:29:46.137  1015  7619 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-31 11:29:46.137  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-31 11:29:46.137  1015  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-31 11:29:46.137  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-31 11:29:46.137  1177  1605 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:29:46.137  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 11:29:46.137  4779  6800 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 11:29:46.167  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:46.167  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:46.167  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:46.177  7655  7655 E AffinityControl: AffinityControl: registerfunction enter
,08-31 11:29:46.197  7655  7655 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 11:29:46.217  1015  1480 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-31 11:29:46.217  1015  1480 D PackageManager: START PACKAGE DELETE: observer{560668901}
08-31 11:29:46.217  1015  1480 D PackageManager: pkg{<packageName>}
,08-31 11:29:46.217  1015  1480 D PackageManager: user{0}
08-31 11:29:46.217  1015  1480 D PackageManager: caller{2000}
08-31 11:29:46.217  1015  1480 D PackageManager: flags{2}
08-31 11:29:46.217  1015  1480 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-31 11:29:46.217  1015  1480 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-31 11:29:46.217  1015  1480 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 11:29:46.217  1015  1480 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-31 11:29:46.217  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
08-31 11:29:46.217  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-31 11:29:46.217  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-31 11:29:46.227  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-31 11:29:46.227  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 11:29:46.227  1015  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-31 11:29:46.237  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-31 11:29:46.237  1015  1041 I ActivityManager: Killing 6736:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-31 11:29:46.327  1015  1055 W PackageSettings: Skipping PackageSetting{37979ce6 com.example.hello/10168} due to missing metadata
,08-31 11:29:46.327  1015  1480 I WindowState: WIN DEATH: Window{23cc3098 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 11:29:46.327   257  1037 I SurfaceFlinger: id=13 Removed NainActivit (6/9),
08-31 11:29:46.327   257  1037 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-31 11:29:46.337   257  1037 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-31 11:29:46.337  1015  1480 D InputDispatcher: Focus left window: 6736
,08-31 11:29:46.347  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 11:29:46.347  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 11:29:46.367  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{4b93638 u0 com.test.thalitest/.MainActivity t2}
,08-31 11:29:46.367  1015  1592 W ActivityManager: Spurious death for ProcessRecord{34c0f7ba 6736:com.test.thalitest/u0a171}, curProc for 6736: null
,08-31 11:29:46.387  1015  1041 D InputDispatcher: Focused application released
,08-31 11:29:46.387  1015  1041 D FocusedStackFrame: Set to : 0
,08-31 11:29:46.387  1015  1041 W ActivityManager: mDVFSHelper.acquire()
,08-31 11:29:46.397  1015  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-31 11:29:46.407  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-31 11:29:46.437  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 11:29:46.437  1482  1482 D Launcher: onRestart, Launcher: 416313709
,08-31 11:29:46.437  1482  1482 D Launcher: onStart, Launcher: 416313709
,08-31 11:29:46.437  1482  1482 D Launcher.HomeView: onStart
,08-31 11:29:46.457  1482  1482 D Launcher: onResume, Launcher: 416313709
,08-31 11:29:46.457  1015  1027 D SettingsProvider: name = kids_home_mode
08-31 11:29:46.457  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:46.457  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:46.457  1015  1027 D SettingsProvider: selectionArgs: false
08-31 11:29:46.457  1015  1027 D SettingsProvider: selectionArgs: 10006
08-31 11:29:46.457  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:46.457  1015  1027 D SettingsProvider: ret = -1
08-31 11:29:46.457  1482  1482 D Launcher.HomeView: onResume
,08-31 11:29:46.467  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-31 11:29:46.467  2638  2638 I art     : Explicit concurrent mark sweep GC freed 19545(1115KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 812us total 38.348ms
,08-31 11:29:46.467  1878  1878 E SamsungIME: mOCRHelper is null
,08-31 11:29:46.477  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 11:29:46.477  2006  2157 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 11:29:46.487  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-31 11:29:46.487  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 11:29:46.487  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 11:29:46.487  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 11:29:46.487  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-31 11:29:46.497  4779  4779 I art     : Explicit concurrent mark sweep GC freed 22167(1342KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 2.041ms total 83.661ms
,08-31 11:29:46.497  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:46.507  1450  1450 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 11:29:46.507  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 11:29:46.517  2911  2911 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 11:29:46 GMT+02:00 2016
,08-31 11:29:46.517  1440  1440 D PersonaManager: isKioskContainerExistOnDevice,
,08-31 11:29:46.517  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty,
,08-31 11:29:46.537  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
,08-31 11:29:46.537  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-31 11:29:46.537  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:46.547  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:46.547  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:46.557  1015  1122 V NetworkStats: performPollLocked() took 18ms
08-31 11:29:46.557  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:46.557  1015  1448 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 11:29:46.557  1015  1448 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 11:29:46.557  1482  1482 D MenuAppsGridFragment: onResume
,08-31 11:29:46.567  1015  1448 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:46.567  1015  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:46.567  1015  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 11:29:46.567  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-31 11:29:46.567  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-31 11:29:46.577  1440  1440 D RegisteredServicesCache: empty dynamic service
,08-31 11:29:46.577  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:46.577  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:46.577  2911  2911 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 11:29:46.587  1015  1480 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-31 11:29:46.587  1015  1480 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-31 11:29:46.587  1015  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-31 11:29:46.587  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.587  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.587  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.587  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:46.597  1015  1594 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-31 11:29:46.597  1015  1594 D SecContentProvider2: mCursor = null
,08-31 11:29:46.607  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) },
,08-31 11:29:46.607  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0,
,08-31 11:29:46.607  7675  7675 I libpersona: KNOX_SDCARD checking this for 10090
08-31 11:29:46.607  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-31 11:29:46.607  7675  7675 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:46.607  7675  7675 E Zygote  : MountEmulatedStorage()
,08-31 11:29:46.607  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 11:29:46.607  7675  7675 E Zygote  : v2
08-31 11:29:46.607  1015  1040 W TextServicesManagerService: no available spell checker services found
,08-31 11:29:46.607  7675  7675 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:46.607  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-31 11:29:46.607  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-31 11:29:46.607  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 11:29:46.607  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 11:29:46.607  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 11:29:46.607  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 11:29:46.607  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-31 11:29:46.607  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-31 11:29:46.607  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-31 11:29:46.607  7675  7675 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:46.607  7675  7675 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:46.617  2911  2911 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 11:29:46.617  2911  2911 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 11:29:46.617  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:46.627  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:46.627  2911  2911 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-31 11:29:46.627  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:29:46.627  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:46.637  1015  1480 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7675 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-31 11:29:46.637  7675  7675 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:46.637  1015  1593 D ActivityManager: handle home activity for 0
08-31 11:29:46.637  1015  1593 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-31 11:29:46.637  1015  1593 D KnoxTimeoutHandler: post home show event for user 0
08-31 11:29:46.637  7675  7675 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:46.637  1015  1593 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 11:29:46.637  1015  1593 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 11:29:46.637  1015  1593 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-31 11:29:46.647  2911  7674 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 11:29:46.647  1482  1482 D Launcher.HomeView: onPause
,08-31 11:29:46.647  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 11:29:46.647  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-31 11:29:46.647  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
08-31 11:29:46.647  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-31 11:29:46.647  1015  3371 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-31 11:29:46.647  2911  7674 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-31 11:29:46.657  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,08-31 11:29:46.657  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-31 11:29:46.667  2911  7674 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-31 11:29:46.667  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.667  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.667  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.667  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:46.667  1015  1592 I TactileAssist: enable value -1
08-31 11:29:46.667  1015  1592 I TactileAssist: internal enable value -1
08-31 11:29:46.667  1015  1592 I TactileAssist: intensity value -1
,08-31 11:29:46.667  1015  1592 I TactileAssist: saveAppList value true
,08-31 11:29:46.667  1015  1592 I TactileAssist: List of disabled apps :
,08-31 11:29:46.667  2911  7674 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-31 11:29:46.677  1015  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7689 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 11:29:46.687  7689  7689 E Zygote  : MountEmulatedStorage()
08-31 11:29:46.687  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-31 11:29:46.687  7689  7689 E Zygote  : v2
08-31 11:29:46.687  7689  7689 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:46.687  7689  7689 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:46.687  7689  7689 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:46.687  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.687  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.687  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.687  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:46.687  7689  7689 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:46.697  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-31 11:29:46.697  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 11:29:46.697  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-31 11:29:46.697  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 11:29:46.697  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 11:29:46.697  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 11:29:46.697  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 11:29:46.697  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 11:29:46.697  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-31 11:29:46.697  7689  7689 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:46.697  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null,
,08-31 11:29:46.707  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-31 11:29:46.707  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-31 11:29:46.707  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-31 11:29:46.707  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-31 11:29:46.717  7698  7698 E Zygote  : MountEmulatedStorage()
08-31 11:29:46.717  7698  7698 E Zygote  : v2
08-31 11:29:46.717  7698  7698 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:46.717  7698  7698 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:46.717  7698  7698 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:46.717  7698  7698 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:46.717  1015  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7698 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 11:29:46.717  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
08-31 11:29:46.727  7698  7698 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:46.747  7698  7698 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:46.747  7698  7698 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:46.767  2911  7674 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-31 11:29:46.767  7689  7689 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:46.767  7689  7689 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:46.777   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher,
08-31 11:29:46.777  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-31 11:29:46.777  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-31 11:29:46.787  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-31 11:29:46.787  2911  7674 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-31 11:29:46.787  1015  1480 D InputDispatcher: Focus entered window: 1482
,08-31 11:29:46.787  2911  7674 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-31 11:29:46.787  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 11:29:46.787  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 11:29:46.787  1482  1482 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 11:29:46.797  7675  7675 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-31 11:29:46.797  7675  7675 D elm:15121: ELMEngine.ELMEngine( context ).
,08-31 11:29:46.797  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
08-31 11:29:46.797  7675  7675 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-31 11:29:46.797  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:46.807  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{147816fe token=android.os.BinderProxy@1fbc2e65 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-31 11:29:46.807  1482  1482 D Launcher.HomeView: onStop
,08-31 11:29:46.807  1015  1379 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 11:29:46.807  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.807  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.807  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.807  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.807  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:46.817  1015  1379 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6736 uid 10171
,08-31 11:29:46.817  1177  1177 I StatusBar: Icon Only
08-31 11:29:46.817  1177  1177 D PanelView: There is/are notification(s) 
08-31 11:29:46.827  1015  7722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 11:29:46.827  7724  7724 E Zygote  : MountEmulatedStorage(),
08-31 11:29:46.827  7724  7724 I libpersona: KNOX_SDCARD checking this for 10048
08-31 11:29:46.827  7724  7724 E Zygote  : v2
08-31 11:29:46.827  7724  7724 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:46.827  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:29:46.827  7724  7724 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:46.827  7724  7724 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:46.837  1015  1055 I art     : Explicit concurrent mark sweep GC freed 76807(5MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 24MB/37MB, paused 4.896ms total 320.610ms,
08-31 11:29:46.837  7724  7724 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 11:29:46.837  1015  1027 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7724 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-31 11:29:46.837  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 11:29:46.837  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:29:46.837  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 11:29:46.847  1878  1878 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-31 11:29:46.857  7698  7698 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-31 11:29:46.857  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:46.867  7724  7724 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:46.867  7724  7724 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:46.867  1015  1709 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-31 11:29:46.867  1015  1709 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-31 11:29:46.877  1015  1709 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:46.877  1015  1709 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:46.877  1015  1709 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-31 11:29:46.877  7675  7675 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-31 11:29:46.877  1015  1379 D SecContentProvider2: uri = -1 selection = getSealedState
08-31 11:29:46.877  1015  1379 D SecContentProvider2: mCursor = null
,08-31 11:29:46.877  7698  7698 I PopupuiReceiver_KNOX: getSealedState : true
,08-31 11:29:46.877  1015  1448 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
,08-31 11:29:46.877  1015  1448 D SecContentProvider2: mCursor = null
,08-31 11:29:46.877  7698  7698 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-31 11:29:46.887  1015  1712 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-31 11:29:46.887  1015  1712 D SecContentProvider2: mCursor = null
,08-31 11:29:46.887  7698  7698 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
,08-31 11:29:46.887  7698  7698 D PopupuiReceiver: Action package removed
08-31 11:29:46.887  1015  1055 D PackageManager: delete codoeFile: 
,08-31 11:29:46.887  7675  7675 D elm:15121: ElmAgentService : onCreate()
,08-31 11:29:46.887  7675  7739 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-31 11:29:46.887  7675  7739 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-31 11:29:46.887  7675  7739 D elm:15121: MDMBridge.getInstance()
08-31 11:29:46.887  7675  7739 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-31 11:29:46.897  1015  1041 W ActivityManager: mDVFSHelper.release()
,08-31 11:29:46.897  7675  7739 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-31 11:29:46.897  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-31 11:29:46.907  1015  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-31 11:29:46.907  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b95f5e8 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147681
,08-31 11:29:46.907  1015  1379 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-31 11:29:46.907  1015  1379 D SecContentProvider2: mCursor = null
,08-31 11:29:46.907  2911  2911 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 11:29:46.917  1015  1055 D PackageManager: result of delete: 1{560668901}
,08-31 11:29:46.917  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 11:29:46.917  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.917  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.917  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.917  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:46.917  7655  7655 D AndroidRuntime: Shutting down VM
,08-31 11:29:46.927  7741  7741 E Zygote  : MountEmulatedStorage(),
08-31 11:29:46.927  7741  7741 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:46.927  7741  7741 E Zygote  : v2
08-31 11:29:46.927  7741  7741 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:46.927  7741  7741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:46.927  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 11:29:46.927  1015  1055 D PackageManager: userId{-1}
08-31 11:29:46.927  1015  1055 D PackageManager: andCode{true}
08-31 11:29:46.937  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7741 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 11:29:46.937  7741  7741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:46.937  7741  7741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:46.937  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-31 11:29:46.937  7675  7675 D elm:15121: ElmAgentService : onDestroy().
,08-31 11:29:46.937  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.937  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.937  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.937  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:46.947  7689  7689 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-31 11:29:46.947  7724  7724 D Compatibility: onReceive() it will make start service
,08-31 11:29:46.957  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:46.957  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:46.967  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:29:46.967  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 11:29:46.967  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:46.967  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-31 11:29:46.967  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 11:29:46.977  7755  7755 E Zygote  : MountEmulatedStorage()
08-31 11:29:46.977  7755  7755 I libpersona: KNOX_SDCARD checking this for 10003
08-31 11:29:46.977  7755  7755 E Zygote  : v2
08-31 11:29:46.977  7755  7755 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:46.977  7755  7755 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:46.977  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:29:46.977  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-31 11:29:46.977  7755  7755 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:46.977  1015  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7755 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-31 11:29:46.977  1015  1510 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-31 11:29:46.977  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:29:46.977  7755  7755 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:46.977  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.977  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.977  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.977  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:46.977  7741  7741 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:46.987  7741  7741 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:46.997   308   308 I art     : Explicit concurrent mark sweep GC freed 8736(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 19.335ms
,08-31 11:29:46.997  1015  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-31 11:29:47.007  7755  7755 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:47.007  7755  7755 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:47.017   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.484ms
,08-31 11:29:47.027   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 565us total 16.064ms
,08-31 11:29:47.037  7771  7771 E Zygote  : MountEmulatedStorage(),
08-31 11:29:47.047  7771  7771 E Zygote  : v2
08-31 11:29:47.047  7771  7771 I libpersona: KNOX_SDCARD checking this for 10145
08-31 11:29:47.047  7771  7771 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:47.047  7771  7771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:47.047  1015  1510 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7771 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:47.047  7771  7771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:47.057  7771  7771 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 11:29:47.057  1015  1499 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-31 11:29:47.057  1015  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-31 11:29:47.057  1015  1499 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:47.057  1015  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:47.057  1015  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-31 11:29:47.077  1015  1709 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-31 11:29:47.077  1015  1709 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-31 11:29:47.077  1015  1709 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:47.077  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-31 11:29:47.077  1015  1709 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:47.077  1015  1709 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-31 11:29:47.087  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-31 11:29:47.087  1015  1510 I ActivityManager: Killing 7137:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-31 11:29:47.087  7741  7741 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-31 11:29:47.087  7741  7741 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 11:29:47.087  7741  7741 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 11:29:47.097  7771  7771 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:47.097  1015  1510 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-31 11:29:47.097  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 11:29:47.097  7771  7771 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:47.097  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.097  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.097  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.097  1015  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:47.117  7724  7788 D Compatibility: onHandleIntent()
08-31 11:29:47.117  7789  7789 E Zygote  : MountEmulatedStorage()
08-31 11:29:47.117  7789  7789 E Zygote  : v2
08-31 11:29:47.117  7789  7789 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:47.117  7789  7789 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:47.117  7789  7789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:47.117  7789  7789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:47.117  7789  7789 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:47.117  1015  1510 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7789 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 11:29:47.117  7724  7788 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-31 11:29:47.127  7724  7788 D Compatibility: found: 2
,08-31 11:29:47.127  1015  1480 D PersonaManager: isKioskContainerExistOnDevice
08-31 11:29:47.127  7655  7655 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 11:29:47.147  7741  7741 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 11:29:47.147  7741  7741 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 11:29:47.147  7741  7741 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 11:29:47.147  7741  7741 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-31 11:29:47.147  7724  7788 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-31 11:29:47.147  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-31 11:29:47.147  7789  7789 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:47.147  7789  7789 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:47.147  7724  7788 D Compatibility: skipping ResolveInfo{291674ec com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-31 11:29:47.147  7724  7788 D Compatibility: considering ResolveInfo{30b7e0b5 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-31 11:29:47.147  7724  7788 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-31 11:29:47.147  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.147  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.147  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.147  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:47.147  7724  7788 D Compatibility: enabling receiver ResolveInfo{5c0034a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-31 11:29:47.157  7724  7788 D Compatibility: enabling receiver ResolveInfo{8fe22bb com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-31 11:29:47.167  7805  7805 E Zygote  : MountEmulatedStorage()
,08-31 11:29:47.167  7805  7805 E Zygote  : v2
08-31 11:29:47.167  7805  7805 I libpersona: KNOX_SDCARD checking this for 10052
08-31 11:29:47.167  7805  7805 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:47.167  7724  7788 D Compatibility: enabling receiver ResolveInfo{1a6bf3d8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-31 11:29:47.167  7805  7805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:47.167  7805  7805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:47.167  7805  7805 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 11:29:47.167  1015  1028 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7805 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-31 11:29:47.167  7724  7788 D Compatibility: enabling receiver ResolveInfo{1552d331 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-31 11:29:47.177  1015  1028 I ActivityManager: Killing 7123:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-31 11:29:47.177  7724  7788 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
08-31 11:29:47.177  1015  1213 I ActivityManager: Killing 7162:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-31 11:29:47.187  7771  7771 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-31 11:29:47.187  7771  7771 D ThemeInfoUtil: isCurrentFestival = false
,08-31 11:29:47.187  1015  1213 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-31 11:29:47.187  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.187  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.187  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.187  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:47.197  7789  7789 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 11:29:47.207  7821  7821 E Zygote  : MountEmulatedStorage(),
08-31 11:29:47.207  7821  7821 I libpersona: KNOX_SDCARD checking this for 10029
08-31 11:29:47.207  7821  7821 E Zygote  : v2
08-31 11:29:47.207  7821  7821 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:47.207  7821  7821 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:47.207  7821  7821 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:47.207  7805  7805 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:47.207  7805  7805 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:47.217  1015  1213 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7821 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-31 11:29:47.217  7821  7821 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:47.217  1015  1213 I ActivityManager: Killing 7090:com.android.chrome/u0a77 (adj 15): empty #21
,08-31 11:29:47.227  1015  1213 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-31 11:29:47.227  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.227  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.227  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.227  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:47.227  7789  7789 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-31 11:29:47.247  7836  7836 E Zygote  : MountEmulatedStorage(),
08-31 11:29:47.247  7836  7836 E Zygote  : v2
08-31 11:29:47.247  7836  7836 I libpersona: KNOX_SDCARD checking this for 10148
08-31 11:29:47.247  7836  7836 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:47.247  7836  7836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:47.247  7821  7821 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:47.247  7821  7821 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:47.247  1015  1448 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-31 11:29:47.247  7836  7836 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:47.247  1015  1448 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-31 11:29:47.247  7836  7836 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:47.247  1015  1213 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7836 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,08-31 11:29:47.257  1015  1213 I ActivityManager: Killing 7181:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-31 11:29:47.257  1015  1592 I ActivityManager: Killing 7004:com.google.android.talk/u0a102 (adj 15): empty #21
,08-31 11:29:47.257  1015  1028 I ActivityManager: Killing 7202:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,08-31 11:29:47.267  1015  1712 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-31 11:29:47.267  1015  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.267  1015  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.267  1015  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.267  1015  1712 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:47.287  7848  7848 E Zygote  : MountEmulatedStorage(),
08-31 11:29:47.287  7848  7848 E Zygote  : v2
08-31 11:29:47.287  7848  7848 I libpersona: KNOX_SDCARD checking this for 10087,
,08-31 11:29:47.287  7848  7848 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 11:29:47.287  7848  7848 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:47.287  7848  7848 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:47.287  7848  7848 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 11:29:47.287  1015  1712 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7848 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,08-31 11:29:47.317  7848  7848 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:47.317  7848  7848 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:47.317  7836  7836 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:47.317  7836  7836 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:47.347  1482  1482 I Choreographer: Skipped 30 frames!  The application may be doing too much work on its main thread.
,08-31 11:29:47.357  1482  1482 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1fbc2e65 time:148131
,08-31 11:29:47.357  1015  1593 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-31 11:29:47.367  7836  7836 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
08-31 11:29:47.367  1015  1712 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-31 11:29:47.367  1015  1712 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-31 11:29:47.367  1015  1028 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-31 11:29:47.367  1015  1712 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:47.367  1015  1712 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:47.367  1015  1712 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08,-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:47.367  7836  7836 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:47.367  7836  7836 D AndroidRuntime: Shutting down VM
08-31 11:29:47.367  7836  7836 E AndroidRuntime: FATAL EXCEPTION: main
08-31 11:29:47.367  7836  7836 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 7836
08-31 11:29:47.367  7836  7836 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 11:29:47.367  7836 , 7836 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-31 11:29:47.367  7836  7836 E AndroidRuntime: 	... 11 more
08-31 11:29:47.367  1015  1510 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-31 11:29:47.367  1015  1510 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-31 11:29:47.367  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
08-31 11:29:47.367  1015  1510 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:47.367  1015  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:47.367  1015  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-31 11:29:47.377  1015  1379 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
08-31 11:29:47.377  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-31 11:29:47.387  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.387  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.387  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.387  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop200.tmp: open failed: EROFS (Read-only file system)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 11:29:47.387  1015  7867 E DropBoxManagerService: 	... 5 more
08-31 11:29:47.397  7869  7869 E Zygote  : MountEmulatedStorage()
08-31 11:29:47.397  7869  7869 E Zygote  : v2
08-31 11:29:47.397  7869  7869 I libpersona: KNOX_SDCARD checking this for 10152
08-31 11:29:47.397  7869  7869 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:47.407  7869  7869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51

```
