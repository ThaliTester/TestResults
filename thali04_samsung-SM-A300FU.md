#### Test 82894682a24f9af_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-26 17:37:04.362  1015  3282 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 17:37:04.362  1015  3282 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
--------- beginning of main
08-26 17:37:04.372  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 17:37:04.362  1015  3282 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 17:37:04.372  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 17:37:04.362  1015  3282 D BatteryService: stay LED for fully charged
08-26 17:37:04.362  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 17:37:04.362  1015  1015 I MotionRecognitionService: Plugged
08-26 17:37:04.362  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-26 17:37:04.372  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 17:37:04.372  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 17:37:04.382  2711  2711 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 17:37:04.382  2711  2805 D HeadsetStateMachine: Disconnected process message: 10
08-26 17:37:04.402  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 17:37:04.402  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 17:37:04.402  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 17:37:04.652  6671  6671 D AndroidRuntime: 
08-26 17:37:04.652  6671  6671 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 17:37:04.662  6671  6671 D AndroidRuntime: CheckJNI is OFF
08-26 17:37:04.662  6671  6671 D AndroidRuntime: readGMSProperty: start
08-26 17:37:04.662  6671  6671 D AndroidRuntime: readGMSProperty: already setted!!
08-26 17:37:04.662  6671  6671 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 17:37:04.662  6671  6671 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 17:37:04.662  6671  6671 D AndroidRuntime: readGMSProperty: end
08-26 17:37:04.662  6671  6671 D AndroidRuntime: addProductProperty: start
08-26 17:37:04.792  6671  6671 E AffinityControl: AffinityControl: registerfunction enter
08-26 17:37:04.812  6671  6671 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 17:37:04.832  1015  1217 E PersonaManagerService: inState():  stateMachine is null !!
08-26 17:37:04.832  1015  1217 I PersonaManagerService: PersonaId don't exist
08-26 17:37:04.832  1015  1217 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 17:37:04.832  1015  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 17:37:04.852  1015  1217 W ActivityManager: mDVFSHelper.acquire()
08-26 17:37:04.862   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-26 17:37:04.862   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-26 17:37:04.862  1015  1217 D FocusedStackFrame: Set to : 0
08-26 17:37:04.872  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:04.872  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:04.872  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:04.872  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:04.872  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 17:37:04.872  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 17:37:04.882  6682  6682 E Zygote  : MountEmulatedStorage()
08-26 17:37:04.882  6682  6682 E Zygote  : v2
08-26 17:37:04.882  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 17:37:04.892  6682  6682 I libpersona: KNOX_SDCARD checking this for 10171
08-26 17:37:04.892  6682  6682 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:04.892  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 17:37:04.892   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-26 17:37:04.892  6682  6682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:04.892  1015  1217 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6682 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 17:37:04.892  1015  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 17:37:04.892  1015  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 17:37:04.892  1015  1217 D InputDispatcher: Focused application set to: xxxx
08-26 17:37:04.892  1015  1217 D InputDispatcher: Focus left window: 1478
08-26 17:37:04.892  6671  6671 D AndroidRuntime: Shutting down VM
08-26 17:37:04.902  6682  6682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:04.902  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 17:37:04.902  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 17:37:04.902  6682  6682 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 17:37:04.912   311   311 I art     : Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 20.426ms
08-26 17:37:04.922  6682  6682 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:04.922  6682  6682 D ActivityThread: Added TimaKeyStore provider
08-26 17:37:04.932   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 18.025ms
08-26 17:37:04.932  1015  1476 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 17:37:04.932  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 17:37:04.942  1015  1015 V ActivityManager: Display changed displayId=0
08-26 17:37:04.952   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 17.274ms
08-26 17:37:04.962  1015  1476 D PersonaManager: isKioskContainerExistOnDevice
08-26 17:37:04.972  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 17:37:04.982   257   451 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-26 17:37:04.982   257  1037 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-26 17:37:04.992  1478  1478 D Launcher: onTrimMemory. Level: 20
08-26 17:37:04.992  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{337d33d3 token=android.os.BinderProxy@481148f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 17:37:05.062  6682  6682 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 17:37:05.082  6682  6682 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6857-6859)
08-26 17:37:05.082  6682  6682 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 17:37:05.102  6682  6682 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a0af3d6}
08-26 17:37:05.102  6682  6682 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 17:37:05.102  6682  6682 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 17:37:05.102  6671  6671 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 17:37:05.132  6682  6682 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 17:37:05.142  6682  6682 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-26 17:37:05.142  6682  6682 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-26 17:37:05.152  6682  6682 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 17:37:05.152  6682  6682 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 17:37:05.152  6682  6682 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 17:37:05.152  6682  6682 I Adreno-EGL: Local Branch: 
08-26 17:37:05.152  6682  6682 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 17:37:05.152  6682  6682 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 17:37:05.152  6682  6682 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 17:37:05.222  6682  6682 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 17:37:05.232  6682  6682 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 17:37:05.232  6682  6682 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 17:37:05.242  6682  6682 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 17:37:05.242  6682  6682 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 17:37:05.342  6682  6682 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 17:37:05.352   287   287 E SMD     : DCD OFF
,08-26 17:37:05.362  6682  6682 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 17:37:05.372  6682  6682 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-26 17:37:05.372  6682  6682 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-26 17:37:05.382  6682  6682 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 17:37:05.382  6682  6682 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 17:37:05.382  6682  6682 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 17:37:05.462  1015  1041 W ActivityManager: Activity pause timeout for ActivityRecord{36fd00dc u0 com.test.thalitest/.MainActivity t2}
,08-26 17:37:05.502  6682  6723 D OpenGLRenderer: Render dirty regions requested: true
,08-26 17:37:05.502  1015  3282 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 17:37:05.502  1015  3282 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 17:37:05.502  1015  3282 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 17:37:05.502  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 17:37:05.502  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 17:37:05.512  6682  6710 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-26 17:37:05.512  6682  6682 V ActivityThread: updateVisibility : ActivityRecord{1311536 token=android.os.BinderProxy@900155b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 17:37:05.522  6682  6682 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-26 17:37:05.522  6682  6682 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 17:37:05.532   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-26 17:37:05.542  1015  1450 D InputDispatcher: Focus entered window: 6682
,08-26 17:37:05.552  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-26 17:37:05.552  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 17:37:05.552  6682  6682 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 17:37:05.552  6682  6723 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 17:37:05.552  6682  6723 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-26 17:37:05.552  6682  6723 D OpenGLRenderer: Enabling debug mode 0
,08-26 17:37:05.572  1015  1028 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 17:37:05.582  1169  1169 I StatusBar: Icon Only
,08-26 17:37:05.582  1169  1169 D PanelView: There is/are notification(s) 
,08-26 17:37:05.592  1015  6727 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 17:37:05.592  1015  1046 I ActivityManager: Displayed Component not be shown by security: +633ms (total +726ms)
,08-26 17:37:05.592  1015  1046 W ActivityManager: mDVFSHelper.release()
08-26 17:37:05.592  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36fd00dc u0 com.test.thalitest/.MainActivity t2} time:107379
,08-26 17:37:05.602  6682  6682 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-26 17:37:05.602   257  1037 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-26 17:37:05.602  6682  6682 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@900155b time:107384
08-26 17:37:05.602   257   451 I SurfaceFlinger: id=12 Removed uhalitest (-2/9),
,08-26 17:37:05.642  1858  1858 I SamsungIME: getCurrentCandidateView
,08-26 17:37:05.672  6682  6682 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6682
,08-26 17:37:05.732  1858  1858 D SamsungIME: Dismiss ExpandCandiate
,08-26 17:37:05.852  6682  6682 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 17:37:05.882  1858  1858 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 17:37:05.922  1858  1858 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 17:37:05.932  6682  6728 D jxcore_app_log: JniHelper::setJavaVM(0xb6fed2b0), pthread_self() = -1218990912
,08-26 17:37:05.932  1858  1858 I SamsungIME: KeybaordView init() : load resources
,08-26 17:37:05.942  6682  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 17:37:05.942  6682  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 17:37:05.942  6682  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 17:37:05.942  6682  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 17:37:05.942  6682  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 17:37:05.942  6682  6728 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d0a53c added. We now have 1 listener(s)
,08-26 17:37:05.942  6682  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-26 17:37:05.952  6682  6728 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 17:37:05.952  6682  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:05.952  6682  6728 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 17:37:05.952  6682  6728 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b2d0b4b added. We now have 1 listener(s)
,08-26 17:37:05.952  6682  6728 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:05.962  6682  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:05.962  6682  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-26 17:37:05.962  6682  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 17:37:05.962  6682  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 17:37:05.962  6682  6728 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 17:37:05.962  1858  1858 I SamsungIME: getCurrentKeyboard
08-26 17:37:05.962  1858  1858 I SamsungIME: getTextKeyboard
,08-26 17:37:05.962  6682  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:05.972  6682  6728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-26 17:37:05.972  6682  6728 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 17:37:05.972  6682  6728 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:05.972  6682  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:05.972  6682  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:05.972  6682  6728 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:05.972  6682  6728 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:05.972  6682  6728 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:05.972  6682  6728 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:05.972  6682  6728 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:05.972  6682  6728 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 17:37:05.972  6682  6728 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:05.982  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:05.982  6682  6728 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 17:37:05.982  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:05.992  1858  1858 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 17:37:06.012  6682  6682 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 17:37:06.452  1015  1303 E Watchdog: !@Sync 3
,08-26 17:37:06.592  6682  6737 W jxcore-log: Initializing JXcore engine
08-26 17:37:06.592  6682  6737 W jxcore-log: JXcore engine is ready
,08-26 17:37:06.642  1993  1993 E audit   : type=1400 msg=audit(1472225826.642:205): avc:  denied  { ioctl } for  pid=6737 comm="Thread-1240" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 17:37:06.652  1993  1993 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:06.652  1993  1993 E audit   : type=1300 msg=audit(1472225826.642:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f5fb8f8 items=0 ppid=311 ppcomm=main pid=6737 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1240" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 17:37:06.652  1993  1993 E audit   : type=1320 msg=audit(1472225826.642:205): 
,08-26 17:37:06.662  6682  6737 W jxcore-log: Starting JXcore engine
,08-26 17:37:06.762  6682  6737 W jxcore-log: Platform android
08-26 17:37:06.762  6682  6737 W jxcore-log: 
08-26 17:37:06.762  6682  6737 W jxcore-log: Process ARCH arm
08-26 17:37:06.762  6682  6737 W jxcore-log: 
,08-26 17:37:06.962  6682  6737 I jxcore-log: JXcore Cordova bridge is ready!,
08-26 17:37:06.962  6682  6737 I jxcore-log: 
08-26 17:37:06.962  6682  6737 W jxcore-log: JXcore engine is started
,08-26 17:37:06.972  6682  6728 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 17:37:06.972  6682  6682 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 17:37:07.372   326   326 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 17:37:07.372   326   326 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 17:37:08.332  1015  1305 I art     : Explicit concurrent mark sweep GC freed 32909(1984KB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 24MB/36MB, paused 2.449ms total 142.786ms
,08-26 17:37:08.352   287   287 E SMD     : DCD OFF
,08-26 17:37:11.352   287   287 E SMD     : DCD OFF,
,08-26 17:37:11.542  1015  1048 I PowerManagerService: [PWL] Off : 50s ago,
,08-26 17:37:11.922  1015  2806 D SSRM:n  : SIOP:: AP = 350
,08-26 17:37:12.372   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 17:37:12.522  5504  5504 D FactoryTest: Not factory mode
,08-26 17:37:12.522  5504  5504 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 17:37:12.522  5504  5504 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-26 17:37:12.522  5504  5504 D MTPRx   : still no open session command from host, so toast
08-26 17:37:12.522  5504  5504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-26 17:37:12.532  5504  5504 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 17:37:12.532  5504  5504 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114313,
,08-26 17:37:12.532  1015  1476 E PersonaManagerService: inState():  stateMachine is null !!
,08-26 17:37:12.532  1015  1476 I PersonaManagerService: PersonaId don't exist
,08-26 17:37:12.532  1015  1476 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 17:37:12.532  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 17:37:12.542  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:12.542  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:12.542  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 17:37:12.542  1015  1476 W ActivityManager: mDVFSHelper.acquire()
,08-26 17:37:12.562  1015  1476 D PersonaManager: isKioskContainerExistOnDevice
,08-26 17:37:12.572  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 17:37:12.572  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 17:37:12.572  1015  1476 D InputDispatcher: Focused application set to: xxxx
,08-26 17:37:12.572  1015  1476 D InputDispatcher: Focus left window: 6682
,08-26 17:37:12.572  5504  5504 E MTPRx   : started activity for popup
,08-26 17:37:12.572  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 17:37:12.572  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 17:37:12.612  5504  5504 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-26 17:37:12.612  5504  5504 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 17:37:12.612  5504  5504 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 17:37:12.612  5504  5504 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 17:37:12.612  5504  5504 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 17:37:12.612  5504  5504 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 17:37:12.642  5504  5504 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 17:37:12.642  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 17:37:12.642  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 17:37:12.642  1015  1476 D InputDispatcher: Focused application set to: xxxx
,08-26 17:37:12.642  1015  1476 D InputDispatcher: Focus entered window: 6682
,08-26 17:37:12.642  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 17:37:12.652  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 17:37:12.652  1015  1133 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 17:37:12.652  1015  1133 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@40d561f attribute=null, token = android.os.BinderProxy@2cbf432f
,08-26 17:37:12.682  5504  5504 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-26 17:37:12.692  5504  5504 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-26 17:37:12.692  5504  5504 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 17:37:12.712  6682  6682 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 17:37:12.712  6682  6682 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-26 17:37:12.712  6682  6682 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 17:37:12.712  6682  6682 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 17:37:12.722  1015  1217 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 17:37:12.722  1015  1217 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-26 17:37:12.722  1015  1217 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 17:37:12.722  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 17:37:12.722  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 17:37:12.732  6682  6682 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 17:37:12.732  6682  6682 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 17:37:12.742  6682  6682 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@33de6347 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1835cdc, 16908290=android.view.AbsSavedState$1@1835cdc}, android:focusedViewId=100}]}]
08-26 17:37:12.742  6682  6682 V ActivityThread: updateVisibility : ActivityRecord{1311536 token=android.os.BinderProxy@900155b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 17:37:12.742  6682  6682 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 17:37:12.742  6682  6682 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 17:37:12.742  6682  6682 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 17:37:12.742  6682  6682 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@900155b time:114521
,08-26 17:37:12.752  1015  3282 D PersonaManager: isKioskContainerExistOnDevice
,08-26 17:37:13.372   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 17:37:14.352   287   287 E SMD     : DCD OFF
,08-26 17:37:14.372   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 17:37:14.422  1015  1738 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 17:37:14.422  1015  1738 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 17:37:14.422  1015  1738 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 17:37:14.422  1015  1738 D BatteryService: stay LED for fully charged
08-26 17:37:14.422  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 17:37:14.432  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 17:37:14.432  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 17:37:14.432  1015  1015 I MotionRecognitionService: Plugged
08-26 17:37:14.432  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-26 17:37:14.432  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 17:37:14.432  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 17:37:14.442  2711  2711 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 17:37:14.442  2711  2805 D HeadsetStateMachine: Disconnected process message: 10
,08-26 17:37:14.452  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 17:37:14.452  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 17:37:14.452  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 17:37:14.922  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 17:37:15.172  1015  2863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 17:37:15.372   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 17:37:15.542  1015  1041 W ActivityManager: mDVFSHelper.release()
,08-26 17:37:16.372   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 17:37:17.362   287   287 E SMD     : DCD OFF,
,08-26 17:37:17.372   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 17:37:18.222  1015  1094 V AlarmManager: waitForAlarm result :4,
08-26 17:37:18.222  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-26 17:37:18.242  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-26 17:37:18.242  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-26 17:37:18.242  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-26 17:37:18.242  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-26 17:37:18.242  1169  1169 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 17:37:18.252  1169  1169 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 17:37:18.262  2018  2018 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-26 17:37:18.262  1169  1169 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 17:37:18.272  1169  1169 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 17:37:18.282  1169  1169 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-26 17:37:18.282  1169  1169 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 17:37:18.302  1169  1169 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 17:37:18.302  1169  1169 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 17:37:18.312  1015  1305 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 17:37:18.312  1015  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-26 17:37:18.312  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:18.312  1015  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:18.312  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:18.322  1169  1169 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 17:37:18.332  1169  1169 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 17:37:18.392  4294  4294 D ConnectivityManager: CallingUid : 10011, CallingPid : 4294
,08-26 17:37:18.392  1015  1217 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 17:37:18.392  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-26 17:37:18.392  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-26 17:37:18.392  1015  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-26 17:37:18.392  4294  6746 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 17:37:18.452  4294  6747 W DriveInitializer: Background init thread started
,08-26 17:37:18.492   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-26 17:37:18.492   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 17:37:18.492  4294  6747 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-26 17:37:18.522  2018  2018 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-26 17:37:18.562  1015  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 17:37:18.562  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-26 17:37:18.562  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:18.562  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:18.562  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:18.582  1015  3282 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-26 17:37:18.582  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-26 17:37:18.602  1015  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 17:37:18.602  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-26 17:37:18.602  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:18.602  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 17:37:18.602  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:18.622  4294  6755 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-26 17:37:18.622  4294  6755 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 17:37:18.652  4294  6747 W DriveInitializer: Background init thread ended
,08-26 17:37:18.662  2018  2018 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 17:37:18.702  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:18.702  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:18.702  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:18.802  1015  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 17:37:18.802  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-26 17:37:18.802  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:18.802  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:18.802  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:18.842  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 17:37:18.842  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-26 17:37:18.842  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:18.842  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:18.842  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:18.892  1015  1738 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 17:37:18.892  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:18.892  1015  1738 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:18.892  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 17:37:18.912  1015  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 17:37:18.912  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:18.922  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:18.922  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:18.982  1015  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:18.982  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:18.982  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:18.982  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:18.992  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:18.992  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:18.992  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:18.992  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:19.002  6760  6760 E Zygote  : MountEmulatedStorage(),
,08-26 17:37:19.012  6760  6760 E Zygote  : v2
08-26 17:37:19.012  6760  6760 I libpersona: KNOX_SDCARD checking this for 10011
08-26 17:37:19.012  6760  6760 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:19.012  1015  1133 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6760 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 17:37:19.012  6760  6760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 17:37:19.012  6760  6760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:19.022  6760  6760 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 17:37:19.052  6760  6760 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:19.052  6760  6760 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:19.072  6760  6760 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 17:37:19.072  6760  6760 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 17:37:19.112  6760  6760 I MultiDex: VM with version 2.1.0 has multidex support
08-26 17:37:19.112  6760  6760 I MultiDex: install
08-26 17:37:19.112  6760  6760 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 17:37:19.142  6760  6760 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 17:37:19.212  6760  6760 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 17:37:19.212  6760  6760 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30beec72: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 17:37:19.212  6760  6760 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 17:37:19.232  6760  6760 D ChimeraCfgMgr: Reading stored module config
,08-26 17:37:19.232  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-26 17:37:19.252  1015  3282 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:19.252  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:19.252  1015  3282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:19.252  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:19.262  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:19.262  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:19.262  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:19.262  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:19.302  2018  2018 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=75328556-8426-46dd-8a57-1d70bd80c7b2
,08-26 17:37:19.312  1015  1450 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 17:37:19.322  1015  1450 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 17:37:19.322  1015  1450 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:19.322  1015  1450 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 17:37:19.322  1015  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:19.332  2018  2018 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 17:37:19.332  6760  6778 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 17:37:19.332  2018  2018 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 17:37:19.352  1015  3282 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:19.352  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:19.352  1015  3282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:19.352  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:19.372  6760  6760 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 17:37:19.372  6760  6760 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 17:37:19.382  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 17:37:19.382  6682  6737 I jxcore-log: 
,08-26 17:37:19.382  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 17:37:19.382  6682  6737 I jxcore-log: 
,08-26 17:37:19.392  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:19.392  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:19.392  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:19.392  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:19.392  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:19.392  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:19.392  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:19.392  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:19.402  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:19.402  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 17:37:19.402  6682  6737 I jxcore-log: 
,08-26 17:37:19.402  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 17:37:19.402  6682  6737 I jxcore-log: 
,08-26 17:37:19.452  3831  3845 I art     : Explicit concurrent mark sweep GC freed 1384(47KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 887us total 31.223ms
,08-26 17:37:19.452  3831  3960 I art     : WaitForGcToComplete blocked for 30.601ms for cause Explicit
,08-26 17:37:19.472   282   698 D WVCdm   : Instantiating CDM.
,08-26 17:37:19.472   282   699 I WVCdm   : CdmEngine::OpenSession
,08-26 17:37:19.472   282   699 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-26 17:37:19.482  3831  3960 I art     : Explicit concurrent mark sweep GC freed 1205(55KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 715us total 23.756ms
,08-26 17:37:19.502   282   699 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 17:37:19.522   282   699 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-26 17:37:19.532  6760  6768 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-26 17:37:19.532  6760  6768 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 17:37:19.532  6760  6768 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 17:37:19.532  6760  6768 I System.out: (HTTPLog)-Thread-1219-620270103: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-26 17:37:19.532  6760  6768 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 17:37:19.532   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 17:37:19.532   277  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 17:37:19.562  2018  2143 W GCoreFlp: No location to return for getLastLocation()
,08-26 17:37:19.582   282   699 I WVCdm   : CdmEngine::QueryKeyControlInfo,
,08-26 17:37:19.582  6760  6768 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 17:37:19.582  6760  6768 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6760, getuid(): 10011
08-26 17:37:19.582   282   282 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-26 17:37:19.582   282   282 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-26 17:37:19.582   282   282 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-26 17:37:19.592   282   282 D WVCdm   : PrepareKeyRequest: nonce=1206797077
,08-26 17:37:19.622  1015  1305 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:19.622  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:19.622  1015  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:19.622  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:19.622  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:19.622  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:19.622  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:19.622  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:19.632  1015  3282 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:19.632  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:19.632  1015  3282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:19.632  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:19.642  4294  6756 D UdcContextInitService: registered all accounts: true
,08-26 17:37:19.652  2018  2146 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 17:37:19.672  2018  2165 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 17:37:19.802  2018  2165 I art     : Explicit concurrent mark sweep GC freed 51874(2MB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 11MB/18MB, paused 1.389ms total 69.274ms
,08-26 17:37:19.862  6760  6768 I qtaguid : Untagging socket 33
,08-26 17:37:19.972  1015  1454 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 17:37:19.972  1015  1454 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 17:37:19.972  1015  1454 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:19.972  1015  1454 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:19.972  1015  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:20.172  6682  6737 D executeNativeTests: Running unit tests
,08-26 17:37:20.192  6790  6790 I dex2oat : ----------------------------------------------------
08-26 17:37:20.192  6790  6790 I dex2oat : <SS>: S T A R T I N G . . .
08-26 17:37:20.192  6790  6790 I dex2oat : <SS>: Zip is absent. Canceled.
,08-26 17:37:20.202  6790  6790 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 17:37:20.262  6790  6790 I dex2oat : dex2oat took 62.407ms (threads: 4)
,08-26 17:37:20.272  6760  6768 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 17:37:20.272  6760  6768 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 17:37:20.272  6760  6768 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 17:37:20.272  6760  6768 I Adreno-EGL: Local Branch: 
08-26 17:37:20.272  6760  6768 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 17:37:20.272  6760  6768 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 17:37:20.272  6760  6768 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 17:37:20.272  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:20.272  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 added. We now have 2 listener(s)
,08-26 17:37:20.282  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 17:37:20.282  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:20.282  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:20.282  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:20.282  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a added. We now have 2 listener(s)
08-26 17:37:20.282  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:20.282  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 17:37:20.282  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:20.282  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:20.282  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:20.282  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:20.282  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:20.282  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:20.282  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:20.282  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:20.282  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:20.282  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:20.282  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:20.292  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.292  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 17:37:20.292  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 17:37:20.292  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 17:37:20.292  6682  6737 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 17:37:20.292  6682  6737 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 17:37:20.292  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 17:37:20.292  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:20.292  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:20.292  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:20.292  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.292  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.292  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.292  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.292  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:20.292  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:20.292  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 removed from the list
08-26 17:37:20.292  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.292  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a removed from the list
,08-26 17:37:20.292  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.292  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.292  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.302  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:20.302  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.302  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:20.302  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.302  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:20.302  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.302  6682  6737 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 17:37:20.302  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:20.302  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.302  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.312  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.312  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.312  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.312  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.312  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.312  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.312  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.312  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.312  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.312  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.312  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:20.312  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.312  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.312  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections,: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 17:37:20.312  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.312  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.312  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.312  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.312  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.312  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.312  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.312  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.312  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.312  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.312  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.312  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.312  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.312  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.322  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.322  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.322  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.322  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.322  6682  6737 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 17:37:20.322  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:20.322  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:20.322  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:20.322  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:20.322  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:20.322  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:20.322  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:20.322  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:20.322  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:20.322  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:20.322  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:20.322  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:20.332  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:20.332  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:20.332  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:20.332  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 17:37:20.332  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 17:37:20.332  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:20.332  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:20.342  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 17:37:20.342  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 17:37:20.352  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 17:37:20.352  6760  6768 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 17:37:20.352  6760  6768 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 17:37:20.352  6760  6768 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 17:37:20.352  6760  6768 I Adreno-EGL: Local Branch: 
08-26 17:37:20.352  6760  6768 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 17:37:20.352  6760  6768 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 17:37:20.352  6760  6768 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-26 17:37:20.352  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 17:37:20.352  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 17:37:20.352  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:20.352  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 17:37:20.362   287   287 E SMD     : DCD OFF
08-26 17:37:20.372  2711  2972 D BtGatt.GattService: registerClient() - UUID=efacaf48-649a-4e8c-aba2-4e16d644d831
,08-26 17:37:20.412  2711  2792 D BtGatt.GattService: onClientRegistered() - UUID=efacaf48-649a-4e8c-aba2-4e16d644d831, clientIf=6
,08-26 17:37:20.422  6682  6691 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 17:37:20.422  2711  2969 D BtGatt.GattService: start scan with filters
,08-26 17:37:20.422  2711  2804 D BtGatt.ScanManager: handling starting scan
,08-26 17:37:20.422  2711  2804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:20.422  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 17:37:20.422  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 17:37:20.422  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 17:37:20.422  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 17:37:20.432  2711  2792 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 17:37:20.432  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.432  2711  2804 D BtGatt.ScanManager: allow scan with filters
,08-26 17:37:20.432  2711  2804 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 17:37:20.432  2711  2804 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 17:37:20.432  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:20.432  2711  2792 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 17:37:20.432  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.432  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:20.432  2711  2804 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:20.432  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 17:37:20.432  2711  2804 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 17:37:20.442  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 17:37:20.442  2711  2792 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 17:37:20.442  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.442  6682  6737 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 17:37:20.442  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:20.442  6682  6737 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 17:37:20.442  2711  2792 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 17:37:20.442  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.442  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 17:37:20.442  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.442  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 17:37:20.442  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 17:37:20.442  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:20.442  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:20.442  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 17:37:20.452  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 17:37:20.452  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 17:37:20.452  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.452  2711  2721 D BtGatt.GattService: stopScan() - queue size =1
,08-26 17:37:20.452  2711  2972 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 17:37:20.452  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:20.452  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 17:37:20.452  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:20.452  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:20.452  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 17:37:20.452  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:20.452  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 17:37:20.452  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 17:37:20.452  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 17:37:20.452  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:20.452  2711  2804 D BtGatt.ScanManager: filter size is 1
08-26 17:37:20.452  2711  2804 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 17:37:20.452  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.452  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:20.452  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.452  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:20.452  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.452  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.452  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.452  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.452  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.462  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:20.462  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:20.462  6682  6737 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 17:37:20.462  2711  2792 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 17:37:20.462  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.462  2711  2804 D BtGatt.ScanManager: stopping BLe Batch
,08-26 17:37:20.462  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:20.462  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:20.462  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:20.462  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:20.462  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:20.462  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:20.462  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:20.462  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:20.462  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:20.462  2711  2792 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 17:37:20.462  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.462  2711  2804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 17:37:20.472  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:20.472  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:20.472  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:20.472  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:20.472  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:20.472  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:20.472  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 17:37:20.472  2711  2792 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 17:37:20.472  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.472  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.472  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.472  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 17:37:20.482  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 17:37:20.482  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 17:37:20.482  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 17:37:20.482  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:20.482  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 17:37:20.482  2711  2972 D BtGatt.GattService: registerClient() - UUID=17aacc84-8d85-4060-94c2-a07c413f20f9
,08-26 17:37:20.522  2711  2792 D BtGatt.GattService: onClientRegistered() - UUID=17aacc84-8d85-4060-94c2-a07c413f20f9, clientIf=6
,08-26 17:37:20.532  6682  6690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 17:37:20.532  2711  2969 D BtGatt.GattService: start scan with filters
,08-26 17:37:20.532  2711  2804 D BtGatt.ScanManager: handling starting scan
,08-26 17:37:20.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 17:37:20.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 17:37:20.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 17:37:20.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 17:37:20.532  2711  2792 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 17:37:20.532  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.532  2711  2804 D BtGatt.ScanManager: allow scan with filters
08-26 17:37:20.532  2711  2804 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 17:37:20.532  2711  2804 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 17:37:20.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:20.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-26 17:37:20.532  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:20.532  2711  2792 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 17:37:20.532  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.532  2711  2804 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:20.532  2711  2804 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 17:37:20.542  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 17:37:20.542  2711  2792 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 17:37:20.542  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.542  6682  6737 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 17:37:20.542  2711  2792 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 17:37:20.542  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.552  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.552  6682  6737 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 17:37:20.552  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.552  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 17:37:20.552  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 17:37:20.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 17:37:20.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:20.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:20.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:20.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 17:37:20.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 17:37:20.552  2711  2721 D BtGatt.GattService: stopScan() - queue size =1
,08-26 17:37:20.552  2711  2804 D BtGatt.ScanManager: filter size is 1
08-26 17:37:20.552  2711  2804 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 17:37:20.552  2711  2972 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 17:37:20.552  2711  2792 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 17:37:20.552  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:20.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 17:37:20.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:20.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:20.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 17:37:20.552  2711  2804 D BtGatt.ScanManager: stopping BLe Batch
,08-26 17:37:20.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:20.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 17:37:20.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 17:37:20.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 17:37:20.562  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:20.562  2711  2792 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 17:37:20.562  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.562  2711  2804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 17:37:20.562  2711  2792 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 17:37:20.562  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.562  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.562  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.562  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:20.562  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.562  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.562  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.562  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.562  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.562  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:20.562  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:20.562  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:20.562  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.562  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.562  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.562  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.562  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.562  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.562  6682  6737 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 17:37:20.562  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:20.572  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:20.572  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:20.572  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:20.572  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:20.572  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:20.572  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:20.572  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:20.572  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:20.572  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:20.572  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:20.572  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.572  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:20.572  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:20.572  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:20.572  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:20.572  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 17:37:20.572  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.582  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 17:37:20.582  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 17:37:20.582  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 17:37:20.582  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 17:37:20.582  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:20.592  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 17:37:20.592  2711  2969 D BtGatt.GattService: registerClient() - UUID=fc5d73da-4df7-419a-aa8e-61c828009d8b
,08-26 17:37:20.602  6760  6768 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 17:37:20.602  6760  6768 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 17:37:20.602  6760  6768 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 17:37:20.602  6760  6768 I Adreno-EGL: Local Branch: 
08-26 17:37:20.602  6760  6768 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 17:37:20.602  6760  6768 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 17:37:20.602  6760  6768 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 17:37:20.632  2711  2792 D BtGatt.GattService: onClientRegistered() - UUID=fc5d73da-4df7-419a-aa8e-61c828009d8b, clientIf=6,
08-26 17:37:20.632  6682  6691 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 17:37:20.632  2711  2722 D BtGatt.GattService: start scan with filters
08-26 17:37:20.632  2711  2804 D BtGatt.ScanManager: handling starting scan
08-26 17:37:20.632  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 17:37:20.632  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 17:37:20.632  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-26 17:37:20.632  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 17:37:20.632  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 17:37:20.642  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:20.642  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 17:37:20.642  2711  2792 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 17:37:20.642  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.642  2711  2804 D BtGatt.ScanManager: allow scan with filters
,08-26 17:37:20.642  2711  2804 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 17:37:20.642  2711  2804 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 17:37:20.642  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 17:37:20.642  2711  2792 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 17:37:20.642  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.642  2711  2804 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:20.642  2711  2804 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 17:37:20.652  6682  6737 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 17:37:20.652  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:20.652  2711  2792 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 17:37:20.652  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.652  6682  6737 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 17:37:20.652  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:20.652  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 17:37:20.652  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.652  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 17:37:20.652  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 17:37:20.652  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:20.652  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:20.652  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:20.652  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 17:37:20.652  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 17:37:20.652  2711  2792 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 17:37:20.652  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.652  2711  2969 D BtGatt.GattService: stopScan() - queue size =1
,08-26 17:37:20.652  2711  2804 D BtGatt.ScanManager: filter size is 1
08-26 17:37:20.662  2711  2804 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 17:37:20.662  2711  2722 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 17:37:20.662  2711  2792 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 17:37:20.662  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:20.662  2711  2804 D BtGatt.ScanManager: stopping BLe Batch
08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 17:37:20.662  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:20.662  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 17:37:20.662  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:20.662  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-26 17:37:20.662  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:20.662  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:20.662  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.662  6682  6737 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 17:37:20.662  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.662  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.662  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.662  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:20.662  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.662  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.662  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.662  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.662  2711  2792 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 17:37:20.662  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.662  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.662  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.662  2711  2804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 17:37:20.662  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.662  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.662  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:20.662  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.672  6682  6737 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 17:37:20.672  2711  2792 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 17:37:20.672  2711  2792 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:20.672  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.672  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.672  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.672  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.672  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 17:37:20.672  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.672  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.672  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.672  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.672  6682  6737 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 17:37:20.672  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.672  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.672  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.672  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.672  6682  6737 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 17:37:20.672  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.672  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.672  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.672  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.672  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.672  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 17:37:20.672  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 17:37:20.672  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:20.672  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 17:37:20.672  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 17:37:20.682  6682  6737 I io.jxcore.node.ConnectionHelper: stop: ,Stopping all activities and killing connections
08-26 17:37:20.682  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.682  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.682  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.682  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.682  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.682  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.682  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.682  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.682  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.682  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.682  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.682  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 17:37:20.682  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.682  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.682  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.682  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.682  6682  6737 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-26 17:37:20.682  6682  6737 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 17:37:20.682  6682  6737 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 17:37:20.682  6682  6737 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-26 17:37:20.682  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 17:37:20.682  6682  6737 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-26 17:37:20.682  6682  6737 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 17:37:20.682  6682  6737 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 17:37:20.682  6682  6737 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 17:37:20.682  6682  6737 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 17:37:20.682  6682  6737 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-26 17:37:20.682  6682  6737 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 17:37:20.682  6682  6737 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 17:37:20.682  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 17:37:20.682  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55,
08-26 17:37:20.682  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 17:37:20.682  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 17:37:20.692  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 17:37:20.692  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 17:37:20.692  6682  6737 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 17:37:20.692  6682  6737 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 17:37:20.692  6682  6737 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 17:37:20.692  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.692  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.692  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.692  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.692  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.692  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.692  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-26 17:37:20.702  6682  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1304)
,08-26 17:37:20.702  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.702  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.702  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.702  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.702  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.702  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.702  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.702  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.702  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:20.702  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.702  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.702  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.702  6682  6737 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-26 17:37:20.702  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:20.702  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.702  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.702  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.702  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:20.702  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.702  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.702  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:20.702  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.702  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.702  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.702  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.702  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.702  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.712  6682  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1304
,08-26 17:37:20.712  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:20.712  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.712  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.712  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.712  6682  6737 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-26 17:37:20.712  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.712  6682  6799 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-26 17:37:20.712  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.712  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.712  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:20.712  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.712  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.712  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.712  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.712  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.712  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:20.712  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.712  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.712  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.712  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.712  6682  6799 D BluetoothSocket: connect(): myUserId = 0
08-26 17:37:20.712  6682  6799 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:20.712  2711  2721 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:20.722  6682  6799 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.722  6682  6737 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 17:37:20.722  6682  6737 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 17:37:20.722  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 17:37:20.722  6682  6737 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 17:37:20.722  6682  6737 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 17:37:20.722  6682  6737 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 17:37:20.722  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 17:37:20.722  6682  6737 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 17:37:20.722  6682  6737 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 17:37:20.722  6682  6737 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 17:37:20.722  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 17:37:20.722  6682  6737 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 17:37:20.722  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.722  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.722  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.722  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.722  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.722  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.722  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.722  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.722  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.722  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release:, 1 listener(s) left
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.722  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.722  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.722  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.722  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.722  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.722  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 17:37:20.722  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.722  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.722  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:20.722  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.722  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.722  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
,08-26 17:37:20.722  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.722  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.722  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.722  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.722  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.722  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.722  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.732  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 17:37:20.732  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:20.732  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.732  6682  6682 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 17:37:20.732  6682  6682 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 17:37:20.732  6682  6801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-26 17:37:20.732  6682  6801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:20.732  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:20.732  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:20.732  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:20.732  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.732  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.732  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.732  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.732  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.732  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.732  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.732  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.732  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.732  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.732  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.732  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.742  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.742  6682  6737 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-26 17:37:20.742  6682  6682 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-26 17:37:20.742  6682  6737 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 17:37:20.742  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 17:37:20.742  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.742  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.742  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.742  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:20.742  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.742  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.742  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.742  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.742  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.742  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.742  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.742  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.742  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.742  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-26 17:37:20.742  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.742  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:20.742  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.752  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.752  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.752  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list,
08-26 17:37:20.752  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.752  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.752  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.752  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.752  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.752  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.752  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.752  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.752  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.752  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.752  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.752  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:20.752  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:20.752  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:20.752  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:20.752  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.752  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.752  6682  6737 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121fee55 not in the list
08-26 17:37:20.752  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.752  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
08-26 17:37:20.752  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:20.752  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.752  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:20.752  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:20.752  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:20.752  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:20.752  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:20.752  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:20.752  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf4906a not in the list
,08-26 17:37:20.752  6682  6737 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 17:37:20.752  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 17:37:20.752  6682  6737 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 17:37:20.752  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 17:37:20.752  6682  6737 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 17:37:20.752  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-26 17:37:20.752  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 17:37:20.752  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-26 17:37:20.752  6682  6737 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 17:37:20.752  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 17:37:20.752  6682  6737 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-26 17:37:20.752  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 17:37:20.752  6682  6737 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 17:37:20.762  6682  6737 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-26 17:37:20.762  6682  6737 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-26 17:37:20.762  6682  6737 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-26 17:37:20.762  6682  6737 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 17:37:20.762  6682  6737 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 17:37:20.762  6682  6737 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 17:37:20.762  6682  6737 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-26 17:37:20.762  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 17:37:20.762  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e26793c added. We now have 2 listener(s)
08-26 17:37:20.762  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:20.762  6682  6737 D BluetoothAdapter: enable()
,08-26 17:37:20.762  6682  6737 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 17:37:20.762  1015  1469 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 17:37:20.772  1015  1469 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 17:37:20.772  1015  1469 D SecContentProvider2: mCursor = null
,08-26 17:37:20.772  1015  1469 D WifiService: setWifiEnabled: true pid=6682, uid=10171
,08-26 17:37:20.772  1015  1469 W ActivityManager: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 17:37:20.772  1015  1469 W WifiService: Failed getting userId using ActivityManagerNative
08-26 17:37:20.772  1015  1469 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 17:37:20.772  1015  1469 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 17:37:20.772  1015  1469 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 17:37:20.772  1015  1469 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 17:37:20.772  1015  1469 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 17:37:20.772  1015  1469 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 17:37:20.772  1015  1469 D SettingsProvider: name = wifi_on
,08-26 17:37:20.782  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:20.782  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fba16c5 added. We now have 3 listener(s)
08-26 17:37:20.782  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:20.782  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:20.782  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3689e81a added. We now have 4 listener(s)
08-26 17:37:20.782  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:20.782  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:20.782  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b8bef4b added. We now have 5 listener(s)
08-26 17:37:20.782  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:20.782  1015  1454 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 17:37:20.782  1015  1454 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 17:37:20.782  1015  1454 D SecContentProvider2: mCursor = null
,08-26 17:37:20.792  1015  1454 D WifiService: setWifiEnabled: false pid=6682, uid=10171
,08-26 17:37:20.792  1015  1454 D SettingsProvider: name = wifi_on
,08-26 17:37:20.792  1015  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 17:37:20.802  1382  1382 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 17:37:20.802  1382  1382 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-26 17:37:20.802  1382  1382 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 17:37:20.802  1382  1382 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-26 17:37:20.802  6682  6737 D BluetoothAdapter: disable()
08-26 17:37:20.802  1015  1217 D SettingsProvider: name = bluetooth_on
,08-26 17:37:20.802  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:20.832  1382  1382 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
,08-26 17:37:20.832  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:20.832  1015  1125 E WifiNative-wlan0: do suspend true
,08-26 17:37:20.832  1015  1124 D WifiP2pService: InactiveState{ what=147461 }
,08-26 17:37:20.832  1015  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-26 17:37:20.832  1015  1124 D WifiP2pService: DefaultState{ what=147461 }
08-26 17:37:20.832  2711  2789 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-26 17:37:20.832  2711  2789 D BluetoothAdapterProperties: Setting state to 13
08-26 17:37:20.832  2711  2789 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 17:37:20.832  2711  2789 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 17:37:20.832  2711  2789 D BluetoothAdapterService: updateAdapterState state is 13
,08-26 17:37:20.832  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:20.832  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 17:37:20.832  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:20.832  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:20.832  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:20.832  2711  2789 D BluetoothAdapterService: Autoconnection is available 
,08-26 17:37:20.832  2711  2789 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 17:37:20.832  2711  2789 D BluetoothAdapterService: terminating service from this receiver
,08-26 17:37:20.842  1015  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 17:37:20.842  2711  2711 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 17:37:20.842  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:20.842  2711  2711 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c50dc58, channel: 19, state: LISTENING
08-26 17:37:20.842  2711  2711 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c50dc58, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@308ba540, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35436696mSocket: android.net.LocalSocket@24f89217 impl:android.net.LocalSocketImpl@f236604 fd:FileDescriptor[74]
08-26 17:37:20.842  2711  2711 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@24f89217 impl:android.net.LocalSocketImpl@f236604 fd:FileDescriptor[74]
,08-26 17:37:20.842  1015  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:20.842  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:20.842  2711  2789 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 17:37:20.842  2711  2789 D BluetoothAdapterProperties: mDiscovering is false
,08-26 17:37:20.842  1015  1484 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 17:37:20.842  2711  2789 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 17:37:20.852  1310  1310 D BluetoothPbap: Proxy object disconnected
08-26 17:37:20.852  1310  1310 D PbapServerProfile: Bluetooth service disconnected
,08-26 17:37:20.852  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:20.852  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:20.852  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:20.852  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:20.852  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:20.852  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:20.852  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:20.852  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:20.852  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:20.852  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:20.852  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:20.852  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:20.852  2711  2792 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 17:37:20.852  2711  2792 D BluetoothAdapterProperties: Scan Mode:20
,08-26 17:37:20.852  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.862  2711  2789 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 17:37:20.862  2711  2789 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-26 17:37:20.862  2711  2789 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 17:37:20.862  2711  4994 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 17:37:20.862  2711  2789 E bt-btif : cmd socket is not created
,08-26 17:37:20.862  2711  2846 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 17:37:20.862  2711  2846 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 17:37:20.862  6682  6799 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@11aa5a41, channel: -1, state: INIT
,08-26 17:37:20.862  6682  6799 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@11aa5a41, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c4e6be6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c283527mSocket: android.net.LocalSocket@107ab3d4 impl:android.net.LocalSocketImpl@1101597d fd:FileDescriptor[105]
08-26 17:37:20.862  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.862  2711  2789 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 17:37:20.862  6682  6799 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@107ab3d4 impl:android.net.LocalSocketImpl@1101597d fd:FileDescriptor[105]
08-26 17:37:20.862  6682  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1304)
,08-26 17:37:20.862  2711  2846 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 17:37:20.862  2711  2846 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:20.862  2711  2846 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 17:37:20.872  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:20.872  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:20.872  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:20.872  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:20.872  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:20.872  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:20.872  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 17:37:20.872  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 17:37:20.872  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:20.872  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:20.872  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 17:37:20.872  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.882  1015  1738 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 17:37:20.882  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-26 17:37:20.882  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:20.882  1015  1738 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 17:37:20.882  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:20.892  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:20.892  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-26 17:37:20.892  1169  1169 D BluetoothTile:  onBluetoothStateChange:
,08-26 17:37:20.892  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 17:37:20.902  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:20.902  1858  1858 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 17:37:20.902  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:20.902  1169  1169 D BluetoothTile:  getBluetoothState : 13
,08-26 17:37:20.902  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:20.902  2711  2711 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b475622, channel: 5, state: LISTENING
08-26 17:37:20.902  2711  2711 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2b475622, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@74f0c79, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29ea38b3mSocket: android.net.LocalSocket@372de70 impl:android.net.LocalSocketImpl@324f05e9 fd:FileDescriptor[76]
08-26 17:37:20.902  2711  2711 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@372de70 impl:android.net.LocalSocketImpl@324f05e9 fd:FileDescriptor[76]
,08-26 17:37:20.902  1310  1310 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:20.902  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-26 17:37:20.902  2711  2711 I BtOppRfcommListener: stopping Accept Thread
08-26 17:37:20.902  2711  2711 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3aa8b26e, channel: 12, state: LISTENING
,08-26 17:37:20.902  2711  2711 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3aa8b26e, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e3b5d3b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f45ad0fmSocket: android.net.LocalSocket@23ff719c impl:android.net.LocalSocketImpl@230917a5 fd:FileDescriptor[79]
08-26 17:37:20.902  2711  2711 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@23ff719c impl:android.net.LocalSocketImpl@230917a5 fd:FileDescriptor[79]
08-26 17:37:20.902  2711  4994 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 17:37:20.902  1015  1450 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 17:37:20.912  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 17:37:20.912  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 17:37:20.912  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:20.912  1015  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:20.912  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 17:37:20.912  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:20.912  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:20.912  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:20.912  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:20.922  1310  1310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 17:37:20.922  1015  1738 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 17:37:20.922  2711  2711 V BluetoothOppManager: cleanUp...
08-26 17:37:20.922  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 17:37:20.922  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:20.922  1015  1738 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:20.922  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 17:37:20.932  1310  1310 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:20.932  1310  1310 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 17:37:20.942  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:20.942  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 17:37:20.942  1015  1738 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 17:37:20.942  1015  1738 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:20.942  1015  1738 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:20.942  1015  1738 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:20.942  1015  1738 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:20.952  6808  6808 E Zygote  : MountEmulatedStorage()
08-26 17:37:20.952  6808  6808 I libpersona: KNOX_SDCARD checking this for 10055
08-26 17:37:20.952  6808  6808 E Zygote  : v2
08-26 17:37:20.952  6808  6808 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:20.952  6808  6808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:20.952  1015  1738 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6808 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-26 17:37:20.962  6808  6808 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:20.962  6808  6808 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:20.972  2018  6758 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-26 17:37:20.972  2018  6758 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 17:37:20.972  2018  6758 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 17:37:20.972  2018  6758 I System.out: (HTTPLog)-Thread-268-352987904: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-26 17:37:20.972  2018  6758 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 17:37:20.982   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 17:37:20.982   277  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 17:37:20.982  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-26 17:37:20.982  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 17:37:20.982   277  1014 D CommandListener: Clearing all IP addresses on wlan0,
08-26 17:37:20.992  2018  4800 V NativeCrypto: Read error: ssl=0xb75168a8: I/O error during system call, Connection timed out,
08-26 17:37:20.992  2018  4800 V NativeCrypto: SSL shutdown failed: ssl=0xb75168a8: I/O error during system call, Broken pipe
08-26 17:37:20.992  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:20.992  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:20.992  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-26 17:37:20.992  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-26 17:37:21.002  6808  6808 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:21.002  1169  1169 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:21.002  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 17:37:21.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:21.002  6808  6808 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:21.002  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-26 17:37:21.002  2018  4800 E GCM     : Wifi connection closed with errorCode 20
08-26 17:37:21.012  2018  6758 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 17:37:21.012  2018  6758 I qtaguid : Tagging socket 48 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2018, getuid(): 10011
,08-26 17:37:21.012  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
08-26 17:37:21.012  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-26 17:37:21.012  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 17:37:21.012  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:21.012  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.012  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.012  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 17:37:21.012  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:21.022  1015  1305 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-26 17:37:21.022  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 17:37:21.022  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler },
08-26 17:37:21.022  1015  1015 D RttService: SCAN_AVAILABLE : 1
,08-26 17:37:21.022  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-26 17:37:21.022  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:21.022  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 17:37:21.042  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:21.042  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-26 17:37:21.042  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 17:37:21.042  1015  1811 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-14ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:21.042  1015  1811 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-14ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:21.042  1015  1811 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 17:37:21.042  1015  1811 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:21.042  1015  1811 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-26 17:37:21.042  1015  1811 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 17:37:21.042  1015  1811 I qtaguid : Tagging socket 364 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
08-26 17:37:21.042  1015  1124 D WifiP2pService: P2pDisablingState
,08-26 17:37:21.052  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 17:37:21.052  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 17:37:21.052  1015  1124 D WifiP2pService: p2p socket connection lost
,08-26 17:37:21.052  1015  1125 E WifiNative-wlan0: do suspend true,
08-26 17:37:21.052  1015  1124 D WifiP2pService: P2pDisabledState
,08-26 17:37:21.052  6808  6808 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 17:37:21.062  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 17:37:21.062  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 17:37:21.062  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 17:37:21.062  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 17:37:21.062  1015  1046 D WifiDisplayController: disconnect
08-26 17:37:21.062  1015  1046 D WifiDisplayController: updateConnection
08-26 17:37:21.062  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 17:37:21.062  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 17:37:21.062  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-26 17:37:21.062  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-26 17:37:21.062  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 17:37:21.062  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 17:37:21.062  2711  2846 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:21.062  2711  2846 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 17:37:21.062  2711  2846 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:21.062  2711  2846 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 17:37:21.062  2711  2846 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 17:37:21.062  2711  2846 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:21.062  1169  1169 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 17:37:21.062  2711  2846 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:21.062  2711  2846 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-26 17:37:21.062  2711  2846 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:21.062  2711  2846 W bt-btif : ag scb idx 1 not allocated
08-26 17:37:21.062  2711  2846 W bt-btif : ag scb idx 2 not allocated
,08-26 17:37:21.062  2711  2846 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 17:37:21.062  1015  1811 I qtaguid : Untagging socket 364
08-26 17:37:21.062  1015  1811 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 17:37:21.062  2711  2933 I bt_userial_mct: exiting userial_read_thread
08-26 17:37:21.062  2711  2933 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-26 17:37:21.062  2711  2792 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 17:37:21.062  2711  2848 I bt_vendor: hw_epilog_process
08-26 17:37:21.062  2711  2792 D bt_userial_mct: userial_close
08-26 17:37:21.062  2711  2792 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 17:37:21.072  1015  1217 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 17:37:21.072  1169  1169 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 17:37:21.092  6808  6808 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 17:37:21.092  6808  6808 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 17:37:21.092  6808  6808 D UserAnalysis: Create SecureDbHelper
,08-26 17:37:21.102  6808  6808 D IntelligenceServiceApplication: onCreate()
,08-26 17:37:21.102  1015  1027 I ActivityManager: Killing 6389:com.samsung.helphub/1000 (adj 15): empty #21
,08-26 17:37:21.112  6808  6808 D IntelligenceServiceApplication: no applications having user consent for prediction,
08-26 17:37:21.112  1015  1469 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 17:37:21.112  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:21.112  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.112  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.112  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:21.122  6832  6832 E Zygote  : MountEmulatedStorage(),
08-26 17:37:21.122  6832  6832 E Zygote  : v2
08-26 17:37:21.122  6832  6832 I libpersona: KNOX_SDCARD checking this for 10105
08-26 17:37:21.122  6832  6832 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:21.122  6832  6832 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:21.122  1015  1469 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6832 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-26 17:37:21.122  1015  3950 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-26 17:37:21.132  6808  6808 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-26 17:37:21.132  6832  6832 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:21.132  6832  6832 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 17:37:21.132  6808  6808 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 17:37:21.142  6832  6832 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:21.152  6832  6832 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:21.152  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-26 17:37:21.152  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-26 17:37:21.172  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 17:37:21.172  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:21.172  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.172  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.172  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 17:37:21.172  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:21.192   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-26 17:37:21.192   277  1010 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-26 17:37:21.192  2018  6758 I qtaguid : Untagging socket 48
08-26 17:37:21.192  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 17:37:21.192  1015  1127 V NetworkStats: updateIfacesLocked()
08-26 17:37:21.192  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:21.192  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-26 17:37:21.192  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:21.192  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 17:37:21.192   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-26 17:37:21.192  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 17:37:21.192  1015  1127 V NetworkStats: performPollLocked() took 5ms
08-26 17:37:21.192  1382  1382 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-26 17:37:21.192  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-26 17:37:21.202  1015  1811 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,08-26 17:37:21.202  1015  1811 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-26 17:37:21.202  1169  1676 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 17:37:21.202  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 17:37:21.202  4294  6746 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 17:37:21.202  1015  1811 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:21.202  1015  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:21.202  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 17:37:21.202  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-26 17:37:21.202  1015  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-26 17:37:21.202  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 17:37:21.202  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 17:37:21.202  1453  1453 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 17:37:21.212  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 17:37:21.212  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:21.212  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:21.212  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.212  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.212  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.212  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:21.212  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:21.212  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:21.212  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
,08-26 17:37:21.222  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:21.222  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 17:37:21.222  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.222  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.222  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.222  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:21.222  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:21.222  1015  1125 D SecContentProvider2: mCursor = null,
08-26 17:37:21.222  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:21.222  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 17:37:21.222  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 17:37:21.222  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:21.222  1310  1310 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:21.222  1169  1169 D HotspotTile: onReceive : 0, 0
,08-26 17:37:21.232  2018  6758 W GLSUser : [AppCertManager] IOException while requesting key: 
08-26 17:37:21.232  2018  6758 W GLSUser : java.net.ConnectException: failed to connect to android.clients.google.com/172.217.16.206 (port 443) after 30000ms: connect failed: ENETUNREACH (Network is unreachable)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:124)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at java.net.Socket.connect(Socket.java:882)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at dja.a(:com.google.android.gms:233)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at dxt.a(:com.google.android.gms:263)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at dxt.a(:com.google.android.gms:4235)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at dxs.a(:com.google.android.gms:47)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at dxm.a(:com.google.android.gms:55)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at dxl.a(:com.google.android.gms:113)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at com.google.android.gms.auth.account.be.legacy.AuthCronChimeraService.b(:com.google.android.gms:3054)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at dir.call(:com.google.android.gms:2045)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at ixu.run(:com.google.android.gms:453)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at jch.run(:com.google.android.gms:17)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at java.lang.Thread.run(Thread.java:818)
08-26 17:37:21.232  2018  6758 W GLSUser : Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at libcore.io.Posix.connect(Native Method)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at libcore.io.BlockGuardOs.connect(,BlockGuardOs.java:111)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
08-26 17:37:21.232  2018  6758 W GLSUser : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
08-26 17:37:21.232  2018  6758 W GLSUser : 	... 30 more
,08-26 17:37:21.232  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 17:37:21.232  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,08-26 17:37:21.232  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 17:37:21.232  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:21.232  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:21.232  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:21.232  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:21.232  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:21.232  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:21.232  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:21.232  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 17:37:21.232  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:21.232  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:21.232  1015  1122 V NetworkStats: updateIfacesLocked()
08-26 17:37:21.232  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:21.232  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-26 17:37:21.232  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 17:37:21.242  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-26 17:37:21.242  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:21.242  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:21.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:21.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:21.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-26 17:37:21.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:21.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:21.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:21.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 17:37:21.242  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:21.242  1015  1122 V NetworkStats: performPollLocked() took 5ms,
08-26 17:37:21.242  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:21.242  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-26 17:37:21.242  6682  6682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 17:37:21.242  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:21.242  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 17:37:21.242  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-26 17:37:21.242  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:21.242  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:21.242  1169  1169 D StatusBar.NetworkController: EthernetConnected: false
08-26 17:37:21.242  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-26 17:37:21.242  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 17:37:21.242  1169  1169 D StatusBar.NetworkController: updateDataNetType()
08-26 17:37:21.242  1169  1169 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 17:37:21.242  1169  1169 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 17:37:21.242   282   698 I WVCdm   : CdmEngine::CloseSession
08-26 17:37:21.242  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 17:37:21.252   282   698 I WVCdm   : L3 Terminate.
08-26 17:37:21.252  2711  2792 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 17:37:21.252  2711  2792 I bt_vendor: bluetooth satus is on
08-26 17:37:21.252  2711  2792 I bt_vendor: bt-vendor : resetting BT status
08-26 17:37:21.252  2711  2792 I bt_vendor: Starting hciattach daemon
08-26 17:37:21.252  2711  2792 I bt_vendor: try to set false
08-26 17:37:21.252  1169  1169 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 17:37:21.252  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-26 17:37:21.252  2711  2792 I bt_vendor: Starting hciattach daemon
08-26 17:37:21.252  2711  2792 I bt_vendor: try to set false
,08-26 17:37:21.252  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 17:37:21.252  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:21.252  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 17:37:21.252  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.252  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.252  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.252  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.252  2711  2792 I bt_vendor: cleanup
,08-26 17:37:21.252  2711  2846 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 17:37:21.252  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:21.252  2711  2792 I GKI_LINUX: GKI_exit_task 0 done
08-26 17:37:21.252  2711  2792 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 17:37:21.262  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:21.262  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:21.262  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:21.262  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-26 17:37:21.262  2711  2789 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 17:37:21.262  2711  2789 D BtConfig.SecureMode: isSecureModeOn:false
08-26 17:37:21.262  2711  2789 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 17:37:21.262  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 17:37:21.262  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 17:37:21.262  2711  2789 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 17:37:21.262  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:21.262  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:21.262  1015  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:21.262  1015  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 17:37:21.262  1015  1469 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.262  1015  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:21.262  1015  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:21.262  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 17:37:21.262  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 17:37:21.262  2711  2789 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 17:37:21.262  2711  2711 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 17:37:21.272  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:21.272  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 17:37:21.272  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.272  2711  2711 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 17:37:21.272  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:21.272  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 17:37:21.272  2711  2711 D BtGatt.GattService: stop()
08-26 17:37:21.272  2711  2711 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 17:37:21.272  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 17:37:21.272  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 17:37:21.272  2711  2789 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 17:37:21.272  1015  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:21.282  2711  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:21.282  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 17:37:21.282  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.282  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:21.282  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:21.282  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 17:37:21.282  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 17:37:21.282  2711  2789 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 17:37:21.282  2711  2711 D HeadsetService: Received stop request...Stopping profile...
,08-26 17:37:21.282  2711  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:21.282  1015  1738 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:21.282  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 17:37:21.282  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.282  1015  1738 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:21.282  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:21.292  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 17:37:21.292  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 17:37:21.292  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 17:37:21.292  2711  2789 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 17:37:21.292  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:21.292  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 17:37:21.292  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.292  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:21.292  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:21.292  1310  1310 D HeadsetProfile: Bluetooth service disconnected
08-26 17:37:21.292  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 17:37:21.292  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 17:37:21.302  2711  2789 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 17:37:21.302  1015  1450 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:21.302  1015  1450 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 17:37:21.302  1015  1450 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.302  1015  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:21.302  1015  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:21.302  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 17:37:21.302  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:21.302  2711  2789 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:21.302  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:21.302  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 17:37:21.302  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.302  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:21.302  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 17:37:21.302  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 17:37:21.302  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 17:37:21.302  2711  2789 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 17:37:21.302  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:21.302  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 17:37:21.312  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.312  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:21.312  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:21.312  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:21.312  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 17:37:21.312  2711  2789 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:21.312  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:21.312  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 17:37:21.312  2711  2789 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:21.312  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 17:37:21.312  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 17:37:21.312  1382  1382 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 17:37:21.312  2711  2789 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 17:37:21.312  2711  2789 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 17:37:21.312  2711  2789 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 17:37:21.312  2711  2789 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-26 17:37:21.312  2711  2789 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 17:37:21.312  2711  2711 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-26 17:37:21.322  2711  2711 D A2dpService: Received stop request...Stopping profile...
,08-26 17:37:21.322  2711  2811 D A2dpStateMachine: Exit Disconnected: -1
,08-26 17:37:21.322   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 17:37:21.322   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 17:37:21.322  6832  6854 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 17:37:21.332  2711  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:21.332  1382  1382 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 17:37:21.332  2711  2711 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 17:37:21.332  2711  2711 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 17:37:21.332  2711  2711 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 17:37:21.332  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 17:37:21.332  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 17:37:21.332  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
,08-26 17:37:21.342  1310  1310 D BluetoothA2dp: Proxy object disconnected
08-26 17:37:21.342  1310  1310 D A2dpProfile: Bluetooth service disconnected
,08-26 17:37:21.342  2711  2711 D HidService: Received stop request...Stopping profile...
08-26 17:37:21.342  2711  2711 D HidService: Stopping Bluetooth HidService
08-26 17:37:21.342  2711  2711 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 17:37:21.342  2711  2711 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 17:37:21.342  2711  2711 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 17:37:21.342  2711  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:21.342  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-26 17:37:21.342  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 17:37:21.342  2018  2165 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 17:37:21.352  1310  1310 D BluetoothInputDevice: Proxy object disconnected
08-26 17:37:21.352  1310  1310 D HidProfile: Bluetooth service disconnected
08-26 17:37:21.352   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 17:37:21.352   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 17:37:21.352  2018  2165 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-26 17:37:21.352  6832  6854 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
08-26 17:37:21.352  2711  2711 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 17:37:21.352  2711  2711 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 17:37:21.352  2018  2165 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 17:37:19.841+0200, stopTime=2016-08-26 17:37:21.360+0200, duration=1519ms
08-26 17:37:21.352  2711  2711 D HealthService: Received stop request...Stopping profile...
08-26 17:37:21.352  2711  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:21.362  1382  1382 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 17:37:21.362  1382  1382 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 17:37:21.362  1382  1382 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 17:37:21.362  1382  1382 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 17:37:21.362  1382  1382 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 17:37:21.362  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:21.362  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:21.362  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:21.362  1015  1128 D Tethering: InitialState.processMessage what=4
,08-26 17:37:21.372  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:21.372  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:21.372  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:21.372  2711  2711 D PanService: Received stop request...Stopping profile...
08-26 17:37:21.372  2711  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:21.372  1015  1128 E Tethering: No numeric data
,08-26 17:37:21.382  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 17:37:21.382  1015  1128 D Tethering: clearTetheredNotification()
,08-26 17:37:21.382  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:21.382  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:21.382  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:21.382  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 17:37:21.382  1310  1310 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 17:37:21.382  1310  1310 D PanProfile: Bluetooth service disconnected
,08-26 17:37:21.382  2711  2711 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 17:37:21.392  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-26 17:37:21.392  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:21.392  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:21.392  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 17:37:21.392  1015  1122 V NetworkStats: performPollLocked() took 4ms
08-26 17:37:21.392  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:21.392  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 17:37:21.392  1169  1169 D HotspotTile: updateTetherState():false, false
,08-26 17:37:21.392  2018  6860 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 17:37:21.402  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:21.402  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:21.402   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 17:37:21.402   277  1010 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 17:37:21.402  2711  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:21.412  2711  2711 D SapService: Received stop request...Stopping profile...
08-26 17:37:21.412  2711  2711 D SapService: Stopping Bluetooth SapService
08-26 17:37:21.412  2711  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:21.412  2711  2711 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-26 17:37:21.412  2711  2711 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 17:37:21.412  2711  2711 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 17:37:21.412  2711  2711 D BluetoothA2dp: Proxy object disconnected
,08-26 17:37:21.412  2711  2711 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 17:37:21.412  2711  2812 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 17:37:21.412  2711  2711 I GKI_LINUX: GKI_exit_task 2 done
08-26 17:37:21.412  2711  2711 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 17:37:21.412  2711  2711 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 17:37:21.412  2711  2711 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:21.412  2711  2711 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:21.422  2711  2711 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 17:37:21.422  2711  2711 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:21.422   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb703f7c8
08-26 17:37:21.422   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-26 17:37:21.422  2711  2711 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:21.422   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 17:37:21.422   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1224477384)
08-26 17:37:21.422  2711  2711 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 17:37:21.422  2711  2711 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 17:37:21.422  2711  2711 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 17:37:21.422  2711  2711 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:21.422  2711  2711 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:21.422  2711  2711 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 17:37:21.422  2711  2711 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 17:37:21.432  1310  1310 D BluetoothMap: Proxy object disconnected
08-26 17:37:21.432  1310  1310 D MapProfile: Bluetooth service disconnected
08-26 17:37:21.432  2711  2711 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 17:37:21.432  2711  2711 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 17:37:21.432  2711  2711 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 17:37:21.432  2711  2711 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 17:37:21.432  2711  2711 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 17:37:21.432  2711  2711 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-26 17:37:21.432  1310  1310 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 17:37:21.432  1310  1310 D SapProfile: Bluetooth service disconnected
08-26 17:37:21.432  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.442  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 17:37:21.442  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.442  2711  2789 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 17:37:21.442  2711  2789 D BluetoothAdapterProperties: Setting state to 10
08-26 17:37:21.442  2711  2789 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 17:37:21.442  2711  2789 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 17:37:21.442  2711  2789 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 17:37:21.452  2711  2789 D BluetoothAdapterService: Autoconnection is available 
08-26 17:37:21.452  2711  2789 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 17:37:21.452  2711  2789 I BluetoothAdapterState: Entering OffState
08-26 17:37:21.452  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 17:37:21.452  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.452  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 17:37:21.452  1441  1452 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:21.452  1441  1452 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 17:37:21.452  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.452  1310  1322 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 17:37:21.452  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 17:37:21.452  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 17:37:21.452  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.462  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 17:37:21.462  1310  1333 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:21.462  1310  1333 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:21.462  2711  2972 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 17:37:21.462  1310  6858 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 17:37:21.462  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.462  1310  1322 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 17:37:21.462  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 17:37:21.462  1310  1333 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 17:37:21.462  1310  6858 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 17:37:21.462  1310  6858 D Bluetoothsap: Unbinding service...
,08-26 17:37:21.462  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 17:37:21.472  6682  6690 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:21.472  6682  6690 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 17:37:21.472  6682  6690 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 17:37:21.472  6682  6690 D BluetoothLeAdvertiser: Exit stop advertising
08-26 17:37:21.472  6682  6690 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 17:37:21.472  6682  6690 D BluetoothLeScanner: Exiting stopAllScan
,08-26 17:37:21.472  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 17:37:21.472  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:21.472  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:21.472  1453  1655 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:21.472  1453  1655 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:21.472  1169  2785 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:21.472  1169  2785 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:21.472  1425  1443 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:21.472  1425  1443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 17:37:21.472  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.472  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 17:37:21.472  2711  2721 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:21.472  2711  2721 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 17:37:21.472  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 17:37:21.472  2018  6005 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:21.472  2018  6005 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:21.482  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 17:37:21.482  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.482  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-26 17:37:21.482   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-26 17:37:21.482   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 17:37:21.482   272   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1224477384) wakelock released: 1, error no: 0
08-26 17:37:21.482   272   338 I rmt_storage: 
,08-26 17:37:21.482   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb703f7c8
08-26 17:37:21.482  2018  2018 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
08-26 17:37:21.482  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 17:37:21.482  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.492  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 17:37:21.492  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 17:37:21.492  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 17:37:21.492  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 17:37:21.492  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 17:37:21.492  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 17:37:21.492  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.492  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 17:37:21.492  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 17:37:21.502  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 17:37:21.502  1382  1382 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 17:37:21.502  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:21.502  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-26 17:37:21.502  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 17:37:21.512  1169  1169 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
,08-26 17:37:21.512  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 17:37:21.512  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:21.512  1169  1169 D BluetoothTile:  getBluetoothState : 10
08-26 17:37:21.512  2711  2792 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 17:37:21.512  2711  2711 I GKI_LINUX: GKI_exit_task 1 done,
08-26 17:37:21.512  2711  2711 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 17:37:21.512  1169  1751 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:21.512  2711  2711 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 17:37:21.512  1169  1751 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
,08-26 17:37:21.512  1169  1169 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:21.512  1169  1169 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:21.512  1015  3282 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 17:37:21.512  1015  1738 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 17:37:21.512  1310  1310 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:21.522  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:21.522  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 17:37:21.522  2018  2153 D BluetoothAdapter: 496223201: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:21.522  1858  1858 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 17:37:21.522  2018  2153 D BluetoothAdapter: 496223201: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:21.522  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 17:37:21.522  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.522  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:21.522  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 17:37:21.522  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:21.522  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:21.522  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:21.522  2711  2711 I art     : System.exit called, status: 0
08-26 17:37:21.522  2711  2711 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 17:37:21.542  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-26 17:37:21.542  1382  1382 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
08-26 17:37:21.552  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:21.552  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:21.552  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:21.562  2018  2165 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 17:37:21.572  1015  1469 I ActivityManager: Process com.android.bluetooth (pid 2711)(adj 0) has died(31,712)
,08-26 17:37:21.602  6832  6832 D StrictMode: StrictMode policy violation; ~duration=270 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:21.602  6832  6832 D StrictMode: StrictMode policy violation; ~duration=269 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:21.602  6832  6832 D StrictMode: StrictMode policy violation; ~duration=266 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:21.602  6832  6832 D StrictMode: StrictMode policy violation; ~duration=265 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:21.602  6832  6832 D StrictMode: StrictMode policy violation; ~duration=262 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:21.602  6832  6832 D StrictMode: StrictMode policy violation; ~duration=227 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:21.602  6832  6832 D StrictMode: StrictMode policy violation; ~duration=226 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:21.602  1015  3282 I ActivityManager: Killing 6425:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-26 17:37:21.602  6832  6832 D StrictMode: StrictMode policy violation; ~duration=226 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:21.602  6832  6832 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:21.612  2018  2018 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:21.612  2018  2018 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-26 17:37:21.622  1015  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 17:37:21.622  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 17:37:21.622  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.622  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:21.622  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 17:37:21.622  1619  1619 I Hs20UtilService: Starting #8
08-26 17:37:21.622  1619  1659 I Hs20UtilService: Message received 5007
08-26 17:37:21.622  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 17:37:21.622  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 17:37:21.622  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 17:37:21.622  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 17:37:21.622  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 17:37:21.622  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 17:37:21.632  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 17:37:21.632  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 17:37:21.632  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 17:37:21.642  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 17:37:21.642  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 17:37:21.642  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 17:37:21.642  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 17:37:21.642  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 17:37:21.642  1015  1738 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-26 17:37:21.642  1015  1738 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.642  1015  1738 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.642  1015  1738 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.642  1015  1738 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.662  6894  6894 E Zygote  : MountEmulatedStorage()
08-26 17:37:21.662  1015  1738 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6894 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 17:37:21.662  6894  6894 E Zygote  : v2
08-26 17:37:21.662  6894  6894 I libpersona: KNOX_SDCARD checking this for 10064
08-26 17:37:21.662  6894  6894 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:21.662  6894  6894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:21.662  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-26 17:37:21.662  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-26 17:37:21.662  6894  6894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:21.662  6894  6894 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 17:37:21.662  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:21.672  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 17:37:21.672  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.672  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.672  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.672  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:21.672  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:21.672  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-26 17:37:21.672  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 17:37:21.672  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:21.672  1169  1169 D HotspotTile: onReceive : 1, 0
08-26 17:37:21.672  2018  2153 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 17:37:21.672  1310  1310 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:21.682  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:21.682  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:21.682  6832  6854 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 17:37:21.692  6894  6894 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:21.692  6894  6894 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:21.702  6894  6894 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 17:37:21.722  6894  6894 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 17:37:21.722  6894  6894 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 17:37:21.732  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:21.732  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-26 17:37:21.742  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:21.752  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:21.752  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:21.752  6894  6894 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 17:37:21.872  1015  1469 I art     : Explicit concurrent mark sweep GC freed 53268(2MB) AllocSpace objects, 8(176KB) LOS objects, 33% free, 24MB/36MB, paused 2.500ms total 163.734ms
,08-26 17:37:21.872  1015  1305 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:21.872  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:21.872  1015  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:21.872  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 17:37:21.872  1015  3950 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 17:37:21.882  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 17:37:21.882  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 17:37:21.882  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.882  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:21.892  6911  6911 E Zygote  : MountEmulatedStorage()
08-26 17:37:21.892  6911  6911 I libpersona: KNOX_SDCARD checking this for 10065
08-26 17:37:21.892  6911  6911 E Zygote  : v2
08-26 17:37:21.892  6911  6911 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:21.892  6911  6911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:21.892  1015  3950 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6911 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 17:37:21.892  6911  6911 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:21.902  6911  6911 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-26 17:37:21.902  1015  3950 I ActivityManager: Killing 6325:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-26 17:37:21.922  6911  6911 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:21.922  6911  6911 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:21.942  1015  2806 D SSRM:n  : SIOP:: AP = 390
,08-26 17:37:21.952  6911  6911 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 17:37:21.952  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:21.952  1015  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:21.952  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-26 17:37:21.952  1015  1305 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-26 17:37:21.962  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.962  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.962  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:21.962  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:21.982  6927  6927 E Zygote  : MountEmulatedStorage()
08-26 17:37:21.982  6927  6927 I libpersona: KNOX_SDCARD checking this for 10102
08-26 17:37:21.982  6927  6927 E Zygote  : v2
08-26 17:37:21.982  6927  6927 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:21.982  6927  6927 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:21.982  1015  1305 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6927 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-26 17:37:21.982  1015  1305 I ActivityManager: Killing 5898:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-26 17:37:21.982  6927  6927 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:21.982  6927  6927 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 17:37:22.002  6927  6927 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:22.002  6927  6927 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:22.012  6927  6927 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 17:37:22.212  6927  6947 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 17:37:22.212  6927  6947 I Babel_SMS: MmsConfig.loadMmsSettings
,08-26 17:37:22.212  6927  6947 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-26 17:37:22.212  6927  6947 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 17:37:22.242  6927  6947 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-26 17:37:22.242  6927  6947 I Babel_SMS: MmsConfig.loadFromResources
,08-26 17:37:22.252  6927  6947 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 17:37:22.252  6927  6947 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 17:37:22.252  1015  1043 D Tethering: interfaceRemoved wlan0
,08-26 17:37:22.262  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 17:37:22.272  1015  1469 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-26 17:37:22.272  1015  1469 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 17:37:22.272  1015  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:22.272  1015  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:22.272  1015  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 17:37:22.292  6927  6927 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:22.292  6927  6927 I Babel_Crash: startup - clean
,08-26 17:37:22.322  1015  1469 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 17:37:22.322  1015  1469 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:22.322  1015  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:22.322  1015  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.322  1015  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:22.332  1619  1619 I Hs20UtilService: Starting #9,
08-26 17:37:22.332  1619  1659 I Hs20UtilService: Message received 5007
08-26 17:37:22.332  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 17:37:22.332  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
,08-26 17:37:22.332  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 17:37:22.332  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 17:37:22.332  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 17:37:22.332  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 17:37:22.332  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 17:37:22.342  6927  6927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 17:37:22.342  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 17:37:22.342  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:22.342  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.342  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.342  6927  6927 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 17:37:22.342  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:22.352  6927  6927 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 17:37:22.352  1619  1619 I Hs20UtilService: Starting #10
,08-26 17:37:22.352  1619  1659 I Hs20UtilService: Message received 5011
,08-26 17:37:22.352  6927  6927 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-26 17:37:22.352  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 17:37:22.352  6927  6927 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-26 17:37:22.352  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 17:37:22.352  6524  6524 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 17:37:22.362  6927  6927 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 17:37:22.362  6524  6524 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 17:37:22.362  6927  6927 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 17:37:22.362  1015  1043 D Tethering: interfaceRemoved p2p0
,08-26 17:37:22.362  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 17:37:22.372  1015  1450 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:22.372  1015  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:22.372  1015  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.372  6927  6927 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 17:37:22.372  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.372  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.372  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.372  6927  6927 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 17:37:22.382  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.382  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.382  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.382   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 17:37:22.382  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:22.382  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:22.382  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.392  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.392  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.392  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.392  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:22.392  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:22.392  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.392  6927  6927 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 17:37:22.392  6927  6927 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 17:37:22.402  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.402  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.402  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.402  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.402  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.402  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.402  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.402  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.402  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.402  6927  6927 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-26 17:37:22.412  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:22.412  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.412  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.412  6927  6927 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 17:37:22.412  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.412  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.412  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.412  6927  6927 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 17:37:22.412  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.412  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.412  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.412  6927  6927 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 17:37:22.422  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.422  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.422  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.422  6927  6927 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 17:37:22.422  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.422  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.422  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.422  6927  6927 W VideoCapabilities: Unsupported mime video/mp43
,08-26 17:37:22.422  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.422  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.422  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 17:37:22.432  6927  6927 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 17:37:22.432  1310  1310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 17:37:22.432  1015  1738 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 17:37:22.432  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 17:37:22.432  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:22.432  1015  1738 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.432  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 17:37:22.432  6927  6927 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 17:37:22.442  1310  1310 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:22.442  1310  1310 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 17:37:22.442  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:22.442  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 17:37:22.452  1015  3950 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 17:37:22.452  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.452  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.452  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.452  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.462  6927  6927 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es,
,08-26 17:37:22.462  6951  6951 E Zygote  : MountEmulatedStorage()
08-26 17:37:22.462  6951  6951 I libpersona: KNOX_SDCARD checking this for 1002
08-26 17:37:22.462  6951  6951 E Zygote  : v2
08-26 17:37:22.462  6951  6951 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:22.462  6951  6951 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:22.472  6951  6951 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:22.472  6951  6951 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:22.472  1015  3950 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6951 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-26 17:37:22.492  6951  6951 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:22.492  6951  6951 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:22.492  6927  6927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 17:37:22.492  6927  6927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 17:37:22.492  6927  6927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 17:37:22.502  6927  6927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-26 17:37:22.502  1015  1469 I ActivityManager: Killing 6458:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-26 17:37:22.502  6927  6927 I vclib   : onServiceConnected
,08-26 17:37:22.512  6951  6951 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 17:37:22.512  6951  6951 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 17:37:22.532  6951  6951 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding GattService
,08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding HeadsetService
,08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding A2dpService
08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding HidService
08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding HealthService
,08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding PanService
08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding SapService
,08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding SapClientService
,08-26 17:37:22.562  6951  6951 D BtSettings.ProfileConfig: Adding HidDevService
08-26 17:37:22.572  6951  6951 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 17:37:22.572  1015  1484 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 17:37:22.572  1015  1484 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.572  1015  1484 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.572  1015  1484 D SettingsProvider: selectionArgs: false
,08-26 17:37:22.572  1015  1484 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.572  1015  1484 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 17:37:22.572  1015  1484 D SettingsProvider: ret = -1
,08-26 17:37:22.572  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 17:37:22.572  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.572  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.572  1015  1133 D SettingsProvider: selectionArgs: false
08-26 17:37:22.572  1015  1133 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.572  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.572  1015  1133 D SettingsProvider: ret = -1
,08-26 17:37:22.572  1015  3282 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 17:37:22.572  1015  3282 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.572  1015  3282 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.572  1015  3282 D SettingsProvider: selectionArgs: false
,08-26 17:37:22.572  1015  3282 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.572  1015  3282 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.572  1015  3282 D SettingsProvider: ret = -1
08-26 17:37:22.572  1015  1469 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 17:37:22.572  1015  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.572  1015  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.572  1015  1469 D SettingsProvider: selectionArgs: false
08-26 17:37:22.572  1015  1469 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.572  1015  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.572  1015  1469 D SettingsProvider: ret = -1
08-26 17:37:22.572  1015  1450 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 17:37:22.572  1015  1450 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.572  1015  1450 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.572  1015  1450 D SettingsProvider: selectionArgs: false
08-26 17:37:22.572  1015  1450 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.572  1015  1450 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.572  1015  1450 D SettingsProvider: ret = -1
,08-26 17:37:22.582  1015  3950 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 17:37:22.582  1015  3950 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 17:37:22.582  1015  3950 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.582  1015  3950 D SettingsProvider: selectionArgs: false
08-26 17:37:22.582  1015  3950 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.582  1015  3950 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.582  1015  3950 D SettingsProvider: ret = -1
,08-26 17:37:22.582  1015  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 17:37:22.582  1015  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.582  1015  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.582  1015  1217 D SettingsProvider: selectionArgs: false
08-26 17:37:22.582  1015  1217 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.582  1015  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.582  1015  1217 D SettingsProvider: ret = -1
,08-26 17:37:22.582  1015  1738 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 17:37:22.582  1015  1738 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.582  1015  1738 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.582  1015  1738 D SettingsProvider: selectionArgs: false
,08-26 17:37:22.582  1015  1738 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.582  1015  1738 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.582  1015  1738 D SettingsProvider: ret = -1
,08-26 17:37:22.582  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:22.582  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.582  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 17:37:22.582  1015  1476 D SettingsProvider: selectionArgs: false
08-26 17:37:22.582  1015  1476 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.582  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.582  1015  1476 D SettingsProvider: ret = -1
08-26 17:37:22.582  1015  1305 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-26 17:37:22.582  1015  1305 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.582  1015  1305 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.582  1015  1305 D SettingsProvider: selectionArgs: false
08-26 17:37:22.582  1015  1305 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.582  1015  1305 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.582  1015  1305 D SettingsProvider: ret = -1
,08-26 17:37:22.582  1015  1454 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 17:37:22.582  1015  1454 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.582  1015  1454 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.582  1015  1454 D SettingsProvider: selectionArgs: false
08-26 17:37:22.582  1015  1454 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.582  1015  1454 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.582  1015  1454 D SettingsProvider: ret = -1,
08-26 17:37:22.582  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 17:37:22.582  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:22.582  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:22.582  1015  1028 D SettingsProvider: selectionArgs: false
,08-26 17:37:22.582  1015  1028 D SettingsProvider: selectionArgs: 1002
08-26 17:37:22.582  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:22.582  1015  1028 D SettingsProvider: ret = -1
,08-26 17:37:22.592  1015  1133 I ActivityManager: Killing 6509:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 17:37:22.592  2018  2018 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:22.592  1015  3282 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:22.592  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 17:37:22.602  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:22.602  1015  3282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:22.602  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:22.612  2018  6967 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 17:37:22.612  2018  2018 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 17:37:22.612  1015  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:22.612  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:22.612  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:22.612  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:22.622  1015  1305 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 17:37:22.622  1015  1305 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:22.622  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.622  1015  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:22.622  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:22.622  1619  1619 I Hs20UtilService: Starting #11
,08-26 17:37:22.622  1619  1659 I Hs20UtilService: Message received 5011
,08-26 17:37:22.632  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 17:37:22.632  1015  3282 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:22.632  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 17:37:22.632  6524  6524 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 17:37:22.632  6524  6524 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 17:37:22.632  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:22.632  1015  3282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:22.632  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:22.642  1015  1454 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 17:37:22.642  1015  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.652  1015  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.652  1015  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.652  1015  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.652  2018  6967 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 17:37:22.662  6968  6968 E Zygote  : MountEmulatedStorage(),
08-26 17:37:22.662  6968  6968 E Zygote  : v2
08-26 17:37:22.662  6968  6968 I libpersona: KNOX_SDCARD checking this for 1000
,08-26 17:37:22.662  6968  6968 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:22.662  6968  6968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 17:37:22.662  6968  6968 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 17:37:22.662  6968  6968 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-26 17:37:22.662  1015  1454 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6968 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 17:37:22.692  6968  6968 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:22.692  6968  6968 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:22.712  6968  6968 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-26 17:37:22.712  6968  6968 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-26 17:37:22.712  6968  6968 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 17:37:22.722  6968  6968 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-26 17:37:22.722  6968  6968 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-26 17:37:22.722  6968  6968 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-26 17:37:22.722  6968  6968 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:22.732  1015  1484 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-26 17:37:22.732  6968  6983 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-26 17:37:22.732  1015  1484 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-26 17:37:22.742  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 17:37:22.742  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.742  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.742  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.742  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.742  1759  1759 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 17:37:22.752  6986  6986 E Zygote  : MountEmulatedStorage()
08-26 17:37:22.752  6986  6986 E Zygote  : v2
08-26 17:37:22.752  6986  6986 I libpersona: KNOX_SDCARD checking this for 10121
08-26 17:37:22.752  6986  6986 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:22.752  1015  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6986 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 17:37:22.752  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 17:37:22.752  6986  6986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:22.762  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.762  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.762  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.762  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.762  6986  6986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:22.762  6986  6986 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 17:37:22.772  6997  6997 E Zygote  : MountEmulatedStorage(),
,08-26 17:37:22.772  6997  6997 E Zygote  : v2
08-26 17:37:22.772  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6997 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 17:37:22.772  6997  6997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:22.772  6997  6997 I libpersona: KNOX_SDCARD checking this for 10001
08-26 17:37:22.772  6997  6997 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:22.782  1015  1476 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 17:37:22.782  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.782  6997  6997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:22.782  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 17:37:22.782  6997  6997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:22.782  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.782  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.792  6986  6986 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:22.792  6986  6986 D ActivityThread: Added TimaKeyStore provider,
,08-26 17:37:22.792  6997  6997 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:22.802  6997  6997 D ActivityThread: Added TimaKeyStore provider,
,08-26 17:37:22.802  7016  7016 E Zygote  : MountEmulatedStorage()
08-26 17:37:22.802  7016  7016 E Zygote  : v2
08-26 17:37:22.802  7016  7016 I libpersona: KNOX_SDCARD checking this for 10031
08-26 17:37:22.802  7016  7016 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:22.802  7016  7016 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:22.802  7016  7016 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 17:37:22.802  1015  1476 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7016 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-26 17:37:22.812  7016  7016 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:22.812  2462  2663 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-26 17:37:22.822  1759  1759 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1,
08-26 17:37:22.822  1759  1759 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-26 17:37:22.822  1759  1759 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-26 17:37:22.822  1759  1759 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 17:37:22.832  1759  1759 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 17:37:22.832  7016  7016 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:22.832  1759  1759 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
08-26 17:37:22.832  7016  7016 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:22.832  6986  6986 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 17:37:22.832  6986  6986 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 17:37:22.832  6986  6986 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 17:37:22.832  1015  3282 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 17:37:22.832   311   311 I art     : Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 30.985ms
,08-26 17:37:22.842  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.842  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.842  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.842  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.852  6986  6986 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:22.852   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.811ms
,08-26 17:37:22.872   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.232ms
,08-26 17:37:22.882  7033  7033 E Zygote  : MountEmulatedStorage(),
08-26 17:37:22.882  7033  7033 E Zygote  : v2
08-26 17:37:22.882  7033  7033 I libpersona: KNOX_SDCARD checking this for 10077
08-26 17:37:22.882  7033  7033 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:22.882  7033  7033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:22.882  1015  3282 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7033 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 17:37:22.892  6986  6986 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 17:37:22.892  7033  7033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:22.892  7033  7033 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
08-26 17:37:22.892  6986  6986 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 17:37:22.902  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-26 17:37:22.902  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.902  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.902  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.902  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.912  7048  7048 E Zygote  : MountEmulatedStorage()
08-26 17:37:22.912  7048  7048 E Zygote  : v2
08-26 17:37:22.912  7048  7048 I libpersona: KNOX_SDCARD checking this for 10141
08-26 17:37:22.912  7048  7048 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:22.922  7048  7048 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 17:37:22.922  7033  7033 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:22.922  7048  7048 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:22.922  7033  7033 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:22.922  7048  7048 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 17:37:22.922  1015  1027 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7048 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-26 17:37:22.922  1015  1027 I ActivityManager: Killing 6488:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 17:37:22.932  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 17:37:22.932  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.932  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.932  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.932  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.942  7016  7016 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 17:37:22.942  7048  7048 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 17:37:22.952  7048  7048 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:22.952  7063  7063 E Zygote  : MountEmulatedStorage()
08-26 17:37:22.952  7063  7063 E Zygote  : v2,
08-26 17:37:22.952  7063  7063 I libpersona: KNOX_SDCARD checking this for 1000
08-26 17:37:22.952  7063  7063 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:22.952  7063  7063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 17:37:22.952  7063  7063 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 17:37:22.952  1015  1028 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7063 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 17:37:22.952  1015  1028 I ActivityManager: Killing 5754:com.android.vending/u0a26 (adj 15): empty #21
08-26 17:37:22.952  7063  7063 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:22.962  1015  1028 I ActivityManager: Killing 6558:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 17:37:22.972  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 17:37:22.982  1015  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 17:37:22.982  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.982  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.982  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:22.982  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:22.982  7048  7048 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-26 17:37:22.982  7048  7048 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 17:37:22.982  7048  7048 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 17:37:22.982  7048  7048 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 17:37:22.992  3390  7076 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-26 17:37:22.992  3390  7076 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-26 17:37:22.992  7080  7080 E Zygote  : MountEmulatedStorage()
08-26 17:37:22.992  7080  7080 I libpersona: KNOX_SDCARD checking this for 10032
08-26 17:37:22.992  7080  7080 E Zygote  : v2
08-26 17:37:22.992  7080  7080 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:22.992  7080  7080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:22.992  1015  1484 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7080 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 17:37:23.002  7080  7080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 17:37:23.002  7080  7080 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 17:37:23.002  3390  7076 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-26 17:37:23.012  7063  7063 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:23.012  7063  7063 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:23.022  3390  7076 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-26 17:37:23.022  3390  7076 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 17:37:23.042  7080  7080 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:23.042  7080  7080 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:23.052  1015  3282 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 17:37:23.062  1015  3950 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 17:37:23.072  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 17:37:23.072  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 17:37:23.072  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:23.072  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:23.072  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 17:37:23.072  1015  1133 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 17:37:23.082  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:23.082  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.082  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.082  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:23.092  7100  7100 E Zygote  : MountEmulatedStorage(),
08-26 17:37:23.092  1015  1133 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7100 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 17:37:23.092  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:23.092  1015  1217 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 17:37:23.092  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:23.092  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-26 17:37:23.092  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-26 17:37:23.092  7100  7100 I libpersona: KNOX_SDCARD checking this for 10110
08-26 17:37:23.092  7100  7100 E Zygote  : v2
08-26 17:37:23.092  7100  7100 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:23.092  7100  7100 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:23.102  7100  7100 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:23.102  7100  7100 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 17:37:23.102  1015  1450 D RCPManagerService: exchangeData() failure , invalid userId
08-26 17:37:23.102  6927  7097 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 17:37:23.112  7063  7063 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 17:37:23.112  1015  1217 I ActivityManager: Killing 6573:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-26 17:37:23.122  7100  7100 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:23.122  7100  7100 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:23.132  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 17:37:23.142  7080  7117 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 17:37:23.142  7080  7117 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 17:37:23.142  7080  7117 D SPPClientService: PushLog.txt file is not deleted.
08-26 17:37:23.142  7080  7117 D SPPClientService: PushLog.txt file is not deleted.
08-26 17:37:23.142  7080  7117 D SPPClientService: ============PushLog. stop!
,08-26 17:37:23.152  7080  7080 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 17:37:23.152  1015  1469 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 17:37:23.152  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.152  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.152  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.152  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:23.162  1015  1469 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7119 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-26 17:37:23.172  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:23.172  1015  1484 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 17:37:23.172  1015  1469 I ActivityManager: Killing 6589:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-26 17:37:23.172  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-26 17:37:23.172  1015  1484 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-26 17:37:23.172  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-26 17:37:23.172  7119  7119 E Zygote  : MountEmulatedStorage(),
,08-26 17:37:23.182  7119  7119 E Zygote  : v2
08-26 17:37:23.182  7119  7119 I libpersona: KNOX_SDCARD checking this for 10036
08-26 17:37:23.182  7119  7119 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:23.182  7119  7119 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:23.182  7119  7119 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:23.182  7119  7119 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-26 17:37:23.202  7119  7119 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:23.202  7119  7119 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:23.212  1015  1738 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 17:37:23.222  7080  7126 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-26 17:37:23.252  1015  1484 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 17:37:23.252  7119  7119 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1b1b82fe
,08-26 17:37:23.252  1015  1469 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-26 17:37:23.252  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.252  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.252  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.252  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:23.262  1015  3950 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 17:37:23.272  7119  7119 I SA      : [SSP] onCreated
,08-26 17:37:23.282  7139  7139 E Zygote  : MountEmulatedStorage(),
08-26 17:37:23.282  7139  7139 E Zygote  : v2
08-26 17:37:23.282  7139  7139 I libpersona: KNOX_SDCARD checking this for 10068,
08-26 17:37:23.282  7139  7139 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:23.282  1015  1469 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7139 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,08-26 17:37:23.282  7063  7063 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
08-26 17:37:23.292  7139  7139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:23.292  7139  7139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:23.292  7139  7139 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 17:37:23.292  7063  7063 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 17:37:23.302  1015  1484 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 17:37:23.302  7119  7119 I SA      : [TPM] There is no property file
,08-26 17:37:23.312  7119  7119 I SA      : [SCU] isHaveSA() - false
,08-26 17:37:23.312  7119  7119 I SA      : [TPM] getModelProperty : null
08-26 17:37:23.312  7119  7119 I SA      : [TPM] getCSCProperty : null
,08-26 17:37:23.312  7119  7119 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 17:37:23.312  7119  7119 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 17:37:23.312  7119  7119 I SA      : [DM] TFT FEATURE: false
,08-26 17:37:23.312  7063  7063 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:23.312  7063  7063 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 17:37:23.312  7063  7063 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 17:37:23.312  7063  7063 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-26 17:37:23.312  1015  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 17:37:23.322  7119  7119 I SA      : [DM] init START
,08-26 17:37:23.322  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.322  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.322  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.322  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:23.322  7139  7139 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:23.322  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 17:37:23.332  7139  7139 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:23.332  7159  7159 E Zygote  : MountEmulatedStorage(),
08-26 17:37:23.332  7159  7159 E Zygote  : v2
08-26 17:37:23.332  7159  7159 I libpersona: KNOX_SDCARD checking this for 10008
08-26 17:37:23.332  7159  7159 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:23.332  7159  7159 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:23.342  1015  1484 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7159 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-26 17:37:23.342  7159  7159 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:23.342  1015  1484 I ActivityManager: Killing 6538:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-26 17:37:23.342  7159  7159 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 17:37:23.342  1015  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-26 17:37:23.342  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:23.352  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.352  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.352  7119  7119 I SA      : [DM] This device is not a Vodafone
08-26 17:37:23.352  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:23.362   287   287 E SMD     : DCD OFF
,08-26 17:37:23.362  1015  1484 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7170 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 17:37:23.362  1015  1484 I ActivityManager: Killing 6018:com.android.mms/u0a41 (adj 15): empty #21,
08-26 17:37:23.362  1015  1484 I ActivityManager: Killing 6610:com.qualcomm.timeservice/1000 (adj 15): empty #22
,08-26 17:37:23.372  7170  7170 E Zygote  : MountEmulatedStorage(),
08-26 17:37:23.372  7170  7170 E Zygote  : v2
,08-26 17:37:23.372  7170  7170 I libpersona: KNOX_SDCARD checking this for 10009
08-26 17:37:23.372  7170  7170 I libpersona: KNOX_SDCARD not a persona,
,08-26 17:37:23.372  7159  7159 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 17:37:23.372  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 17:37:23.372  7159  7159 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:23.372  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 17:37:23.382  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 17:37:23.382   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 17:37:23.392  7119  7119 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-26 17:37:23.392  7119  7119 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 17:37:23.402  7119  7119 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 17:37:23.402  7119  7119 I SA      : [SCU] isHaveSA() - false
08-26 17:37:23.402  7119  7119 I SA      : support phone number id : false
08-26 17:37:23.402  7119  7119 I SA      : [DM] Supports Ref Jpn : true
08-26 17:37:23.402  7119  7119 I SA      : [DM] init END
,08-26 17:37:23.412  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:23.412  7170  7170 D ActivityThread: Added TimaKeyStore provider
08-26 17:37:23.412  7119  7119 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 17:37:23.412  7119  7119 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-26 17:37:23.412  7119  7119 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 17:37:23.422  7100  7100 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 17:37:23.422  7100  7100 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 17:37:23.422  7100  7100 I GAv4    :   adb logcat -s GAv4
,08-26 17:37:23.422  7139  7139 D BadgeProvider: onCreate
08-26 17:37:23.422  7119  7119 I SA      : [SLFUCHKMGR] constructor called
,08-26 17:37:23.422  7139  7139 D BadgeProvider: DatabaseHelper
,08-26 17:37:23.442   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/,
08-26 17:37:23.442   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 17:37:23.442  7100  7182 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 17:37:23.462  7139  7153 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 17:37:23.462  7119  7119 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-26 17:37:23.462  7119  7119 I SA      : [OR] == isSIMCardReady false ==
,08-26 17:37:23.462   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 17:37:23.462   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 17:37:23.462  7119  7119 I SA      : [SCU] == networkStateCheck == false
,08-26 17:37:23.462  7119  7119 I SA      : [OR] onReceive END
08-26 17:37:23.462  7100  7182 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 17:37:23.462  1015  1484 I ActivityManager: Killing 6629:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-26 17:37:23.472  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:23.482  7100  7100 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 17:37:23.482  1015  1305 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 17:37:23.492  1478  1478 D Launcher.Model: reloadBadges entered.
08-26 17:37:23.492  7139  7153 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-26 17:37:23.492  7139  7153 D BadgeProvider: sendNotify, [notify] : null
08-26 17:37:23.492  7139  7153 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 17:37:23.492  7139  7153 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 17:37:23.492  7139  7153 D BadgeProvider: update, [UpdateCount] : 1
,08-26 17:37:23.502  7100  7100 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 17:37:23.512   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 17:37:23.512   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 17:37:23.512  7100  7194 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 17:37:23.512  3954  3954 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 17:37:23 GMT+02:00 2016
,08-26 17:37:23.512  1015  1484 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 17:37:23.512  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 17:37:23.512  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:23.512  1015  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:23.512  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 17:37:23.522  1015  1454 I ActivityManager: Killing 6646:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-26 17:37:23.522   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 17:37:23.522   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 17:37:23.522  7100  7194 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 17:37:23.522  3954  3954 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 17:37:23.532  1015  1454 D CountryDetector: No listener is left
,08-26 17:37:23.542  1015  1217 I ActivityManager: Killing 6465:com.android.calendar/u0a131 (adj 15): empty #21
,08-26 17:37:23.542  3954  3954 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 17:37:23.542  1015  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 17:37:23.542  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 17:37:23.552  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:23.552  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:23.552  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:23.552  3954  3954 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 17:37:23.562  3954  3954 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 17:37:23.562  7100  7195 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 17:37:23.562  4294  4294 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 17:37:23.562  3954  7197 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 17:37:23.562  4294  4790 I iu.UploadsManager: num queued entries: 0
,08-26 17:37:23.562  4294  4790 I iu.UploadsManager: num updated entries: 0
,08-26 17:37:23.562  4294  4790 I iu.SyncManager: NEXT; no task
,08-26 17:37:23.572  3954  7197 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 17:37:23.582  3954  7197 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-26 17:37:23.592  3954  7197 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-26 17:37:23.592  3954  3954 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 17:37:23.602  2018  2165 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-26 17:37:23.612  2018  2165 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-26 17:37:23.612  1015  1450 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-26 17:37:23.612  1015  1450 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 17:37:23.612  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0,
,08-26 17:37:23.612  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 17:37:23.752  1015  1469 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:23.752  1015  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:23.752  1015  1469 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:23.752  1015  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 17:37:23.752  7100  7100 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 17:37:23.772  7100  7100 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5551-5553)
08-26 17:37:23.772  7100  7100 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 17:37:23.772  7100  7100 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35a0d1b1}
,08-26 17:37:23.772  7100  7100 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 17:37:23.772  7100  7100 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 17:37:23.792  7100  7100 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 17:37:23.792  7100  7100 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 17:37:23.802  7100  7100 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 17:37:23.812  7100  7100 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 17:37:23.812  7100  7100 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 17:37:23.812  7100  7100 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 17:37:23.812  7100  7100 I Adreno-EGL: Local Branch: 
08-26 17:37:23.812  7100  7100 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 17:37:23.812  7100  7100 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 17:37:23.812  7100  7100 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 17:37:23.852  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 17:37:23.852  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 17:37:23.852  1015  1028 D SecContentProvider2: mCursor = null
,08-26 17:37:23.852  1015  1028 D WifiService: setWifiEnabled: true pid=6682, uid=10171
,08-26 17:37:23.852  1015  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 17:37:23.852  1015  1028 W WifiService: Failed getting userId using ActivityManagerNative
08-26 17:37:23.852  1015  1028 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 17:37:23.852  1015  1028 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 17:37:23.852  1015  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 17:37:23.852  1015  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 17:37:23.852  1015  1028 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 17:37:23.852  1015  1028 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 17:37:23.852  1015  1028 D SettingsProvider: name = wifi_on
,08-26 17:37:23.862  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 17:37:23.892  7100  7100 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 17:37:23.892  7100  7227 W cr.media: Requires BLUETOOTH permission
,08-26 17:37:23.902  7100  7100 I NSApplication: Starting up...
,08-26 17:37:23.902  1015  1305 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 17:37:23.902  1015  1476 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 17:37:23.912  1015  1217 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 17:37:23.912  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:23.912  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.912  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:23.912  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:23.922  1015  1217 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7232 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 17:37:23.922  7232  7232 E Zygote  : MountEmulatedStorage()
08-26 17:37:23.922  7232  7232 E Zygote  : v2
08-26 17:37:23.922  7232  7232 I libpersona: KNOX_SDCARD checking this for 10117
08-26 17:37:23.922  7232  7232 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:23.922  1015  1217 I ActivityManager: Killing 6894:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
08-26 17:37:23.922  7232  7232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:23.932  7232  7232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 17:37:23.932  7232  7232 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 17:37:23.952  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:23.952  7232  7232 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:23.972  7232  7232 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 17:37:24.222  1015  1043 D Tethering: interfaceAdded wlan0
,08-26 17:37:24.232  1015  1128 E Tethering: No numeric data
,08-26 17:37:24.232  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 17:37:24.232  1015  1128 D Tethering: clearTetheredNotification()
,08-26 17:37:24.232  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-26 17:37:24.232  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:24.242  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 17:37:24.242  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:24.242  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:24.242  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 17:37:24.242  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 17:37:24.242  1015  1128 D Tethering: InitialState.processMessage what=4
,08-26 17:37:24.242  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 17:37:24.242  1169  1169 D HotspotTile: updateTetherState():false, false
,08-26 17:37:24.242  1015  1128 E Tethering: No numeric data
,08-26 17:37:24.242  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 17:37:24.242  1015  1128 D Tethering: clearTetheredNotification()
,08-26 17:37:24.242  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 17:37:24.242  1015  1122 V NetworkStats: performPollLocked() took 8ms
08-26 17:37:24.242  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:24.242  1169  1169 D HotspotTile: updateTetherState():false, false
,08-26 17:37:24.242  1015  1043 D Tethering: interfaceAdded p2p0
,08-26 17:37:24.242  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:24.242  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
08-26 17:37:24.242  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:24.252  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-26 17:37:24.252  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:24.252  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 17:37:24.252  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 17:37:24.252  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 17:37:24.252  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 17:37:24.252  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 17:37:24.252  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:24.252  1015  1122 V NetworkStats: performPollLocked() took 6ms
08-26 17:37:24.262  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:24.262  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:24.262   277  1014 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-26 17:37:24.262   277  1014 D SoftapController: Softap fwReload - Ok,
,08-26 17:37:24.262   277  1014 D CommandListener: Setting iface cfg,
08-26 17:37:24.262   277  1014 D CommandListener: Trying to bring down wlan0
08-26 17:37:24.262   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-26 17:37:24.272  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant,
,08-26 17:37:24.282  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-26 17:37:24.282  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 17:37:24.282  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 17:37:24.282  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:24.282  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:24.282  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:24.282  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:24.292  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:24.292  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 17:37:24.292  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 17:37:24.292  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:24.292  1169  1169 D HotspotTile: onReceive : 2, 0
,08-26 17:37:24.302  1310  1310 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:24.302  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:24.302  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:24.322  7260  7260 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 17:37:24.322  7260  7260 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 17:37:24.322  7260  7260 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 17:37:24.332  1015  3282 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-26 17:37:24.332  1015  3282 I ActivityManager: Killing 6911:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-26 17:37:24.352  1015  1450 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 17:37:24.352  1015  1450 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:24.352  1015  1450 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:24.352  1015  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:24.352  1015  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:24.352  1619  1619 I Hs20UtilService: Starting #12
08-26 17:37:24.352  7260  7260 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 17:37:24.352  1619  1659 I Hs20UtilService: Message received 5011
,08-26 17:37:24.352  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-26 17:37:24.352   408   408 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7260
08-26 17:37:24.352   408   408 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-26 17:37:24.352  7260  7260 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,08-26 17:37:24.352  7260  7260 I wpa_supplicant: ssSupport state is = 1
08-26 17:37:24.352  7260  7260 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-26 17:37:24.352  7260  7260 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 17:37:24.352   408   408 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7260
08-26 17:37:24.352   408   408 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
08-26 17:37:24.362  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 17:37:24.362  6524  6524 D SecurityLogAgent: StateMachine : Current State = 1
08-26 17:37:24.362  6524  6524 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 17:37:24.382   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 17:37:24.482  1015  1450 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 17:37:24.482  1015  1450 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 17:37:24.482  1015  1450 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 17:37:24.482  1015  1450 D BatteryService: stay LED for fully charged
,08-26 17:37:24.482  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 17:37:24.482  1015  1015 I MotionRecognitionService: Plugged,
08-26 17:37:24.482  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 17:37:24.492  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 17:37:24.492  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 17:37:24.492  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 17:37:24.492  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 17:37:24.512  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 17:37:24.512  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 17:37:24.512  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 17:37:24.522   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-26 17:37:24.522  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-26 17:37:24.572  7260  7260 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 17:37:24.572  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 17:37:24.582  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 17:37:24.582   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7260
08-26 17:37:24.582   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-26 17:37:24.582  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 17:37:24.582  7260  7260 I wpa_supplicant: ssSupport state is = 1
08-26 17:37:24.582  7260  7260 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,08-26 17:37:24.582  7260  7260 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 17:37:24.582  7260  7260 E wpa_supplicant: SIM READ ERROR
08-26 17:37:24.582  7260  7260 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 17:37:24.592  7260  7260 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 17:37:24.592  7260  7260 E wpa_supplicant: SIM READ ERROR
08-26 17:37:24.592  7260  7260 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 17:37:24.592  7260  7260 I wpa_supplicant: wpa_default_ap_write_once,
08-26 17:37:24.592  7260  7260 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 17:37:24.592  7260  7260 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 17:37:24.592  7260  7260 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 17:37:24.592  7260  7260 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 17:37:24.592  7260  7260 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-26 17:37:24.592  7260  7260 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 17:37:24.592  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 17:37:24.592  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:24.592  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:24.722  7260  7260 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 17:37:24.982  7260  7260 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 17:37:24.982  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-26 17:37:24.992  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 17:37:25.002   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7260
,08-26 17:37:25.002   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 17:37:25.002  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 17:37:25.002  7260  7260 I wpa_supplicant: ssSupport state is = 1
,08-26 17:37:25.002  7260  7260 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 17:37:25.002  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 17:37:25.012  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-26 17:37:25.022   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7260
08-26 17:37:25.022   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 17:37:25.022  7260  7260 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 17:37:25.022  7260  7260 I wpa_supplicant: ssSupport state is = 1
08-26 17:37:25.022  7260  7260 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 17:37:25.022  7260  7260 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 17:37:25.022  7260  7260 E wpa_supplicant: SIM READ ERROR
08-26 17:37:25.022  7260  7260 I wpa_supplicant: wpa_default_ap_write_once
08-26 17:37:25.022  7260  7260 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 17:37:25.022  7260  7260 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 17:37:25.022  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 17:37:25.022  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 17:37:25.022  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
,08-26 17:37:25.022  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 17:37:25.022  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 17:37:25.022  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 17:37:25.212  7260  7260 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 17:37:25.212  7260  7260 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 17:37:25.242  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 17:37:25.242  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 17:37:25.242  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
,08-26 17:37:25.362  7260  7260 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 17:37:25.362  7260  7260 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-26 17:37:25.362  7260  7260 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 17:37:25.372  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-26 17:37:25.372  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 17:37:25.372  7260  7260 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-26 17:37:25.372  7260  7260 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 17:37:25.372  7260  7260 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 17:37:25.372  7260  7260 E wpa_supplicant: SIM READ ERROR,
08-26 17:37:25.372  7260  7260 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 17:37:25.382   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 17:37:25.402  7260  7260 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 17:37:25.412  7260  7260 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 17:37:25.412  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
08-26 17:37:25.412  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:25.412  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:25.412  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:25.412  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:25.412  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:25.412  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:25.412  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:25.412  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 17:37:25.412  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 17:37:25.412  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:25.412  1169  1169 D HotspotTile: onReceive : 3, 0
08-26 17:37:25.412  1310  1310 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:25.422  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:25.422  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:25.422  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:25.422  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:25.422  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:25.422  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:25.422  1015  1454 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 17:37:25.422  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:25.422  1015  1454 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 17:37:25.422  1015  1454 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:25.422  1015  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:25.422  1015  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 17:37:25.422  1619  1619 I Hs20UtilService: Starting #13
08-26 17:37:25.422  1619  1659 I Hs20UtilService: Message received 5011
,08-26 17:37:25.432  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 17:37:25.432  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 17:37:25.432  6524  6524 D SecurityLogAgent: StateMachine : Current State = 1
08-26 17:37:25.432  6524  6524 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 17:37:25.432  1015  1125 E WifiConfigStore: Not a HS20,
08-26 17:37:25.432  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 17:37:25.442  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65],
,08-26 17:37:25.442  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-26 17:37:25.442  7260  7260 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 17:37:25.442  7260  7260 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 17:37:25.442  7260  7260 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 17:37:25.442  7260  7260 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 17:37:25.442  7260  7260 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 17:37:25.442  7260  7260 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 17:37:25.442  7260  7260 I wpa_supplicant: First Scan Start
08-26 17:37:25.442  7260  7260 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 17:37:25.442  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-26 17:37:25.442  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 17:37:25.442  1015  1125 I WifiNative-HAL: startHal
08-26 17:37:25.442  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d6c488c,
08-26 17:37:25.442  1015  1125 I WifiNative-HAL: Could not start hal
08-26 17:37:25.442  6927  6927 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:25.452  1015  1125 E WifiNative-wlan0: do suspend true
,08-26 17:37:25.452  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 },
,08-26 17:37:25.452  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 17:37:25.452  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 17:37:25.452  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:25.452  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-26 17:37:25.452  1015  1148 I WifiNative-HAL: startHal
08-26 17:37:25.452  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9ea7e9bc
08-26 17:37:25.452  1015  1148 I WifiNative-HAL: Could not start hal
08-26 17:37:25.452  1015  1148 E WifiScanningService: could not start HAL
08-26 17:37:25.452   277  1014 D CommandListener: Setting iface cfg
08-26 17:37:25.452  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:25.452   277  1014 D CommandListener: Trying to bring up p2p0
,08-26 17:37:25.452  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 17:37:25.452  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 17:37:25.452  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-26 17:37:25.452  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 17:37:25.452  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 17:37:25.452  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 17:37:25.452  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-26 17:37:25.462  1015  1124 D WifiP2pService: P2pEnablingState
08-26 17:37:25.462  7260  7260 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 17:37:25.462  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 17:37:25.462  1015  1124 D WifiP2pService: P2p socket connection successful
,08-26 17:37:25.462  1015  1124 D WifiP2pService: P2pEnabledState
,08-26 17:37:25.462  7260  7260 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 17:37:25.462  7260  7260 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-26 17:37:25.462  1015  1125 E WifiStateMachine: Failed to set frequency band 0,
08-26 17:37:25.462  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 17:37:25.462  1015  1127 E ConnectivityService: updateNetworkInfo(),
,08-26 17:37:25.462  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 17:37:25.462  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
08-26 17:37:25.462  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 17:37:25.462  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 17:37:25.462  1015  1125 D SecContentProvider2: mCursor = null
08-26 17:37:25.462  1015  1046 D WifiDisplayController: disconnect
08-26 17:37:25.462  1015  1046 D WifiDisplayController: updateConnection,
08-26 17:37:25.462  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 17:37:25.462  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,08-26 17:37:25.472  1169  1169 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 17:37:25.472  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:25.472  1015  1738 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 17:37:25.472  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:25.472  1169  1169 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 17:37:25.472  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 17:37:25.472  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 17:37:25.472  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-26 17:37:25.472  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-26 17:37:25.472  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 17:37:25.472  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 17:37:25.472  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 17:37:25.472  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
08-26 17:37:25.472  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 17:37:25.472  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 17:37:25.472  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  secondary type: null
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  wps: 0
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  grpcapab: 0
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  devcapab: 0
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  status: 3
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  wfdInfo: null
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-26 17:37:25.472  1015  1046 D WifiDisplayController:  SConnectInfo : null
,08-26 17:37:25.472  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 17:37:25.482  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 17:37:25.482  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 17:37:25.482  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 17:37:25.482  1015  3950 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 17:37:25.482  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:25.482  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:25.482  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:25.482  1015  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:25.492  7273  7273 E Zygote  : MountEmulatedStorage()
,08-26 17:37:25.492  7273  7273 E Zygote  : v2
08-26 17:37:25.492  7273  7273 I libpersona: KNOX_SDCARD checking this for 10064
08-26 17:37:25.492  7273  7273 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:25.492  7273  7273 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:25.492  1015  3950 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7273 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 17:37:25.492  7273  7273 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:25.502  7273  7273 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:25.502  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
08-26 17:37:25.502  7260  7260 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 17:37:25.502  1015  1124 D WifiP2pService: InactiveState
08-26 17:37:25.502  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-26 17:37:25.502  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
08-26 17:37:25.502  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-26 17:37:25.502  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 17:37:25.512   311   311 I art     : Explicit concurrent mark sweep GC freed 8680(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 21.561ms
,08-26 17:37:25.532   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.364ms
,08-26 17:37:25.542  7273  7273 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:25.542  7273  7273 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:25.552   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 695us total 16.895ms
,08-26 17:37:25.562  7273  7273 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 17:37:25.572  7273  7273 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 17:37:25.572  7273  7273 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 17:37:25.602  7273  7273 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 17:37:25.602  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 17:37:25.612  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:25.612  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:25.612  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:25.612  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:25.622  7288  7288 E Zygote  : MountEmulatedStorage()
,08-26 17:37:25.622  7288  7288 E Zygote  : v2
08-26 17:37:25.622  7288  7288 I libpersona: KNOX_SDCARD checking this for 10065
08-26 17:37:25.622  7288  7288 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:25.622  7288  7288 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:25.622  1015  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7288 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 17:37:25.622  1015  1028 I ActivityManager: Killing 6808:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-26 17:37:25.622  7288  7288 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:25.622  7288  7288 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:25.642  7288  7288 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:25.642  7288  7288 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:25.662  7288  7288 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 17:37:25.672  1015  1469 I ActivityManager: Killing 6951:com.android.bluetooth/1002 (adj 15): empty #21
,08-26 17:37:25.862  1015  1027 I ActivityManager: Killing 6832:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-26 17:37:26.362   287   287 E SMD     : DCD OFF
,08-26 17:37:26.382   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 17:37:26.692  7260  7260 I wpa_supplicant: nl80211: Received scan results (28 BSSes)
08-26 17:37:26.692  7260  7260 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 17:37:26.692  7260  7260 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-26 17:37:26.692  7260  7260 I wpa_supplicant: Trying to associate with  'G700'
,08-26 17:37:26.692  7260  7260 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-26 17:37:26.692  7260  7260 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
08-26 17:37:26.702  1015  7269 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 17:37:26.722  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:26.722  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:26.812  7260  7260 E wpa_supplicant: Cmd 35605 not handled
08-26 17:37:26.812  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 17:37:26.812  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:26.812  7260  7260 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 17:37:26.812  1015  1043 D Tethering: interfaceStatusChanged wlan0, false,
08-26 17:37:26.812  7260  7260 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-26 17:37:26.812  7260  7260 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 17:37:26.812  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-26 17:37:26.812  7260  7260 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 17:37:26.812  7260  7260 I wpa_supplicant: Associated with F4.99.3E
08-26 17:37:26.812  7260  7260 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 17:37:26.812  7260  7260 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 17:37:26.812  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:26.812  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 17:37:26.812  7260  7260 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-26 17:37:26.822  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 17:37:26.822  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:26.822  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 17:37:26.822  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 17:37:26.822  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 17:37:26.822  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-26 17:37:26.822  1015  1128 E Tethering: No numeric data
08-26 17:37:26.822  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 17:37:26.822  1015  1128 D Tethering: clearTetheredNotification()
,08-26 17:37:26.822  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:26.822  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-26 17:37:26.832  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:26.832  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 17:37:26.832  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 17:37:26.832  1169  1169 D HotspotTile: updateTetherState():false, false
08-26 17:37:26.832  7260  7260 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 17:37:26.832  7260  7260 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 17:37:26.832  7260  7260 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-26 17:37:26.832  7260  7260 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-26 17:37:26.832  7260  7260 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 17:37:26.832  1015  1122 V NetworkStats: performPollLocked() took 7ms
08-26 17:37:26.832  7260  7260 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 17:37:26.832  7260  7260 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 17:37:26.832  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 17:37:26.832  1015  1125 D SecContentProvider2: mCursor = null
08-26 17:37:26.832  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:26.832  7260  7260 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 17:37:26.842  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 17:37:26.832  7260  7260 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 17:37:26.842  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:26.842  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:26.842  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 17:37:26.842  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-26 17:37:26.842  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:26.842  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:26.852  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 17:37:26.852  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 17:37:26.862  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 17:37:26.862  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 17:37:26.862  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:26.862  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:26.862  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:26.862  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:26.862  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.862  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.862  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.862  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.862  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 17:37:26.862  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 17:37:26.862  1015  1028 D SecContentProvider2: mCursor = null
,08-26 17:37:26.862  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 17:37:26.862  1015  1028 D WifiService: setWifiEnabled: false pid=6682, uid=10171
08-26 17:37:26.862  1015  1028 D SettingsProvider: name = wifi_on
08-26 17:37:26.862  1015  3282 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 17:37:26.872  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:26.872  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:26.872  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:26.872  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:26.872  1619  1619 I Hs20UtilService: Starting #14
,08-26 17:37:26.872  1619  1659 I Hs20UtilService: Message received 5007
,08-26 17:37:26.872  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 17:37:26.872  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 17:37:26.882  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 17:37:26.882  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 17:37:26.882  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 17:37:26.882  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 17:37:26.882  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 17:37:26.892  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:26.902   277  1014 D CommandListener: Setting iface cfg,
,08-26 17:37:26.902  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 17:37:26.902  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 17:37:26.902  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:26.912  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 17:37:26.912  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:26.912  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.912  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.912  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.912  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:26.922  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:26.932  1015  1125 E WifiNative-wlan0: do suspend true,
,08-26 17:37:26.932  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
08-26 17:37:26.932  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 17:37:26.932  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 17:37:26.932  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 17:37:26.932  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:26.942   277  1014 D CommandListener: Clearing all IP addresses on wlan0
08-26 17:37:26.942  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.942  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.942  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:26.942  1015  1127 E ConnectivityService: updateNetworkInfo(),
08-26 17:37:26.942  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:26.942  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:26.942  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-26 17:37:26.942  1015  1125 D SecContentProvider2: mCursor = null
08-26 17:37:26.942  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:26.942   277  1014 E Netd    : no such netId 503,
08-26 17:37:26.942  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
08-26 17:37:26.942  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 17:37:26.942  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 17:37:26.952  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 17:37:26.952  1015  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-26 17:37:26.952  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-26 17:37:26.952  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:26.952  1015  1127 V NetworkStats: updateIfacesLocked()
08-26 17:37:26.952  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-26 17:37:26.952  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:26.952  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-26 17:37:26.952  1015  1127 V NetworkStats: performPollLocked() took 4ms
,08-26 17:37:26.952  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:26.952  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 17:37:26.952  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 17:37:26.952  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 17:37:26.952  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.952  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.952  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.952  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.952  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:26.952  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-26 17:37:26.952  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:26.962  1015  1469 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 17:37:26.962  1015  1469 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:26.962  1015  1469 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:26.962  1015  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:26.962  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 17:37:26.962  1015  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 17:37:26.962  1015  1124 D WifiP2pService: P2pDisablingState
,08-26 17:37:26.962  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 17:37:26.962  1015  1124 D WifiP2pService: p2p socket connection lost
08-26 17:37:26.962  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 17:37:26.962  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-26 17:37:26.962  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 17:37:26.962  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 17:37:26.962  1015  1124 D WifiP2pService: P2pDisabledState
08-26 17:37:26.962  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-26 17:37:26.962  1619  1619 I Hs20UtilService: Starting #15
08-26 17:37:26.962  1015  7303 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:26.962  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 17:37:26.962  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 17:37:26.962  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 17:37:26.962  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:26.962  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-26 17:37:26.972  1015  7303 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-26 17:37:26.972  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 17:37:26.972  1619  1659 I Hs20UtilService: Message received 5007
,08-26 17:37:26.972  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 17:37:26.972  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 17:37:26.972  1015  1046 D WifiDisplayController: disconnect
08-26 17:37:26.972  1015  1046 D WifiDisplayController: updateConnection
08-26 17:37:26.972  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 17:37:26.972  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 17:37:26.972  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 17:37:26.972  1015  1125 E WifiNative-wlan0: do suspend true
,08-26 17:37:26.972  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-26 17:37:26.972  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:26.972  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-26 17:37:26.972  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:26.972   277  1014 D CommandListener: Clearing all IP addresses on wlan0
08-26 17:37:26.972  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 17:37:26.982  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 17:37:26.982  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:26.982  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:26.982  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.982  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:26.982  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.982  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:26.982  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 17:37:26.982  1169  1169 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 17:37:26.982  1015  1133 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 17:37:26.982  1169  1169 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 17:37:26.982  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 17:37:26.982  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 17:37:26.982  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 17:37:26.982  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 17:37:26.982  7260  7260 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 17:37:26.982  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 17:37:26.992  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:26.992  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:26.992  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.992  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.992  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:26.992  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:27.002  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:27.002  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:27.002  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:27.002  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 17:37:27.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:27.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:27.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:27.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:27.002  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:27.002  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 17:37:27.002  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:27.002  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 17:37:27.002  1310  1310 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:27.002  1169  1169 D HotspotTile: onReceive : 0, 0
,08-26 17:37:27.002  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:27.002  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:27.002  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:27.002  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:27.002  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:27.002  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:27.002  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:27.002  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:27.002  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:27.002  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:27.002  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:27.002  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:27.012  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:27.012  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:27.012  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:27.012  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:27.012  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:27.012  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:27.012  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:27.012  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:27.012  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:27.012  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:27.012  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 17:37:27.012  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 17:37:27.012  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 17:37:27.022  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 17:37:27.022  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 17:37:27.022  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 17:37:27.022  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 17:37:27.022  7273  7273 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 17:37:27.022  7273  7273 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 17:37:27.022  7273  7273 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 17:37:27.022  7288  7288 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 17:37:27.032  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 17:37:27.032  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:27.032  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:27.032  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:27.032  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:27.032  1619  1619 I Hs20UtilService: Starting #16
,08-26 17:37:27.032  1619  1659 I Hs20UtilService: Message received 5007
,08-26 17:37:27.032  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 17:37:27.032  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 17:37:27.032  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 17:37:27.032  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 17:37:27.032  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 17:37:27.032  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 17:37:27.032  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 17:37:27.042  1015  1450 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 17:37:27.042  1015  1450 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:27.042  1015  1450 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:27.042  1015  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:27.042  1015  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:27.052  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 17:37:27.052  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 17:37:27.052  1619  1619 I Hs20UtilService: Starting #17
,08-26 17:37:27.052  6524  6524 D SecurityLogAgent: StateMachine : Current State = 1
08-26 17:37:27.052  6524  6524 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 17:37:27.052  1619  1659 I Hs20UtilService: Message received 5011
,08-26 17:37:27.172  7260  7260 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 17:37:27.252  7260  7260 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 17:37:27.252  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 17:37:27.252  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 17:37:27.252  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 17:37:27.272  7260  7260 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 17:37:27.272  7260  7260 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 17:37:27.272  7260  7260 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 17:37:27.272  7260  7260 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 17:37:27.272  7260  7260 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 17:37:27.272  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 17:37:27.272  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:27.272  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:27.282  1015  1128 D Tethering: InitialState.processMessage what=4
,08-26 17:37:27.282  1015  1128 E Tethering: No numeric data
,08-26 17:37:27.282  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-26 17:37:27.282  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:27.282  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 17:37:27.282  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 17:37:27.282  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 17:37:27.282  1169  1169 D HotspotTile: updateTetherState():false, false,
08-26 17:37:27.282  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 17:37:27.292  1015  1122 V NetworkStats: performPollLocked() took 5ms,
08-26 17:37:27.282  1015  1128 D Tethering: clearTetheredNotification()
08-26 17:37:27.292  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 17:37:27.292  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:27.292  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:27.292  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 17:37:27.292  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:27.292  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 17:37:27.292  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:27.292  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 17:37:27.292  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:27.382   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 17:37:27.612  7260  7260 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 17:37:27.652  1015  1454 I ActivityManager: Killing 6968:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 17:37:27.732  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 17:37:27.732  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:27.732  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:27.732  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:27.732  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:27.732  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:27.742  7260  7260 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 17:37:27.842  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-26 17:37:27.842  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 17:37:27.842  6927  6927 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:27.852  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 17:37:27.852  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 17:37:27.852  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:27.852  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 17:37:27.852  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 17:37:27.852  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:27.862  2018  2153 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-26 17:37:27.862  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,08-26 17:37:27.862  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1),
08-26 17:37:27.862  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,08-26 17:37:27.862  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 17:37:27.862  1310  1310 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:27.862  1169  1169 D HotspotTile: onReceive : 1, 0
,08-26 17:37:27.872  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:27.872  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:27.872  1015  1305 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 17:37:27.872  1015  1305 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:27.872  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:27.872  1015  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:27.872  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:27.882  1619  1619 I Hs20UtilService: Starting #18
,08-26 17:37:27.882  1619  1659 I Hs20UtilService: Message received 5011
,08-26 17:37:27.882  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 17:37:27.882  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 17:37:27.882  6524  6524 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 17:37:27.882  6524  6524 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 17:37:28.452  1015  1043 D Tethering: interfaceRemoved wlan0
,08-26 17:37:28.452  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 17:37:28.602  1015  1043 D Tethering: interfaceRemoved p2p0
,08-26 17:37:28.602  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 17:37:29.362   287   287 E SMD     : DCD OFF,
,08-26 17:37:29.392  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 17:37:29.892  6682  6737 D BluetoothAdapter: enable()
,08-26 17:37:29.892  1015  1738 W ActivityManager: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-26 17:37:29.902  1015  1738 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-26 17:37:29.902  1015  1738 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 17:37:29.902  1015  1738 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 17:37:29.902  1015  1738 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 17:37:29.902  1015  1738 W BluetoothManagerService: ,	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 17:37:29.902  1015  1738 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 17:37:29.902  1015  1738 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 17:37:29.902  1015  1738 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 17:37:29.902  1015  1738 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 17:37:29.902  1015  1738 D SettingsProvider: name = bluetooth_on,
,08-26 17:37:29.912  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 17:37:29.912  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 17:37:29.912  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-26 17:37:29.912  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 17:37:29.912  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:29.912  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:29.912  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:29.912  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:29.932  7309  7309 E Zygote  : MountEmulatedStorage()
,08-26 17:37:29.932  7309  7309 E Zygote  : v2
08-26 17:37:29.932  7309  7309 I libpersona: KNOX_SDCARD checking this for 1002
08-26 17:37:29.932  7309  7309 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:29.932  7309  7309 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:29.932  1015  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7309 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 17:37:29.932  7309  7309 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:29.932  7309  7309 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 17:37:29.962  7309  7309 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:29.962  7309  7309 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:29.982  7309  7309 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 17:37:29.982  7309  7309 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 17:37:30.012  7309  7309 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 17:37:30.042  7309  7309 D BtSettings.ProfileConfig: Adding GattService
,08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding HeadsetService
,08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding A2dpService
08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding HidService
08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding HealthService
08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding PanService
08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding SapService
08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding SapClientService
,08-26 17:37:30.052  7309  7309 D BtSettings.ProfileConfig: Adding HidDevService
08-26 17:37:30.052  7309  7309 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 17:37:30.052  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 17:37:30.052  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.052  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.052  1015  1027 D SettingsProvider: selectionArgs: false
08-26 17:37:30.052  1015  1027 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.052  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.052  1015  1027 D SettingsProvider: ret = -1
,08-26 17:37:30.052  1015  1484 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 17:37:30.052  1015  1484 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.052  1015  1484 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.052  1015  1484 D SettingsProvider: selectionArgs: false
08-26 17:37:30.052  1015  1484 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.052  1015  1484 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.052  1015  1484 D SettingsProvider: ret = -1
,08-26 17:37:30.062  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 17:37:30.062  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  1133 D SettingsProvider: selectionArgs: false
08-26 17:37:30.062  1015  1133 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  1133 D SettingsProvider: ret = -1
,08-26 17:37:30.062  1015  1454 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 17:37:30.062  1015  1454 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  1454 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  1454 D SettingsProvider: selectionArgs: false
,08-26 17:37:30.062  1015  1454 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  1454 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  1454 D SettingsProvider: ret = -1
,08-26 17:37:30.062  1015  1450 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 17:37:30.062  1015  1450 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  1450 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  1450 D SettingsProvider: selectionArgs: false
,08-26 17:37:30.062  1015  1450 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  1450 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  1450 D SettingsProvider: ret = -1
,08-26 17:37:30.062  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 17:37:30.062  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  1028 D SettingsProvider: selectionArgs: false
08-26 17:37:30.062  1015  1028 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  1028 D SettingsProvider: ret = -1
08-26 17:37:30.062  1015  1305 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 17:37:30.062  1015  1305 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  1305 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  1305 D SettingsProvider: selectionArgs: false
08-26 17:37:30.062  1015  1305 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  1305 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  1305 D SettingsProvider: ret = -1
08-26 17:37:30.062  1015  1476 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 17:37:30.062  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  1476 D SettingsProvider: selectionArgs: false
08-26 17:37:30.062  1015  1476 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  1476 D SettingsProvider: ret = -1
08-26 17:37:30.062  1015  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:30.062  1015  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  1217 D SettingsProvider: selectionArgs: false
08-26 17:37:30.062  1015  1217 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  1217 D SettingsProvider: ret = -1
08-26 17:37:30.062  1015  1738 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:30.062  1015  1738 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  1738 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  1738 D SettingsProvider: selectionArgs: false
08-26 17:37:30.062  1015  1738 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  1738 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  1738 D SettingsProvider: ret = -1
08-26 17:37:30.062  1015  1469 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 17:37:30.062  1015  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  1469 D SettingsProvider: selectionArgs: false
08-26 17:37:30.062  1015  1469 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  1469 D SettingsProvider: ret = -1
08-26 17:37:30.062  1015  3282 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 17:37:30.062  1015  3282 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.062  1015  3282 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:30.062  1015  3282 D SettingsProvider,: selectionArgs: false
08-26 17:37:30.062  1015  3282 D SettingsProvider: selectionArgs: 1002
08-26 17:37:30.062  1015  3282 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.062  1015  3282 D SettingsProvider: ret = -1
,08-26 17:37:30.082  7309  7309 D BluetoothAdapterState: make
,08-26 17:37:30.082  7309  7309 I bluedroid: init
,08-26 17:37:30.082  7309  7324 I BluetoothAdapterState: Entering OffState
,08-26 17:37:30.092  7309  7309 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 17:37:30.092  7309  7309 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 17:37:30.092  7309  7309 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 17:37:30.092  7309  7309 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 17:37:30.092  7309  7309 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-26 17:37:30.092  7309  7309 I bluedroid: get_profile_interface socket
08-26 17:37:30.092  7309  7309 I bluedroid: get_profile_interface map_client
,08-26 17:37:30.092  7309  7327 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 17:37:30.092  7309  7309 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 17:37:30.092  7309  7327 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 17:37:30.092  7309  7327 E BluetoothServiceJni: populateRssiValuesNative
,08-26 17:37:30.092  7309  7327 I bluedroid: getModelRssiValues
08-26 17:37:30.102  7309  7327 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 17:37:30.102  7309  7327 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 17:37:30.102  1015  1015 D SettingsProvider: name = bluetooth_name
,08-26 17:37:30.102  7309  7327 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 17:37:30.102  7309  7309 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:30.102  1015  3282 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 17:37:30.102  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 17:37:30.102  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:30.112  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.112  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:30.112  7309  7318 I bluedroid: config_hci_snoop_log
,08-26 17:37:30.112  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-26 17:37:30.112  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-26 17:37:30.112  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 17:37:30.112  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 17:37:30.112  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 17:37:30.122  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 17:37:30.122  7309  7309 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-26 17:37:30.122  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 17:37:30.122  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 17:37:30.122  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 17:37:30.122  7309  7324 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 17:37:30.122  7309  7324 D BluetoothAdapterProperties: Setting state to 11
08-26 17:37:30.122  7309  7324 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 17:37:30.122  7309  7324 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 17:37:30.122  7309  7324 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 17:37:30.122  7309  7324 D BluetoothAdapterService: Autoconnection is available 
08-26 17:37:30.122  7309  7324 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 17:37:30.132  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:30.132  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-26 17:37:30.132  7309  7324 D BluetoothSecureManager: getInstant: null
08-26 17:37:30.132  7309  7324 D BluetoothSecureManager: calling getMethod for getService
,08-26 17:37:30.132  7309  7324 D BluetoothSecureManager: calling getService
,08-26 17:37:30.132  7309  7324 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1caca7ae
,08-26 17:37:30.132  1015  1476 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 17:37:30.132  1015  1476 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-26 17:37:30.132  7309  7324 D BtConfig.SecureMode: isSecureModeOn:false
08-26 17:37:30.132  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 17:37:30.142  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 17:37:30.142  7309  7324 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 17:37:30.142  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 17:37:30.142  7309  7324 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 17:37:30.142  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:30.142  1169  1169 D BluetoothTile:  getBluetoothState : 11
08-26 17:37:30.142  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 17:37:30.142  1858  1858 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 17:37:30.142  7309  7324 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 17:37:30.142  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 17:37:30.142  7309  7324 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 17:37:30.142  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 17:37:30.142  7309  7324 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 17:37:30.142  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 17:37:30.142  7309  7324 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 17:37:30.142  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:30.142  7309  7324 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 17:37:30.142  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 17:37:30.142  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
08-26 17:37:30.142  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 17:37:30.142  1310  1310 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:30.142  7309  7324 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 17:37:30.152  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 17:37:30.152  7309  7324 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:30.152  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 17:37:30.152  1015  1133 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 17:37:30.152  7309  7324 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:30.152  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 17:37:30.152  7309  7324 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 17:37:30.152  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 17:37:30.152  7309  7324 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 17:37:30.152  1015  3950 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 17:37:30.152  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 17:37:30.162  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:30.162  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:30.162  7309  7324 D BluetoothBondStateMachine: make
,08-26 17:37:30.172  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 17:37:30.172  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 17:37:30.172  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 17:37:30.172  7309  7329 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 17:37:30.302  1015  1484 I art     : Explicit concurrent mark sweep GC freed 70739(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.399ms total 161.512ms
,08-26 17:37:30.312  1015  1450 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:30.312  1015  1450 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 17:37:30.312  1310  1310 D BluetoothNotiBroadcastReceiver: onReceive
08-26 17:37:30.312  1015  1450 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:30.312  1015  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.312  1015  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:30.312  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 17:37:30.312  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 17:37:30.312  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
,08-26 17:37:30.312  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:30.312  7309  7309 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:30.312  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 17:37:30.312  7309  7309 D BtGatt.GattService: Received start request. Starting profile...
08-26 17:37:30.312  7309  7309 D BtGatt.GattService: start()
08-26 17:37:30.312  7309  7309 D BtGatt.GattService: start()
08-26 17:37:30.312  7309  7309 I bluedroid: get_profile_interface gatt
08-26 17:37:30.312  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:30.312  7309  7309 D BtGatt.AdvertiseManager: advertise manager created
08-26 17:37:30.322  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:30.322  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.322  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 17:37:30.322  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 17:37:30.322  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 17:37:30.322  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-26 17:37:30.322  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:30.322  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 17:37:30.322  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:30.322  1015  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:30.322  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.322  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 17:37:30.322  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 17:37:30.322  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 17:37:30.322  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 17:37:30.322  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 17:37:30.322  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:30.322  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:30.322  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:30.332  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:30.332  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 17:37:30.332  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:30.332  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 17:37:30.332  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:30.332  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.332  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:30.342  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 17:37:30.342  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 17:37:30.342  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 17:37:30.342  1015  1305 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 17:37:30.342  7309  7309 D BtGatt.GattService: mStartError = false
08-26 17:37:30.342  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:30.342  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:30.342  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:30.342  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:30.342  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:30.342  7309  7309 D HeadsetService: Received start request. Starting profile...
,08-26 17:37:30.342  7309  7309 D HeadsetService: start()
08-26 17:37:30.342  7309  7309 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 17:37:30.342  7309  7309 D HeadsetStateMachine: make
,08-26 17:37:30.352  7309  7309 E HeadsetStateMachine: # of Max HF connection is 2,
,08-26 17:37:30.352  7334  7334 E Zygote  : MountEmulatedStorage()
08-26 17:37:30.352  7334  7334 I libpersona: KNOX_SDCARD checking this for 10055
,08-26 17:37:30.352  7334  7334 E Zygote  : v2,
08-26 17:37:30.352  7334  7334 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:30.352  7334  7334 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:30.362  1015  1305 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7334 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-26 17:37:30.362  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:30.362  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-26 17:37:30.362  7334  7334 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:30.362  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:30.362  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.362  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:30.362  7334  7334 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:30.362  1015  3950 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 17:37:30.362  1015  3950 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 17:37:30.362  1015  3950 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:30.372  1015  3950 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.372  1015  3950 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 17:37:30.372  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 17:37:30.372  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 17:37:30.372  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 17:37:30.372  1015  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:30.372  1015  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 17:37:30.372  1015  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:30.372  1015  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.372  1015  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:30.372  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:30.372  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:30.372  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-26 17:37:30.372  1015  1484 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 17:37:30.372  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 17:37:30.372  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:30.372  1015  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.372  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 17:37:30.372  7309  7309 I bluedroid: get_profile_interface handsfree
08-26 17:37:30.372  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:30.372  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 17:37:30.372  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:30.372  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.372  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:30.372  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-26 17:37:30.382  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 17:37:30.382  7309  7324 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 17:37:30.382  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:30.382  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 17:37:30.382  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:30.382  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:30.382  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 17:37:30.382  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 17:37:30.382  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:30.382  7309  7324 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:30.382  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:30.382  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:30.382  7309  7324 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:30.382  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 17:37:30.382  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 17:37:30.382  7309  7324 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 17:37:30.382  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 17:37:30.382  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 17:37:30.382  7309  7324 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 17:37:30.382  7309  7324 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 17:37:30.392  7309  7309 I DualScoManager: Instantiating Dual Sco Manager
08-26 17:37:30.392  7309  7309 I DualScoManager: Set HeadsetServiceHelper
,08-26 17:37:30.402  7334  7334 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:30.402  7334  7334 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:30.402  7309  7309 D BluetoothAtMessage: createCMTIContentObservers
,08-26 17:37:30.402  1015  1027 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-26 17:37:30.402  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:30.402  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 17:37:30.402  1015  1027 D SettingsProvider: selectionArgs: false
08-26 17:37:30.402  1015  1027 D SettingsProvider: selectionArgs: 1002
,08-26 17:37:30.402  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:30.402  1015  1027 D SettingsProvider: ret = -1
,08-26 17:37:30.402  7309  7333 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 17:37:30.402  7309  7309 D HeadsetService: mStartError = false
08-26 17:37:30.402  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:30.412  7309  7309 D A2dpService: Received start request. Starting profile...
08-26 17:37:30.412  7309  7309 D A2dpService: start()
,08-26 17:37:30.412  7309  7333 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 17:37:30.412  7309  7333 D HeadsetStateMachine: map size, before remove : 0
08-26 17:37:30.412  7309  7333 D HeadsetStateMachine: map size, after remove: 0
08-26 17:37:30.412  7309  7309 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 17:37:30.412  7309  7309 I bluedroid: get_profile_interface avrcp
,08-26 17:37:30.422  7309  7309 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 17:37:30.422  7309  7309 D Avrcp   : Initialize Media Controller
08-26 17:37:30.422  7309  7309 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 17:37:30.422  7309  7309 E Avrcp   : getActiveSessions
,08-26 17:37:30.422  7309  7309 D Avrcp   : pick active media Controller
08-26 17:37:30.422  7309  7309 D Avrcp   : Get the active Media Controller 
,08-26 17:37:30.432  7334  7334 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 17:37:30.442  7309  7309 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 17:37:30.442  7309  7351 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 17:37:30.442  7309  7309 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 17:37:30.442  7309  7309 D A2dpStateMachine: make
,08-26 17:37:30.452  7309  7351 D BluetoothMediaBrowser: no now playing list
,08-26 17:37:30.452  7309  7351 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 17:37:30.452  7309  7309 I bluedroid: get_profile_interface a2dp
,08-26 17:37:30.452  7309  7354 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 17:37:30.452  7309  7309 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 17:37:30.462  7309  7309 D A2dpService: mStartError = false,
08-26 17:37:30.462  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:30.462  7309  7353 D A2dpStateMachine: Enter Disconnected: -2
08-26 17:37:30.462  7309  7309 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 17:37:30.462  7309  7309 D HidService: Received start request. Starting profile...
,08-26 17:37:30.462  7309  7309 D HidService: start()
,08-26 17:37:30.462  7309  7309 I bluedroid: get_profile_interface hidhost
08-26 17:37:30.462  7334  7334 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 17:37:30.462  7309  7309 D HidService: setHidService(): set to: null
08-26 17:37:30.462  7309  7309 D HidService: mStartError = false
,08-26 17:37:30.462  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:30.462  7334  7334 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 17:37:30.462  7334  7334 D UserAnalysis: Create SecureDbHelper
,08-26 17:37:30.462  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false,
,08-26 17:37:30.462  7309  7309 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 17:37:30.472  7309  7309 D HealthService: Received start request. Starting profile...
,08-26 17:37:30.472  7309  7309 D HealthService: start()
,08-26 17:37:30.472  7334  7334 D IntelligenceServiceApplication: onCreate()
,08-26 17:37:30.472  7309  7309 I bluedroid: get_profile_interface health
,08-26 17:37:30.472  7309  7309 D HealthService: mStartError = false
08-26 17:37:30.472  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:30.472  7309  7309 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 17:37:30.472  1425  1435 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 17:37:30.472  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 17:37:30.472  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 17:37:30.472  1425  1435 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 17:37:30.472  7309  7309 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 17:37:30.482  7309  7309 D PanService: Received start request. Starting profile...
,08-26 17:37:30.482  7309  7309 D PanService: start()
,08-26 17:37:30.482  7309  7309 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 17:37:30.482  1015  3950 I ActivityManager: Killing 6986:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-26 17:37:30.482  7309  7309 I bluedroid: get_profile_interface pan
,08-26 17:37:30.482  7309  7309 D PanService: mStartError = false
08-26 17:37:30.482  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:30.482  7309  7309 D HeadsetStateMachine: Proxy object connected
,08-26 17:37:30.482  7309  7309 D BluetoothMapService: Received start request. Starting profile...
08-26 17:37:30.482  7309  7309 D BluetoothMapService: start()
,08-26 17:37:30.482  7334  7334 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 17:37:30.482  7309  7309 D BluetoothMapService: mStartError = false
08-26 17:37:30.482  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:30.482  7309  7309 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 17:37:30.482  7309  7333 D HeadsetStateMachine: Disconnected process message: 11
,08-26 17:37:30.482  7309  7309 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 17:37:30.492  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-26 17:37:30.492  7334  7334 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 17:37:30.492  7309  7309 D SapService: Received start request. Starting profile...
08-26 17:37:30.492  7309  7309 D SapService: start()
08-26 17:37:30.492  7309  7309 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 17:37:30.492  7309  7309 I bluedroid: get_profile_interface sap
08-26 17:37:30.492  7309  7309 D SapService: mStartError = false
08-26 17:37:30.492  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:30.492  7309  7309 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 17:37:30.492  7309  7309 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 17:37:30.492  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 17:37:30.492  7309  7333 D HeadsetStateMachine: Disconnected process message: 18
08-26 17:37:30.492  7309  7309 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 17:37:30.492  7309  7333 D HeadsetStateMachine: Disconnected process message: 10
08-26 17:37:30.492  7309  7309 D BluetoothA2dp: Proxy object connected
08-26 17:37:30.492  7309  7309 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 17:37:30.492  7309  7333 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 17:37:30.492  7309  7333 D HeadsetStateMachine: Disconnected process message: 11
,08-26 17:37:30.502  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 17:37:30.502  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 17:37:30.502  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 17:37:30.502  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 17:37:30.502  1015  1217 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 17:37:30.502  7334  7334 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 17:37:30.502  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:30.502  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:30.502  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:30.502  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:30.512  7359  7359 E Zygote  : MountEmulatedStorage()
,08-26 17:37:30.512  7359  7359 E Zygote  : v2
08-26 17:37:30.512  7359  7359 I libpersona: KNOX_SDCARD checking this for 10105
,08-26 17:37:30.512  7359  7359 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:30.522  1015  1217 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7359 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-26 17:37:30.522  7359  7359 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:30.522  7359  7359 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:30.522  7359  7359 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 17:37:30.542  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 17:37:30.542  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 17:37:30.542  7359  7359 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:30.542  7359  7359 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:30.552  7309  7324 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 17:37:30.552  7309  7324 I bluedroid: enable
,08-26 17:37:30.552  7309  7372 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 17:37:30.552  7309  7324 I bt_hci_bdroid: init
,08-26 17:37:30.552  7309  7324 I bt_vendor: bt-vendor : init
08-26 17:37:30.552  7309  7324 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 17:37:30.552  7309  7324 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 17:37:30.552  7309  7324 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 17:37:30.552  7309  7324 D bt_userial_mct: userial_init
08-26 17:37:30.552  7309  7324 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 17:37:30.552  7309  7324 I bt_vendor: Starting hciattach daemon
08-26 17:37:30.552  7309  7324 I bt_vendor: try to set false
,08-26 17:37:30.552  7309  7324 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 17:37:30.552  7309  7324 I bt_vendor: Starting hciattach daemon
08-26 17:37:30.552  7309  7324 I bt_vendor: try to set true
,08-26 17:37:30.582  7379  7379 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 17:37:30.642  7385  7385 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 17:37:30.642  7388  7388 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 17:37:30.662  7390  7390 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 17:37:30.672  7391  7391 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 17:37:30.682  7392  7392 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 17:37:30.692  7393  7393 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 17:37:30.712   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 17:37:30.712   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 17:37:30.712  7359  7397 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 17:37:30.722   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 17:37:30.722   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 17:37:30.722  7359  7397 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 17:37:30.862  7359  7359 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:30.862  7359  7359 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:30.862  7359  7359 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:30.862  7359  7359 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:30.862  7359  7359 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:30.862  7359  7359 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:30.862  7359  7359 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:30.862  7359  7359 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 17:37:30.862  7359  7359 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 17:37:30.872  1015  1028 I ActivityManager: Killing 6997:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
08-26 17:37:30.872  2018  2018 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 17:37:30.882  2018  2018 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 17:37:30.932  7359  7396 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 17:37:30.942  7408  7408 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-26 17:37:30.952  7409  7409 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 17:37:30.962  1015  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:30.972  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:30.972  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:30.972  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 17:37:31.012  7309  7324 I bt_vendor: bluetooth satus is on
,08-26 17:37:31.012  7309  7376 D bt_userial_mct: userial_open(port:0)
08-26 17:37:31.012  7309  7376 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 17:37:31.012  7309  7376 I bt_vendor: Done intiailizing UART
,08-26 17:37:31.012  7309  7376 I bt_vendor: Done intiailizing UART
,08-26 17:37:31.012  7309  7376 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,08-26 17:37:31.012  7309  7376 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-26 17:37:31.022  7309  7413 D bt_userial_mct: Entering userial_read_thread()
,08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_SAP
,08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 17:37:31.022  7309  7372 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 17:37:31.122  7309  7372 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 17:37:31.122  7309  7372 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4181ed1 
,08-26 17:37:31.122  7309  7372 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4181ed1 
,08-26 17:37:31.142  7309  7327 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 17:37:31.142  7309  7327 E bt-btif : Calling BTA_HhEnable
,08-26 17:37:31.142  7309  7327 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 17:37:31.142  7309  7327 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 17:37:31.142  7309  7327 E BluetoothServiceJni: populateRssiValuesNative
,08-26 17:37:31.142  7309  7327 I bluedroid: getModelRssiValues
08-26 17:37:31.142  7309  7327 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 17:37:31.142  7309  7327 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 17:37:31.152  1015  1015 D SettingsProvider: name = bluetooth_name
,08-26 17:37:31.152  7309  7327 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 17:37:31.152  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:31.162  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:31.162  7309  7327 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 17:37:31.162  7309  7327 D BluetoothAdapterProperties: Scan Mode:20
,08-26 17:37:31.162  7309  7327 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 17:37:31.162  7309  7327 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-26 17:37:31.162  7309  7327 E bt-btif : HC lpm_result_cb 1
08-26 17:37:31.162  7309  7327 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-26 17:37:31.162  7309  7327 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 17:37:31.162  7309  7327 E bt-btif : btif_sock_init: !vhci_init
,08-26 17:37:31.162  7309  7327 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 17:37:31.172  7309  7413 E bt_mct  : hci lib postload completed,
,08-26 17:37:31.172  7309  7327 D IOP_DB_BT: db_open: db_open : handle 3028094992l, read 13894 bytes onto local cache
,08-26 17:37:31.172  7309  7327 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-26 17:37:31.172  7309  7327 D IOP_DB_BT: db_query: result 1
,08-26 17:37:31.172  7309  7327 I         : iop_db_open: iop_db_open status 0
,08-26 17:37:31.172  7309  7327 D bte_conf: Device ID record 1 : primary
,08-26 17:37:31.172  7309  7327 D bte_conf:   vendorId            = 0075
,08-26 17:37:31.172  7309  7327 D bte_conf:   vendorIdSource      = 0001
08-26 17:37:31.172  7309  7327 D bte_conf:   product             = 0100
,08-26 17:37:31.172  7309  7327 D bte_conf:   version             = 0200
,08-26 17:37:31.172  7309  7327 D bte_conf:   clientExecutableURL = 
08-26 17:37:31.172  7309  7327 D bte_conf:   serviceDescription  = 
,08-26 17:37:31.182  7309  7327 D bte_conf:   documentationURL    = 
08-26 17:37:31.182  7309  7327 D bte_conf: bte_load_did_conf no section named DID2.,
,08-26 17:37:31.182  7309  7327 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 17:37:31.182  7309  7324 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 17:37:31.182  7309  7324 D BluetoothAdapterProperties: ScanMode =  20
,08-26 17:37:31.182  7309  7324 D BluetoothAdapterProperties: State =  11
,08-26 17:37:31.182  1015  1133 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 17:37:31.182  7309  7324 D BluetoothAdapterProperties: Setting state to 12
,08-26 17:37:31.182  7309  7324 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 17:37:31.192  7309  7327 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 17:37:31.192  7309  7327 D BluetoothAdapterProperties: Scan Mode:21
08-26 17:37:31.192  7309  7327 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 17:37:31.192  1015  1476 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 17:37:31.192  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 17:37:31.192  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:31.192  1015  1476 D SettingsProvider: selectionArgs: false
,08-26 17:37:31.192  1015  1476 D SettingsProvider: selectionArgs: 1002
,08-26 17:37:31.192  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 17:37:31.192  1015  1476 D SettingsProvider: ret = -1
,08-26 17:37:31.192  7309  7324 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 17:37:31.202  7309  7324 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 17:37:31.202  1015  3950 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:31.202  1015  3950 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.202  1015  3950 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:31.202  1015  3950 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:31.202  1015  3950 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.222  7309  7324 D BluetoothAdapterService: Autoconnection is available 
,08-26 17:37:31.222  7309  7324 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 17:37:31.222  7309  7324 D BluetoothAdapterService: starting service from this receiver
,08-26 17:37:31.222  1015  1450 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:31.222  1015  1450 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.222  1441  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 17:37:31.222  1015  1450 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:31.222  1441  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 17:37:31.222  1015  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:31.222  1015  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.222  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:31.222  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:31.222  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:31.222  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:31.222  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:31.222  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:31.222  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:31.222  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:31.222  7309  7324 I BluetoothAdapterState: Entering On State from state = 11
,08-26 17:37:31.222  1015  1045 D BluetoothPan: Binding service...
,08-26 17:37:31.222  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 17:37:31.222  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.232  1310  1333 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 17:37:31.232  7309  7309 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 17:37:31.232  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:31.232  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-26 17:37:31.232  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.242  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:31.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:31.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:31.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:31.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:31.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:31.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:31.242  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:31.242  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:31.242  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:31.242  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.242  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.242  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 17:37:31.242  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:31.242  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 17:37:31.242  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.242  1015  1015 D BluetoothA2dp: Proxy object connected
,08-26 17:37:31.252  1310  1322 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:31.252  1310  1322 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:31.252  1310  6858 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 17:37:31.252  7309  7309 I BluetoothPbapService: Handler(): got msg=1
08-26 17:37:31.252  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 17:37:31.252  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.252  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 17:37:31.252  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.252  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.252  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.252  1015  1454 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 17:37:31.252  7359  7368 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:31.252  7359  7368 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 17:37:31.252  1310  1333 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 17:37:31.252  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 17:37:31.252  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.252  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.252  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.252  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.262  1310  1322 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 17:37:31.262  7309  7417 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 17:37:31.262  1310  1322 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 17:37:31.262  1310  1310 D BluetoothPbap: Proxy object connected
08-26 17:37:31.262  1310  1310 D PbapServerProfile: Bluetooth service connected
08-26 17:37:31.262  1310  1310 D BluetoothInputDevice: Proxy object connected
08-26 17:37:31.262  1310  1310 D HidProfile: Bluetooth service connected
,08-26 17:37:31.262  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 17:37:31.262  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.262  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:31.262  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.262  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.262  1310  1322 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 17:37:31.262  1310  1322 D Bluetoothsap: Binding service...
,08-26 17:37:31.262  1310  1310 D BluetoothMap: Proxy object connected
,08-26 17:37:31.262  1310  1310 D MapProfile: Bluetooth service connected
08-26 17:37:31.262  1310  1310 D BluetoothMap: getConnectedDevices()
,08-26 17:37:31.262  7309  7417 D BluetoothSocket: bindListen(): myUserId = 0
08-26 17:37:31.262  7309  7417 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:31.262  1310  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 17:37:31.262  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 17:37:31.262  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.272  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.272  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.272  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.272  1310  1322 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-26 17:37:31.272  7309  7417 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-26 17:37:31.272  7309  7417 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 17:37:31.272  7309  7417 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 17:37:31.272  7309  7417 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f8198c3
,08-26 17:37:31.272  7309  7417 D BluetoothSocket: channel: 19
,08-26 17:37:31.272  7309  7417 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-26 17:37:31.272  1453  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:31.272  1310  1310 D BluetoothA2dp: Proxy object connected
,08-26 17:37:31.272  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 17:37:31.272  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:31.272  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.272  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.272  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.272  1453  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 17:37:31.272  1310  1310 D A2dpProfile: Bluetooth service connected
,08-26 17:37:31.272  7309  7318 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 17:37:31.272  6682  6690 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:31.272  6682  6690 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:31.282  1310  6858 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:31.282  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 17:37:31.282  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:31.282  1310  1310 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 17:37:31.282  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.282  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.282  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 17:37:31.282  1310  1310 D SapProfile: Bluetooth service connected
08-26 17:37:31.282  1310  1310 D Bluetoothsap: getConnectedDevices()
,08-26 17:37:31.282  1310  6858 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 17:37:31.282  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:31.282  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 17:37:31.282  1453  2444 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 17:37:31.282  1453  2444 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:31.282  1169  1201 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:31.282  1169  1201 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:31.282  1425  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:31.282  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 17:37:31.282  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:31.282  1310  1310 D HeadsetProfile: Bluetooth service connected
,08-26 17:37:31.282  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:31.282  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.282  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.292  1425  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 17:37:31.292  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:31.292  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 17:37:31.292  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 17:37:31.292  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:31.292  7309  7317 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:31.292  7309  7317 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:31.292  1425  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:31.292  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 17:37:31.292  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:31.292  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.292  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.292  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.292  1425  1443 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 17:37:31.292  1425  1435 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 17:37:31.292  1425  1435 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:31.292  1425  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:31.292  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 17:37:31.292  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:31.302  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.302  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.302  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.302  1425  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 17:37:31.302  1310  1333 D BluetoothPan: Binding service...
,08-26 17:37:31.302  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 17:37:31.302  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.302  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.302  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.302  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.302  2018  2026 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 17:37:31.302  2018  2026 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 17:37:31.302  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 17:37:31.302  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 17:37:31.302  1310  1310 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 17:37:31.302  1310  1310 D PanProfile: Bluetooth service connected
,08-26 17:37:31.302  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:31.302  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-26 17:37:31.302  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 17:37:31.312  1425  1425 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3fd2eb2f, true
,08-26 17:37:31.312  1169  1169 D BluetoothTile:  onBluetoothStateChange:
,08-26 17:37:31.312  1858  1858 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 17:37:31.312  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 17:37:31.312  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:31.312  1169  1169 D BluetoothTile:  getBluetoothState : 12
,08-26 17:37:31.312  1425  1425 D BluetoothHeadset: registerMessageListener
,08-26 17:37:31.322  1015  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:31.322  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.322  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:31.322  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:31.322  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:31.322  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:31.322  1310  1310 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:31.322  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:31.322  1015  1305 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 17:37:31.322  7309  7328 D HeadsetService: registerMessageListener
,08-26 17:37:31.332  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 17:37:31.332  7309  7328 D HeadsetService: registerMessageListener
,08-26 17:37:31.332  7309  7333 D HeadsetStateMachine: Disconnected process message: 70
,08-26 17:37:31.332  7309  7333 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@308ba540
,08-26 17:37:31.332  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 17:37:31.332  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 17:37:31.332  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 17:37:31.332  7309  7420 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 17:37:31.332  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:31.342  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:31.342  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 17:37:31.342  1310  1310 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 17:37:31.342  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 17:37:31.342  1310  1310 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 17:37:31.342  1310  1310 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 17:37:31.342  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 17:37:31.342  1310  1310 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 17:37:31.342  7309  7420 D BluetoothSocket: bindListen(): myUserId = 0
08-26 17:37:31.342  7309  7420 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:31.342  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:31.342  7309  7420 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-26 17:37:31.342  7309  7420 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 17:37:31.342  7309  7420 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 17:37:31.342  7309  7420 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@74f0c79
08-26 17:37:31.342  7309  7420 D BluetoothSocket: channel: 5
,08-26 17:37:31.342  7309  7333 D HeadsetStateMachine: Disconnected process message: 9
,08-26 17:37:31.342  7309  7333 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 17:37:31.352   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 17:37:31.352   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 17:37:31.352  1310  1310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 17:37:31.352   282   282 V voice   : voice_set_parameters: exit with code(-2)
08-26 17:37:31.352   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 17:37:31.352   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 17:37:31.352  1015  1305 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 17:37:31.352   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 17:37:31.352  1015  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-26 17:37:31.352   282   282 V audio_hw_primary: adev_set_parameters: exit
08-26 17:37:31.352  7309  7333 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 17:37:31.352  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.352  1015  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.352  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 17:37:31.362  1310  1310 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:31.362  1310  1310 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 17:37:31.372  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:31.372  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 17:37:31.372  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:31.382  7309  7309 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 17:37:31.382  1015  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:31.382  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.382  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.382  1015  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:31.382  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:31.392  2018  2018 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:31.392  1015  3282 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 17:37:31.392  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 17:37:31.402  1015  3282 W ActivityManager: userId = 0, bbcId = -10000,
08-26 17:37:31.402  1015  3282 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:31.402  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:31.402  2018  7427 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 17:37:31.402  2018  2018 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 17:37:31.412  1015  1454 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:31.412  1015  1454 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.412  1015  1454 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:31.412  1015  1027 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-26 17:37:31.412  1015  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:31.422  7309  7431 D BluetoothSocket: bindListen(): myUserId = 0
08-26 17:37:31.422  7309  7431 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:31.422  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:31.432  7309  7431 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-26 17:37:31.432  7309  7431 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 17:37:31.432  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:31.432  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:31.432  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:31.432  7309  7431 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 17:37:31.432  7309  7431 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e3b5d3b
08-26 17:37:31.432  7309  7431 D BluetoothSocket: channel: 12
08-26 17:37:31.432  7309  7431 I BtOppRfcommListener: Accept thread started.
,08-26 17:37:31.432  2018  7427 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 17:37:31.972  1015  2806 D SSRM:n  : SIOP:: AP = 370
,08-26 17:37:32.362   287   287 E SMD     : DCD OFF
,08-26 17:37:32.912  6682  6737 D BluetoothAdapter: disable()
,08-26 17:37:32.912  1015  1027 D SettingsProvider: name = bluetooth_on
,08-26 17:37:32.922  7309  7324 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 17:37:32.922  7309  7324 D BluetoothAdapterProperties: Setting state to 13
08-26 17:37:32.922  7309  7324 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 17:37:32.922  7309  7324 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 17:37:32.922  7309  7324 D BluetoothAdapterService: updateAdapterState state is 13
08-26 17:37:32.922  1015  1738 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:32.922  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 17:37:32.922  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:32.922  1015  1738 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:32.922  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:32.932  7309  7309 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 17:37:32.932  7309  7324 D BluetoothAdapterService: Autoconnection is available 
,08-26 17:37:32.932  7309  7324 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 17:37:32.932  7309  7324 D BluetoothAdapterService: terminating service from this receiver
,08-26 17:37:32.932  7309  7309 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c50dc58, channel: 19, state: LISTENING
08-26 17:37:32.932  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 17:37:32.932  7309  7309 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c50dc58, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f8198c3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35a0d1b1mSocket: android.net.LocalSocket@35436696 impl:android.net.LocalSocketImpl@24f89217 fd:FileDescriptor[74]
08-26 17:37:32.932  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:32.932  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:32.932  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:32.932  7309  7309 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35436696 impl:android.net.LocalSocketImpl@24f89217 fd:FileDescriptor[74]
,08-26 17:37:32.932  7309  7324 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 17:37:32.932  7309  7324 D BluetoothAdapterProperties: mDiscovering is false
,08-26 17:37:32.932  1015  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 17:37:32.942  7309  7324 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 17:37:32.942  1310  1310 D BluetoothPbap: Proxy object disconnected
08-26 17:37:32.942  1310  1310 D PbapServerProfile: Bluetooth service disconnected
,08-26 17:37:32.942  7309  7327 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 17:37:32.942  7309  7327 D BluetoothAdapterProperties: Scan Mode:20
,08-26 17:37:32.942  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:32.942  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-26 17:37:32.952  1169  1169 D BluetoothTile:  onBluetoothStateChange:
,08-26 17:37:32.952  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 17:37:32.952  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:32.962  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:32.962  1169  1169 D BluetoothTile:  getBluetoothState : 13
,08-26 17:37:32.962  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:32.962  1858  1858 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 17:37:32.962  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 17:37:32.962  1015  1469 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 17:37:32.962  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 17:37:32.972  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 17:37:32.972  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 17:37:32.972  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:32.972  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:32.972  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:32.972  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:32.972  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:32.972  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:32.972  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:32.972  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:32.972  1310  1310 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:32.972  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:32.972  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:32.972  7309  7324 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 17:37:32.972  7309  7324 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 17:37:32.972  7309  7324 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-26 17:37:32.972  1015  1484 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:32.972  7309  7324 E bt-btif : cmd socket is not created
,08-26 17:37:32.972  7309  7372 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 17:37:32.972  7309  7372 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 17:37:32.972  7309  7372 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 17:37:32.982  7309  7372 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:32.982  7309  7372 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:32.982  7309  7431 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 17:37:32.982  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 17:37:32.982  7309  7324 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 17:37:32.982  1310  1310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 17:37:32.982  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:32.982  1015  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:32.982  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:32.992  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:32.992  6682  6682 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 17:37:32.992  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:32.992  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:32.992  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 17:37:33.002  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 17:37:33.002  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:33.002  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:33.002  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 17:37:33.012  7309  7309 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@263fd7ed, channel: 5, state: LISTENING
,08-26 17:37:33.012  7309  7309 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@263fd7ed, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@74f0c79, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b475622mSocket: android.net.LocalSocket@29ea38b3 impl:android.net.LocalSocketImpl@372de70 fd:FileDescriptor[76]
,08-26 17:37:33.012  7309  7309 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29ea38b3 impl:android.net.LocalSocketImpl@372de70 fd:FileDescriptor[76]
,08-26 17:37:33.012  7309  7309 I BtOppRfcommListener: stopping Accept Thread
08-26 17:37:33.012  7309  7309 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@324f05e9, channel: 12, state: LISTENING
,08-26 17:37:33.012  7309  7309 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@324f05e9, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e3b5d3b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3aa8b26emSocket: android.net.LocalSocket@f45ad0f impl:android.net.LocalSocketImpl@23ff719c fd:FileDescriptor[80]
,08-26 17:37:33.012  7309  7309 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@f45ad0f impl:android.net.LocalSocketImpl@23ff719c fd:FileDescriptor[80]
,08-26 17:37:33.012  7309  7431 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 17:37:33.012  1310  1310 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:33.022  1310  1310 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 17:37:33.022  7309  7309 V BluetoothOppManager: cleanUp...
,08-26 17:37:33.022  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:33.032  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 17:37:33.042  2018  2018 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:33.052  2018  2018 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 17:37:33.182  7309  7372 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 17:37:33.182  7309  7372 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:33.182  7309  7372 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:33.182  7309  7372 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:33.182  7309  7372 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:33.182  7309  7372 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:33.182  7309  7372 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 17:37:33.182  7309  7372 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 17:37:33.182  7309  7372 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 17:37:33.182  7309  7372 W bt-btif : ag scb idx 1 not allocated
08-26 17:37:33.182  7309  7372 W bt-btif : ag scb idx 2 not allocated
08-26 17:37:33.182  7309  7372 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 17:37:33.182  7309  7413 I bt_userial_mct: exiting userial_read_thread
08-26 17:37:33.182  7309  7413 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 17:37:33.182  7309  7327 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 17:37:33.182  7309  7376 I bt_vendor: hw_epilog_process
08-26 17:37:33.182  7309  7327 D bt_userial_mct: userial_close
08-26 17:37:33.182  7309  7327 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 17:37:34.492  7309  7327 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 17:37:34.492  7309  7327 I bt_vendor: bluetooth satus is on
08-26 17:37:34.492  7309  7327 I bt_vendor: bt-vendor : resetting BT status
08-26 17:37:34.492  7309  7327 I bt_vendor: Starting hciattach daemon
08-26 17:37:34.492  7309  7327 I bt_vendor: try to set false
,08-26 17:37:34.492  7309  7327 I bt_vendor: Starting hciattach daemon
,08-26 17:37:34.492  7309  7327 I bt_vendor: try to set false
,08-26 17:37:34.492  7309  7327 I bt_vendor: cleanup
08-26 17:37:34.492  7309  7372 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 17:37:34.492  7309  7327 I GKI_LINUX: GKI_exit_task 0 done
08-26 17:37:34.492  7309  7327 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 17:37:34.492  7309  7324 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 17:37:34.492  7309  7324 D BtConfig.SecureMode: isSecureModeOn:false,
,08-26 17:37:34.492  7309  7324 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
08-26 17:37:34.492  1015  1305 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:34.492  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-26 17:37:34.492  1015  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-26 17:37:34.492  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 17:37:34.502  1015  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:34.492  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-26 17:37:34.502  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 17:37:34.502  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.502  1015  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:34.502  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:34.502  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 17:37:34.502  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 17:37:34.502  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 17:37:34.502  7309  7309 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:34.502  7309  7309 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 17:37:34.502  7309  7309 D BtGatt.GattService: stop()
08-26 17:37:34.502  7309  7309 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 17:37:34.502  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.502  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:34.502  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 17:37:34.502  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:34.512  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:34.502  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 17:37:34.512  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 17:37:34.502  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 17:37:34.502  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 17:37:34.512  7309  7309 D HeadsetService: Received stop request...Stopping profile...
08-26 17:37:34.512  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.512  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:34.512  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:34.512  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 17:37:34.512  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 17:37:34.512  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 17:37:34.512  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:34.512  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 17:37:34.512  1015  1738 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:34.512  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 17:37:34.512  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.512  1015  1738 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:34.512  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 17:37:34.512  1310  1310 D HeadsetProfile: Bluetooth service disconnected
,08-26 17:37:34.512  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 17:37:34.512  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 17:37:34.522  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 17:37:34.522  1015  1454 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:34.522  1015  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 17:37:34.522  1015  1454 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.522  1015  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:34.522  1015  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:34.532  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-26 17:37:34.532  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 17:37:34.532  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 17:37:34.532  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:34.532  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 17:37:34.532  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.532  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:34.532  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:34.532  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:34.532  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:34.532  7309  7324 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:34.532  1015  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:34.532  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 17:37:34.532  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.532  1015  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:34.532  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-26 17:37:34.542  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 17:37:34.542  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 17:37:34.542  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 17:37:34.542  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.542  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:34.542  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:34.542  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:34.542  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 17:37:34.542  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-26 17:37:34.542  7309  7324 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 17:37:34.542  7309  7324 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 17:37:34.542  7309  7324 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 17:37:34.542  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-26 17:37:34.542  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 17:37:34.542  7309  7309 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 17:37:34.552  1015  1217 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 17:37:34.542  7309  7309 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 17:37:34.542  7309  7309 D A2dpService: Received stop request...Stopping profile...
,08-26 17:37:34.542  7309  7353 D A2dpStateMachine: Exit Disconnected: -1
08-26 17:37:34.542  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:34.552  7309  7309 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 17:37:34.552  7309  7309 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 17:37:34.552  1310  1310 D BluetoothA2dp: Proxy object disconnected,
08-26 17:37:34.552  1310  1310 D A2dpProfile: Bluetooth service disconnected
08-26 17:37:34.552  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-26 17:37:34.552  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 17:37:34.552  7309  7309 D HidService: Received stop request...Stopping profile...
,08-26 17:37:34.552  7309  7309 D HidService: Stopping Bluetooth HidService
08-26 17:37:34.552  7309  7309 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 17:37:34.552  7309  7309 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 17:37:34.552  7309  7309 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 17:37:34.552  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:34.552  7309  7309 D HealthService: Received stop request...Stopping profile...
,08-26 17:37:34.552  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:34.552  1310  1310 D BluetoothInputDevice: Proxy object disconnected
08-26 17:37:34.552  1310  1310 D HidProfile: Bluetooth service disconnected
,08-26 17:37:34.552  7309  7309 D PanService: Received stop request...Stopping profile...
08-26 17:37:34.552  1015  1217 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 17:37:34.552  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
08-26 17:37:34.552  1015  1217 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 17:37:34.552  1015  1217 D BatteryService: stay LED for fully charged
08-26 17:37:34.562  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 17:37:34.562  1015  1015 I MotionRecognitionService: Plugged
,08-26 17:37:34.562  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 17:37:34.562  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 17:37:34.562  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 17:37:34.562  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 17:37:34.562  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 17:37:34.572  7309  7309 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 17:37:34.582  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 17:37:34.582  1310  1310 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 17:37:34.582  1310  1310 D PanProfile: Bluetooth service disconnected
,08-26 17:37:34.582  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:34.582  7309  7309 D SapService: Received stop request...Stopping profile...
,08-26 17:37:34.582  7309  7309 D SapService: Stopping Bluetooth SapService
,08-26 17:37:34.582  7309  7309 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a454bf1
,08-26 17:37:34.582  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 17:37:34.582  7309  7309 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 17:37:34.582  7309  7309 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 17:37:34.582  7309  7309 D BluetoothA2dp: Proxy object disconnected
08-26 17:37:34.582  7309  7309 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 17:37:34.592  7309  7354 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 17:37:34.592  1310  1310 D BluetoothMap: Proxy object disconnected
08-26 17:37:34.592  1310  1310 D MapProfile: Bluetooth service disconnected
08-26 17:37:34.592  1310  1310 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 17:37:34.592  1310  1310 D SapProfile: Bluetooth service disconnected
,08-26 17:37:34.592  7309  7309 I GKI_LINUX: GKI_exit_task 2 done
08-26 17:37:34.592  7309  7309 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 17:37:34.592  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 17:37:34.592  7309  7309 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:34.592  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 17:37:34.592  7309  7309 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:34.592  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 17:37:34.592  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 17:37:34.592  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 17:37:34.592  7309  7309 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:34.592  7309  7309 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:34.592  7309  7309 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 17:37:34.592  7309  7309 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 17:37:34.592  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 17:37:34.592  7309  7309 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:34.592  7309  7309 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:34.592  7309  7309 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 17:37:34.592  7309  7309 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 17:37:34.592  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 17:37:34.592  7309  7309 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 17:37:34.592  7309  7309 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 17:37:34.592  7309  7309 E BluetoothAdapterService(440749041): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-26 17:37:34.592  7309  7309 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 17:37:34.592  7309  7309 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 17:37:34.592  7309  7324 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-26 17:37:34.592  7309  7324 D BluetoothAdapterProperties: Setting state to 10
,08-26 17:37:34.592  7309  7324 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 17:37:34.592  7309  7324 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 17:37:34.592  7309  7324 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 17:37:34.592  7309  7324 D BluetoothAdapterService: Autoconnection is available 
,08-26 17:37:34.602  7309  7324 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 17:37:34.602  7309  7324 I BluetoothAdapterState: Entering OffState
08-26 17:37:34.602  1441  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:34.602  1441  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.602  1310  1322 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 17:37:34.602  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 17:37:34.602  1310  1333 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 17:37:34.602  1310  1333 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.602  1310  6858 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 17:37:34.602  7359  7367 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 17:37:34.602  7359  7367 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.602  1310  1322 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 17:37:34.602  1310  1333 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 17:37:34.602  1310  6858 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 17:37:34.602  1310  6858 D Bluetoothsap: Unbinding service...
,08-26 17:37:34.602  7309  7328 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 17:37:34.612  6682  6690 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 17:37:34.612  6682  6690 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.612  6682  6690 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-26 17:37:34.612  6682  6690 D BluetoothLeAdvertiser: Exit stop advertising
08-26 17:37:34.612  6682  6690 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-26 17:37:34.612  6682  6690 D BluetoothLeScanner: Exiting stopAllScan
,08-26 17:37:34.612  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 17:37:34.612  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.612  1453  1470 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 17:37:34.612  1453  1470 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.612  1169  1984 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 17:37:34.612  1169  1984 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.612  7309  7317 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 17:37:34.612  7309  7317 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.612  1425  7418 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 17:37:34.622  1425  7418 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.622  2018  2026 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 17:37:34.622  2018  2026 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 17:37:34.622  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 17:37:34.622  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 17:37:34.632  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:34.632  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-26 17:37:34.632  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 17:37:34.632  1169  1169 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:34.632  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 17:37:34.632  1169  1751 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
,08-26 17:37:34.642  7309  7327 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 17:37:34.642  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:34.642  1169  1169 D BluetoothTile:  getBluetoothState : 10
08-26 17:37:34.642  7309  7309 I GKI_LINUX: GKI_exit_task 1 done
08-26 17:37:34.642  7309  7309 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 17:37:34.642  1169  1751 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
,08-26 17:37:34.642  7309  7309 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 17:37:34.642  1169  1169 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:34.642  1169  1169 D BluetoothAdapter: 712253201: getState() :  mService = null. Returning STATE_OFF
,08-26 17:37:34.642  1015  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 17:37:34.642  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 17:37:34.642  1858  1858 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 17:37:34.642  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 17:37:34.642  2018  2153 D BluetoothAdapter: 496223201: getState() :  mService = null. Returning STATE_OFF
08-26 17:37:34.642  2018  2153 D BluetoothAdapter: 496223201: getState() :  mService = null. Returning STATE_OFF
,08-26 17:37:34.642  1310  1310 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:34.642  7309  7309 I art     : System.exit called, status: 0
,08-26 17:37:34.642  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:34.642  7309  7309 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 17:37:34.652  1015  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 17:37:34.652  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 17:37:34.652  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.652  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:34.652  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:34.652  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:34.652  1310  1310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 17:37:34.652  1015  1469 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 17:37:34.652  1015  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 17:37:34.652  1015  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:34.652  1015  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:34.652  1015  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 17:37:34.662  1310  1310 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:34.662  1310  1310 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 17:37:34.672  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:34.672  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 17:37:34.682  1015  1476 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 17:37:34.682  1015  1476 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 17:37:34.682  1015  1476 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-26 17:37:34.682  1015  1476 W BroadcastQueue: android.os.TransactionTooLargeException
08-26 17:37:34.682  1015  1476 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 17:37:34.682  1015  1476 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 17:37:34.682  1015  1476 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-26 17:37:34.682  1015  1476 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-26 17:37:34.682  1015  1476 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-26 17:37:34.682  1015  1476 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-26 17:37:34.682  1015  1476 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-26 17:37:34.682  1015  1476 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-26 17:37:34.682  1015  1476 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 17:37:34.682  1015  1476 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 17:37:34.692  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:34.692  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:34.692  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:34.692  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:34.702  7447  7447 E Zygote  : MountEmulatedStorage()
08-26 17:37:34.702  7447  7447 I libpersona: KNOX_SDCARD checking this for 1002
08-26 17:37:34.702  7447  7447 E Zygote  : v2
08-26 17:37:34.702  7447  7447 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:34.702  7447  7447 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:34.702  7447  7447 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:34.712  7447  7447 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 17:37:34.712  1015  1476 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7447 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 17:37:34.722  7447  7447 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:34.732  7447  7447 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:34.742  7447  7447 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 17:37:34.742  7447  7447 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 17:37:34.762  7447  7447 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding GattService
,08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding HeadsetService
,08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding A2dpService
08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding HidService
,08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding HealthService
08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding PanService
08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding SapService
,08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding SapClientService
,08-26 17:37:34.792  7447  7447 D BtSettings.ProfileConfig: Adding HidDevService
08-26 17:37:34.792  7447  7447 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 17:37:34.792  1015  1738 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 17:37:34.792  1015  1738 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.792  1015  1738 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.792  1015  1738 D SettingsProvider: selectionArgs: false
08-26 17:37:34.792  1015  1738 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.792  1015  1738 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.792  1015  1738 D SettingsProvider: ret = -1
,08-26 17:37:34.792  1015  1454 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 17:37:34.792  1015  1454 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.792  1015  1454 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.792  1015  1454 D SettingsProvider: selectionArgs: false
08-26 17:37:34.792  1015  1454 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.792  1015  1454 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.792  1015  1454 D SettingsProvider: ret = -1
,08-26 17:37:34.792  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 17:37:34.792  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.792  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.792  1015  1133 D SettingsProvider: selectionArgs: false
08-26 17:37:34.792  1015  1133 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.792  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 17:37:34.792  1015  1133 D SettingsProvider: ret = -1
08-26 17:37:34.792  1015  1305 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 17:37:34.792  1015  1305 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.792  1015  1305 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.792  1015  1305 D SettingsProvider: selectionArgs: false
,08-26 17:37:34.792  1015  1305 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.792  1015  1305 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.792  1015  1305 D SettingsProvider: ret = -1
,08-26 17:37:34.792  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 17:37:34.792  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.792  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.792  1015  1028 D SettingsProvider: selectionArgs: false
08-26 17:37:34.792  1015  1028 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.802  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.802  1015  1028 D SettingsProvider: ret = -1
,08-26 17:37:34.802  1015  1450 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
08-26 17:37:34.802  1015  1450 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.802  1015  1450 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.802  1015  1450 D SettingsProvider: selectionArgs: false
,08-26 17:37:34.802  1015  1450 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.802  1015  1450 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.802  1015  1450 D SettingsProvider: ret = -1
08-26 17:37:34.802  1015  3282 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 17:37:34.802  1015  3282 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.802  1015  3282 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.802  1015  3282 D SettingsProvider: selectionArgs: false
08-26 17:37:34.802  1015  3282 D SettingsProvider: selectionArgs: 1002
,08-26 17:37:34.802  1015  3282 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.802  1015  3282 D SettingsProvider: ret = -1
08-26 17:37:34.802  1015  1476 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 17:37:34.802  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 17:37:34.802  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 17:37:34.802  1015  1476 D SettingsProvider: selectionArgs: false
08-26 17:37:34.802  1015  1476 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.802  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.802  1015  1476 D SettingsProvider: ret = -1
08-26 17:37:34.802  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:34.802  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.802  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 17:37:34.802  1015  1027 D SettingsProvider: selectionArgs: false
08-26 17:37:34.802  1015  1027 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.802  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.802  1015  1027 D SettingsProvider: ret = -1
08-26 17:37:34.802  1015  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:34.802  1015  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-26 17:37:34.802  1015  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.802  1015  1217 D SettingsProvider: selectionArgs: false
08-26 17:37:34.802  1015  1217 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.802  1015  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.802  1015  1217 D SettingsProvider: ret = -1
08-26 17:37:34.802  1015  1469 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-26 17:37:34.802  1015  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.802  1015  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.802  1015  1469 D SettingsProvider: selectionArgs: false
08-26 17:37:34.802  1015  1469 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.802  1015  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.802  1015  1469 D SettingsProvider: ret = -1
08-26 17:37:34.802  1015  1484 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-26 17:37:34.802  1015  1484 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:34.802  1015  1484 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:34.802  1015  1484 D SettingsProvider: selectionArgs: false
08-26 17:37:34.802  1015  1484 D SettingsProvider: selectionArgs: 1002
08-26 17:37:34.802  1015  1484 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:34.802  1015  1484 D SettingsProvider: ret = -1
,08-26 17:37:34.812  2018  2018 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:34.822  1015  3950 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:34.822  1015  3950 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 17:37:34.822  1015  3950 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.822  1015  3950 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:34.822  1015  3950 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:34.822  2018  7463 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 17:37:34.832  2018  2018 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 17:37:34.832  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:34.832  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:34.832  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:34.832  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:34.842  2018  7463 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 17:37:35.172  1015  2863 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 17:37:35.372   287   287 E SMD     : DCD OFF,
,08-26 17:37:35.922  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:35.922  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:36.452  1015  1303 E Watchdog: !@Sync 4,
,08-26 17:37:36.542  1015  1048 I PowerManagerService: [PWL] Off : 75s ago
,08-26 17:37:36.542  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-26 17:37:36.542  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-26 17:37:36.542  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=15303)
,08-26 17:37:37.392   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 17:37:38.372   287   287 E SMD     : DCD OFF,
,08-26 17:37:38.392   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 17:37:38.922  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:38.922  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a856072 added. We now have 6 listener(s),
08-26 17:37:38.922  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:38.932  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:38.932  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3858fcc3 added. We now have 7 listener(s)
,08-26 17:37:38.932  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-26 17:37:38.932  6682  6737 I System.out: IsBluetoothEnabled,
,08-26 17:37:38.932  6682  6737 D BluetoothAdapter: disable(),
,08-26 17:37:38.932  1015  1450 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 17:37:38.942  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:38.942  6682  6737 D BluetoothAdapter: enable()
,08-26 17:37:38.942  1015  3282 W ActivityManager: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 17:37:38.942  1015  3282 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 17:37:38.942  1015  3282 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 17:37:38.942  1015  3282 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 17:37:38.942  1015  3282 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 17:37:38.942  1015  3282 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 17:37:38.942  1015  3282 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 17:37:38.942  1015  3282 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 17:37:38.942  1015  3282 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 17:37:38.942  1015  3282 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 17:37:38.952  1015  3282 D SettingsProvider: name = bluetooth_on,
,08-26 17:37:38.952  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 17:37:38.952  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 17:37:38.962  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-26 17:37:38.962  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 17:37:38.992  7447  7447 D BluetoothAdapterState: make
,08-26 17:37:38.992  7447  7447 I bluedroid: init
,08-26 17:37:38.992  7447  7468 I BluetoothAdapterState: Entering OffState,
,08-26 17:37:38.992  7447  7447 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 17:37:38.992  7447  7447 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 17:37:38.992  7447  7447 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 17:37:38.992  7447  7447 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 17:37:38.992  7447  7447 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-26 17:37:38.992  7447  7447 I bluedroid: get_profile_interface socket
08-26 17:37:38.992  7447  7447 I bluedroid: get_profile_interface map_client
08-26 17:37:38.992  7447  7471 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 17:37:39.002  7447  7447 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 17:37:39.002  7447  7471 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 17:37:39.002  7447  7471 E BluetoothServiceJni: populateRssiValuesNative
,08-26 17:37:39.002  7447  7471 I bluedroid: getModelRssiValues
08-26 17:37:39.002  7447  7471 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 17:37:39.002  7447  7471 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 17:37:39.002  7447  7447 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:39.002  1015  1015 D SettingsProvider: name = bluetooth_name
,08-26 17:37:39.002  7447  7471 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
08-26 17:37:39.002  1015  1454 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 17:37:39.002  1015  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.012  1015  1454 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:39.012  1015  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.012  1015  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.012  7447  7458 I bluedroid: config_hci_snoop_log
,08-26 17:37:39.012  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 17:37:39.012  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-26 17:37:39.012  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 17:37:39.012  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 17:37:39.012  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 17:37:39.022  7447  7447 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-26 17:37:39.032  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 17:37:39.032  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 17:37:39.032  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 17:37:39.032  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 17:37:39.032  7447  7468 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 17:37:39.032  7447  7468 D BluetoothAdapterProperties: Setting state to 11
08-26 17:37:39.032  7447  7468 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 17:37:39.032  7447  7468 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 17:37:39.032  7447  7468 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 17:37:39.032  7447  7468 D BluetoothAdapterService: Autoconnection is available 
08-26 17:37:39.032  7447  7468 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 17:37:39.042  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:39.042  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-26 17:37:39.042  7447  7468 D BluetoothSecureManager: getInstant: null
08-26 17:37:39.042  7447  7468 D BluetoothSecureManager: calling getMethod for getService
08-26 17:37:39.042  7447  7468 D BluetoothSecureManager: calling getService
,08-26 17:37:39.042  7447  7468 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2ba788dc
,08-26 17:37:39.042  1015  1484 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 17:37:39.042  1015  1484 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-26 17:37:39.042  7447  7468 D BtConfig.SecureMode: isSecureModeOn:false,
08-26 17:37:39.042  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 17:37:39.042  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 17:37:39.042  1169  1169 D BluetoothTile:  getBluetoothState : 11
,08-26 17:37:39.042  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:39.042  7447  7468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 17:37:39.042  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 17:37:39.042  1858  1858 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0,
,08-26 17:37:39.052  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
08-26 17:37:39.052  7447  7468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-26 17:37:39.052  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-26 17:37:39.052  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 17:37:39.052  1310  1310 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:39.052  7447  7468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 17:37:39.052  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 17:37:39.052  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:39.052  7447  7468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-26 17:37:39.052  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 17:37:39.052  7447  7468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 17:37:39.052  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 17:37:39.052  7447  7468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 17:37:39.052  1015  1305 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 17:37:39.052  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:39.052  7447  7468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 17:37:39.052  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 17:37:39.052  7447  7468 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 17:37:39.052  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 17:37:39.062  1015  1133 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 17:37:39.062  1015  1738 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:39.062  7447  7468 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:39.062  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 17:37:39.062  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 17:37:39.062  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:39.062  1015  1738 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:39.062  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:39.062  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 17:37:39.062  7447  7468 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:39.062  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 17:37:39.062  7447  7468 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 17:37:39.062  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 17:37:39.062  7447  7468 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 17:37:39.062  7447  7468 D BluetoothBondStateMachine: make
,08-26 17:37:39.062  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 17:37:39.062  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 17:37:39.062  7447  7468 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 17:37:39.062  7447  7475 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 17:37:39.062  1015  1305 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:39.062  1015  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.072  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:39.072  1015  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.072  1310  1310 D BluetoothNotiBroadcastReceiver: onReceive
08-26 17:37:39.072  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.072  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 17:37:39.072  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 17:37:39.072  7447  7468 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 17:37:39.072  7447  7447 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 17:37:39.072  7447  7447 D BtGatt.GattService: Received start request. Starting profile...
08-26 17:37:39.072  7447  7447 D BtGatt.GattService: start()
08-26 17:37:39.072  7447  7447 D BtGatt.GattService: start()
08-26 17:37:39.072  7447  7447 I bluedroid: get_profile_interface gatt
08-26 17:37:39.072  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
08-26 17:37:39.072  7447  7447 D BtGatt.AdvertiseManager: advertise manager created
,08-26 17:37:39.072  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 17:37:39.072  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 17:37:39.082  1015  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:39.082  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.082  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:39.082  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.082  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.082  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 17:37:39.082  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 17:37:39.082  7447  7468 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 17:37:39.092  1015  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:39.092  1015  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.092  1015  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:39.092  1015  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.092  1015  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.092  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 17:37:39.092  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 17:37:39.092  7447  7468 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 17:37:39.102  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:39.102  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 17:37:39.102  7447  7447 D BtGatt.GattService: mStartError = false
08-26 17:37:39.102  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
,08-26 17:37:39.102  7447  7447 D HeadsetService: Received start request. Starting profile...
,08-26 17:37:39.102  7447  7447 D HeadsetService: start()
,08-26 17:37:39.102  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:39.102  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.102  7447  7447 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 17:37:39.102  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 17:37:39.102  7447  7447 D HeadsetStateMachine: make
,08-26 17:37:39.112  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 17:37:39.112  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 17:37:39.112  7447  7468 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 17:37:39.112  7447  7447 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 17:37:39.112  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:39.112  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.122  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:39.122  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:39.122  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.122  1015  1217 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 17:37:39.122  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 17:37:39.122  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 17:37:39.122  7447  7468 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 17:37:39.122  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.122  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:39.122  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.122  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 17:37:39.132  1015  1454 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 17:37:39.132  1015  1454 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.132  1015  1454 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:39.132  1015  1454 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.132  1015  1454 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 17:37:39.132  7447  7447 I bluedroid: get_profile_interface handsfree
,08-26 17:37:39.132  1015  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:39.132  1015  1469 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.132  1015  1469 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:39.132  1015  1469 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.132  1015  1469 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.132  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:39.132  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 17:37:39.132  7447  7468 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 17:37:39.142  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:39.142  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.142  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:39.142  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.142  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.142  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 17:37:39.142  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 17:37:39.142  7447  7468 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 17:37:39.142  1015  3282 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 17:37:39.142  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 17:37:39.142  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:39.142  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.142  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.152  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 17:37:39.152  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:39.152  7447  7468 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 17:37:39.152  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:39.152  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:39.152  7447  7468 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 17:37:39.152  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-26 17:37:39.152  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 17:37:39.152  7447  7468 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 17:37:39.152  7447  7468 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService,
08-26 17:37:39.152  7447  7468 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 17:37:39.152  7447  7468 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 17:37:39.152  7447  7468 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 17:37:39.152  7447  7447 I DualScoManager: Instantiating Dual Sco Manager
,08-26 17:37:39.152  7447  7447 I DualScoManager: Set HeadsetServiceHelper
,08-26 17:37:39.152  7447  7447 D BluetoothAtMessage: createCMTIContentObservers
,08-26 17:37:39.152  1015  1305 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-26 17:37:39.152  1015  1305 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 17:37:39.152  1015  1305 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:39.152  1015  1305 D SettingsProvider: selectionArgs: false
08-26 17:37:39.152  1015  1305 D SettingsProvider: selectionArgs: 1002
08-26 17:37:39.152  1015  1305 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 17:37:39.152  1015  1305 D SettingsProvider: ret = -1
,08-26 17:37:39.162  7447  7478 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 17:37:39.162  7447  7447 D HeadsetService: mStartError = false
08-26 17:37:39.162  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
,08-26 17:37:39.162  7447  7447 D A2dpService: Received start request. Starting profile...
08-26 17:37:39.162  7447  7447 D A2dpService: start()
,08-26 17:37:39.162  7447  7447 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 17:37:39.162  7447  7447 I bluedroid: get_profile_interface avrcp
,08-26 17:37:39.162  7447  7478 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 17:37:39.162  7447  7478 D HeadsetStateMachine: map size, before remove : 0
08-26 17:37:39.162  7447  7478 D HeadsetStateMachine: map size, after remove: 0
,08-26 17:37:39.172  2018  2018 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:39.172  2018  2018 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 17:37:39.182  7447  7447 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 17:37:39.182  7447  7447 D Avrcp   : Initialize Media Controller
,08-26 17:37:39.182  7447  7447 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 17:37:39.182  7447  7447 E Avrcp   : getActiveSessions
08-26 17:37:39.182  7447  7447 D Avrcp   : pick active media Controller
08-26 17:37:39.182  7447  7447 D Avrcp   : Get the active Media Controller 
,08-26 17:37:39.202  7447  7447 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 17:37:39.202  7447  7482 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 17:37:39.202  7447  7447 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 17:37:39.202  7447  7447 D A2dpStateMachine: make
,08-26 17:37:39.212  7447  7447 I bluedroid: get_profile_interface a2dp
,08-26 17:37:39.212  7447  7484 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 17:37:39.212  7447  7482 D BluetoothMediaBrowser: no now playing list
08-26 17:37:39.212  7447  7447 E bt-btif : warning : media task started media_task_refcnt 1 
08-26 17:37:39.212  7447  7482 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 17:37:39.212  7447  7447 D A2dpService: mStartError = false
,08-26 17:37:39.212  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
,08-26 17:37:39.212  7447  7447 E BluetoothAdapterService(981022295): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 17:37:39.212  7447  7483 D A2dpStateMachine: Enter Disconnected: -2
08-26 17:37:39.212  7447  7447 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 17:37:39.212  7447  7447 D HidService: Received start request. Starting profile...
,08-26 17:37:39.212  7447  7447 D HidService: start()
,08-26 17:37:39.212  7447  7447 I bluedroid: get_profile_interface hidhost
08-26 17:37:39.212  7447  7447 D HidService: setHidService(): set to: null
,08-26 17:37:39.212  7447  7447 D HidService: mStartError = false
08-26 17:37:39.212  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
,08-26 17:37:39.222  7447  7447 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 17:37:39.222  7447  7447 D HealthService: Received start request. Starting profile...,
08-26 17:37:39.222  7447  7447 D HealthService: start()
,08-26 17:37:39.222  7447  7447 I bluedroid: get_profile_interface health
08-26 17:37:39.222  7447  7447 D HealthService: mStartError = false
08-26 17:37:39.222  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
,08-26 17:37:39.222  7447  7447 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 17:37:39.222  1425  7418 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 17:37:39.222  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 17:37:39.222  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 17:37:39.222  1425  7418 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 17:37:39.222  7447  7447 D HeadsetStateMachine: Proxy object connected
,08-26 17:37:39.222  7447  7447 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 17:37:39.232  7447  7447 D PanService: Received start request. Starting profile...
,08-26 17:37:39.232  7447  7447 D PanService: start()
08-26 17:37:39.232  7447  7447 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 17:37:39.232  7447  7447 I bluedroid: get_profile_interface pan
,08-26 17:37:39.232  7447  7447 D PanService: mStartError = false
,08-26 17:37:39.232  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
,08-26 17:37:39.232  7447  7447 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 17:37:39.232  7447  7478 D HeadsetStateMachine: Disconnected process message: 11,
,08-26 17:37:39.232  7447  7447 D BluetoothMapService: Received start request. Starting profile...
,08-26 17:37:39.232  7447  7447 D BluetoothMapService: start()
,08-26 17:37:39.242  7447  7447 D BluetoothMapService: mStartError = false
,08-26 17:37:39.242  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
,08-26 17:37:39.242  7447  7447 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 17:37:39.242  7447  7447 D HeadsetPhoneState: Signal level : previous=0 curr=0,
08-26 17:37:39.242  7447  7478 D HeadsetStateMachine: Disconnected process message: 18
08-26 17:37:39.242  7447  7447 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 17:37:39.242  7447  7447 D SapService: Received start request. Starting profile...
08-26 17:37:39.242  7447  7447 D SapService: start()
08-26 17:37:39.242  7447  7447 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 17:37:39.242  7447  7447 I bluedroid: get_profile_interface sap
08-26 17:37:39.242  7447  7447 D SapService: mStartError = false
08-26 17:37:39.242  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
08-26 17:37:39.242  7447  7447 E BluetoothAdapterService(981022295): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-26 17:37:39.242  7447  7447 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 17:37:39.242  7447  7447 D BluetoothA2dp: Proxy object connected
08-26 17:37:39.242  7447  7447 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-26 17:37:39.242  7447  7478 D HeadsetStateMachine: Disconnected process message: 10
08-26 17:37:39.242  7447  7478 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 17:37:39.242  7447  7478 D HeadsetStateMachine: Disconnected process message: 11
,08-26 17:37:39.242  7447  7447 E BluetoothAdapterService(981022295): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 17:37:39.242  7447  7447 E BluetoothAdapterService(981022295): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 17:37:39.242  7447  7447 E BluetoothAdapterService(981022295): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 17:37:39.242  7447  7447 E BluetoothAdapterService(981022295): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 17:37:39.262  7447  7447 E BluetoothAdapterService(981022295): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 17:37:39.262  7447  7447 E BluetoothAdapterService(981022295): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 17:37:39.272  7447  7468 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 17:37:39.272  7447  7468 I bluedroid: enable
,08-26 17:37:39.272  7447  7468 I bt_hci_bdroid: init
,08-26 17:37:39.272  7447  7489 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 17:37:39.272  7447  7468 I bt_vendor: bt-vendor : init
08-26 17:37:39.272  7447  7468 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 17:37:39.272  7447  7468 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 17:37:39.272  7447  7468 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 17:37:39.272  7447  7468 D bt_userial_mct: userial_init
,08-26 17:37:39.272  7447  7468 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 17:37:39.272  7447  7468 I bt_vendor: Starting hciattach daemon
08-26 17:37:39.272  7447  7468 I bt_vendor: try to set false
,08-26 17:37:39.282  7447  7468 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 17:37:39.282  7447  7468 I bt_vendor: Starting hciattach daemon
08-26 17:37:39.282  7447  7468 I bt_vendor: try to set true
,08-26 17:37:39.292  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-26 17:37:39.332  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 17:37:39.342  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 17:37:39.362  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 17:37:39.362  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-26 17:37:39.372  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 17:37:39.382  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 17:37:39.392   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 17:37:39.582  7509  7509 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-26 17:37:39.592  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 17:37:39.632  7447  7468 I bt_vendor: bluetooth satus is on,
08-26 17:37:39.632  7447  7491 D bt_userial_mct: userial_open(port:0)
08-26 17:37:39.632  7447  7491 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 17:37:39.632  7447  7491 I bt_vendor: Done intiailizing UART,
,08-26 17:37:39.642  7447  7491 I bt_vendor: Done intiailizing UART,
08-26 17:37:39.642  7447  7491 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 17:37:39.642  7447  7491 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
08-26 17:37:39.642  7447  7512 D bt_userial_mct: Entering userial_read_thread()
,08-26 17:37:39.642  7447  7489 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 17:37:39.652  7447  7489 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 17:37:39.742  7447  7489 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 17:37:39.742  7447  7489 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4187ed1 
,08-26 17:37:39.742  7447  7489 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4187ed1 
,08-26 17:37:39.762  7447  7471 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 17:37:39.762  7447  7471 E bt-btif : Calling BTA_HhEnable
,08-26 17:37:39.772  7447  7471 E bt-btif : BTM_SEC_REG[3]: id 37, is_orig 0, psm 0x0019, proto_id 7
,08-26 17:37:39.772  7447  7471 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 17:37:39.772  7447  7471 E BluetoothServiceJni: populateRssiValuesNative
,08-26 17:37:39.772  7447  7471 I bluedroid: getModelRssiValues
,08-26 17:37:39.772  7447  7471 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 17:37:39.772  7447  7471 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 17:37:39.772  1015  1015 D SettingsProvider: name = bluetooth_name
,08-26 17:37:39.772  7447  7471 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 17:37:39.782  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:39.782  7447  7471 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 17:37:39.782  7447  7471 D BluetoothAdapterProperties: Scan Mode:20
,08-26 17:37:39.782  7447  7471 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 17:37:39.782  7447  7471 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-26 17:37:39.782  7447  7471 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-26 17:37:39.782  7447  7471 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-26 17:37:39.782  7447  7471 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 17:37:39.782  7447  7471 E bt-btif : btif_sock_init: !vhci_init
08-26 17:37:39.782  7447  7471 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-26 17:37:39.782  7447  7471 D IOP_DB_BT: db_open: db_open : handle 3027988496l, read 13894 bytes onto local cache
08-26 17:37:39.782  7447  7471 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-26 17:37:39.782  7447  7471 D IOP_DB_BT: db_query: result 1
08-26 17:37:39.782  7447  7471 I         : iop_db_open: iop_db_open status 0
,08-26 17:37:39.782  7447  7471 D bte_conf: Device ID record 1 : primary
08-26 17:37:39.782  7447  7471 D bte_conf:   vendorId            = 0075
08-26 17:37:39.782  7447  7471 D bte_conf:   vendorIdSource      = 0001
08-26 17:37:39.782  7447  7471 D bte_conf:   product             = 0100
08-26 17:37:39.782  7447  7471 D bte_conf:   version             = 0200
08-26 17:37:39.782  7447  7471 D bte_conf:   clientExecutableURL = 
08-26 17:37:39.782  7447  7471 D bte_conf:   serviceDescription  = 
08-26 17:37:39.782  7447  7471 D bte_conf:   documentationURL    = 
08-26 17:37:39.782  7447  7471 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 17:37:39.782  7447  7471 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 17:37:39.782  7447  7468 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 17:37:39.782  7447  7468 D BluetoothAdapterProperties: ScanMode =  20
08-26 17:37:39.782  7447  7468 D BluetoothAdapterProperties: State =  11
,08-26 17:37:39.792  1015  1484 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
08-26 17:37:39.792  7447  7468 D BluetoothAdapterProperties: Setting state to 12
08-26 17:37:39.792  7447  7468 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 17:37:39.792  7447  7471 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 17:37:39.792  7447  7471 D BluetoothAdapterProperties: Scan Mode:21
08-26 17:37:39.792  7447  7471 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 17:37:39.792  1015  1476 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-26 17:37:39.792  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:39.792  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:39.792  1015  1476 D SettingsProvider: selectionArgs: false
08-26 17:37:39.792  1015  1476 D SettingsProvider: selectionArgs: 1002
08-26 17:37:39.792  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 17:37:39.792  1015  1476 D SettingsProvider: ret = -1
,08-26 17:37:39.792  7447  7468 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 17:37:39.792  7447  7468 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 17:37:39.792  7447  7512 E bt_mct  : hci lib postload completed
,08-26 17:37:39.792  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:39.792  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.802  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:39.802  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 17:37:39.802  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.802  7447  7468 D BluetoothAdapterService: Autoconnection is available 
,08-26 17:37:39.802  7447  7468 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 17:37:39.802  7447  7468 D BluetoothAdapterService: starting service from this receiver
,08-26 17:37:39.812  1015  1738 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 17:37:39.812  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.812  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:39.812  1015  1738 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.812  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.812  1441  1452 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 17:37:39.812  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:39.812  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:39.812  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:39.812  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:39.812  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:39.812  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:39.812  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:39.812  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:39.812  1441  1452 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 17:37:39.812  1015  1045 D BluetoothPan: Binding service...
08-26 17:37:39.812  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 17:37:39.812  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 17:37:39.812  7447  7460 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 17:37:39.822  7447  7468 I BluetoothAdapterState: Entering On State from state = 11
,08-26 17:37:39.822  1310  1333 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 17:37:39.832  7447  7447 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 17:37:39.842  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:39.962  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:39.962  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:39.962  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:39.962  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 17:37:39.962  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:39.962  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:39.962  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:39.962  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:39.962  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:39.962  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 17:37:39.962  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1cb93940 added. We now have 8 listener(s)
,08-26 17:37:39.962  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:39.972  1015  1450 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 17:37:39.972  1015  1450 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 17:37:39.972  1015  1450 D SecContentProvider2: mCursor = null
,08-26 17:37:39.972  1015  1450 D WifiService: setWifiEnabled: false pid=6682, uid=10171
,08-26 17:37:39.982  1015  1450 D SettingsProvider: name = wifi_on
,08-26 17:37:39.982  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:39.982  1015  1133 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 17:37:39.982  1015  1133 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 17:37:39.982  1015  1133 D SecContentProvider2: mCursor = null
,08-26 17:37:39.982  1015  1133 D WifiService: setWifiEnabled: true pid=6682, uid=10171
,08-26 17:37:39.982  1015  1133 W ActivityManager: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 17:37:39.982  1015  1133 W WifiService: Failed getting userId using ActivityManagerNative
08-26 17:37:39.982  1015  1133 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6682, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 17:37:39.982  1015  1133 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 17:37:39.982  1015  1133 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 17:37:39.982  1015  1133 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 17:37:39.982  1015  1133 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 17:37:39.982  1015  1133 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 17:37:39.982  1015  1133 D SettingsProvider: name = wifi_on
,08-26 17:37:39.992  1015  1045 I art     : Explicit concurrent mark sweep GC freed 22602(1332KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 5.519ms total 166.094ms
08-26 17:37:39.992  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 17:37:39.992  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.992  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:39.992  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:39.992  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:39.992  7447  7460 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:39.992  7447  7460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:39.992  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 17:37:39.992  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 17:37:39.992  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 17:37:39.992  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 17:37:39.992  1310  6858 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:39.992  1015  1015 D BluetoothA2dp: Proxy object connected
08-26 17:37:39.992  1310  6858 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:39.992  1310  1322 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 17:37:39.992  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 17:37:40.002  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 17:37:40.002  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 17:37:40.002  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.002  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.002  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.002  7447  7447 I BluetoothPbapService: Handler(): got msg=1
,08-26 17:37:40.012  7359  7368 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:40.012  7359  7368 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:40.012  1310  6858 D BluetoothMap: onBluetoothStateChange: up=true
08-26 17:37:40.012  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 17:37:40.012  1015  1450 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 17:37:40.012  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 17:37:40.012  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 17:37:40.012  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.012  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.012  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.012  1310  1310 D BluetoothPbap: Proxy object connected
08-26 17:37:40.012  1310  1310 D PbapServerProfile: Bluetooth service connected
,08-26 17:37:40.022  1310  6858 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 17:37:40.022  1310  1310 D BluetoothInputDevice: Proxy object connected
08-26 17:37:40.022  1310  1310 D HidProfile: Bluetooth service connected
,08-26 17:37:40.022  1310  6858 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:40.022  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 17:37:40.022  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 17:37:40.022  7447  7519 V BluetoothPbapService: PBAP Service initSocket try: 0
08-26 17:37:40.022  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.022  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.022  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.022  1310  1322 D Bluetoothsap: onBluetoothStateChange: up=true
,08-26 17:37:40.022  1310  1322 D Bluetoothsap: Binding service...
,08-26 17:37:40.022  1310  1310 D BluetoothMap: Proxy object connected
08-26 17:37:40.022  1310  1310 D MapProfile: Bluetooth service connected
08-26 17:37:40.022  1310  1310 D BluetoothMap: getConnectedDevices()
,08-26 17:37:40.022  1310  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 17:37:40.022  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-26 17:37:40.022  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 17:37:40.022  7447  7519 D BluetoothSocket: bindListen(): myUserId = 0
08-26 17:37:40.022  7447  7519 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:40.022  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.022  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.022  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.022  1310  1322 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 17:37:40.032  1453  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:40.032  7447  7519 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-26 17:37:40.032  7447  7519 D BluetoothSocket: bindListen(), new LocalSocket 
,08-26 17:37:40.032  7447  7519 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 17:37:40.032  7447  7519 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@74f0c79
08-26 17:37:40.032  7447  7519 D BluetoothSocket: channel: 19
08-26 17:37:40.032  7447  7519 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-26 17:37:40.032  1310  1310 D BluetoothA2dp: Proxy object connected
,08-26 17:37:40.032  1310  1310 D A2dpProfile: Bluetooth service connected
08-26 17:37:40.032  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 17:37:40.032  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:40.032  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.032  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.032  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.032  1453  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 17:37:40.032  6682  6691 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:40.032  6682  6691 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:40.032  1310  6858 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:40.032  1310  1310 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 17:37:40.042  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 17:37:40.042  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:40.042  1310  1310 D SapProfile: Bluetooth service connected
08-26 17:37:40.042  1310  1310 D Bluetoothsap: getConnectedDevices()
08-26 17:37:40.042  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.042  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.042  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.042  1310  6858 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 17:37:40.042  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:40.042  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:40.042  1453  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 17:37:40.042  1453  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 17:37:40.042  1310  1310 D HeadsetProfile: Bluetooth service connected
08-26 17:37:40.042  1169  1201 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 17:37:40.042  1169  1201 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:40.042  1425  1435 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:40.042  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 17:37:40.042  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:40.042  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:40.042  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.042  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.042  1425  1435 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 17:37:40.052  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:40.052  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 17:37:40.052  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 17:37:40.052  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 17:37:40.052  1425  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:40.052  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 17:37:40.052  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:40.052  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:40.052  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.052  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.052  1425  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 17:37:40.052  1425  1435 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 17:37:40.052  1425  1435 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:40.052  1425  7418 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 17:37:40.062  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 17:37:40.062  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 17:37:40.062  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:40.062  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.062  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.062  1425  7418 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 17:37:40.062  1310  1333 D BluetoothPan: Binding service...
,08-26 17:37:40.062  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 17:37:40.062  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 17:37:40.062  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:40.062  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.062  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.062  1310  1310 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 17:37:40.062  1310  1310 D PanProfile: Bluetooth service connected
08-26 17:37:40.062  2018  2150 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 17:37:40.062  2018  2150 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 17:37:40.072  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 17:37:40.072  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 17:37:40.072  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:40.072  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-26 17:37:40.072  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 17:37:40.072  1425  1425 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@5d0a53c, true
,08-26 17:37:40.072  1425  1425 D BluetoothHeadset: registerMessageListener
,08-26 17:37:40.072  1169  1169 D BluetoothTile:  onBluetoothStateChange:
,08-26 17:37:40.072  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 17:37:40.082  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:40.082  1169  1169 D BluetoothTile:  getBluetoothState : 12
,08-26 17:37:40.082  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:40.082  1858  1858 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 17:37:40.082  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:40.082  1015  1738 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 17:37:40.082  1015  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:40.092  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 17:37:40.092  7447  7472 D HeadsetService: registerMessageListener
,08-26 17:37:40.092  7447  7472 D HeadsetService: registerMessageListener
,08-26 17:37:40.092  7447  7478 D HeadsetStateMachine: Disconnected process message: 70
,08-26 17:37:40.092  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 17:37:40.092  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 17:37:40.092  7447  7478 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@110b5dbe
,08-26 17:37:40.092  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:40.092  1015  3950 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 17:37:40.092  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 17:37:40.092  1310  1310 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:40.092  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.092  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:40.092  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:40.102  1169  1751 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 17:37:40.102  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-26 17:37:40.102  7447  7521 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 17:37:40.102  1310  1310 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-26 17:37:40.102  1310  1310 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 17:37:40.102  1310  1310 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 17:37:40.102  1310  1310 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-26 17:37:40.102  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-26 17:37:40.102  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 17:37:40.102  7447  7521 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 17:37:40.112  7447  7478 D HeadsetStateMachine: Disconnected process message: 9
08-26 17:37:40.112  7447  7521 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:40.112  7447  7478 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 17:37:40.112  7447  7521 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-26 17:37:40.112  7447  7521 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 17:37:40.112  7447  7521 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 17:37:40.112  7447  7521 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@375afe1f
,08-26 17:37:40.112  7447  7521 D BluetoothSocket: channel: 5
,08-26 17:37:40.112  1310  1310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 17:37:40.112  1015  1450 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 17:37:40.112  1015  1450 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 17:37:40.112  1015  1450 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.112  1015  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.112  1015  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 17:37:40.122   282   698 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 17:37:40.122   282   698 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 17:37:40.122   282   698 V voice   : voice_set_parameters: exit with code(-2)
08-26 17:37:40.122   282   698 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 17:37:40.122   282   698 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 17:37:40.122   282   698 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 17:37:40.122   282   698 V audio_hw_primary: adev_set_parameters: exit
,08-26 17:37:40.122  7447  7478 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 17:37:40.132  1310  1310 D DockEventReceiver: finishStartingService: stopping service
,08-26 17:37:40.132  1310  1310 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 17:37:40.132  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 17:37:40.132  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 17:37:40.142  7447  7447 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
,08-26 17:37:40.142  7447  7447 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 17:37:40.142  1015  1738 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 17:37:40.142  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 17:37:40.142  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:40.142  1015  1738 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.142  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 17:37:40.172  1015  1738 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 17:37:40.172  2018  2018 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 17:37:40.172  1015  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 17:37:40.172  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 17:37:40.172  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.172  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:40.172  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:40.182  7447  7530 D BluetoothSocket: bindListen(): myUserId = 0
08-26 17:37:40.182  7447  7530 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 17:37:40.182  2018  7531 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 17:37:40.182  2018  2018 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 17:37:40.182  7447  7530 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-26 17:37:40.182  7447  7530 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 17:37:40.182  7447  7530 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 17:37:40.182  7447  7530 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e3b5d3b
,08-26 17:37:40.192  7447  7530 D BluetoothSocket: channel: 12
,08-26 17:37:40.192  7447  7530 I BtOppRfcommListener: Accept thread started.
,08-26 17:37:40.192  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:40.192  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:40.192  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 17:37:40.202  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:40.212  1015  3950 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 17:37:40.212  1015  3950 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.212  1015  3950 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 17:37:40.212  1015  3950 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 17:37:40.222  2018  7531 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 17:37:40.352  1015  1043 D Tethering: interfaceAdded wlan0
,08-26 17:37:40.352  1015  1128 E Tethering: No numeric data
,08-26 17:37:40.352  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-26 17:37:40.352  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:40.362  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:40.362  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 17:37:40.362  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 17:37:40.362  1169  1169 D HotspotTile: updateTetherState():false, false
,08-26 17:37:40.362  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 17:37:40.362  1015  1128 D Tethering: clearTetheredNotification()
08-26 17:37:40.362  1015  1122 V NetworkStats: performPollLocked() took 10ms
08-26 17:37:40.362  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:40.372  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 17:37:40.372  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:40.372  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:40.372  1015  1128 D Tethering: InitialState.processMessage what=4
,08-26 17:37:40.372  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:40.372  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:40.372  1015  1128 E Tethering: No numeric data
,08-26 17:37:40.372  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 17:37:40.372  1015  1128 D Tethering: clearTetheredNotification()
,08-26 17:37:40.372  1015  1043 D Tethering: interfaceAdded p2p0,
08-26 17:37:40.382  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 17:37:40.382  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 17:37:40.382  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 17:37:40.382  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 17:37:40.382  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-26 17:37:40.382  1169  1169 D HotspotTile: updateTetherState():false, false
08-26 17:37:40.382  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-26 17:37:40.382  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:40.392  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:40.392  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 17:37:40.392   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 17:37:40.392  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:40.392  1015  1122 V NetworkStats: performPollLocked() took 9ms
08-26 17:37:40.402   277  1014 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 17:37:40.402  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:40.402   277  1014 D SoftapController: Softap fwReload - Ok
08-26 17:37:40.402  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:40.402   277  1014 D CommandListener: Setting iface cfg,
08-26 17:37:40.402   277  1014 D CommandListener: Trying to bring down wlan0
08-26 17:37:40.402   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-26 17:37:40.412  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 17:37:40.412  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-26 17:37:40.412  1015  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory,
,08-26 17:37:40.422  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:40.422  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 17:37:40.422  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:40.422  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:40.422  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:40.422  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:40.422  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:40.422  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 17:37:40.422  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:40.422  1169  1169 D HotspotTile: onReceive : 2, 0
08-26 17:37:40.422  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 17:37:40.422  1310  1310 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:40.432  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:40.432  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 17:37:40.432  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 17:37:40.432  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:40.432  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:40.432  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:40.432  1619  1619 I Hs20UtilService: Starting #19
,08-26 17:37:40.432  1619  1659 I Hs20UtilService: Message received 5011
,08-26 17:37:40.442  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 17:37:40.442  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 17:37:40.442  6524  6524 D SecurityLogAgent: StateMachine : Current State = 1
08-26 17:37:40.442  6524  6524 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 17:37:40.462  7540  7540 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-26 17:37:40.462  7540  7540 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 17:37:40.462  7540  7540 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 17:37:40.472  7540  7540 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-26 17:37:40.482   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7540
08-26 17:37:40.482   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 17:37:40.482  7540  7540 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-26 17:37:40.482  7540  7540 I wpa_supplicant: ssSupport state is = 1
08-26 17:37:40.482  7540  7540 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 17:37:40.482  7540  7540 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 17:37:40.482   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7540,
08-26 17:37:40.482   408   408 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 17:37:40.622   408   408 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-26 17:37:40.622  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-26 17:37:40.672  7540  7540 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 17:37:40.672  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 17:37:40.682  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 17:37:40.682   408   408 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7540
08-26 17:37:40.682   408   408 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 17:37:40.682  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 17:37:40.682  7540  7540 I wpa_supplicant: ssSupport state is = 1,
08-26 17:37:40.682  7540  7540 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 17:37:40.682  7540  7540 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 17:37:40.682  7540  7540 E wpa_supplicant: SIM READ ERROR
08-26 17:37:40.682  7540  7540 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 17:37:40.682  7540  7540 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 17:37:40.682  7540  7540 E wpa_supplicant: SIM READ ERROR
08-26 17:37:40.682  7540  7540 I wpa_supplicant: Blacklist: Clear (all) 
08-26 17:37:40.682  7540  7540 I wpa_supplicant: wpa_default_ap_write_once
08-26 17:37:40.682  7540  7540 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 17:37:40.682  7540  7540 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 17:37:40.682  7540  7540 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-26 17:37:40.682  7540  7540 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 17:37:40.682  7540  7540 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 17:37:40.682  7540  7540 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 17:37:40.682  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 17:37:40.682  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:40.682  1015  1043 D Tethering: interfaceStatusChanged wlan0, false,
,08-26 17:37:40.752  7540  7540 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 17:37:40.762  1015  2062 V SAMP_SPCM_test: CSC File load.. 
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering,
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling,
08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-26 17:37:40.782  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-26 17:37:40.832  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
,08-26 17:37:40.842  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-26 17:37:40.842  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-26 17:37:40.842  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-26 17:37:40.842  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,08-26 17:37:40.842  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 17:37:40.842  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
,08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
,08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,08-26 17:37:40.852  1015  2062 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-26 17:37:40.852  1015  2062 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,08-26 17:37:40.862  1015  2062 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:40.862  1015  2062 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:40.862  1015  2062 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:40.862  1015  2062 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:40.872  7543  7543 E Zygote  : MountEmulatedStorage()
08-26 17:37:40.872  7543  7543 I libpersona: KNOX_SDCARD checking this for 1000
08-26 17:37:40.872  7543  7543 E Zygote  : v2
08-26 17:37:40.872  7543  7543 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:40.872  1015  2062 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7543 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 17:37:40.872  7543  7543 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:40.872  7543  7543 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:40.882  7543  7543 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:40.902  7543  7543 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:40.902  7543  7543 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:40.912  7540  7540 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 17:37:40.912  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 17:37:40.922  7543  7543 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,08-26 17:37:40.932  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-26 17:37:40.932   408   408 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7540
08-26 17:37:40.932   408   408 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 17:37:40.932  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 17:37:40.932  7540  7540 I wpa_supplicant: ssSupport state is = 1
08-26 17:37:40.932  7540  7540 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 17:37:40.932  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 17:37:40.942  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-26 17:37:40.952   408   408 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7540
08-26 17:37:40.952   408   408 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 17:37:40.952  7540  7540 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 17:37:40.952  7540  7540 I wpa_supplicant: ssSupport state is = 1
08-26 17:37:40.952  7540  7540 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 17:37:40.952  7540  7540 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 17:37:40.952  7540  7540 E wpa_supplicant: SIM READ ERROR
08-26 17:37:40.952  7540  7540 I wpa_supplicant: wpa_default_ap_write_once
08-26 17:37:40.952  7540  7540 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 17:37:40.952  7540  7540 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 17:37:40.952  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 17:37:40.952  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 17:37:40.952  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 17:37:40.952  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 17:37:40.952  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 17:37:40.952  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 17:37:40.972  1015  2062 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-26 17:37:41.042  7540  7540 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-26 17:37:41.042  7540  7540 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 17:37:41.102  7540  7540 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-26 17:37:41.102  7540  7540 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 17:37:41.102  7540  7540 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 17:37:41.362  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 17:37:41.362  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 17:37:41.362  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-26 17:37:41.372   287   287 E SMD     : DCD OFF
,08-26 17:37:41.392   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 17:37:41.422  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-26 17:37:41.422  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 17:37:41.422  7540  7540 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 17:37:41.422  7540  7540 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 17:37:41.422  7540  7540 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 17:37:41.422  7540  7540 E wpa_supplicant: SIM READ ERROR
08-26 17:37:41.422  7540  7540 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 17:37:41.442  7540  7540 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 17:37:41.452  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 17:37:41.452  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:41.452  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:41.452  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:41.452  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:41.452  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:41.452  7540  7540 I wpa_supplicant: Skip scan - bUseNetwork false
08-26 17:37:41.452  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:41.452  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 17:37:41.452  1169  1751 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 17:37:41.462  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 17:37:41.462  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-26 17:37:41.462  1169  1169 D HotspotTile: onReceive : 3, 0
,08-26 17:37:41.462  1310  1310 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 17:37:41.462  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 17:37:41.462  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:41.472  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:41.472  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:41.472  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:41.472  1619  1619 I Hs20UtilService: Starting #20,
,08-26 17:37:41.472  1619  1659 I Hs20UtilService: Message received 5011
,08-26 17:37:41.472  1015  1125 E WifiConfigStore: Not a HS20
08-26 17:37:41.472  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 17:37:41.472  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:41.472  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:41.472  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:41.472  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:41.472  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:41.472  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-26 17:37:41.472  6682  6682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:41.472  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 17:37:41.472  6682  6682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:41.472  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 17:37:41.482  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 17:37:41.482  6524  6524 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 17:37:41.482  6524  6524 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 17:37:41.482  6524  6524 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 17:37:41.482  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 17:37:41.482  7540  7540 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 17:37:41.482  7540  7540 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 17:37:41.482  7540  7540 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 17:37:41.482  7540  7540 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 17:37:41.482  7540  7540 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 17:37:41.482  7540  7540 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=,
08-26 17:37:41.482  7540  7540 I wpa_supplicant: First Scan Start
08-26 17:37:41.482  7540  7540 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 17:37:41.482  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-26 17:37:41.482  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 17:37:41.482  1015  1125 I WifiNative-HAL: startHal
08-26 17:37:41.482  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d6c488c
08-26 17:37:41.482  1015  1125 I WifiNative-HAL: Could not start hal
08-26 17:37:41.482  6927  6927 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 17:37:41.482  1015  1125 E WifiNative-wlan0: do suspend true
,08-26 17:37:41.482  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 17:37:41.482  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 17:37:41.492  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 17:37:41.492  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
08-26 17:37:41.492  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215],
,08-26 17:37:41.492  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-26 17:37:41.492  1015  1124 D WifiP2pService: P2pEnablingState
08-26 17:37:41.492   277  1014 D CommandListener: Setting iface cfg
08-26 17:37:41.492  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 17:37:41.492  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 17:37:41.492  1015  1124 D WifiP2pService: P2p socket connection successful
,08-26 17:37:41.492  1015  1148 I WifiNative-HAL: startHal
08-26 17:37:41.492  1015  1124 D WifiP2pService: P2pEnabledState
08-26 17:37:41.492   277  1014 D CommandListener: Trying to bring up p2p0
,08-26 17:37:41.492  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9ea7e9bc
08-26 17:37:41.492  1015  1148 I WifiNative-HAL: Could not start hal
,08-26 17:37:41.492  1015  1148 E WifiScanningService: could not start HAL
,08-26 17:37:41.492  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
08-26 17:37:41.492  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-26 17:37:41.492  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-26 17:37:41.492  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:41.492  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 17:37:41.502  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
08-26 17:37:41.492  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 17:37:41.502  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 17:37:41.492  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-26 17:37:41.502  1015  1046 D WifiDisplayController: disconnect
08-26 17:37:41.492  7540  7540 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 17:37:41.502  1015  1046 D WifiDisplayController: updateConnection
08-26 17:37:41.492  7540  7540 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 17:37:41.502  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 17:37:41.492  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:41.502  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 17:37:41.502  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 17:37:41.502  7540  7540 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 17:37:41.502  1015  1125 E WifiStateMachine: Failed to set frequency band 0
08-26 17:37:41.502  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:41.502  1015  1125 D SecContentProvider2: mCursor = null
08-26 17:37:41.502  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 17:37:41.502  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-26 17:37:41.502  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 17:37:41.502  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-26 17:37:41.502  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 17:37:41.502  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 17:37:41.502  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-26 17:37:41.502  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:41.502  1015  1125 D SecContentProvider2: mCursor = null
08-26 17:37:41.502  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 17:37:41.502  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 17:37:41.502  1169  1169 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 17:37:41.512  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 17:37:41.512  1015  1133 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 17:37:41.512  1169  1169 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 17:37:41.512  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  secondary type: null
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  wps: 0
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  grpcapab: 0
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  devcapab: 0
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  status: 3
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  wfdInfo: null
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-26 17:37:41.512  1015  1046 D WifiDisplayController:  SConnectInfo : null
,08-26 17:37:41.512  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 17:37:41.512  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 17:37:41.512  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 17:37:41.512  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 17:37:41.512  7273  7273 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 17:37:41.512  7273  7273 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 17:37:41.512  7273  7273 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 17:37:41.522  7288  7288 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 17:37:41.532  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 17:37:41.532  1015  1124 D WifiP2pService: InactiveState
,08-26 17:37:41.532  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-26 17:37:41.532  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 17:37:41.532  7540  7540 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 17:37:41.532  1015  1124 D WifiP2pService: InactiveState{ what=143376 },
08-26 17:37:41.532  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 17:37:41.992  1015  2806 D SSRM:n  : SIOP:: AP = 350
,08-26 17:37:42.012  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 17:37:42.012  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:42.012  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:42.012  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:42.012  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:42.012  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:42.012  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:42.012  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 17:37:42.022  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 17:37:42.022  6682  6737 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 17:37:42.022  6682  6737 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 17:37:42.022  6682  6737 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@33de6347 Bundle[{}]
,08-26 17:37:42.022  6682  6737 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 17:37:42.022  6682  6737 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 17:37:42.032  6682  6737 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 17:37:42.032  6682  6737 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 17:37:42.032  6682  6737 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 17:37:42.032  6682  6737 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 17:37:42.042  6682  6737 I System.out: Running OutgoingSocketThread
,08-26 17:37:42.042  6682  7564 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1334)
,08-26 17:37:42.042  6682  7564 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 51549
,08-26 17:37:42.042  6682  7564 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 17:37:42.392   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-26 17:37:42.672  7540  7540 I wpa_supplicant: nl80211: Received scan results (31 BSSes),
08-26 17:37:42.672  7540  7540 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 17:37:42.672  7540  7540 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 17:37:42.672  7540  7540 I wpa_supplicant: Trying to associate with  'G700'
,08-26 17:37:42.672  7540  7540 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 17:37:42.672  7540  7540 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-26 17:37:42.682  1015  7562 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 17:37:42.692  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:42.692  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:42.802  7540  7540 E wpa_supplicant: Cmd 35605 not handled
08-26 17:37:42.802  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 17:37:42.802  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:42.802  7540  7540 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 17:37:42.802  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-26 17:37:42.802  7540  7540 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-26 17:37:42.802  7540  7540 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 17:37:42.802  7540  7540 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 17:37:42.802  7540  7540 I wpa_supplicant: Associated with F4.99.3E
,08-26 17:37:42.802  7540  7540 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 17:37:42.802  7540  7540 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 17:37:42.802  7540  7540 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-26 17:37:42.802  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:42.802  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:42.802  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:42.802  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 17:37:42.802  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 17:37:42.802  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-26 17:37:42.802  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-26 17:37:42.802  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 17:37:42.802  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-26 17:37:42.812  1015  1128 E Tethering: No numeric data
,08-26 17:37:42.812  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 17:37:42.812  1015  1128 D Tethering: clearTetheredNotification()
08-26 17:37:42.812  7540  7540 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 17:37:42.812  7540  7540 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-26 17:37:42.812  7540  7540 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
,08-26 17:37:42.812  7540  7540 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 17:37:42.812  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-26 17:37:42.812  7540  7540 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 17:37:42.812  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:42.812  7540  7540 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 17:37:42.812  7540  7540 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 17:37:42.812  7540  7540 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 17:37:42.812  7540  7540 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-26 17:37:42.812  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:42.812  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 17:37:42.822  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 17:37:42.822  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 17:37:42.822  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-26 17:37:42.822  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:42.822  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:42.822  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 17:37:42.822  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:42.822  1169  1169 D HotspotTile: updateTetherState():false, false
08-26 17:37:42.822  1015  1122 V NetworkStats: performPollLocked() took 10ms
,08-26 17:37:42.832  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:42.832  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:42.832  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 17:37:42.832  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 17:37:42.842  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 17:37:42.842  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:42.842  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:42.842  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:42.842  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:42.842  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:42.842  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 17:37:42.842  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 17:37:42.842  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:42.842  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 17:37:42.852  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:42.852  1015  3282 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 17:37:42.852  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 17:37:42.852  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:42.852  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:42.852  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:42.862  1619  1619 I Hs20UtilService: Starting #21
,08-26 17:37:42.862  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 17:37:42.862  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 17:37:42.862  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 17:37:42.862  1619  1659 I Hs20UtilService: Message received 5007
,08-26 17:37:42.862  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 17:37:42.862  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 17:37:42.862  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 17:37:42.862  1310  1310 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 17:37:42.862  1310  2303 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 17:37:42.872   277  1014 D CommandListener: Setting iface cfg
,08-26 17:37:42.872  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,08-26 17:37:42.882  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 17:37:42.882  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:42.882  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 17:37:42.882  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:42.892  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 17:37:42.892  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:42.892  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:42.892  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:42.892  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:42.892  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:42.902  1015  1125 E WifiNative-wlan0: do suspend false
,08-26 17:37:42.902  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-26 17:37:42.902  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-26 17:37:42.902  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 17:37:42.902  1015  1125 D SecContentProvider2: mCursor = null
,08-26 17:37:43.042  6682  6737 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1335)
,08-26 17:37:43.042  6682  6737 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1335)
,08-26 17:37:43.042  6682  6737 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1340)
,08-26 17:37:43.042  6682  6737 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 17:37:43.042  6682  6737 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1341)
,08-26 17:37:43.052  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:43.052  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31cf1079 added. We now have 2 listener(s)
,08-26 17:37:43.052  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 17:37:43.052  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:43.052  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:43.052  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.052  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c511be added. We now have 9 listener(s)
08-26 17:37:43.052  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:43.052  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 17:37:43.062  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:43.062  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:43.062  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:43.062  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:43.062  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:43.062  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:43.062  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:43.062  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:43.062  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:43.062  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:43.072  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:43.072  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:43.072  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3998a96c added. We now have 3 listener(s)
,08-26 17:37:43.072  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:43.072  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:43.072  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 17:37:43.072  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:43.072  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:43.072  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.072  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f273b35 added. We now have 10 listener(s)
08-26 17:37:43.072  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:43.072  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:43.072  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:43.072  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:43.072  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:43.072  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.072  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:43.072  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:43.072  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31cf1079 removed from the list
08-26 17:37:43.072  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.072  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c511be removed from the list
08-26 17:37:43.072  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:43.072  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:43.072  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.072  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:43.082  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:43.082  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:43.082  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.082  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c511be not in the list
08-26 17:37:43.082  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.082  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-26 17:37:43.082  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 17:37:43.082  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:43.082  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:43.082  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f273b35 removed from the list
08-26 17:37:43.082  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:43.082  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.082  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:43.082  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:43.082  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3998a96c removed from the list
,08-26 17:37:43.082  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:43.082  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17bc8bca added. We now have 2 listener(s)
,08-26 17:37:43.092  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 17:37:43.092  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:43.092  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:43.092  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.092  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@361b413b added. We now have 9 listener(s)
,08-26 17:37:43.092  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:43.092  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 17:37:43.092  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:43.102  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:43.102  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:43.102  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:43.102  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:43.102  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:43.102  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:43.102  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:43.102  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:43.102  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:43.112  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 17:37:43.112  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:43.112  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@279d55b1 added. We now have 3 listener(s)
,08-26 17:37:43.112  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 17:37:43.112  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:43.112  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 17:37:43.112  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:43.112  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:43.112  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.112  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ff9a96 added. We now have 10 listener(s)
08-26 17:37:43.112  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:43.112  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:43.112  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:43.112  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:43.112  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:43.112  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 17:37:43.122  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 17:37:43.122  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 17:37:43.132  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 17:37:43.132  7567  7567 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 17:37:43.132  7567  7567 I dhcpcd  : version 5.5.6 starting
,08-26 17:37:43.132  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 17:37:43.132  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:43.132  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 17:37:43.132  7567  7567 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 17:37:43.142  7447  7472 D BtGatt.GattService: registerClient() - UUID=aab25fdc-e569-47b3-8103-08410cee79cf
,08-26 17:37:43.182  7447  7471 D BtGatt.GattService: onClientRegistered() - UUID=aab25fdc-e569-47b3-8103-08410cee79cf, clientIf=6,
08-26 17:37:43.182  6682  6690 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 17:37:43.182  7447  7473 D BtGatt.GattService: start scan with filters
08-26 17:37:43.182  7447  7477 D BtGatt.ScanManager: handling starting scan
08-26 17:37:43.192  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 17:37:43.192  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 17:37:43.192  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 17:37:43.192  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 17:37:43.192  7447  7477 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a793657
,08-26 17:37:43.192  7447  7471 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-26 17:37:43.192  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:43.192  7447  7477 D BtGatt.ScanManager: allow scan with filters
08-26 17:37:43.192  7447  7477 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 17:37:43.192  7447  7477 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-26 17:37:43.192  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:43.192  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 17:37:43.192  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:43.192  7447  7471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 17:37:43.192  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:43.192  7447  7477 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:43.192  7447  7477 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-26 17:37:43.192  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 17:37:43.192  7447  7471 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 17:37:43.192  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.202  6682  6737 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 17:37:43.202  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:43.202  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 17:37:43.202  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.202  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 17:37:43.202  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 17:37:43.202  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 17:37:43.202  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:43.202  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:43.202  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 17:37:43.202  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 17:37:43.202  7447  7471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-26 17:37:43.202  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:43.202  7447  7520 D BtGatt.GattService: stopScan() - queue size =1
,08-26 17:37:43.202  7447  7460 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 17:37:43.212  7567  7567 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 17:37:43.212  7567  7567 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 17:37:43.212  7567  7567 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-26 17:37:43.212  7567  7567 I dhcpcd  : bssid match
,08-26 17:37:43.212  7567  7567 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-26 17:37:43.212  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 17:37:43.212  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-26 17:37:43.212  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:43.212  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:43.212  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 17:37:43.212  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:43.212  7447  7477 D BtGatt.ScanManager: filter size is 1
,08-26 17:37:43.212  7447  7477 D BtGatt.ScanManager: delete FilterIndex - 3
08-26 17:37:43.212  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 17:37:43.212  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 17:37:43.212  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 17:37:43.212  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:43.222  7447  7471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 17:37:43.222  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.222  7447  7477 D BtGatt.ScanManager: stopping BLe Batch
,08-26 17:37:43.222  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 17:37:43.222  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 17:37:43.222  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:43.222  7447  7471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 17:37:43.222  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:43.222  7447  7477 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 17:37:43.222  7447  7471 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 17:37:43.222  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.232  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:43.232  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:43.232  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:43.232  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.232  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:43.232  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17bc8bca removed from the list
08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.232  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@361b413b removed from the list
08-26 17:37:43.232  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:43.232  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:43.232  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.232  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.232  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@361b413b not in the list
08-26 17:37:43.232  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.232  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.232  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ff9a96 removed from the list
,08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:43.232  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.232  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:43.232  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:43.232  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@279d55b1 removed from the list
,08-26 17:37:43.232  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:43.232  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d92ca22 added. We now have 2 listener(s)
,08-26 17:37:43.242  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 17:37:43.242  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:43.242  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:43.242  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.242  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9629cb3 added. We now have 9 listener(s)
,08-26 17:37:43.242  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:43.242  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 17:37:43.242  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:43.252  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:43.252  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:43.252  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:43.252  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:43.252  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:43.252  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:43.252  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:43.252  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:43.252  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:43.252  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:43.252  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:43.252  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed809e9 added. We now have 3 listener(s)
,08-26 17:37:43.252  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:43.252  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:43.262  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 17:37:43.262  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:43.262  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:43.262  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.262  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3837666e added. We now have 10 listener(s)
,08-26 17:37:43.262  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:43.262  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 17:37:43.262  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 17:37:43.262  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:43.262  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:43.262  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:43.262  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 17:37:43.262  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 17:37:43.272  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 17:37:43.272  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 17:37:43.272  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 17:37:43.272  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:43.272  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 17:37:43.282  7447  7472 D BtGatt.GattService: registerClient() - UUID=4bd1c5c8-956c-49e3-bf39-84320485b2ee
,08-26 17:37:43.312  7567  7567 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-26 17:37:43.322  7447  7471 D BtGatt.GattService: onClientRegistered() - UUID=4bd1c5c8-956c-49e3-bf39-84320485b2ee, clientIf=6
,08-26 17:37:43.322  6682  6691 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 17:37:43.322  7447  7473 D BtGatt.GattService: start scan with filters
,08-26 17:37:43.322  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 17:37:43.322  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 17:37:43.322  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 17:37:43.322  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 17:37:43.322  7447  7477 D BtGatt.ScanManager: handling starting scan
,08-26 17:37:43.332  7447  7471 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 17:37:43.332  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:43.332  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 17:37:43.332  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:43.332  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:43.332  7447  7477 D BtGatt.ScanManager: allow scan with filters
08-26 17:37:43.332  7447  7477 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 17:37:43.332  7447  7477 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 17:37:43.332  7447  7471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 17:37:43.332  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.332  7447  7477 D BtGatt.ScanManager: Starting BLE batch scan
08-26 17:37:43.332  7447  7477 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 17:37:43.342  7447  7471 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-26 17:37:43.342  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.342  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 17:37:43.342  7447  7471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 17:37:43.342  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.352  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 17:37:43.352  6682  6737 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 17:37:43.352  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 17:37:43.352  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 17:37:43.352  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 17:37:43.352  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:43.352  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:43.352  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 17:37:43.352  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 17:37:43.352  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d92ca22 removed from the list
08-26 17:37:43.352  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:43.352  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9629cb3 removed from the list
08-26 17:37:43.352  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 17:37:43.352  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:43.362  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:43.362  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 17:37:43.362  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:43.362  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:43.362  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:43.362  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:43.362  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 17:37:43.362  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9629cb3 not in the list
08-26 17:37:43.362  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 17:37:43.362  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:43.362  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 17:37:43.362  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 17:37:43.362  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 17:37:43.362  7447  7460 D BtGatt.GattService: stopScan() - queue size =1
,08-26 17:37:43.362  7447  7472 D BtGatt.GattService: unregisterClient() - clientIf=6
08-26 17:37:43.362  7447  7477 D BtGatt.ScanManager: filter size is 1
,08-26 17:37:43.372  7447  7477 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 17:37:43.372  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:43.372  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 17:37:43.372  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:43.372  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:43.372  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 17:37:43.372  7447  7471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 17:37:43.372  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:43.372  7447  7477 D BtGatt.ScanManager: stopping BLe Batch
,08-26 17:37:43.372  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:43.372  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 17:37:43.372  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 17:37:43.372  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 17:37:43.372  7447  7471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 17:37:43.372  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.382  7447  7477 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 17:37:43.382  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:43.382  7447  7471 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 17:37:43.382  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.382  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 17:37:43.382  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 17:37:43.382  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:43.382  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:43.382  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 17:37:43.382  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.382  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3837666e removed from the list
,08-26 17:37:43.392  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:43.392  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 17:37:43.392  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:43.392  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 17:37:43.392  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed809e9 removed from the list
,08-26 17:37:43.392  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:43.392  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38777b7a added. We now have 2 listener(s)
,08-26 17:37:43.392  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 17:37:43.392  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 17:37:43.392  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:43.392  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.392  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cdaef2b added. We now have 9 listener(s)
,08-26 17:37:43.402  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:43.402  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 17:37:43.402  7567  7567 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-26 17:37:43.402  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-26 17:37:43.412  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:43.412  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:43.412  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:43.412  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:43.412  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:43.412  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:43.412  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:43.412  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:43.412  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-26 17:37:43.412  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:43.412  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 17:37:43.412  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cbe0d21 added. We now have 3 listener(s)
,08-26 17:37:43.422  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:43.422  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 17:37:43.422  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:43.422  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 17:37:43.422  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.422  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d71d546 added. We now have 10 listener(s)
08-26 17:37:43.422  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 17:37:43.422  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:43.422  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 17:37:43.422  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 17:37:43.422  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 17:37:43.422  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 17:37:43.422  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:43.422  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 17:37:43.442  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 17:37:43.442  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 17:37:43.442  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 17:37:43.442  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 17:37:43.442  6682  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 17:37:43.452  7447  7458 D BtGatt.GattService: registerClient() - UUID=bee5313c-f8c4-4e4a-bdc9-995110b923b6
,08-26 17:37:43.492  7447  7471 D BtGatt.GattService: onClientRegistered() - UUID=bee5313c-f8c4-4e4a-bdc9-995110b923b6, clientIf=6
,08-26 17:37:43.492  6682  6691 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 17:37:43.492  7447  7520 D BtGatt.GattService: start scan with filters,
08-26 17:37:43.502  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-26 17:37:43.502  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 17:37:43.502  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 17:37:43.502  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 17:37:43.502  7447  7477 D BtGatt.ScanManager: handling starting scan
08-26 17:37:43.502  7447  7471 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 17:37:43.502  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.502  7447  7477 D BtGatt.ScanManager: allow scan with filters
08-26 17:37:43.502  7447  7477 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 17:37:43.502  7447  7477 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-26 17:37:43.502  7447  7471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 17:37:43.502  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:43.502  7447  7477 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 17:37:43.502  7447  7477 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
08-26 17:37:43.502  7447  7471 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 17:37:43.502  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:43.502  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:43.502  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 17:37:43.502  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 17:37:43.512  7447  7471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 17:37:43.512  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.512  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 17:37:43.532  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:43.532  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:43.532  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:43.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:43.532  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 17:37:43.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:43.532  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38777b7a removed from the list
08-26 17:37:43.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.532  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cdaef2b removed from the list
08-26 17:37:43.532  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:43.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:43.532  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
08-26 17:37:43.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 17:37:43.532  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 17:37:43.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:43.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:43.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.532  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cdaef2b not in the list
08-26 17:37:43.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-26 17:37:43.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 17:37:43.532  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 17:37:43.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 17:37:43.532  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 17:37:43.532  7447  7460 D BtGatt.GattService: stopScan() - queue size =1
,08-26 17:37:43.542  7447  7472 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 17:37:43.542  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 17:37:43.542  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 17:37:43.542  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 17:37:43.542  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 17:37:43.542  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 17:37:43.542  7447  7477 D BtGatt.ScanManager: filter size is 1
,08-26 17:37:43.542  7447  7477 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 17:37:43.542  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 17:37:43.542  7447  7471 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 17:37:43.542  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 17:37:43.542  7447  7477 D BtGatt.ScanManager: stopping BLe Batch,
,08-26 17:37:43.542  7447  7471 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 17:37:43.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 17:37:43.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 17:37:43.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 17:37:43.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:43.552  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-26 17:37:43.552  7447  7477 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 17:37:43.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:43.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:43.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.552  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:43.552  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d71d546 removed from the list
08-26 17:37:43.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 17:37:43.552  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.552  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:43.552  6682  6682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 17:37:43.552  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:43.552  6682  6682 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 17:37:43.552  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cbe0d21 removed from the list
08-26 17:37:43.552  7447  7471 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 17:37:43.552  7447  7471 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 17:37:43.552  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:43.552  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2765ffd2 added. We now have 2 listener(s)
,08-26 17:37:43.562  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 17:37:43.562  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:43.562  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 17:37:43.562  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.562  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cc18a3 added. We now have 9 listener(s)
08-26 17:37:43.562  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 17:37:43.562  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 17:37:43.572  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 17:37:43.582  6682  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 17:37:43.582  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 17:37:43.582  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 17:37:43.582  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 17:37:43.582  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 17:37:43.582  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 17:37:43.582  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 17:37:43.582  6682  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 17:37:43.582  6682  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 17:37:43.582  6682  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 17:37:43.582  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 17:37:43.582  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@138a3f59 added. We now have 3 listener(s)
,08-26 17:37:43.592  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 17:37:43.592  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-26 17:37:43.592  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 17:37:43.592  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-26 17:37:43.592  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 17:37:43.592  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@900471e added. We now have 10 listener(s)
08-26 17:37:43.592  6682  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 17:37:43.592  6682  6737 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 17:37:43.592  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:43.592  6682  6737 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 17:37:43.592  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:43.592  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 17:37:43.592  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 17:37:43.592  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:43.592  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2765ffd2 removed from the list
08-26 17:37:43.592  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.592  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cc18a3 removed from the list,
08-26 17:37:43.592  6682  6682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 17:37:43.592  6682  6737 D io.jxcore.node.ConnectivityMonitor: stop
08-26 17:37:43.592  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:43.592  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 17:37:43.592  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 17:37:43.602  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:43.602  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 17:37:43.602  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.602  6682  6737 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cc18a3 not in the list
08-26 17:37:43.602  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 17:37:43.602  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:43.602  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-26 17:37:43.602  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 17:37:43.602  6682  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 17:37:43.602  6682  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@900471e removed from the list
08-26 17:37:43.602  6682  6737 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 17:37:43.602  6682  6737 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 17:37:43.602  6682  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 17:37:43.602  6682  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 17:37:43.602  6682  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@138a3f59 removed from the list
08-26 17:37:43.602  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 17:37:43.602  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 17:37:43.602  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-26 17:37:43.602  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 17:37:43.602  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 17:37:43.602  6682  6737 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 17:37:43.602  6682  7595 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1348, name: My test thread name)
08-26 17:37:43.602  6682  7595 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1348, thread name: My test thread name)
08-26 17:37:43.602  6682  7595 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1348, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 17:37:43.612  6682  7597 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1350, name: My test thread name)
08-26 17:37:43.612  6682  7597 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1350, thread name: My test thread name)
,08-26 17:37:43.612  6682  7597 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1350, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 17:37:43.612  6682  6737 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 17:37:43.612  6682  6737 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 17:37:43.612  6682  6737 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 17:37:43.612  6682  6737 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 17:37:43.612  6682  6737 D com.test.thalitest.ThaliTestRunner: Total duration: 23339 ms
08-26 17:37:43.612  6682  6737 I jxcore-log: *Native tests were executed*
08-26 17:37:43.612  6682  6737 I jxcore-log: 
08-26 17:37:43.612  6682  6737 I jxcore-log: Total number of executed tests:  80
08-26 17:37:43.612  6682  6737 I jxcore-log: 
08-26 17:37:43.612  6682  6737 I jxcore-log: Number of passed tests:  80
08-26 17:37:43.612  6682  6737 I jxcore-log: 
08-26 17:37:43.612  6682  6737 I jxcore-log: Number of failed tests:  0
08-26 17:37:43.612  6682  6737 I jxcore-log: 
08-26 17:37:43.612  6682  6737 I jxcore-log: Number of ignored tests:  0
08-26 17:37:43.612  6682  6737 I jxcore-log: 
08-26 17:37:43.612  6682  6737 I jxcore-log: Total duration:  23339
08-26 17:37:43.612  6682  6737 I jxcore-log: 
08-26 17:37:43.612  6682  6737 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 17:37:43.612  6682  6737 I jxcore-log: 
08-26 17:37:43.612  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:43.612  6682  6737 I jxcore-log: 
,08-26 17:37:43.622  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:43.622  6682  6737 I jxcore-log: 
08-26 17:37:43.622  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:43.622  6682  6737 I jxcore-log: 
08-26 17:37:43.632  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:43.632  6682  6737 I jxcore-log: 
08-26 17:37:43.632  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:43.632  6682  6737 I jxcore-log: 
08-26 17:37:43.632  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:43.632  6682  6737 I jxcore-log: 
,08-26 17:37:43.632  6682  6682 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68),
08-26 17:37:43.632  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 17:37:43.632  6682  6737 I jxcore-log: 
08-26 17:37:43.632  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:43.632  6682  6737 I jxcore-log: 
,08-26 17:37:43.642  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:43.642  6682  6737 I jxcore-log: 
,08-26 17:37:43.642  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-26 17:37:43.642  6682  6737 I jxcore-log: 
,08-26 17:37:43.642  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 17:37:43.642  6682  6737 I jxcore-log: 
,08-26 17:37:43.642  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-26 17:37:43.642  6682  6737 I jxcore-log: 
,08-26 17:37:43.642  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:43.642  6682  6737 I jxcore-log: 
,08-26 17:37:43.642  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-26 17:37:43.642  6682  6737 I jxcore-log: 
,08-26 17:37:43.642  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:43.642  6682  6737 I jxcore-log: 
,08-26 17:37:43.642  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:43.642  6682  6737 I jxcore-log: 
,08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-26 17:37:43.652  6682  6737 I jxcore-log: 
08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 17:37:43.652  6682  6737 I jxcore-log: ,
08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
,08-26 17:37:43.652  6682  6737 I jxcore-log: 
,08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 17:37:43.652  6682  6737 I jxcore-log: 
,08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 17:37:43.652  6682  6737 I jxcore-log: 
,08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 17:37:43.652  6682  6737 I jxcore-log: ,
,08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 17:37:43.652  6682  6737 I jxcore-log: 
,08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 17:37:43.652  6682  6737 I jxcore-log: 
,08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 17:37:43.652  6682  6737 I jxcore-log: 
08-26 17:37:43.652  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 17:37:43.652  6682  6737 I jxcore-log: 
,08-26 17:37:43.662  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 17:37:43.662  6682  6737 I jxcore-log: 
,08-26 17:37:43.712  1015  1125 E WifiNative-wlan0: do suspend true,
,08-26 17:37:43.722  6682  6682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 17:37:43.722  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 17:37:43.722  6682  6737 I jxcore-log: 
,08-26 17:37:43.732  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
08-26 17:37:43.732  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-26 17:37:43.742  1015  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-26 17:37:43.742  1015  1125 E WifiStateMachine: VerifyingLinkState enter
08-26 17:37:43.742  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:43.742  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:43.742  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 17:37:43.742  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.742  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.742  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:43.742  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-26 17:37:43.742  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-26 17:37:43.742  1015  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-26 17:37:43.752  1015  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-26 17:37:43.752  1015  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 17:37:43.752  1015  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 17:37:43.762  1015  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 17:37:43.762  1015  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 17:37:43.762  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:43.762  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:43.762  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.762  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.762  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.762  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:43.772  1015  1484 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 17:37:43.772  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 17:37:43.772  1015  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-26 17:37:43.772  1015  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-26 17:37:43.772  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:43.772  1015  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:43.772  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:43.772  1619  1619 I Hs20UtilService: Starting #22
,08-26 17:37:43.772  1015  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504,
,08-26 17:37:43.772  1619  1659 I Hs20UtilService: Message received 5007
08-26 17:37:43.782  1015  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-26 17:37:43.782  1015  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 17:37:43.782  1015  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1],
08-26 17:37:43.782  1015  1127 D ConnectivityService: LTETest block dns file not exists
08-26 17:37:43.782  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 17:37:43.782  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-26 17:37:43.782  1310  1310 I NearbySettings: MountReceiver.onReceive - Keep current state,
,08-26 17:37:43.792  1015  1127 V NetworkStats: updateIfacesLocked()
,08-26 17:37:43.792  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.792  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-26 17:37:43.792  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 17:37:43.792  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-26 17:37:43.802  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:43.802  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 17:37:43.802  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.802  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.802  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.802  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:43.802  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.802  1015  1127 V NetworkStats: performPollLocked() took 7ms
,08-26 17:37:43.802  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 17:37:43.802  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 17:37:43.812  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 17:37:43.812  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 17:37:43.812  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-26 17:37:43.812  1169  1169 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:43.812  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 17:37:43.812  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.812  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-26 17:37:43.812  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:43.812  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 17:37:43.812  1015  1127 E ConnectivityService: updateNetworkInfo()
08-26 17:37:43.812  1015  1127 V NetworkStats: updateIfacesLocked()
08-26 17:37:43.812  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.812  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-26 17:37:43.812  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.812  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.812  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.812  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:43.812  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 17:37:43.812  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.812  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:43.822  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.822  1015  1127 V NetworkStats: performPollLocked() took 4ms
,08-26 17:37:43.822  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.822  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:43.822  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:43.822  1015  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-26 17:37:43.822  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 17:37:43.822  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-26 17:37:43.822  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 17:37:43.822  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 17:37:43.822  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-26 17:37:43.822  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 17:37:43.822  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:43.822  1015  7565 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 17:37:43.822  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:43.822  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:43.822   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 17:37:43.822   277  1010 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-26 17:37:43.822  1619  1619 I Hs20UtilService: Starting #23
,08-26 17:37:43.822  1619  1659 I Hs20UtilService: Message received 5007
08-26 17:37:43.832  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 17:37:43.832  1015  1127 D ConnectivityService:    accepting network in place of null
,08-26 17:37:43.832  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-26 17:37:43.832  1453  1453 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 17:37:43.832  1015  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-26 17:37:43.832  1015  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 17:37:43.832  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 17:37:43.832  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 17:37:43.832  1015  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-26 17:37:43.832  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 17:37:43.832  1310  1310 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 17:37:43.832  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-26 17:37:43.832  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 17:37:43.832  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,08-26 17:37:43.832  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 17:37:43.832  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 17:37:43.832  1310  1310 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-26 17:37:43.832  1310  1310 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 17:37:43.832  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.832  1015  1122 V NetworkStats: updateIfacesLocked()
08-26 17:37:43.832  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-26 17:37:43.832  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:43.832  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 17:37:43.832  1169  1676 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 17:37:43.842  1169  1169 D StatusBar.NetworkController: EthernetConnected: false
08-26 17:37:43.842  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 17:37:43.842  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 17:37:43.842  1169  1169 D StatusBar.NetworkController: updateDataNetType()
08-26 17:37:43.842  1169  1169 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 17:37:43.842  1169  1169 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 17:37:43.842  4294  6746 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 17:37:43.842  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:43.842  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.842  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 17:37:43.842  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.842  1015  1122 V NetworkStats: performPollLocked() took 6ms
08-26 17:37:43.842  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.842  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:43.842  1169  1169 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 17:37:43.842  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 17:37:43.852  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 17:37:43.852  1169  1169 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:43.852  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 17:37:43.852  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.852  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.852  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:43.852  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:43.852  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:43.852  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:43.852  1015  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 17:37:43.852  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 17:37:43.852  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:43.852  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:43.852  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 17:37:43.862  1619  1619 I Hs20UtilService: Starting #24
,08-26 17:37:43.862  1619  1659 I Hs20UtilService: Message received 5007
08-26 17:37:43.862  1310  1310 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 17:37:43.862  1310  1310 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 17:37:43.862  1015  3950 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 17:37:43.872  1015  1469 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-26 17:37:43.872  1015  1469 D SecContentProvider2: mCursor = null
,08-26 17:37:43.872  1015  1028 D SecContentProvider2: uri = 15 selection = getToastGravity,
08-26 17:37:43.872  1015  1028 D SecContentProvider2: mCursor = null
,08-26 17:37:43.872  1015  1133 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-26 17:37:43.872  1015  1133 D SecContentProvider2: mCursor = null
,08-26 17:37:43.872  1015  1454 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-26 17:37:43.872  1015  1454 D SecContentProvider2: mCursor = null
08-26 17:37:43.872  1015  1450 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-26 17:37:43.872  1015  1450 D SecContentProvider2: mCursor = null
,08-26 17:37:43.872  1015  3282 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-26 17:37:43.872  1015  3282 D SecContentProvider2: mCursor = null
,08-26 17:37:43.882  6682  6682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 17:37:43.882  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 17:37:43.882  6682  6737 I jxcore-log: 
,08-26 17:37:43.902  7600  7600 D AndroidRuntime: 
08-26 17:37:43.902  7600  7600 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 17:37:43.902   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-26 17:37:43.902  7600  7600 D AndroidRuntime: CheckJNI is OFF
,08-26 17:37:43.902  7600  7600 D AndroidRuntime: readGMSProperty: start
08-26 17:37:43.902  7600  7600 D AndroidRuntime: readGMSProperty: already setted!!
08-26 17:37:43.902  7600  7600 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 17:37:43.902  7600  7600 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 17:37:43.902  7600  7600 D AndroidRuntime: readGMSProperty: end
08-26 17:37:43.902  7600  7600 D AndroidRuntime: addProductProperty: start
,08-26 17:37:43.912  1015  1469 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015,
,08-26 17:37:43.912  1015  7565 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 17:37:43.922  1169  1169 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,08-26 17:37:43.982  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 15:37:43 GMT], X-Android-Received-Millis=[1472225863990], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472225863957]},
08-26 17:37:43.982  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 17:37:43.982  1015  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-26 17:37:43.982  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated,
08-26 17:37:43.982  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504],
08-26 17:37:43.982  1169  1676 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 17:37:43.982  1015  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-26 17:37:43.982  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 17:37:43.992  4294  6746 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 17:37:43.982  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 17:37:43.992  1169  1169 D StatusBar.NetworkController: EthernetConnected: false
08-26 17:37:43.992  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 17:37:43.992  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 17:37:43.992  1169  1169 D StatusBar.NetworkController: updateDataNetType()
08-26 17:37:43.992  1169  1169 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 17:37:43.992  1169  1169 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 17:37:44.002  1169  1169 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 17:37:44.002  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 17:37:44.002  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 17:37:44.002  1169  1169 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 17:37:44.002  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 17:37:44.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:44.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:44.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 17:37:44.002  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 17:37:44.052  6682  6682 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 17:37:44.052  6682  6737 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 17:37:44.052  6682  6737 I jxcore-log: 
,08-26 17:37:44.072  7600  7600 E AffinityControl: AffinityControl: registerfunction enter
,08-26 17:37:44.102  7600  7600 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-26 17:37:44.112  1015  3950 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
,08-26 17:37:44.112  1015  3950 D PackageManager: START PACKAGE DELETE: observer{417390036}
,08-26 17:37:44.112  1015  3950 D PackageManager: pkg{<packageName>}
08-26 17:37:44.112  1015  3950 D PackageManager: user{0}
08-26 17:37:44.112  1015  3950 D PackageManager: caller{2000}
08-26 17:37:44.112  1015  3950 D PackageManager: flags{2}
,08-26 17:37:44.112  1015  3950 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 17:37:44.112  1015  3950 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-26 17:37:44.112  1015  3950 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 17:37:44.112  1015  3950 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-26 17:37:44.122  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-26 17:37:44.122  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 17:37:44.122  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-26 17:37:44.122  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled,
08-26 17:37:44.122  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 17:37:44.122  1015  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-26 17:37:44.142  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-26 17:37:44.152  1015  1041 I ActivityManager: Killing 6682:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 17:37:44.212  1015  1055 W PackageSettings: Skipping PackageSetting{385916a6 com.example.hello/10168} due to missing metadata
,08-26 17:37:44.232  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{36fd00dc u0 com.test.thalitest/.MainActivity t2}
,08-26 17:37:44.232  1015  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 17:37:44.242  1015  1096 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
,08-26 17:37:44.242  1015  1096 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,08-26 17:37:44.252  1015  1041 D InputDispatcher: Focus left window: 6682,
08-26 17:37:44.262  1015  1041 W InputDispatcher: Attempted to unregister already unregistered input channel
08-26 17:37:44.262   257  1037 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-26 17:37:44.262   257  5896 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-26 17:37:44.272  1015  1041 D InputDispatcher: Focused application released
,08-26 17:37:44.272  1015  1041 D FocusedStackFrame: Set to : 0
,08-26 17:37:44.272  1015  1133 W WindowManager: Failed looking up window
08-26 17:37:44.272  1015  1133 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@2cbf432f does not exist
08-26 17:37:44.272  1015  1133 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
08-26 17:37:44.272  1015  1133 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
08-26 17:37:44.272  1015  1133 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
08-26 17:37:44.272  1015  1133 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,08-26 17:37:44.272  1015  1133 I WindowState: WIN DEATH: null
,08-26 17:37:44.282  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 17:37:44.282  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 17:37:44.282  1015  1041 W ActivityManager: mDVFSHelper.acquire()
,08-26 17:37:44.282  1015  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-26 17:37:44.302  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-26 17:37:44.302  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-26 17:37:44.322  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 17:37:44.322  1478  1478 D Launcher: onRestart, Launcher: 189904429
,08-26 17:37:44.322  1478  1478 D Launcher: onStart, Launcher: 189904429
,08-26 17:37:44.322  1478  1478 D Launcher.HomeView: onStart
,08-26 17:37:44.322  1478  1478 D Launcher: onResume, Launcher: 189904429
,08-26 17:37:44.332  1015  1469 D SettingsProvider: name = kids_home_mode
,08-26 17:37:44.332  1015  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 17:37:44.332  1015  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 17:37:44.332  1015  1469 D SettingsProvider: selectionArgs: false
,08-26 17:37:44.332  1015  1469 D SettingsProvider: selectionArgs: 10006
08-26 17:37:44.332  1015  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 17:37:44.332  1015  1469 D SettingsProvider: ret = -1
08-26 17:37:44.332  1478  1478 D Launcher.HomeView: onResume
,08-26 17:37:44.332  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 17:37:44.342  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 17:37:44.362  1858  1858 E SamsungIME: mOCRHelper is null
,08-26 17:37:44.362  2018  2146 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 17:37:44.372  6155  6155 I art     : Explicit concurrent mark sweep GC freed 19905(1084KB) AllocSpace objects, 2(32KB) LOS objects, 50% free, 3MB/7MB, paused 937us total 50.927ms
,08-26 17:37:44.372   287   287 E SMD     : DCD OFF
,08-26 17:37:44.382  4294  4294 I art     : Explicit concurrent mark sweep GC freed 22218(1360KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.260ms total 80.060ms
,08-26 17:37:44.392  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 17:37:44.392  4294  4306 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-26 17:37:44.392  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-26 17:37:44.392  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 17:37:44.402  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 17:37:44.402  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 17:37:44.402  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-26 17:37:44.402  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 17:37:44.402  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-26 17:37:44.402  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-26 17:37:44.422  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 17:37:44.422  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 17:37:44.422  1015  1122 V NetworkStats: performPollLocked() took 21ms
,08-26 17:37:44.422  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:44.442  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-26 17:37:44.442  3954  3954 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 17:37:44 GMT+02:00 2016
,08-26 17:37:44.442  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 17:37:44.442  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0,
08-26 17:37:44.442  1015  1040 W TextServicesManagerService: no available spell checker services found
08-26 17:37:44.442  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-26 17:37:44.462  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-26 17:37:44.462  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 17:37:44.472  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 17:37:44.472  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:44.472  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 17:37:44.472  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-26 17:37:44.482  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:44.482  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:44.482  1478  1478 D MenuAppsGridFragment: onResume
,08-26 17:37:44.482  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 17:37:44.482  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 17:37:44.482  1441  1441 D RegisteredServicesCache: empty dynamic service
08-26 17:37:44.482  1015  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 17:37:44.482  1015  1028 D SecContentProvider2: mCursor = null
,08-26 17:37:44.492  3954  3954 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 17:37:44.492  1015  1484 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41,
,08-26 17:37:44.492  3954  3954 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 17:37:44.492  3954  3954 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 17:37:44.522  1015  1484 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-26 17:37:44.522  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 17:37:44.522  1015  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 17:37:44.522  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:44.522  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.522  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:44.522  1015  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.522  3954  3954 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 17:37:44.532  3954  7619 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 17:37:44.532  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 17:37:44.542  7620  7620 E Zygote  : MountEmulatedStorage()
08-26 17:37:44.542  7620  7620 E Zygote  : v2
08-26 17:37:44.542  7620  7620 I libpersona: KNOX_SDCARD checking this for 10090
08-26 17:37:44.542  7620  7620 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:44.542  7620  7620 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:44.542  7620  7620 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:44.542  3954  7619 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-26 17:37:44.542  7620  7620 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:44.552  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 17:37:44.552  1015  1484 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7620 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-26 17:37:44.552  1015  1055 I art     : Explicit concurrent mark sweep GC freed 77015(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 25MB/37MB, paused 16.766ms total 228.659ms
,08-26 17:37:44.562  3954  7619 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-26 17:37:44.562  3954  7619 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-26 17:37:44.572  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-26 17:37:44.572  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.572  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.572  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.572  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.572  1015  1127 V NetworkStats: updateIfacesLocked()
,08-26 17:37:44.582  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-26 17:37:44.582  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 17:37:44.582  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 17:37:44.582  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-26 17:37:44.582  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 17:37:44.582  1015  1450 I TactileAssist: enable value -1
08-26 17:37:44.582  1015  1450 I TactileAssist: internal enable value -1
08-26 17:37:44.582  1015  1450 I TactileAssist: intensity value -1
08-26 17:37:44.582  1015  1450 I TactileAssist: saveAppList value true
,08-26 17:37:44.592  7635  7635 E Zygote  : MountEmulatedStorage()
08-26 17:37:44.592  7635  7635 E Zygote  : v2
08-26 17:37:44.592  7635  7635 I libpersona: KNOX_SDCARD checking this for 1000
08-26 17:37:44.592  1015  1450 I TactileAssist: List of disabled apps :
08-26 17:37:44.592  7635  7635 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:44.592  7635  7635 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:44.592  7635  7635 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:44.592  7635  7635 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 17:37:44.592  7620  7620 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:44.592  1015  1127 V NetworkStats: performPollLocked() took 19ms
08-26 17:37:44.592  7620  7620 D ActivityThread: Added TimaKeyStore provider
08-26 17:37:44.592  1015  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7635 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 17:37:44.592  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:44.602  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-26 17:37:44.602  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.602  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.602  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.602  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:44.612  7644  7644 E Zygote  : MountEmulatedStorage()
08-26 17:37:44.612  7644  7644 I libpersona: KNOX_SDCARD checking this for 1000
08-26 17:37:44.612  7644  7644 E Zygote  : v2
08-26 17:37:44.612  7644  7644 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:44.612  7644  7644 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:44.612  1015  1305 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 17:37:44.612  1015  1305 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 17:37:44.612  1015  1305 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 17:37:44.612  1015  1305 D BatteryService: stay LED for fully charged
,08-26 17:37:44.622  7644  7644 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 17:37:44.622  7644  7644 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:44.622  1015  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7644 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 17:37:44.632  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 17:37:44.642  7635  7635 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:44.642  7635  7635 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:44.642  7644  7644 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:44.642  7644  7644 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:44.642  3954  7619 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-26 17:37:44.652  1015  1476 D ActivityManager: handle home activity for 0
,08-26 17:37:44.652  1015  1476 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-26 17:37:44.652  1015  1476 D KnoxTimeoutHandler: post home show event for user 0
08-26 17:37:44.652  1015  1476 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 17:37:44.652  1015  1476 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 17:37:44.652  1015  1476 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 17:37:44.652  1478  1478 D Launcher.HomeView: onPause
,08-26 17:37:44.652  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 17:37:44.652  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 17:37:44.662  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-26 17:37:44.662  1015  1055 D PackageManager: delete codoeFile: 
,08-26 17:37:44.672  3954  7619 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-26 17:37:44.672  3954  7619 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-26 17:37:44.682  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-26 17:37:44.692  1015  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-26 17:37:44.702  1015  1217 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
08-26 17:37:44.702  1015  1055 D PackageManager: result of delete: 1{417390036}
08-26 17:37:44.702  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.702  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.702  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.702  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:44.702  3954  3954 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 17:37:44.702  7620  7620 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-26 17:37:44.712  7620  7620 D elm:15121: ELMEngine.ELMEngine( context ).
,08-26 17:37:44.712  7635  7635 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-26 17:37:44.712  7665  7665 E Zygote  : MountEmulatedStorage()
08-26 17:37:44.712  7665  7665 E Zygote  : v2
08-26 17:37:44.712  7665  7665 I libpersona: KNOX_SDCARD checking this for 10048
08-26 17:37:44.712  7665  7665 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:44.722  7665  7665 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:44.722  7600  7600 D AndroidRuntime: Shutting down VM
08-26 17:37:44.722  7620  7620 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-26 17:37:44.722  7665  7665 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:44.722  1015  1217 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7665 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-26 17:37:44.722  7665  7665 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 17:37:44.722  1169  1676 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 17:37:44.722  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-26 17:37:44.732  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 17:37:44.732  1015  3282 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-26 17:37:44.732  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 17:37:44.732  1015  3282 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-26 17:37:44.732  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504],
08-26 17:37:44.732  1169  1676 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 17:37:44.742  4294  6746 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 17:37:44.742  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 17:37:44.742  1015  1055 D PackageManager: userId{-1}
08-26 17:37:44.742  1015  1055 D PackageManager: andCode{true}
,08-26 17:37:44.742  1015  3282 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:44.742  1015  3282 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:44.742  1015  3282 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-26 17:37:44.742  4294  6746 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 17:37:44.752  7644  7644 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-26 17:37:44.752  1015  1305 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-26 17:37:44.752  1015  1305 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-26 17:37:44.752  7665  7665 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:44.752  1015  1305 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:44.752  1015  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:44.752  1015  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-26 17:37:44.752  7665  7665 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:44.752  7620  7620 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-26 17:37:44.752  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 17:37:44.762  7620  7620 D elm:15121: ElmAgentService : onCreate()
08-26 17:37:44.762  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.762  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.762  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.762  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.762  7620  7681 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-26 17:37:44.762  7620  7681 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-26 17:37:44.762  7620  7681 D elm:15121: MDMBridge.getInstance()
08-26 17:37:44.762  7620  7681 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 17:37:44.762  7620  7681 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 17:37:44.772  7683  7683 E Zygote  : MountEmulatedStorage()
08-26 17:37:44.772  7683  7683 I libpersona: KNOX_SDCARD checking this for 10003
08-26 17:37:44.772  7683  7683 E Zygote  : v2
08-26 17:37:44.772  7683  7683 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:44.782  1015  1305 D SecContentProvider2: uri = -1 selection = getSealedState
08-26 17:37:44.782  1015  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7683 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 17:37:44.782  1015  1305 D SecContentProvider2: mCursor = null
08-26 17:37:44.782  1015  1041 W ActivityManager: mDVFSHelper.release()
08-26 17:37:44.782  7644  7644 I PopupuiReceiver_KNOX: getSealedState : true
08-26 17:37:44.782  1015  1469 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-26 17:37:44.782  1015  1476 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-26 17:37:44.792  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.782  1015  1476 D SecContentProvider2: mCursor = null
08-26 17:37:44.792  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.792  7683  7683 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:44.792  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.792  7644  7644 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-26 17:37:44.792  1015  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:44.792  1015  3282 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-26 17:37:44.792  1015  3282 D SecContentProvider2: mCursor = null
08-26 17:37:44.792  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 17:37:44.792  7644  7644 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-26 17:37:44.792  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 17:37:44.792  7644  7644 D PopupuiReceiver: Action package removed
08-26 17:37:44.792  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 17:37:44.792  7683  7683 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:44.792  7683  7683 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 17:37:44.792  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 17:37:44.792  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 17:37:44.792  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 17:37:44.792  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-26 17:37:44.792  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 17:37:44.792  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-26 17:37:44.792  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 17:37:44.792  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 17:37:44.792  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 17:37:44.792  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 17:37:44.802  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 17:37:44.802   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-26 17:37:44.802   311   311 I art     : Explicit concurrent mark sweep GC freed 8707(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 28.083ms
,08-26 17:37:44.812  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 17:37:44.812  7683  7683 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:44.812  7683  7683 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:44.812  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 17:37:44.812  1015  1450 D InputDispatcher: Focus entered window: 1478
,08-26 17:37:44.812  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 17:37:44.812  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 17:37:44.812  1478  1478 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 17:37:44.822  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 17:37:44.822   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.552ms
08-26 17:37:44.822  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 17:37:44.822  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 17:37:44.822  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 17:37:44.822  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 17:37:44.832  1015  3282 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 17:37:44.832  1015  7699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 17:37:44.832  1015  3282 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6682 uid 10171
08-26 17:37:44.832  1015  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-26 17:37:44.842  1858  1858 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-26 17:37:44.842   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.459ms,
08-26 17:37:44.842  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 17:37:44.842  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 17:37:44.842  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-26 17:37:44.842  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 17:37:44.852  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-26 17:37:44.852  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 17:37:44.852  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 17:37:44.852  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-26 17:37:44.852  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 17:37:44.852  7701  7701 E Zygote  : MountEmulatedStorage()
08-26 17:37:44.852  7701  7701 I libpersona: KNOX_SDCARD checking this for 1000
08-26 17:37:44.852  7701  7701 E Zygote  : v2
08-26 17:37:44.852  7701  7701 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:44.852  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-26 17:37:44.852  1015  1469 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7701 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 17:37:44.852  7701  7701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:44.862  7701  7701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:44.862  7701  7701 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:44.872  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-26 17:37:44.872  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 17:37:44.872  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 17:37:44.872  1015  2806 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 17:37:44.872  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-26 17:37:44.872  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 17:37:44.872  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-26 17:37:44.872  7620  7620 D elm:15121: ElmAgentService : onDestroy().
08-26 17:37:44.872  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 17:37:44.872  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 17:37:44.872  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 17:37:44.872  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-26 17:37:44.872  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-26 17:37:44.872  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-26 17:37:44.872  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-26 17:37:44.882  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 17:37:44.882  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-26 17:37:44.882  1015  1454 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-26 17:37:44.882  1015  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.882  1015  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.882  1015  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.882  1015  1454 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:44.892  7701  7701 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:44.892  7701  7701 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:44.902  7715  7715 E Zygote  : MountEmulatedStorage()
08-26 17:37:44.902  7715  7715 E Zygote  : v2
08-26 17:37:44.902  7715  7715 I libpersona: KNOX_SDCARD checking this for 10145
08-26 17:37:44.902  7715  7715 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:44.902  7715  7715 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 17:37:44.902  1015  1454 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7715 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 17:37:44.902  1015  1454 I ActivityManager: Killing 7016:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-26 17:37:44.912  7715  7715 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:44.912  7715  7715 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 17:37:44.912  1015  1454 I ActivityManager: Killing 7063:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-26 17:37:44.922  1015  1454 I ActivityManager: Killing 7033:com.android.chrome/u0a77 (adj 15): empty #21
,08-26 17:37:44.922  7600  7600 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 17:37:44.932  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4dcacde u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:146711
,08-26 17:37:44.932  1015  1738 I ActivityManager: Killing 6927:com.google.android.talk/u0a102 (adj 15): empty #21
,08-26 17:37:44.942  7715  7715 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:44.942  7715  7715 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:44.952  7701  7701 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 17:37:44.962  7665  7665 D Compatibility: onReceive() it will make start service
,08-26 17:37:44.962  1015  1738 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-26 17:37:44.962  1015  1738 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-26 17:37:44.962  1015  1738 W ActivityManager: userId = 0, bbcId = -10000
08-26 17:37:44.962  1015  1738 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 17:37:44.962  1015  1738 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-26 17:37:44.972  1015  1305 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-26 17:37:44.972  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.972  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.972  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:44.972  1015  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:44.972  7665  7732 D Compatibility: onHandleIntent()
,08-26 17:37:44.972  7665  7732 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-26 17:37:44.982  7665  7732 D Compatibility: found: 2
,08-26 17:37:44.982  7665  7732 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-26 17:37:44.982  7665  7732 D Compatibility: skipping ResolveInfo{1fad9cac com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-26 17:37:44.982  7701  7701 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-26 17:37:44.992  7665  7732 D Compatibility: considering ResolveInfo{3bb04d75 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-26 17:37:44.992  7665  7732 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-26 17:37:44.992  7665  7732 D Compatibility: enabling receiver ResolveInfo{3f28d10a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-26 17:37:44.992  7665  7732 D Compatibility: enabling receiver ResolveInfo{bce3d7b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-26 17:37:44.992  7736  7736 E Zygote  : MountEmulatedStorage()
08-26 17:37:44.992  7736  7736 I libpersona: KNOX_SDCARD checking this for 10052
08-26 17:37:44.992  7736  7736 E Zygote  : v2
08-26 17:37:44.992  7736  7736 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:45.002  7736  7736 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:45.002  7736  7736 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:45.002  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 17:37:45.002  7736  7736 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 17:37:45.002  1015  1450 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-26 17:37:45.002  1015  1450 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
08-26 17:37:45.002  7665  7732 D Compatibility: enabling receiver ResolveInfo{25add798 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-26 17:37:45.012  1015  1305 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7736 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-26 17:37:45.012  7665  7732 D Compatibility: enabling receiver ResolveInfo{1a454bf1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-26 17:37:45.012  1015  1454 D PersonaManager: isKioskContainerExistOnDevice,
,08-26 17:37:45.022  7665  7732 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-26 17:37:45.022  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-26 17:37:45.022  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 17:37:45.022  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-26 17:37:45.022  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 17:37:45.032  7715  7715 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-26 17:37:45.032  7715  7715 D ThemeInfoUtil: isCurrentFestival = false
,08-26 17:37:45.042  7736  7736 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 17:37:45.042  7736  7736 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:45.042  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 17:37:45.042  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 17:37:45.062  7447  7447 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 17:37:45.062  1015  3282 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-26 17:37:45.062  1169  1169 I StatusBar: Icon Only
,08-26 17:37:45.062  1169  1169 D PanelView: There is/are notification(s) 
08-26 17:37:45.062  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 17:37:45.062  7447  7478 D HeadsetStateMachine: Disconnected process message: 10
,08-26 17:37:45.062  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 17:37:45.062  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 17:37:45.062  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 17:37:45.062  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 17:37:45.062  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 17:37:45.062  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:45.062  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:45.062  1015  3282 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:45.082  7751  7751 E Zygote  : MountEmulatedStorage()
08-26 17:37:45.082  7751  7751 I libpersona: KNOX_SDCARD checking this for 10087
,08-26 17:37:45.082  7751  7751 E Zygote  : v2
08-26 17:37:45.082  7751  7751 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:45.082  7751  7751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:45.082  1015  3282 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7751 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,08-26 17:37:45.082  1015  3282 I ActivityManager: Killing 7100:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,08-26 17:37:45.082  7751  7751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 17:37:45.082  1015  1027 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 17:37:45.082  1015  1027 D SecContentProvider2: mCursor = null
,08-26 17:37:45.092  7751  7751 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 17:37:45.092  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 17:37:45.092  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:45.092  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:45.092  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:45.092  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:45.112  7751  7751 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 17:37:45.112  7751  7751 D ActivityThread: Added TimaKeyStore provider
,08-26 17:37:45.112  7765  7765 E Zygote  : MountEmulatedStorage()
08-26 17:37:45.112  7765  7765 I libpersona: KNOX_SDCARD checking this for 1000
08-26 17:37:45.112  7765  7765 E Zygote  : v2
08-26 17:37:45.112  7765  7765 I libpersona: KNOX_SDCARD not a persona
,08-26 17:37:45.112  7765  7765 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:45.122  7765  7765 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 17:37:45.122  7765  7765 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 17:37:45.122  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7765 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 17:37:45.122  1015  1015 I MotionRecognitionService: Plugged
08-26 17:37:45.122  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 17:37:45.122  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-26 17:37:45.122  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:45.122  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:45.122  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 17:37:45.122  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 17:37:45.152  7765  7765 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 17:37:45.152  7782  7782 I libpersona: KNOX_SDCARD checking this for 10148
08-26 17:37:45.152  7765  7765 D ActivityThread: Added TimaKeyStore provider
08-26 17:37:45.152  7782  7782 I libpersona: KNOX_SDCARD not a persona
08-26 17:37:45.152  7782  7782 E Zygote  : MountEmulatedStorage()
08-26 17:37:45.152  7782  7782 E Zygote  : v2
,08-26 17:37:45.152  7782  7782 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 17:37:45.152  7782  7782 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 17:37:45.152  1015  1028 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7782 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-26 17:37:45.162  7782  7782 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 17:37:45.162  1015  1028 I ActivityManager: Killing 7080:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-26 17:37:45.162  1015  1476 I ActivityManager: Killing 7119:com.osp.app.signin/u0a36 (adj 15): empty #21

```
