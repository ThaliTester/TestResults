#### Test 8233723530fac5a_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-23 12:25:17.166  1016  1808 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 12:25:17.166  1016  1808 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 12:25:17.166  1016  1808 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 12:25:17.166  1016  1808 D BatteryService: stay LED for fully charged
08-23 12:25:17.166  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 12:25:17.176  1016  1016 I MotionRecognitionService: Plugged
08-23 12:25:17.176  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
08-23 12:25:17.176  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 12:25:17.176  1433  1433 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 12:25:17.176  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 12:25:17.176  1433  1433 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-23 12:25:17.186  3176  3176 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 12:25:17.186  3176  3279 D HeadsetStateMachine: Disconnected process message: 10
08-23 12:25:17.206  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 12:25:17.206  1174  1174 D SViewCoverView: level :100 plugged : 2
08-23 12:25:17.206  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 12:25:17.206  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 12:25:17.206  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 12:25:17.706  6816  6816 D AndroidRuntime: 
08-23 12:25:17.706  6816  6816 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 12:25:17.706  6816  6816 D AndroidRuntime: CheckJNI is OFF
08-23 12:25:17.706  6816  6816 D AndroidRuntime: readGMSProperty: start
08-23 12:25:17.706  6816  6816 D AndroidRuntime: readGMSProperty: already setted!!
08-23 12:25:17.706  6816  6816 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 12:25:17.706  6816  6816 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 12:25:17.706  6816  6816 D AndroidRuntime: readGMSProperty: end
08-23 12:25:17.706  6816  6816 D AndroidRuntime: addProductProperty: start
08-23 12:25:17.836  6816  6816 E AffinityControl: AffinityControl: registerfunction enter
08-23 12:25:17.866  6816  6816 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 12:25:17.886  1016  1029 E PersonaManagerService: inState():  stateMachine is null !!
08-23 12:25:17.886  1016  1029 I PersonaManagerService: PersonaId don't exist
08-23 12:25:17.886  1016  1029 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 12:25:17.886  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 12:25:17.906  1016  1029 W ActivityManager: mDVFSHelper.acquire()
08-23 12:25:17.906   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-23 12:25:17.916   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-23 12:25:17.916  1016  1029 D FocusedStackFrame: Set to : 0
08-23 12:25:17.926  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:17.926  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:17.926  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:17.926  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:17.926  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 12:25:17.926  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 12:25:17.936  6828  6828 E Zygote  : MountEmulatedStorage()
08-23 12:25:17.936  6828  6828 I libpersona: KNOX_SDCARD checking this for 10171
08-23 12:25:17.936  6828  6828 E Zygote  : v2
08-23 12:25:17.936  6828  6828 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:17.936  6828  6828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:25:17.936  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 12:25:17.936  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 12:25:17.936   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-23 12:25:17.946  6828  6828 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:25:17.946  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 12:25:17.946  1016  1029 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6828 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 12:25:17.946  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 12:25:17.946  6828  6828 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 12:25:17.956  1016  1029 D InputDispatcher: Focused application set to: xxxx
08-23 12:25:17.956  1016  1029 D InputDispatcher: Focus left window: 1499
08-23 12:25:17.956  6816  6816 D AndroidRuntime: Shutting down VM
08-23 12:25:17.956  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 12:25:17.956  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 12:25:17.966  6828  6828 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:17.966  6828  6828 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:17.976  1016  1217 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-23 12:25:17.976  1016  1016 V ActivityManager: Display changed displayId=0
08-23 12:25:17.986  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 12:25:17.996  1016  1217 D PersonaManager: isKioskContainerExistOnDevice
08-23 12:25:18.006  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-23 12:25:18.036   258   440 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-23 12:25:18.036   258   445 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-23 12:25:18.046  1499  1499 D Launcher: onTrimMemory. Level: 20
08-23 12:25:18.046  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{1e140c9e token=android.os.BinderProxy@33cdeb71 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 12:25:18.096   291   291 E SMD     : DCD OFF
08-23 12:25:18.106  6828  6828 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-23 12:25:18.126  6828  6828 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7103-7105)
08-23 12:25:18.126  6828  6828 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 12:25:18.156  6828  6828 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3dc2d2f2}
08-23 12:25:18.156  6828  6828 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 12:25:18.166  6816  6816 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 12:25:18.176  6828  6828 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 12:25:18.216  6828  6828 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,08-23 12:25:18.226  6828  6828 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-23 12:25:18.226  6828  6828 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 12:25:18.266  6828  6828 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 12:25:18.266  6828  6828 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 12:25:18.266  6828  6828 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 12:25:18.266  6828  6828 I Adreno-EGL: Local Branch: 
08-23 12:25:18.266  6828  6828 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 12:25:18.266  6828  6828 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 12:25:18.266  6828  6828 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 12:25:18.346  6828  6828 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 12:25:18.376  6828  6828 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 12:25:18.376  6828  6828 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 12:25:18.386  6828  6828 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-23 12:25:18.386  6828  6828 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-23 12:25:18.506  6828  6828 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:25:18.506  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{30b57c77 u0 com.test.thalitest/.MainActivity t2}
,08-23 12:25:18.516  6828  6828 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 12:25:18.526  6828  6828 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-23 12:25:18.526  6828  6828 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-23 12:25:18.536  6828  6828 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 12:25:18.536  6828  6828 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:25:18.536  6828  6828 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:25:18.606  6828  6868 D OpenGLRenderer: Render dirty regions requested: true
08-23 12:25:18.606  1016  1808 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 12:25:18.606  1016  1808 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 12:25:18.606  1016  1808 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 12:25:18.606  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 12:25:18.606  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 12:25:18.616  6828  6855 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-23 12:25:18.616  6828  6828 V ActivityThread: updateVisibility : ActivityRecord{94eb252 token=android.os.BinderProxy@15c74b87 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 12:25:18.626  6828  6828 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 12:25:18.626  6828  6828 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-23 12:25:18.636   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-23 12:25:18.646  1016  1213 D InputDispatcher: Focus entered window: 6828
,08-23 12:25:18.646  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 12:25:18.656  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 12:25:18.656  6828  6828 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 12:25:18.656  6828  6868 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 12:25:18.656  6828  6868 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-23 12:25:18.656  6828  6868 D OpenGLRenderer: Enabling debug mode 0
,08-23 12:25:18.676  1016  1797 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 12:25:18.686  1174  1174 I StatusBar: Icon Only
,08-23 12:25:18.686  1174  1174 D PanelView: There is/are notification(s) 
08-23 12:25:18.686  1016  6872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 12:25:18.696  1016  1046 I ActivityManager: Displayed Component not be shown by security: +696ms (total +775ms)
,08-23 12:25:18.696  1016  1046 W ActivityManager: mDVFSHelper.release(),
08-23 12:25:18.696  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{30b57c77 u0 com.test.thalitest/.MainActivity t2} time:107679
,08-23 12:25:18.706  6828  6828 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
,08-23 12:25:18.706  6828  6828 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@15c74b87 time:107684
08-23 12:25:18.706   258   440 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-23 12:25:18.706   258   445 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-23 12:25:18.736  1894  1894 I SamsungIME: getCurrentCandidateView
,08-23 12:25:18.816  6828  6828 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6828
,08-23 12:25:18.836  1894  1894 D SamsungIME: Dismiss ExpandCandiate
,08-23 12:25:18.986  1894  1894 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 12:25:19.026  1894  1894 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 12:25:19.036  6828  6828 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 12:25:19.036  1894  1894 I SamsungIME: KeybaordView init() : load resources
,08-23 12:25:19.066  1894  1894 I SamsungIME: getCurrentKeyboard
08-23 12:25:19.066  1894  1894 I SamsungIME: getTextKeyboard
,08-23 12:25:19.086  1894  1894 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 12:25:19.136  6828  6875 D jxcore_app_log: JniHelper::setJavaVM(0xb7afb2b0), pthread_self() = -1207409808
,08-23 12:25:19.136  6828  6875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 12:25:19.136  6828  6875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 12:25:19.136  6828  6875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 12:25:19.136  6828  6875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 12:25:19.136  6828  6875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 12:25:19.136  6828  6875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106a0138 added. We now have 1 listener(s)
,08-23 12:25:19.146  6828  6875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-23 12:25:19.146  6828  6875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-23 12:25:19.146  6828  6875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 12:25:19.146  6828  6875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 12:25:19.146  6828  6875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33342477 added. We now have 1 listener(s)
,08-23 12:25:19.146  6828  6875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:25:19.156  6828  6875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:25:19.156  6828  6875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 12:25:19.156  6828  6875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 12:25:19.156  6828  6875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 12:25:19.156  6828  6875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 12:25:19.156  6828  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:25:19.166  6828  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-23 12:25:19.166  6828  6875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 12:25:19.166  6828  6875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:25:19.166  6828  6875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:25:19.166  6828  6875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:25:19.166  6828  6875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:25:19.166  6828  6875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:25:19.166  6828  6875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:25:19.166  6828  6875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:25:19.166  6828  6875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:25:19.166  6828  6875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 12:25:19.166  6828  6875 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:25:19.166  6828  6875 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 12:25:19.166  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:25:19.176  6828  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:25:19.196  6828  6828 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 12:25:19.396  1016  1326 E Watchdog: !@Sync 3
,08-23 12:25:19.676  6828  6882 W jxcore-log: Initializing JXcore engine
08-23 12:25:19.676  6828  6882 W jxcore-log: JXcore engine is ready
,08-23 12:25:19.736  2011  2011 E audit   : type=1400 msg=audit(1471947919.736:205): avc:  denied  { ioctl } for  pid=6882 comm="Thread-1245" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 12:25:19.736  2011  2011 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:25:19.736  2011  2011 E audit   : type=1300 msg=audit(1471947919.736:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e5fb8f8 items=0 ppid=313 ppcomm=main pid=6882 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1245" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 12:25:19.736  2011  2011 E audit   : type=1320 msg=audit(1471947919.736:205): 
,08-23 12:25:19.746  6828  6882 W jxcore-log: Starting JXcore engine
,08-23 12:25:19.856  6828  6882 W jxcore-log: Platform android,
08-23 12:25:19.856  6828  6882 W jxcore-log: 
08-23 12:25:19.856  6828  6882 W jxcore-log: Process ARCH arm
08-23 12:25:19.856  6828  6882 W jxcore-log: 
,08-23 12:25:20.056  6828  6882 I jxcore-log: JXcore Cordova bridge is ready!
08-23 12:25:20.056  6828  6882 I jxcore-log: 
,08-23 12:25:20.056  6828  6882 W jxcore-log: JXcore engine is started
,08-23 12:25:20.076  6828  6875 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 12:25:20.076  6828  6828 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 12:25:20.096   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-23 12:25:20.096   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 12:25:20.096  6828  6882 E jxcore  : Error!: missing name after . operator
08-23 12:25:20.096  6828  6882 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 12:25:20.106  6828  6828 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56),
08-23 12:25:20.106  6828  6828 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 12:25:20.116  1016  1217 D FocusedStackFrame: Set to : 0
08-23 12:25:20.116  1016  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 12:25:20.116  1016  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 12:25:20.116  1016  1217 D InputDispatcher: Focused application set to: xxxx
08-23 12:25:20.116  1016  1217 D InputDispatcher: Focus left window: 6828
08-23 12:25:20.116  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 12:25:20.116  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 12:25:20.126  1016  1217 I ActivityManager: Killing 6499:com.samsung.helphub/1000 (adj 15): empty #21
,08-23 12:25:20.126  6828  6875 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 12:25:20.126  6828  6828 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 12:25:20.126  6828  6828 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-23 12:25:20.126  6828  6828 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:25:20.126  6828  6828 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:25:20.126  6828  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:25:20.126  6828  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:25:20.126  6828  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@106a0138 removed from the list
08-23 12:25:20.126  6828  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:25:20.126  6828  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33342477 removed from the list
08-23 12:25:20.126  6828  6828 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:25:20.126  6828  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 12:25:20.136  6828  6828 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 12:25:20.136   258  1111 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-23 12:25:20.136   258   440 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-23 12:25:20.146  1016  1028 W ActivityManager: mDVFSHelper.acquire()
,08-23 12:25:20.156  1016  1028 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-23 12:25:20.186  1499  1499 D Launcher: onRestart, Launcher: 618071289
,08-23 12:25:20.186  1499  1499 D Launcher: onStart, Launcher: 618071289
,08-23 12:25:20.186  1499  1499 D Launcher.HomeView: onStart
,08-23 12:25:20.186  1499  1499 D Launcher: onResume, Launcher: 618071289
08-23 12:25:20.186  1016  1217 D SettingsProvider: name = kids_home_mode
08-23 12:25:20.186  1016  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 12:25:20.186  1016  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 12:25:20.186  1016  1217 D SettingsProvider: selectionArgs: false
08-23 12:25:20.186  1016  1217 D SettingsProvider: selectionArgs: 10006
08-23 12:25:20.186  1016  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 12:25:20.186  1016  1217 D SettingsProvider: ret = -1
08-23 12:25:20.186  1499  1499 D Launcher.HomeView: onResume
,08-23 12:25:20.196  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 12:25:20.196  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:25:20.196  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.196  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-23 12:25:20.196  1499  1499 D MenuAppsGridFragment: onResume
,08-23 12:25:20.196  1499  1499 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-23 12:25:20.196  1016  1028 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
08-23 12:25:20.196  1016  1028 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-23 12:25:20.206  1499  1499 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-23 12:25:20.206  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:25:20.206  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.206  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
08-23 12:25:20.206  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-23 12:25:20.206  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:20.206  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.206  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:20.206  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:20.216  6886  6886 E Zygote  : MountEmulatedStorage(),
08-23 12:25:20.216  6886  6886 I libpersona: KNOX_SDCARD checking this for 10039
,08-23 12:25:20.216  6886  6886 E Zygote  : v2
08-23 12:25:20.216  6886  6886 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:20.216  6886  6886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:25:20.226  6886  6886 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:25:20.226  6886  6886 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:25:20.236  1016  1028 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6886 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-23 12:25:20.236  1016  1029 D ActivityManager: handle home activity for 0
08-23 12:25:20.236  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 12:25:20.236  1016  1029 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-23 12:25:20.236  1016  1029 D KnoxTimeoutHandler: post home show event for user 0
08-23 12:25:20.236  1016  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 12:25:20.236  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-23 12:25:20.236  1016  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 12:25:20.236  1016  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 12:25:20.236  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-23 12:25:20.236  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 12:25:20.236  1499  1499 D Launcher.HomeView: onPause
,08-23 12:25:20.236  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 12:25:20.246  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:20.246  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.246  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-23 12:25:20.246  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:20.246  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-23 12:25:20.246  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.246  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,08-23 12:25:20.246  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.246  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.246  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:20.246  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:20.256  6886  6886 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:20.256  6886  6886 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:20.266  1016  1041 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6901 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,08-23 12:25:20.266  6901  6901 E Zygote  : MountEmulatedStorage()
08-23 12:25:20.266  6901  6901 I libpersona: KNOX_SDCARD checking this for 10089
08-23 12:25:20.266  6901  6901 E Zygote  : v2
08-23 12:25:20.266  6901  6901 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:20.266  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:25:20.266  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
08-23 12:25:20.266  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:20.266  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.266  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-23 12:25:20.266  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.266  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:20.266  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.266  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:20.266  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:25:20.276  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-23 12:25:20.286  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:20.286  6901  6901 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:20.286  6914  6914 E Zygote  : MountEmulatedStorage(),
08-23 12:25:20.286  6914  6914 E Zygote  : v2
08-23 12:25:20.286  6914  6914 I libpersona: KNOX_SDCARD checking this for 10139
08-23 12:25:20.286  6914  6914 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:20.286  6914  6914 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:25:20.296  1016  1041 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6914 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,08-23 12:25:20.296  6914  6914 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:25:20.296  6914  6914 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 12:25:20.316  6901  6901 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 12:25:20.316  6901  6901 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-23 12:25:20.326  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:20.326  1016  1498 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1499, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-23 12:25:20.326  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.326  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-23 12:25:20.326  6886  6886 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 12:25:20.326  6886  6886 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:25:20.326  6886  6886 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 12:25:20.326  6886  6886 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 12:25:20.326  6886  6886 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 12:25:20.326  6886  6886 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 12:25:20.326  6886  6886 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-23 12:25:20.326  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:20.326  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.326  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
08-23 12:25:20.326   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-23 12:25:20.326  6914  6914 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:20.336  6914  6914 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:20.336  2584  2584 D Recents_RecreateReceiver: onReceive by home
,08-23 12:25:20.336  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 12:25:20.336  1016  1797 D InputDispatcher: Focus entered window: 1499
,08-23 12:25:20.336  1016  1808 W ActivityManager: userId = 0, bbcId = -10000,
08-23 12:25:20.346  1016  1808 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.346  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 12:25:20.346  1016  1808 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
08-23 12:25:20.346  1016  1808 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
08-23 12:25:20.346  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 12:25:20.346  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 12:25:20.346  1499  1499 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 12:25:20.346  1016  1808 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.346  1016  1808 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.346  1016  1808 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.346  1016  1808 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:20.366  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{1e140c9e token=android.os.BinderProxy@33cdeb71 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-23 12:25:20.366  1499  1499 D Launcher.HomeView: onStop
,08-23 12:25:20.366  1016  1456 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 12:25:20.366  6828  6828 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 12:25:20.376  1894  1894 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-23 12:25:20.376  1016  6932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 12:25:20.376  1016  1808 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6935 uid=10084 gids={50084, 9997} abi=armeabi-v7a,
08-23 12:25:20.376  1174  1174 I StatusBar: Icon Only
,08-23 12:25:20.386  6935  6935 E Zygote  : MountEmulatedStorage()
08-23 12:25:20.386  6935  6935 I libpersona: KNOX_SDCARD checking this for 10084
08-23 12:25:20.386  6935  6935 E Zygote  : v2
08-23 12:25:20.386  6935  6935 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:20.386  1174  1174 D PanelView: There is/are notification(s) 
08-23 12:25:20.386  6935  6935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:25:20.386  6914  6914 V TaskCloserActivity: TaskCloserActivity enter()
,08-23 12:25:20.386  6935  6935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 12:25:20.386  6935  6935 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-23 12:25:20.396  6883  6883 D AndroidRuntime: 
08-23 12:25:20.396  6883  6883 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 12:25:20.396  6883  6883 D AndroidRuntime: CheckJNI is OFF
08-23 12:25:20.396  6883  6883 D AndroidRuntime: readGMSProperty: start
08-23 12:25:20.396  6883  6883 D AndroidRuntime: readGMSProperty: already setted!!
08-23 12:25:20.396  6883  6883 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 12:25:20.396  6883  6883 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 12:25:20.396  6883  6883 D AndroidRuntime: readGMSProperty: end
08-23 12:25:20.396  6883  6883 D AndroidRuntime: addProductProperty: start
,08-23 12:25:20.406  6914  6914 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-23 12:25:20.406  1499  1499 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33cdeb71 time:109385
,08-23 12:25:20.406  1016  1456 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:20.406  1016  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.406  1016  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
08-23 12:25:20.406  1016  1456 I ActivityManager: Killing 6530:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-23 12:25:20.416  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:20.416  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.416  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
08-23 12:25:20.416  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
08-23 12:25:20.426  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.426  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.426  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.426  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.436  6935  6935 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:20.436  6935  6935 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:20.436  6952  6952 E Zygote  : MountEmulatedStorage()
08-23 12:25:20.436  6952  6952 E Zygote  : v2
08-23 12:25:20.436  6952  6952 I libpersona: KNOX_SDCARD checking this for 10135
08-23 12:25:20.436  6952  6952 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:20.446  6952  6952 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-23 12:25:20.446  1016  1029 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6952 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,08-23 12:25:20.446  1016  1029 I ActivityManager: Killing 6562:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-23 12:25:20.446  1016  1046 W ActivityManager: mDVFSHelper.release()
08-23 12:25:20.446  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{caa6b91 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:109425
08-23 12:25:20.446  6952  6952 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:25:20.456  6952  6952 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:25:20.456  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-23 12:25:20.466  6935  6935 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 12:25:20.476  6952  6952 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:20.476  6952  6952 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:20.496  1016  4284 D PersonaManager: isKioskContainerExistOnDevice
,08-23 12:25:20.496  6952  6952 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-23 12:25:20.496  6952  6952 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 12:25:20.496  6952  6952 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 12:25:20.496  6952  6952 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-23 12:25:20.496  6952  6952 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 12:25:20.506  1016  1213 I ActivityManager: Killing 6608:com.samsung.android.sm/1000 (adj 15): empty #21
,08-23 12:25:20.536  6886  6886 D NearbySource: Nearby Source Create!
,08-23 12:25:20.536  6886  6886 D NearbyContext: Nearby Context Create!
,08-23 12:25:20.546  6883  6883 E AffinityControl: AffinityControl: registerfunction enter
,08-23 12:25:20.546  1016  1317 I ActivityManager: Killing 6592:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-23 12:25:20.576  6883  6883 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-23 12:25:20.576   257   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-23 12:25:20.576   257   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 12:25:20.576  6886  6886 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-23 12:25:20.576  6886  6886 D SLinkSource: Samsung link source created
,08-23 12:25:20.586  1016  1808 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 12:25:20.586  1016  1808 D PackageManager: START PACKAGE DELETE: observer{144486557}
08-23 12:25:20.586  1016  1808 D PackageManager: pkg{<packageName>}
08-23 12:25:20.586  1016  1808 D PackageManager: user{0}
08-23 12:25:20.586  1016  1808 D PackageManager: caller{2000}
08-23 12:25:20.586  1016  1808 D PackageManager: flags{2}
08-23 12:25:20.586  1016  1808 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 12:25:20.586  1016  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 12:25:20.586  1016  1808 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 12:25:20.586  1016  1808 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 12:25:20.586  1016  1808 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 12:25:20.586  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 12:25:20.586  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 12:25:20.586  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 12:25:20.586  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 12:25:20.586  1016  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-23 12:25:20.586  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-23 12:25:20.586  1016  1041 I ActivityManager: Killing 6828:com.test.thalitest/u0a171 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-23 12:25:20.676  1016  1055 W PackageSettings: Skipping PackageSetting{1fe74d3 com.example.hello/10168} due to missing metadata
,08-23 12:25:20.706  1016  1456 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 12:25:20.726  1016  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 12:25:20.726  1016  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-23 12:25:20.726  6886  6886 D GalleryCacheReady: Receive : home resume
,08-23 12:25:20.736  1016  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-23 12:25:20.756  6886  6977 D ContactProvider: getAllContactInfoList Start
,08-23 12:25:20.786  1016  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 12:25:20.786  2718  2718 I art     : Explicit concurrent mark sweep GC freed 21864(1213KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 943us total 48.315ms
,08-23 12:25:20.806  1894  1894 E SamsungIME: mOCRHelper is null
,08-23 12:25:20.806  2039  2219 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 12:25:20.816  1469  1469 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 12:25:20.826  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:20.826  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.826  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-23 12:25:20.826  4861  4861 I art     : Explicit concurrent mark sweep GC freed 1311(52KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/16MB, paused 1.133ms total 84.821ms
,08-23 12:25:20.836  6164  6164 D Mms/UIEventReceiver: ui event
,08-23 12:25:20.846  1016  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
,08-23 12:25:20.846  1016  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-23 12:25:20.856  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:25:20.856  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 12:25:20.856  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 12:25:20.856  1016  1213 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-23 12:25:20.856  1016  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:25:20.856  1016  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.856  1016  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-23 12:25:20.866  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:25:20.866  1016  1123 V NetworkStats: performPollLocked() took 12ms
,08-23 12:25:20.866  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,08-23 12:25:20.866  1455  1455 D RegisteredServicesCache: empty dynamic service
,08-23 12:25:20.876  6914  6914 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-23 12:25:20.886  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-23 12:25:20.886  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-23 12:25:20.886  1016  1040 W TextServicesManagerService: no available spell checker services found
,08-23 12:25:20.896  1016  1029 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-23 12:25:20.896  1016  1029 D SecContentProvider2: mCursor = null
,08-23 12:25:20.896  2943  2943 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 12:25:20 GMT+02:00 2016
,08-23 12:25:20.896  1016  1498 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-23 12:25:20.896  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 12:25:20.896  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:20.896  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:20.896  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 12:25:20.906  1455  1455 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 12:25:20.906  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,08-23 12:25:20.916  2943  2943 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 12:25:20.926  1016  1496 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-23 12:25:20.926  1016  1496 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-23 12:25:20.936  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:25:20.936  6737  6737 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-23 12:25:20.946  1016  1317 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-23 12:25:20.946  1016  1317 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-23 12:25:20.946  1016  1317 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:25:20.946  1016  1317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 12:25:20.946  1016  1317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-23 12:25:20.946  6737  6737 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-23 12:25:20.946  2943  2943 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 12:25:20.956  6737  6737 D elm:15121: ElmAgentService : onCreate()
08-23 12:25:20.956  2943  2943 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 12:25:20.956  6737  6980 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-23 12:25:20.956  6737  6980 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-23 12:25:20.956  6737  6980 D elm:15121: MDMBridge.getInstance()
,08-23 12:25:20.956  6737  6980 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 12:25:20.956  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:25:20.956  2943  2943 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 12:25:20.956  6737  6980 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 12:25:20.966  1016  1016 I art     : Explicit concurrent mark sweep GC freed 46624(3MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 24MB/36MB, paused 4.159ms total 214.625ms
,08-23 12:25:20.966  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 12:25:20.966  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 12:25:20.966  1016  1055 I art     : WaitForGcToComplete blocked for 130.070ms for cause Explicit
,08-23 12:25:20.966  2943  6979 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-23 12:25:20.966  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-23 12:25:20.966  1016  1217 I TactileAssist: enable value -1
08-23 12:25:20.966  1016  1217 I TactileAssist: internal enable value -1
08-23 12:25:20.966  1016  1217 I TactileAssist: intensity value -1
08-23 12:25:20.966  1016  1217 I TactileAssist: saveAppList value true
,08-23 12:25:20.976  1016  1217 I TactileAssist: List of disabled apps :
,08-23 12:25:20.976  2943  6979 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-23 12:25:20.986  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.986  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.986  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:20.986  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:20.986  2943  6979 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-23 12:25:20.996  2943  6979 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-23 12:25:20.996  6982  6982 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:25:20.996  6982  6982 E Zygote  : MountEmulatedStorage()
08-23 12:25:20.996  6982  6982 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:20.996  6982  6982 E Zygote  : v2
08-23 12:25:20.996  1016  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 12:25:20.996  6982  6982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:25:20.996  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-23 12:25:20.996  6886  6977 D ContactProvider: getAllContactInfoList End
08-23 12:25:20.996  6982  6982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:25:20.996  6982  6982 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:25:21.006  6886  6977 I syncContacts: thread: 1228, sync time = 391
,08-23 12:25:21.006  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.006  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.006  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.006  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.026  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:25:21.026  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-23 12:25:21.026  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-23 12:25:21.036  6994  6994 E Zygote  : MountEmulatedStorage()
08-23 12:25:21.036  6994  6994 E Zygote  : v2
08-23 12:25:21.036  6994  6994 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:25:21.036  6994  6994 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:21.036  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-23 12:25:21.036  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-23 12:25:21.036  6994  6994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:25:21.036  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
08-23 12:25:21.036  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:25:21.036  6994  6994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:25:21.036  6994  6994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:25:21.046  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter,
,08-23 12:25:21.046  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-23 12:25:21.046  1016  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6994 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 12:25:21.066  6982  6982 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:21.066  6982  6982 D ActivityThread: Added TimaKeyStore provider
08-23 12:25:21.066  6737  6737 D elm:15121: ElmAgentService : onDestroy().
08-23 12:25:21.066  6994  6994 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:21.066  6994  6994 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.076  2943  6979 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-23 12:25:21.086  1016  1496 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-23 12:25:21.086  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.086  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.086  2943  6979 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-23 12:25:21.086  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.086  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.096  2943  6979 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-23 12:25:21.096   291   291 E SMD     : DCD OFF
08-23 12:25:21.096  7012  7012 I libpersona: KNOX_SDCARD checking this for 10048
08-23 12:25:21.096  7012  7012 E Zygote  : MountEmulatedStorage()
08-23 12:25:21.096  7012  7012 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:21.096  7012  7012 E Zygote  : v2
,08-23 12:25:21.106  7012  7012 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 12:25:21.106  7012  7012 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:25:21.106  7012  7012 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
08-23 12:25:21.106  1016  1496 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7012 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-23 12:25:21.126  2943  2943 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-23 12:25:21.136  6994  6994 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-23 12:25:21.136  1016  1464 D SecContentProvider2: uri = -1 selection = getSealedState
,08-23 12:25:21.136  1016  1464 D SecContentProvider2: mCursor = null
,08-23 12:25:21.146  6994  6994 I PopupuiReceiver_KNOX: getSealedState : true,
08-23 12:25:21.146  1016  1489 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-23 12:25:21.146  1016  1489 D SecContentProvider2: mCursor = null
,08-23 12:25:21.146  6994  6994 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-23 12:25:21.146  1016  1213 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-23 12:25:21.146  1016  1213 D SecContentProvider2: mCursor = null
08-23 12:25:21.146  7012  7012 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:21.146  7012  7012 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.146  6994  6994 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-23 12:25:21.146  6994  6994 D PopupuiReceiver: Action package removed
,08-23 12:25:21.146  1016  1317 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-23 12:25:21.156  6982  6982 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 ,
,08-23 12:25:21.156  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.156  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.156  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.156  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.176  7027  7027 E Zygote  : MountEmulatedStorage(),
08-23 12:25:21.176  7027  7027 E Zygote  : v2
08-23 12:25:21.176  7027  7027 I libpersona: KNOX_SDCARD checking this for 10145,
08-23 12:25:21.176  7027  7027 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:21.176  7027  7027 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 12:25:21.186  7027  7027 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:25:21.186  7027  7027 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:25:21.186  1016  1317 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7027 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 12:25:21.186  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-23 12:25:21.196  1016  1317 I ActivityManager: Killing 6639:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-23 12:25:21.196  1016  1055 I art     : Explicit concurrent mark sweep GC freed 14845(984KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 3.096ms total 226.679ms
,08-23 12:25:21.196  1016  1498 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-23 12:25:21.196  1016  1498 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-23 12:25:21.196  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:25:21.206  1016  1498 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:21.206  1016  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:21.206  1016  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-23 12:25:21.216  7027  7027 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:21.216  7027  7027 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.216  1016  1317 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-23 12:25:21.226  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.226  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.226  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.226  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.236  7044  7044 E Zygote  : MountEmulatedStorage(),
08-23 12:25:21.236  7044  7044 E Zygote  : v2
08-23 12:25:21.236  7044  7044 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:25:21.236  7044  7044 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:21.236  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:25:21.236  1016  1055 D PackageManager: delete codoeFile: ,
08-23 12:25:21.236  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 12:25:21.236  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:25:21.246  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 12:25:21.246  1016  1317 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7044 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 12:25:21.256  1016  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-23 12:25:21.256  1016  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-23 12:25:21.256  1016  1055 D PackageManager: result of delete: 1{144486557}
,08-23 12:25:21.256  6883  6883 D AndroidRuntime: Shutting down VM
,08-23 12:25:21.266  7012  7012 D Compatibility: onReceive() it will make start service
08-23 12:25:21.266  1016  1489 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-23 12:25:21.266  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-23 12:25:21.266  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:21.266  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:21.266  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-23 12:25:21.266   313   313 I art     : Explicit concurrent mark sweep GC freed 8704(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 24.259ms
,08-23 12:25:21.276  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:21.276  1016  4284 I ActivityManager: Killing 6660:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21,
08-23 12:25:21.276  7044  7044 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.286   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 16.730ms
,08-23 12:25:21.296  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 12:25:21.296  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 12:25:21.296  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-23 12:25:21.296  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-23 12:25:21.296  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 12:25:21.296  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 12:25:21.296  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 12:25:21.296  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 12:25:21.296  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 12:25:21.296  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-23 12:25:21.296  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-23 12:25:21.296  1016  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 12:25:21.296  1016  1055 D PackageManager: userId{-1}
08-23 12:25:21.296  1016  1055 D PackageManager: andCode{true}
08-23 12:25:21.296  7012  7059 D Compatibility: onHandleIntent()
,08-23 12:25:21.296  7012  7059 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-23 12:25:21.306  1016  1797 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-23 12:25:21.306  7012  7059 D Compatibility: found: 2
,08-23 12:25:21.306  1016  1797 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.306  1016  1797 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.306  1016  1797 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.306  1016  1797 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.306   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 17.039ms
,08-23 12:25:21.306  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-23 12:25:21.316  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 12:25:21.316  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:25:21.316  7012  7059 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-23 12:25:21.316  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 12:25:21.316  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 12:25:21.316  7012  7059 D Compatibility: skipping ResolveInfo{e3693a8 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-23 12:25:21.316  7012  7059 D Compatibility: considering ResolveInfo{a2a3ec1 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-23 12:25:21.316  7012  7059 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-23 12:25:21.316  7044  7044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 12:25:21.326  7061  7061 E Zygote  : MountEmulatedStorage()
,08-23 12:25:21.326  7061  7061 E Zygote  : v2
08-23 12:25:21.326  7061  7061 I libpersona: KNOX_SDCARD checking this for 10052
08-23 12:25:21.326  7061  7061 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:21.326  7061  7061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:25:21.326  7012  7059 D Compatibility: enabling receiver ResolveInfo{3d61b666 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-23 12:25:21.326  1016  1797 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7061 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-23 12:25:21.326  7061  7061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:25:21.336  7061  7061 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 12:25:21.336  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 12:25:21.336  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 12:25:21.336  1016  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-23 12:25:21.336  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-23 12:25:21.336  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-23 12:25:21.336  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 12:25:21.336  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-23 12:25:21.336  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 12:25:21.336  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 12:25:21.336  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 12:25:21.336  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 12:25:21.336  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 12:25:21.336  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-23 12:25:21.336  1016  3382 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-23 12:25:21.336  7012  7059 D Compatibility: enabling receiver ResolveInfo{2111eda7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-23 12:25:21.336  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.336  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.336  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.336  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.346  7044  7044 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-23 12:25:21.346  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:25:21.346  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 12:25:21.346  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 12:25:21.356  7012  7059 D Compatibility: enabling receiver ResolveInfo{1354254 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-23 12:25:21.356  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 12:25:21.356  7012  7059 D Compatibility: enabling receiver ResolveInfo{1edb05fd com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-23 12:25:21.366  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 12:25:21.366  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-23 12:25:21.366  1016  1456 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-23 12:25:21.366  1016  1456 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-23 12:25:21.366  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 12:25:21.366  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 12:25:21.366  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-23 12:25:21.376  7012  7059 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-23 12:25:21.376  7072  7072 E Zygote  : MountEmulatedStorage()
08-23 12:25:21.376  7072  7072 E Zygote  : v2
08-23 12:25:21.376  7072  7072 I libpersona: KNOX_SDCARD checking this for 1000
08-23 12:25:21.376  7072  7072 I libpersona: KNOX_SDCARD not a persona
08-23 12:25:21.376  7072  7072 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 12:25:21.376  7072  7072 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 12:25:21.376  7072  7072 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:25:21.376  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7072 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 12:25:21.386  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-23 12:25:21.386  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-23 12:25:21.386  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-23 12:25:21.386  7061  7061 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:21.386  1016  1464 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-23 12:25:21.386  7061  7061 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.386  7027  7027 D ThemeInfoUtil: getCurrentFestivalName is [null]
,08-23 12:25:21.396  7027  7027 D ThemeInfoUtil: isCurrentFestival = false
08-23 12:25:21.396  1016  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.396  1016  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.396  1016  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.396  1016  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.396  7072  7072 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:21.396  7072  7072 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.406  7092  7092 E Zygote  : MountEmulatedStorage()
08-23 12:25:21.406  7092  7092 E Zygote  : v2
08-23 12:25:21.406  7092  7092 I libpersona: KNOX_SDCARD checking this for 10087
08-23 12:25:21.406  7092  7092 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:21.406  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:25:21.406  1016  1464 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7092 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a,
,08-23 12:25:21.406  1016  1464 I ActivityManager: Killing 6679:com.osp.app.signin/u0a36 (adj 15): empty #21
08-23 12:25:21.416  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:25:21.416  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 12:25:21.426  1016  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 12:25:21.436  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:21.436  7092  7092 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.436  1016  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-23 12:25:21.436  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.436  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.436  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.436  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.456  7108  7108 E Zygote  : MountEmulatedStorage(),
08-23 12:25:21.456  7108  7108 E Zygote  : v2
08-23 12:25:21.456  7108  7108 I libpersona: KNOX_SDCARD checking this for 10148
08-23 12:25:21.456  7108  7108 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:21.456  7108  7108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 12:25:21.456  7108  7108 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 12:25:21.456  7108  7108 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 12:25:21.466  1016  1496 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7108 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-23 12:25:21.466  1016  1496 I ActivityManager: Killing 6695:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-23 12:25:21.466  6883  6883 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 12:25:21.486  1016  4284 I ActivityManager: Killing 6628:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-23 12:25:21.486  7108  7108 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:21.486  7108  7108 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.506  7072  7072 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-23 12:25:21.506  7072  7072 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-23 12:25:21.506  7072  7072 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-23 12:25:21.516  1016  1498 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-23 12:25:21.516  1016  1456 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-23 12:25:21.526  7072  7072 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-23 12:25:21.526  7072  7072 I PCWCLIENTTRACE_PushUtil: sales region : global
08-23 12:25:21.526  7072  7072 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-23 12:25:21.526  7072  7072 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-23 12:25:21.526  1016  1317 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast,
,08-23 12:25:21.526  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.526  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.526  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.526  1016  1317 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.536  7108  7108 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-23 12:25:21.556  7125  7125 E Zygote  : MountEmulatedStorage()
08-23 12:25:21.556  7125  7125 E Zygote  : v2
08-23 12:25:21.556  7125  7125 I libpersona: KNOX_SDCARD checking this for 10029
08-23 12:25:21.556  7125  7125 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:21.556  7125  7125 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:25:21.556  1016  1317 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7125 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-23 12:25:21.556  1016  1317 I ActivityManager: Killing 6717:com.qualcomm.timeservice/1000 (adj 15): empty #21,
08-23 12:25:21.556  7125  7125 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:25:21.556  7125  7125 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 12:25:21.566  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox,
08-23 12:25:21.566  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-23 12:25:21.566  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:21.566  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:25:21.566  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-23 12:25:21.566  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-23 12:25:21.566  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-23 12:25:21.566  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-23 12:25:21.576  1016  1464 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 12:25:21.566  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 12:25:21.576  1016  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-23 12:25:21.566  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
08-23 12:25:21.576  1016  1464 W ActivityManager: userId = 0, bbcId = -10000
08-23 12:25:21.576  1016  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 12:25:21.576  1016  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-23 12:25:21.576  1016  1808 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-23 12:25:21.576  7125  7125 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 12:25:21.576  1016  1808 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.576  1016  1808 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.576  1016  1808 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.576  1016  1808 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.586  7125  7125 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.596  7142  7142 E Zygote  : MountEmulatedStorage()
,08-23 12:25:21.596  7142  7142 E Zygote  : v2
,08-23 12:25:21.596  7142  7142 I libpersona: KNOX_SDCARD checking this for 10152
08-23 12:25:21.596  7142  7142 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:21.606  7142  7142 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 12:25:21.606  1016  1808 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7142 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-23 12:25:21.606  7142  7142 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 12:25:21.606  7142  7142 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 12:25:21.616  1016  1028 I ActivityManager: Killing 6754:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-23 12:25:21.626  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-23 12:25:21.626  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.626  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.626  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 12:25:21.626  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 12:25:21.636  7142  7142 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 12:25:21.636  7142  7142 D ActivityThread: Added TimaKeyStore provider
,08-23 12:25:21.656  1016  1028 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7157 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-23 12:25:21.656  7157  7157 E Zygote  : MountEmulatedStorage()
08-23 12:25:21.656  7157  7157 E Zygote  : v2
08-23 12:25:21.656  7157  7157 I libpersona: KNOX_SDCARD checking this for 10055
08-23 12:25:21.656  7157  7157 I libpersona: KNOX_SDCARD not a persona
,08-23 12:25:21.666  7157  7157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 12:25:21.666  7157  7157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,

```
