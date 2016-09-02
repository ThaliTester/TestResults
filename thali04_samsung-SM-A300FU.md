#### Test 81418577ad1885e_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
09-02 12:07:27.086   295   295 E SMD     : DCD OFF
,09-02 12:07:27.976  6743  6743 D AndroidRuntime: 
09-02 12:07:27.976  6743  6743 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 12:07:27.986  6743  6743 D AndroidRuntime: CheckJNI is OFF
09-02 12:07:27.986  6743  6743 D AndroidRuntime: readGMSProperty: start
09-02 12:07:27.986  6743  6743 D AndroidRuntime: readGMSProperty: already setted!!
09-02 12:07:27.986  6743  6743 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-02 12:07:27.986  6743  6743 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-02 12:07:27.986  6743  6743 D AndroidRuntime: readGMSProperty: end
09-02 12:07:27.986  6743  6743 D AndroidRuntime: addProductProperty: start
09-02 12:07:28.116  6743  6743 E AffinityControl: AffinityControl: registerfunction enter
09-02 12:07:28.146  6743  6743 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-02 12:07:28.156  1017  1471 E PersonaManagerService: inState():  stateMachine is null !!
09-02 12:07:28.156  1017  1471 I PersonaManagerService: PersonaId don't exist
09-02 12:07:28.156  1017  1471 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-02 12:07:28.156  1017  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-02 12:07:28.186  1017  1471 W ActivityManager: mDVFSHelper.acquire()
09-02 12:07:28.186   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-02 12:07:28.186   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-02 12:07:28.196  1017  1471 D FocusedStackFrame: Set to : 0
09-02 12:07:28.206  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-02 12:07:28.206  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-02 12:07:28.206  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:28.206  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:28.206  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:28.206  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:28.216  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-02 12:07:28.216  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-02 12:07:28.216   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-02 12:07:28.226  1017  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-02 12:07:28.226  1017  1471 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6754 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-02 12:07:28.226  1017  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-02 12:07:28.226  6754  6754 I libpersona: KNOX_SDCARD checking this for 10171
09-02 12:07:28.226  6754  6754 E Zygote  : MountEmulatedStorage()
09-02 12:07:28.226  6754  6754 I libpersona: KNOX_SDCARD not a persona
09-02 12:07:28.226  6754  6754 E Zygote  : v2
09-02 12:07:28.226  6754  6754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:28.236  1017  1471 D InputDispatcher: Focused application set to: xxxx
09-02 12:07:28.236  1017  1471 D InputDispatcher: Focus left window: 1484
09-02 12:07:28.236  6754  6754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:07:28.236  6743  6743 D AndroidRuntime: Shutting down VM
09-02 12:07:28.236  6754  6754 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-02 12:07:28.236  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 12:07:28.236  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-02 12:07:28.256  6754  6754 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 12:07:28.256  6754  6754 D ActivityThread: Added TimaKeyStore provider
09-02 12:07:28.266  1017  1481 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-02 12:07:28.266  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-02 12:07:28.276  1017  1017 V ActivityManager: Display changed displayId=0
09-02 12:07:28.296  1017  1481 D PersonaManager: isKioskContainerExistOnDevice
09-02 12:07:28.306  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-02 12:07:28.316   258  1102 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
09-02 12:07:28.316   258  6012 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
09-02 12:07:28.316  1484  1484 V ActivityThread: updateVisibility : ActivityRecord{27050d13 token=android.os.BinderProxy@3156533a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-02 12:07:28.316  1484  1484 D Launcher: onTrimMemory. Level: 20
09-02 12:07:28.416  6754  6754 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-02 12:07:28.446  6743  6743 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-02 12:07:28.466  6754  6754 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 5329-5333)
,09-02 12:07:28.466  6754  6754 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-02 12:07:28.486  6754  6754 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5336616}
,09-02 12:07:28.486  6754  6754 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-02 12:07:28.486  6754  6754 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 12:07:28.526  6754  6754 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-02 12:07:28.536  6754  6754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:07:28.536  6754  6754 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 12:07:28.566  6754  6754 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 12:07:28.566  6754  6754 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 12:07:28.566  6754  6754 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 12:07:28.566  6754  6754 I Adreno-EGL: Local Branch: 
09-02 12:07:28.566  6754  6754 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 12:07:28.566  6754  6754 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 12:07:28.566  6754  6754 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 12:07:28.656  6754  6754 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 12:07:28.676  6754  6754 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-02 12:07:28.676  6754  6754 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-02 12:07:28.686  6754  6754 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-02 12:07:28.686  6754  6754 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-02 12:07:28.776  6754  6754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:07:28.796  6754  6754 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 12:07:28.796  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{1703a48b u0 com.test.thalitest/.MainActivity t2}
,09-02 12:07:28.806  6754  6754 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-02 12:07:28.806  6754  6754 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-02 12:07:28.816  6754  6754 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-02 12:07:28.816  6754  6754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:07:28.816  6754  6754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:07:28.866  6754  6793 D OpenGLRenderer: Render dirty regions requested: true
,09-02 12:07:28.866  1017  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-02 12:07:28.866  1017  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-02 12:07:28.866  1017  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-02 12:07:28.866  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-02 12:07:28.866  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-02 12:07:28.876  6754  6781 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-02 12:07:28.876  6754  6754 V ActivityThread: updateVisibility : ActivityRecord{10ffa776 token=android.os.BinderProxy@3076069b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-02 12:07:28.886  6754  6754 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-02 12:07:28.886  6754  6754 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-02 12:07:28.896   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-02 12:07:28.916  1017  1029 D InputDispatcher: Focus entered window: 6754
,09-02 12:07:28.916  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-02 12:07:28.916  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 12:07:28.916  6754  6754 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-02 12:07:28.916  6754  6793 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 12:07:28.926  6754  6793 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-02 12:07:28.926  6754  6793 D OpenGLRenderer: Enabling debug mode 0
,09-02 12:07:28.946  1017  1483 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-02 12:07:28.946  1017  6798 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 12:07:28.956  1173  1173 I StatusBar: Icon Only
09-02 12:07:28.956  1173  1173 D PanelView: There is/are notification(s) 
,09-02 12:07:28.966  1017  1047 I ActivityManager: Displayed Component not be shown by security: +667ms (total +757ms)
,09-02 12:07:28.966  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1703a48b u0 com.test.thalitest/.MainActivity t2} time:105834
09-02 12:07:28.966  1017  1047 W ActivityManager: mDVFSHelper.release()
,09-02 12:07:28.966   258   438 I SurfaceFlinger: id=12 Removed uhalitest (7/9),
09-02 12:07:28.976   258  6013 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-02 12:07:28.976  6754  6754 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-02 12:07:28.976  6754  6754 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3076069b time:105843
,09-02 12:07:28.996  1915  1915 I SamsungIME: getCurrentCandidateView
,09-02 12:07:29.096  6754  6754 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6754
,09-02 12:07:29.126  1915  1915 D SamsungIME: Dismiss ExpandCandiate
,09-02 12:07:29.276  1915  1915 I SamsungIME: getDebugLevel  : 0x4f4c,
,09-02 12:07:29.286  1017  2016 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 12:07:29.286  1017  2016 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-02 12:07:29.286  1017  2016 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-02 12:07:29.286  1017  2016 D BatteryService: stay LED for fully charged
,09-02 12:07:29.286  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 12:07:29.296  1017  1017 I MotionRecognitionService: Plugged
,09-02 12:07:29.296  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 12:07:29.296  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-02 12:07:29.296  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 12:07:29.296  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 12:07:29.296  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-02 12:07:29.306  3176  3176 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-02 12:07:29.306  3176  3280 D HeadsetStateMachine: Disconnected process message: 10
,09-02 12:07:29.326  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-02 12:07:29.326  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-02 12:07:29.326  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:29.326  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:29.326  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:29.346  1915  1915 I SamsungIME: getDebugLevel  : 0x4f4c
,09-02 12:07:29.356  1915  1915 I SamsungIME: KeybaordView init() : load resources
,09-02 12:07:29.376  1915  1915 I SamsungIME: getCurrentKeyboard
09-02 12:07:29.376  1915  1915 I SamsungIME: getTextKeyboard
,09-02 12:07:29.406  1915  1915 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-02 12:07:29.446  6754  6754 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 12:07:29.526  6754  6800 D jxcore_app_log: JniHelper::setJavaVM(0xb79682b0), pthread_self() = -1209048104
,09-02 12:07:29.536  6754  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 12:07:29.536  6754  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 12:07:29.536  6754  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 12:07:29.536  6754  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 12:07:29.536  6754  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-02 12:07:29.536  6754  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1410697c added. We now have 1 listener(s)
,09-02 12:07:29.546  6754  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-02 12:07:29.546  6754  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-02 12:07:29.546  6754  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:07:29.546  6754  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-02 12:07:29.546  6754  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a1cc8b added. We now have 1 listener(s)
09-02 12:07:29.546  6754  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:07:29.556  6754  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:07:29.556  6754  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-02 12:07:29.556  6754  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 12:07:29.556  6754  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 12:07:29.556  6754  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2,
,09-02 12:07:29.556  6754  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:07:29.566  6754  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-02 12:07:29.566  6754  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 12:07:29.566  6754  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:29.566  6754  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:29.566  6754  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:29.566  6754  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:29.566  6754  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:29.566  6754  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:29.566  6754  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:29.566  6754  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:29.566  6754  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 12:07:29.566  6754  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:07:29.576  6754  6800 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 12:07:29.576  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:29.576  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:29.596  6754  6754 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 12:07:30.086   295   295 E SMD     : DCD OFF
,09-02 12:07:30.126  6754  6808 W jxcore-log: Initializing JXcore engine
09-02 12:07:30.126  6754  6808 W jxcore-log: JXcore engine is ready
,09-02 12:07:30.176  2028  2028 E audit   : type=1400 msg=audit(1472810850.176:205): avc:  denied  { ioctl } for  pid=6808 comm="Thread-1256" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-02 12:07:30.176  2028  2028 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:07:30.176  2028  2028 E audit   : type=1300 msg=audit(1472810850.176:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9e45c8f8 items=0 ppid=314 ppcomm=main pid=6808 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1256" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-02 12:07:30.176  2028  2028 E audit   : type=1320 msg=audit(1472810850.176:205): 
,09-02 12:07:30.186  6754  6808 W jxcore-log: Starting JXcore engine
,09-02 12:07:30.296  6754  6808 W jxcore-log: Platform android
09-02 12:07:30.296  6754  6808 W jxcore-log: 
09-02 12:07:30.296  6754  6808 W jxcore-log: Process ARCH arm
09-02 12:07:30.296  6754  6808 W jxcore-log: 
,09-02 12:07:30.506  6754  6808 I jxcore-log: JXcore Cordova bridge is ready!
09-02 12:07:30.506  6754  6808 I jxcore-log: 
,09-02 12:07:30.506  6754  6808 W jxcore-log: JXcore engine is started
,09-02 12:07:30.516  6754  6800 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 12:07:30.516  6754  6754 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 12:07:31.206  1017  1309 E Watchdog: !@Sync 3,
,09-02 12:07:32.146   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
09-02 12:07:32.146   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-02 12:07:33.086   295   295 E SMD     : DCD OFF,
,09-02 12:07:34.826  1017  3339 D SSRM:n  : SIOP:: AP = 340
,09-02 12:07:34.866  1017  1049 I PowerManagerService: [PWL] Off : 50s ago,
,09-02 12:07:36.086   295   295 E SMD     : DCD OFF,
,09-02 12:07:37.146   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 12:07:37.936  5649  5649 D FactoryTest: Not factory mode
,09-02 12:07:37.936  5649  5649 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-02 12:07:37.936  5649  5649 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-02 12:07:37.936  5649  5649 D MTPRx   : still no open session command from host, so toast
,09-02 12:07:37.936  5649  5649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-02 12:07:37.936  5649  5649 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-02 12:07:37.936  5649  5649 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114808
,09-02 12:07:37.936  1017  1481 E PersonaManagerService: inState():  stateMachine is null !!
,09-02 12:07:37.946  1017  1481 I PersonaManagerService: PersonaId don't exist
09-02 12:07:37.946  1017  1481 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-02 12:07:37.946  1017  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-02 12:07:37.946  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:37.946  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:37.946  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-02 12:07:37.956  1017  1481 W ActivityManager: mDVFSHelper.acquire()
,09-02 12:07:37.966  1017  1481 D PersonaManager: isKioskContainerExistOnDevice
,09-02 12:07:37.976  1017  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-02 12:07:37.976  1017  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-02 12:07:37.976  1017  1481 D InputDispatcher: Focused application set to: xxxx
09-02 12:07:37.976  1017  1481 D InputDispatcher: Focus left window: 6754
,09-02 12:07:37.976  5649  5649 E MTPRx   : started activity for popup,
,09-02 12:07:37.986  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 12:07:37.986  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 12:07:38.006  5649  5649 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-02 12:07:38.006  5649  5649 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-02 12:07:38.006  5649  5649 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-02 12:07:38.006  5649  5649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:07:38.006  5649  5649 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 12:07:38.006  5649  5649 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 12:07:38.026  5649  5649 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-02 12:07:38.026  1017  2016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-02 12:07:38.026  1017  2016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-02 12:07:38.026  1017  2016 D InputDispatcher: Focused application set to: xxxx
,09-02 12:07:38.026  1017  2016 D InputDispatcher: Focus entered window: 6754
,09-02 12:07:38.036  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-02 12:07:38.036  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 12:07:38.036  1017  4396 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-02 12:07:38.036  1017  4396 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@368d296a attribute=null, token = android.os.BinderProxy@1821ddba
,09-02 12:07:38.076  5649  5649 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-02 12:07:38.086  5649  5649 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-02 12:07:38.086  5649  5649 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-02 12:07:38.106  6754  6754 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-02 12:07:38.106  6754  6754 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-02 12:07:38.106  6754  6754 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 12:07:38.106  6754  6754 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-02 12:07:38.116  1017  1383 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-02 12:07:38.116  1017  1383 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-02 12:07:38.116  1017  1383 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-02 12:07:38.116  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-02 12:07:38.116  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-02 12:07:38.126  6754  6754 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 12:07:38.126  6754  6754 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-02 12:07:38.126  6754  6754 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a5a5887 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1e58011c, 16908290=android.view.AbsSavedState$1@1e58011c}, android:focusedViewId=100}]}]
,09-02 12:07:38.126  6754  6754 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-02 12:07:38.126  6754  6754 V ActivityThread: updateVisibility : ActivityRecord{10ffa776 token=android.os.BinderProxy@3076069b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-02 12:07:38.126  6754  6754 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 12:07:38.126  6754  6754 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-02 12:07:38.126  6754  6754 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3076069b time:114999
,09-02 12:07:38.136  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
,09-02 12:07:38.146   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 12:07:38.256  1017  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-02 12:07:39.096   295   295 E SMD     : DCD OFF,
,09-02 12:07:39.146   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 12:07:39.346  1017  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 12:07:39.346  1017  1483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-02 12:07:39.346  1017  1483 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-02 12:07:39.346  1017  1483 D BatteryService: stay LED for fully charged
,09-02 12:07:39.346  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 12:07:39.346  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-02 12:07:39.346  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 12:07:39.346  1017  1017 I MotionRecognitionService: Plugged
,09-02 12:07:39.346  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 12:07:39.356  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-02 12:07:39.356  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-02 12:07:39.356  3176  3176 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-02 12:07:39.366  3176  3280 D HeadsetStateMachine: Disconnected process message: 10
,09-02 12:07:39.376  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-02 12:07:39.376  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-02 12:07:39.376  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:39.376  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:39.376  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:40.146   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 12:07:40.956  1017  1042 W ActivityManager: mDVFSHelper.release()
,09-02 12:07:41.146   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 12:07:42.096   295   295 E SMD     : DCD OFF,
,09-02 12:07:42.146   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-02 12:07:42.796  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-02 12:07:42.796  6754  6808 I jxcore-log: 
,09-02 12:07:42.806  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-02 12:07:42.806  6754  6808 I jxcore-log: 
,09-02 12:07:42.806  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:42.806  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:42.806  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:42.806  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:42.806  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:42.806  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:42.806  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:42.806  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:42.806  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:07:42.816  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 12:07:42.816  6754  6808 I jxcore-log: 
,09-02 12:07:42.816  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 12:07:42.816  6754  6808 I jxcore-log: 
,09-02 12:07:43.136  1017  1095 V AlarmManager: waitForAlarm result :4,
,09-02 12:07:43.136  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-02 12:07:43.166  1962  1962 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-02 12:07:43.266  1962  1962 I art     : Explicit concurrent mark sweep GC freed 48961(2MB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 10MB/17MB, paused 1.181ms total 70.001ms
,09-02 12:07:43.266  4753  4753 D ConnectivityManager: CallingUid : 10011, CallingPid : 4753
,09-02 12:07:43.276  1017  1500 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 12:07:43.276  1017  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
09-02 12:07:43.276  1017  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-02 12:07:43.276  1017  1128 D ConnectivityService: apparently satisfied.  currentScore=60
,09-02 12:07:43.276  4753  6819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
,09-02 12:07:43.286  1017  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:43.286  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-02 12:07:43.286  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:43.286  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:43.286  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:43.346  4753  6820 W DriveInitializer: Background init thread started
,09-02 12:07:43.396   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-02 12:07:43.396   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 12:07:43.396  4753  6820 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-02 12:07:43.446  1017  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 12:07:43.446  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-02 12:07:43.446  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:43.446  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:43.446  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:43.476  1017  1029 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-02 12:07:43.476  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-02 12:07:43.486  1017  1210 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:43.486  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-02 12:07:43.486  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:43.486  1017  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:43.486  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:43.516  4753  6828 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-02 12:07:43.516  4753  6828 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-02 12:07:43.526  4753  6820 W DriveInitializer: Background init thread ended
,09-02 12:07:43.566  1962  1962 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-02 12:07:43.586  6754  6808 D executeNativeTests: Running unit tests
,09-02 12:07:43.596  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:43.596  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:43.596  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:43.696  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:07:43.696  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 added. We now have 2 listener(s)
,09-02 12:07:43.696  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-02 12:07:43.696  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:07:43.696  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:07:43.696  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:07:43.696  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa added. We now have 2 listener(s)
09-02 12:07:43.696  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:07:43.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:07:43.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:07:43.706  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:43.706  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:43.706  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:43.706  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:43.706  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:43.706  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:43.706  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:43.706  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:43.706  1017  4394 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:43.706  1017  4394 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-02 12:07:43.706  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:07:43.706  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:07:43.716  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:07:43.716  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:07:43.716  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 12:07:43.716  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:43.716  6754  6808 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-02 12:07:43.716  6754  6808 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 12:07:43.716  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:07:43.716  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:07:43.716  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:07:43.716  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:07:43.716  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:43.716  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:43.716  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:43.716  1017  4394 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:43.716  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 12:07:43.716  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:43.716  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.716  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:07:43.716  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:07:43.716  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 removed from the list
09-02 12:07:43.716  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:43.716  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa removed from the list
,09-02 12:07:43.726  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:43.726  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:43.726  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:43.726  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.726  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:43.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:43.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:43.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:43.726  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:43.726  6754  6808 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-02 12:07:43.726  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:43.726  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:43.726  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:43.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:43.726  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.726  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:43.726  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:43.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:43.726  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:43.726  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:43.726  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.726  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:43.726  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.726  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:43.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:43.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:43.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:43.726  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:07:43.736  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:43.736  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:43.736  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:43.736  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:43.736  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.736  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:43.736  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:43.736  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:43.736  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:43.736  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:43.736  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.736  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:43.736  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.736  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:43.746  1017  4395 I art     : Explicit concurrent mark sweep GC freed 36756(2001KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.686ms total 174.526ms
09-02 12:07:43.746  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:43.746  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:43.746  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:43.746  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:43.746  6754  6808 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 12:07:43.746  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:43.756  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:43.756  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:43.756  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:43.756  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:43.756  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:43.756  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:43.756  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:43.756  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:43.766  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:43.766  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:07:43.766  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:07:43.766  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:07:43.766  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:07:43.766  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:43.766  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:07:43.776  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 12:07:43.776  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:43.776  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:43.786  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 12:07:43.786  1017  1212 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:43.786  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
09-02 12:07:43.786  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 12:07:43.786  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:43.786  1017  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:43.786  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 12:07:43.796  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-02 12:07:43.796  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-02 12:07:43.796  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 12:07:43.796  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:07:43.796  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:07:43.836  3176  3193 D BtGatt.GattService: registerClient() - UUID=19275c85-b3e7-4721-abee-4f46832381b7
,09-02 12:07:43.846  1017  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:43.846  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:43.846  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:43.846  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:43.856  1017  4395 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:43.856  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:43.856  1017  4395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:43.856  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:43.876  3176  3270 D BtGatt.GattService: onClientRegistered() - UUID=19275c85-b3e7-4721-abee-4f46832381b7, clientIf=6
,09-02 12:07:43.886  6754  6767 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 12:07:43.886  3176  3282 D BtGatt.GattService: start scan with filters
,09-02 12:07:43.886  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 12:07:43.886  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:07:43.886  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:07:43.886  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 12:07:43.886  3176  3277 D BtGatt.ScanManager: handling starting scan
,09-02 12:07:43.896  3176  3277 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:43.896  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:07:43.896  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:07:43.896  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 12:07:43.906  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:07:43.906  6754  6808 I io.jxcore.node.ConnectionHelper: start: OK,
,09-02 12:07:43.916  3176  3270 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-02 12:07:43.916  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:43.916  6754  6808 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:07:43.916  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:07:43.916  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:07:43.916  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.916  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:07:43.916  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:07:43.916  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:07:43.916  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 12:07:43.916  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 12:07:43.916  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:43.916  3176  3277 D BtGatt.ScanManager: allow scan with filters
,09-02 12:07:43.916  3176  3277 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-02 12:07:43.916  3176  3277 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-02 12:07:43.916  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 12:07:43.916  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 12:07:43.916  3176  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 12:07:43.926  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:43.926  3176  3190 D BtGatt.GattService: stopScan() - queue size =1
09-02 12:07:43.926  3176  3277 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:07:43.926  3176  3277 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 12:07:43.926  3176  3193 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 12:07:43.926  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:07:43.926  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:07:43.926  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:07:43.926  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:07:43.926  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 12:07:43.926  3176  3270 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-02 12:07:43.926  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:07:43.926  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:07:43.926  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:07:43.926  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:07:43.926  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 12:07:43.926  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:07:43.936  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:43.936  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:43.936  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:43.936  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:07:43.936  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:43.936  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:43.936  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:43.936  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:43.936  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:43.936  6754  6808 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 12:07:43.936  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:43.936  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:07:43.936  3176  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 12:07:43.936  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:07:43.936  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:07:43.936  3176  3277 D BtGatt.ScanManager: filter size is 1
09-02 12:07:43.936  3176  3277 D BtGatt.ScanManager: delete FilterIndex - 3
,09-02 12:07:43.946  3176  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 12:07:43.946  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:07:43.946  3176  3277 D BtGatt.ScanManager: stopping BLe Batch
,09-02 12:07:43.946  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:43.946  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:43.946  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:43.946  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:43.946  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:43.946  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:43.946  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:43.946  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:43.946  1017  2016 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:43.946  3176  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-02 12:07:43.946  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:07:43.946  3176  3277 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 12:07:43.946  1017  2016 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:43.946  1017  2016 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:43.946  1017  2016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:43.956  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:43.956  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:07:43.956  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:07:43.956  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:07:43.956  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:07:43.956  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:43.956  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 12:07:43.956  1017  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:43.956  1017  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:43.956  1017  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:43.956  1017  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:43.956  3176  3270 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 12:07:43.956  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:07:43.956  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-02 12:07:43.966  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-02 12:07:43.966  6834  6834 E Zygote  : MountEmulatedStorage(),
09-02 12:07:43.966  6834  6834 I libpersona: KNOX_SDCARD checking this for 10011
09-02 12:07:43.966  6834  6834 E Zygote  : v2
09-02 12:07:43.966  6834  6834 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:43.966  1017  2016 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6834 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
09-02 12:07:43.966  6834  6834 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:43.976  6834  6834 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:43.976  6834  6834 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 12:07:43.976  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:07:43.986  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:07:43.986  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:07:43.986  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 12:07:43.986  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
09-02 12:07:43.986  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:07:43.996  3176  3282 D BtGatt.GattService: registerClient() - UUID=7d450dd4-303f-4a46-8a4f-6593c7a64397
,09-02 12:07:43.996  6834  6834 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:43.996  6834  6834 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:44.016  6834  6834 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-02 12:07:44.016  6834  6834 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-02 12:07:44.036  3176  3270 D BtGatt.GattService: onClientRegistered() - UUID=7d450dd4-303f-4a46-8a4f-6593c7a64397, clientIf=6,
09-02 12:07:44.036  6754  6768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-02 12:07:44.036  3176  3190 D BtGatt.GattService: start scan with filters
09-02 12:07:44.036  3176  3277 D BtGatt.ScanManager: handling starting scan
09-02 12:07:44.036  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 12:07:44.036  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:07:44.036  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:07:44.036  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:07:44.036  3176  3270 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-02 12:07:44.036  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.036  3176  3277 D BtGatt.ScanManager: allow scan with filters
,09-02 12:07:44.036  3176  3277 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 12:07:44.036  3176  3277 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-02 12:07:44.046  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:07:44.046  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 12:07:44.046  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:07:44.046  3176  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 12:07:44.046  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:07:44.046  3176  3277 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 12:07:44.046  3176  3277 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 12:07:44.046  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:07:44.056  3176  3270 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
09-02 12:07:44.056  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.056  6754  6808 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 12:07:44.056  3176  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 12:07:44.056  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:07:44.066  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.066  6754  6808 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:07:44.066  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.066  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:07:44.066  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.066  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:07:44.066  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:07:44.066  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:07:44.066  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:07:44.066  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:07:44.066  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:07:44.066  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,09-02 12:07:44.066  6834  6834 I MultiDex: VM with version 2.1.0 has multidex support
09-02 12:07:44.066  6834  6834 I MultiDex: install,
09-02 12:07:44.066  6834  6834 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-02 12:07:44.066  3176  3193 D BtGatt.GattService: stopScan() - queue size =1
09-02 12:07:44.066  3176  3277 D BtGatt.ScanManager: filter size is 1
,09-02 12:07:44.066  3176  3277 D BtGatt.ScanManager: delete FilterIndex - 4
,09-02 12:07:44.066  3176  3190 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 12:07:44.066  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:07:44.066  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:07:44.066  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:07:44.066  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:07:44.066  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 12:07:44.066  3176  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 12:07:44.066  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.066  3176  3277 D BtGatt.ScanManager: stopping BLe Batch
,09-02 12:07:44.076  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:44.076  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:07:44.076  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:07:44.076  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 12:07:44.076  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:07:44.076  3176  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 12:07:44.076  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.076  3176  3277 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 12:07:44.076  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:44.076  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.076  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.076  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:07:44.076  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.076  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.076  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.076  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.076  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.076  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:44.076  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:44.076  3176  3270 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 12:07:44.076  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.076  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.076  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:07:44.086  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.086  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.086  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.086  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.086  6754  6808 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 12:07:44.086  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:07:44.096  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:44.096  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:44.096  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:44.096  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:44.096  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:44.096  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:44.096  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:44.096  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:44.096  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:44.096  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:07:44.096  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:07:44.096  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:07:44.096  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:07:44.096  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:44.096  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 12:07:44.106  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-02 12:07:44.106  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:07:44.106  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:44.116  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:07:44.116  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:07:44.116  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 12:07:44.116  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-02 12:07:44.116  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:07:44.126  3176  3282 D BtGatt.GattService: registerClient() - UUID=a3babb65-5b8f-4bd1-896f-516427b91f91
,09-02 12:07:44.126  6834  6834 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-02 12:07:44.166  3176  3270 D BtGatt.GattService: onClientRegistered() - UUID=a3babb65-5b8f-4bd1-896f-516427b91f91, clientIf=6
,09-02 12:07:44.166  6754  6768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 12:07:44.166  3176  3190 D BtGatt.GattService: start scan with filters
,09-02 12:07:44.166  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 12:07:44.166  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:07:44.166  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:07:44.166  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:07:44.166  3176  3277 D BtGatt.ScanManager: handling starting scan
,09-02 12:07:44.176  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:07:44.176  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:07:44.176  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 12:07:44.176  3176  3270 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 12:07:44.176  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.176  3176  3277 D BtGatt.ScanManager: allow scan with filters
09-02 12:07:44.176  3176  3277 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 12:07:44.176  3176  3277 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-02 12:07:44.176  3176  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 12:07:44.176  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.176  3176  3277 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 12:07:44.186  3176  3277 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-02 12:07:44.186  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:07:44.186  6754  6808 I io.jxcore.node.ConnectionHelper: start: OK
09-02 12:07:44.186  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.186  6754  6808 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:07:44.186  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.186  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:07:44.186  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.186  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:07:44.186  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:07:44.186  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:07:44.186  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:07:44.186  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:07:44.186  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:07:44.186  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 12:07:44.186  3176  3193 D BtGatt.GattService: stopScan() - queue size =1
,09-02 12:07:44.186  3176  3282 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 12:07:44.186  6834  6834 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-02 12:07:44.196  3176  3270 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-02 12:07:44.196  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.196  6834  6834 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31ee72b2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-02 12:07:44.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:07:44.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:07:44.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:07:44.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:07:44.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 12:07:44.196  6834  6834 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-02 12:07:44.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:07:44.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:07:44.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:07:44.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 12:07:44.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:07:44.196  3176  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-02 12:07:44.196  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:07:44.196  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:07:44.196  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.196  6754  6808 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 12:07:44.196  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.196  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.196  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:07:44.196  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.196  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.196  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.206  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:44.206  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:07:44.206  3176  3277 D BtGatt.ScanManager: filter size is 1
09-02 12:07:44.206  3176  3277 D BtGatt.ScanManager: delete FilterIndex - 5
,09-02 12:07:44.206  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.206  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.206  3176  3270 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 12:07:44.206  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.206  3176  3277 D BtGatt.ScanManager: stopping BLe Batch
,09-02 12:07:44.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.206  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.206  3176  3270 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 12:07:44.206  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.206  3176  3277 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 12:07:44.206  6754  6808 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-02 12:07:44.206  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.206  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.206  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 12:07:44.206  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.206  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.206  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.206  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.206  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.206  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.206  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.206  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.206  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:07:44.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:07:44.206  3176  3270 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 12:07:44.206  3176  3270 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:07:44.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.206  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.216  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 12:07:44.216  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.216  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.216  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.216  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.216  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.216  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.216  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.216  6754  6808 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 12:07:44.216  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.216  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.216  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.216  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.216  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.216  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.216  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.216  1017  4394 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
09-02 12:07:44.216  6754  6808 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-02 12:07:44.216  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.216  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.216  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.216  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.216  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.216  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.216  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:07:44.226  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:07:44.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 12:07:44.226  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:07:44.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 12:07:44.226  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 12:07:44.226  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.226  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.226  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.226  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.226  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.226  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.226  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.226  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.226  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.226  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.226  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.226  6834  6834 D ChimeraCfgMgr: Reading stored module config
09-02 12:07:44.226  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.226  6754  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:44.226  6754  6808 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-02 12:07:44.226  6754  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:44.226  6754  6808 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 12:07:44.226  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 12:07:44.226  6754  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 12:07:44.226  6754  6808 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:07:44.226  6754  6808 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 12:07:44.226  6754  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:44.226  6754  6808 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:07:44.226  6754  6808 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 12:07:44.226  6754  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:44.226  6754  6808 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 12:07:44.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-02 12:07:44.236  1017  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:44.236  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:44.236  1017  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:44.236  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:44.236  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-02 12:07:44.236  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 12:07:44.236  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 12:07:44.246  6754  6808 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 12:07:44.246  6754  6808 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 12:07:44.246  6754  6808 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 12:07:44.246  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.246  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.246  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.246  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-02 12:07:44.246  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.246  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.246  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.246  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.246  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.246  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.246  6754  6808 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-02 12:07:44.246  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.246  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.246  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.246  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.246  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.246  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.246  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.246  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.246  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.246  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.246  6754  6808 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 12:07:44.246  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.246  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.246  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.246  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.246  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.246  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.246  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.246  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.246  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.246  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.246  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.256  6754  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1320)
,09-02 12:07:44.256  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:07:44.256  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.256  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.256  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.256  6754  6808 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 12:07:44.256  6754  6808 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 12:07:44.256  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:07:44.256  6754  6808 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 12:07:44.256  6754  6808 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 12:07:44.256  6754  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 12:07:44.256  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-02 12:07:44.256  6754  6808 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 12:07:44.256  6754  6808 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 12:07:44.256  6754  6808 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 12:07:44.256  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 12:07:44.256  6754  6808 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 12:07:44.256  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.256  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.256  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:07:44.256  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.256  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.256  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.256  6754  6857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1320
09-02 12:07:44.256  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.256  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.256  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.256  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.256  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.256  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.256  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.256  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.256  1017  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:44.256  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.256  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:44.256  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.266  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.266  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.266  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.266  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.266  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.266  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.266  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.266  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.266  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.266  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.266  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.266  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.266  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.266  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.266  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.266  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.266  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.266  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.266  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.266  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.266  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.266  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:4,4.266  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.266  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.266  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.266  6754  6856 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,09-02 12:07:44.266  6754  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:07:44.266  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-02 12:07:44.276  6754  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 12:07:44.286  6754  6856 D BluetoothSocket: connect(): myUserId = 0
,09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:07:44.286  6754  6856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:07:44.286  6754  6754 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 12:07:44.286  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:07:44.286  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.286  6754  6858 D BluetoothSocket: bindListen(): myUserId = 0
09-02 12:07:44.286  6754  6858 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:07:44.286  6754  6754 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:07:44.286  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.286  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.286  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.286  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.286  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.286  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.286  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.286  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.286  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.286  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.286  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.286  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.286  3176  3193 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:07:44.286  6754  6856 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-02 12:07:44.286  6754  6858 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-02 12:07:44.286  6754  6858 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 12:07:44.286  6754  6858 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 12:07:44.286  6754  6858 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35a23d7c
09-02 12:07:44.286  6754  6858 D BluetoothSocket: channel: 6
09-02 12:07:44.286  6754  6858 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@eb82605, channel: 6, state: LISTENING
09-02 12:07:44.286  6754  6858 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@eb82605, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35a23d7c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@cdbe65amSocket: android.net.LocalSocket@3d6cb08b impl:android.net.LocalSocketImpl@1b93b568 fd:FileDescriptor[105]
09-02 12:07:44.286  6754  6858 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d6cb08b impl:android.net.LocalSocketImpl@1b93b568 fd:FileDescriptor[105]
09-02 12:07:44.286  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:07:44.286  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.286  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.286  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.296  6754  6808 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 12:07:44.296  6754  6808 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-02 12:07:44.296  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-02 12:07:44.296  6754  6858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-02 12:07:44.296  6754  6858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 12:07:44.296  6754  6858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 12:07:44.296  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 12:07:44.296  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.296  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.296  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:07:44.296  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.296  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.296  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.296  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.296  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.296  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.296  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.296  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.296  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.296  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.296  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.296  6754  6754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
09-02 12:07:44.296  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.296  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.296  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.296  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.296  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:07:44.296  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.296  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:07:44.296  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.296  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.296  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.296  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.296  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.296  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.296  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.296  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.296  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.296  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.296  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.306  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.306  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.306  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.306  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.306  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:07:44.306  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:07:44.306  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:07:44.306  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:07:44.306  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.306  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.306  6754  6808 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d0fad95 not in the list
09-02 12:07:44.306  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.306  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
09-02 12:07:44.306  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:07:44.306  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.306  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:07:44.306  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:07:44.306  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:44.306  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:07:44.306  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:07:44.306  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:07:44.306  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce7eaa not in the list
,09-02 12:07:44.306  6754  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 12:07:44.306  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 12:07:44.306  6754  6808 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 12:07:44.306  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-02 12:07:44.306  6754  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 12:07:44.306  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-02 12:07:44.316  1962  1962 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=69c50ca6-8d2a-45d7-93dc-396bd5bbaaa0
,09-02 12:07:44.316  6834  6849 I art     : Background sticky concurrent mark sweep GC freed 23004(1106KB) AllocSpace objects, 2(32KB) LOS objects, 2% free, 7MB/7MB, paused 25.264ms total 82.575ms
09-02 12:07:44.316  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 12:07:44.316  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-02 12:07:44.326  6754  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 12:07:44.326  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:07:44.326  6754  6808 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 12:07:44.326  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 12:07:44.326  6754  6808 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 12:07:44.326  6754  6808 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-02 12:07:44.326  6754  6808 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 12:07:44.326  6754  6808 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-02 12:07:44.326  6754  6808 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-02 12:07:44.326  6754  6808 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 12:07:44.326  6754  6808 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 12:07:44.326  6754  6808 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-02 12:07:44.326  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-02 12:07:44.326  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@359a1d81 added. We now have 2 listener(s)
09-02 12:07:44.326  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:07:44.326  6754  6808 D BluetoothAdapter: enable()
,09-02 12:07:44.326  6754  6808 D BluetoothAdapter: enable(): BT is already enabled..!
,09-02 12:07:44.336  1017  4394 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-02 12:07:44.336  1017  4394 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-02 12:07:44.336  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:44.336  1017  4394 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:44.336  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:44.346  1017  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-02 12:07:44.346  1017  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 12:07:44.346  1017  1030 D WifiService: setWifiEnabled: true pid=6754, uid=10171
09-02 12:07:44.346  1017  1030 D SecContentProvider2: mCursor = null
,09-02 12:07:44.346  1962  1962 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-02 12:07:44.346  1962  1962 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-02 12:07:44.356  1017  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-02 12:07:44.356  1017  1030 W WifiService: Failed getting userId using ActivityManagerNative
09-02 12:07:44.356  1017  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-02 12:07:44.356  1017  1030 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 12:07:44.356  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 12:07:44.356  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 12:07:44.356  1017  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 12:07:44.356  1017  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 12:07:44.356  1017  1030 D SettingsProvider: name = wifi_on
,09-02 12:07:44.356  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:07:44.366  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a620e26 added. We now have 3 listener(s)
,09-02 12:07:44.366  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:07:44.366  6834  6854 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-02 12:07:44.376  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:07:44.376  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3373ca67 added. We now have 4 listener(s)
09-02 12:07:44.376  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:07:44.376  6834  6834 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-02 12:07:44.376  6834  6834 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-02 12:07:44.376  1017  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:44.376  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:07:44.376  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22a2c014 added. We now have 5 listener(s)
,09-02 12:07:44.376  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:07:44.386  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.386  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:44.386  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:44.386  1017  1212 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-02 12:07:44.386  1017  1212 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 12:07:44.386  1017  1212 D SecContentProvider2: mCursor = null
,09-02 12:07:44.386  1017  1212 D WifiService: setWifiEnabled: false pid=6754, uid=10171
,09-02 12:07:44.386  1017  1212 D SettingsProvider: name = wifi_on
,09-02 12:07:44.396  6754  6808 D BluetoothAdapter: disable()
,09-02 12:07:44.406  1017  1471 D SettingsProvider: name = bluetooth_on
,09-02 12:07:44.406  1017  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-02 12:07:44.406  1351  1351 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 12:07:44.406  1351  1351 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-02 12:07:44.406  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:07:44.406  1351  1351 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 12:07:44.406  1351  1351 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 12:07:44.416  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:07:44.416  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:07:44.416  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:44.416  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:44.416  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:44.416  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:44.416  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:44.416  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:44.416  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:07:44.426  3176  3267 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-02 12:07:44.426  3176  3267 D BluetoothAdapterProperties: Setting state to 13
09-02 12:07:44.426  3176  3267 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 12:07:44.426  3176  3267 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 12:07:44.426  3176  3267 D BluetoothAdapterService: updateAdapterState state is 13
09-02 12:07:44.426  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-02 12:07:44.426  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:44.426  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:07:44.426  1017  1383 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:44.426  1017  1383 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.426  1017  1383 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.426  1017  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:44.426  1017  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:44.426  3176  3176 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-02 12:07:44.426  3176  3176 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@210b3498, channel: 19, state: LISTENING
,09-02 12:07:44.426  3176  3176 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@210b3498, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@384c3580, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15be4f1mSocket: android.net.LocalSocket@174818d6 impl:android.net.LocalSocketImpl@2cc7f757 fd:FileDescriptor[74]
09-02 12:07:44.426  3176  3176 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@174818d6 impl:android.net.LocalSocketImpl@2cc7f757 fd:FileDescriptor[74]
09-02 12:07:44.426  3176  3267 D BluetoothAdapterService: Autoconnection is available 
,09-02 12:07:44.426  3176  3267 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-02 12:07:44.426  3176  3267 D BluetoothAdapterService: terminating service from this receiver
,09-02 12:07:44.426  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.426  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.436  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:44.436  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:44.436  1351  1351 I wpa_supplicant: Scan aborted because the firmware maybe busy.
09-02 12:07:44.436  1351  1351 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
09-02 12:07:44.436  1351  1351 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,09-02 12:07:44.436  3176  3267 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 12:07:44.436  1017  1126 E WifiNative-wlan0: do suspend true
,09-02 12:07:44.436  3176  3267 D BluetoothAdapterProperties: mDiscovering is false
,09-02 12:07:44.436  1017  4394 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 12:07:44.436  3176  3267 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-02 12:07:44.436  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:44.436  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:44.436  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:44.436  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:07:44.436  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:44.436  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:44.436  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:44.436  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:44.436  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:07:44.436  3855  3855 D BluetoothPbap: Proxy object disconnected
09-02 12:07:44.436  3855  3855 D PbapServerProfile: Bluetooth service disconnected
,09-02 12:07:44.446  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:44.446  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:07:44.446  3176  3270 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 12:07:44.446  3176  3270 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:07:44.446  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:44.466  3176  3267 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 12:07:44.466  3176  3267 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-02 12:07:44.466  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:44.466  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:44.466  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:44.466  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:07:44.466  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:44.466  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:44.466  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:07:44.466  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:07:44.466  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:07:44.466  3176  3267 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-02 12:07:44.466  3176  3267 E bt-btif : cmd socket is not created
,09-02 12:07:44.466  3176  3299 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-02 12:07:44.466  3176  3299 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-02 12:07:44.466  6754  6856 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24d0e6b2, channel: -1, state: INIT
09-02 12:07:44.466  3176  5236 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-02 12:07:44.466  3176  3267 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-02 12:07:44.466  6754  6856 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24d0e6b2, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32e8a603, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@38f5c980mSocket: android.net.LocalSocket@3d0bfbb9 impl:android.net.LocalSocketImpl@ee2bbfe fd:FileDescriptor[106]
09-02 12:07:44.466  6754  6856 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d0bfbb9 impl:android.net.LocalSocketImpl@ee2bbfe fd:FileDescriptor[106]
09-02 12:07:44.466  6754  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1320)
,09-02 12:07:44.466  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:44.466  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:07:44.476  3176  3299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:07:44.476  3176  3299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:44.476  3176  3299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-02 12:07:44.476  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:44.476  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:44.476  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,09-02 12:07:44.486  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-02 12:07:44.486  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 12:07:44.496  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 12:07:44.496  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:44.496  1173  1173 D BluetoothTile:  getBluetoothState : 13
,09-02 12:07:44.496  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 12:07:44.496  1915  1915 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 12:07:44.496  3176  3176 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2fb8df2d, channel: 5, state: LISTENING
09-02 12:07:44.496  3176  3176 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2fb8df2d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11bff7b9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f84ec62mSocket: android.net.LocalSocket@316ab1f3 impl:android.net.LocalSocketImpl@2197feb0 fd:FileDescriptor[76]
09-02 12:07:44.496  3176  3176 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@316ab1f3 impl:android.net.LocalSocketImpl@2197feb0 fd:FileDescriptor[76]
,09-02 12:07:44.496  3855  3855 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:44.496  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 12:07:44.506   290   726 D WVCdm   : Instantiating CDM.
,09-02 12:07:44.506  1017  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 12:07:44.506   290   290 I WVCdm   : CdmEngine::OpenSession
09-02 12:07:44.506  1017  1383 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 12:07:44.506   290   290 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-02 12:07:44.506  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:44.506  3176  3176 I BtOppRfcommListener: stopping Accept Thread
09-02 12:07:44.506  3176  3176 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9714129, channel: 12, state: LISTENING
09-02 12:07:44.506  3176  3176 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9714129, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2102ee7b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15c96caemSocket: android.net.LocalSocket@22747a4f impl:android.net.LocalSocketImpl@10f655dc fd:FileDescriptor[79]
09-02 12:07:44.506  3176  3176 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22747a4f impl:android.net.LocalSocketImpl@10f655dc fd:FileDescriptor[79]
,09-02 12:07:44.506  3176  5236 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-02 12:07:44.506  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:44.506  3176  3176 V BluetoothOppManager: cleanUp...
,09-02 12:07:44.516  1017  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:44.516  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.516  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:44.516  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:44.516  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:44.516  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 12:07:44.516  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:07:44.516  1017  1483 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 12:07:44.516  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.516  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.516  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:44.516  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 12:07:44.536  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:07:44.546  3855  3855 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 12:07:44.546   290   290 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-02 12:07:44.556  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:44.556  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-02 12:07:44.556  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-02 12:07:44.556  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:44.556  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:44.556  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:44.556  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:44.576  6870  6870 E Zygote  : MountEmulatedStorage(),
09-02 12:07:44.576  1017  1476 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6870 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-02 12:07:44.576  6870  6870 E Zygote  : v2
09-02 12:07:44.576  6870  6870 I libpersona: KNOX_SDCARD checking this for 10055
09-02 12:07:44.576  6870  6870 I libpersona: KNOX_SDCARD not a persona,
,09-02 12:07:44.576  6870  6870 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:44.576   290   290 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-02 12:07:44.576  6870  6870 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:44.576  6870  6870 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:44.586  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
09-02 12:07:44.586  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 12:07:44.586   278  1010 D CommandListener: Clearing all IP addresses on wlan0,
09-02 12:07:44.596  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:44.596  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 12:07:44.596  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.596  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.596  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.596  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 12:07:44.596  1962  3032 V NativeCrypto: Read error: ssl=0xb7e5db98: I/O error during system call, Connection timed out
,09-02 12:07:44.596  1962  3032 V NativeCrypto: SSL shutdown failed: ssl=0xb7e5db98: I/O error during system call, Broken pipe
09-02 12:07:44.606  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:07:44.606  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:07:44.606  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:07:44.606  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-02 12:07:44.606  1962  3032 E GCM     : Wifi connection closed with errorCode 20
,09-02 12:07:44.606  1017  1483 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011,
,09-02 12:07:44.606  6870  6870 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:44.616  6870  6870 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:44.626  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 12:07:44.626  1017  1718 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-17ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:07:44.626  1017  1718 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-17ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:07:44.626  1017  1718 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-02 12:07:44.626  1017  1718 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:07:44.626  1017  1718 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-02 12:07:44.626  1017  1718 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
09-02 12:07:44.626  1017  1718 I qtaguid : Tagging socket 347 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
09-02 12:07:44.626  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
,09-02 12:07:44.626  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 12:07:44.626  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
09-02 12:07:44.626  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:44.626  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:07:44.626  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.626  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.626  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.626  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.636  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-02 12:07:44.646  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 12:07:44.646  1017  1017 D RttService: SCAN_AVAILABLE : 1
09-02 12:07:44.646  1017  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:07:44.646  1017  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:07:44.646  4317  4437 I art     : Explicit concurrent mark sweep GC freed 1501(51KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 710us total 27.303ms
09-02 12:07:44.646   290   290 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-02 12:07:44.656   290   726 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-02 12:07:44.656   290   726 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-02 12:07:44.656   290   726 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-02 12:07:44.656  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:07:44.656  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-02 12:07:44.656  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-02 12:07:44.656  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-02 12:07:44.656   290   726 D WVCdm   : PrepareKeyRequest: nonce=1011188807
09-02 12:07:44.656  1017  1125 D WifiP2pService: P2pDisablingState
09-02 12:07:44.656  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-02 12:07:44.656  1017  1125 D WifiP2pService: p2p socket connection lost
09-02 12:07:44.656  1017  1126 E WifiNative-wlan0: do suspend true
09-02 12:07:44.656  1017  1125 D WifiP2pService: P2pDisabledState
,09-02 12:07:44.666  3176  3299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:07:44.666  3176  3299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:44.666  3176  3299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:07:44.666  3176  3299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:07:44.666  3176  3299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:44.666  3176  3299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:07:44.666  3176  3299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:07:44.666  3176  3299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:44.666  3176  3299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:07:44.666  3176  3299 W bt-btif : ag scb idx 1 not allocated
09-02 12:07:44.666  3176  3299 W bt-btif : ag scb idx 2 not allocated
09-02 12:07:44.666  3176  3299 E bt-btif : BTA AG is already disabled, ignoring ...
,09-02 12:07:44.666  3176  3358 I bt_userial_mct: exiting userial_read_thread
09-02 12:07:44.666  3176  3358 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 12:07:44.666  3176  3270 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 12:07:44.666  3176  3301 I bt_vendor: hw_epilog_process
09-02 12:07:44.666  3176  3270 D bt_userial_mct: userial_close,
09-02 12:07:44.666  3176  3270 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-02 12:07:44.676  6870  6870 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-02 12:07:44.686  1017  1718 I qtaguid : Untagging socket 347
,09-02 12:07:44.686  1017  1718 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 12:07:44.686  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 12:07:44.686  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-02 12:07:44.686  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-02 12:07:44.686  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 12:07:44.686  1017  1047 D WifiDisplayController: disconnect
09-02 12:07:44.686  1017  1047 D WifiDisplayController: updateConnection
09-02 12:07:44.686  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 12:07:44.686  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 12:07:44.686  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-02 12:07:44.686  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 12:07:44.686  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-02 12:07:44.686  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 12:07:44.696  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-02 12:07:44.696  1017  4394 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 12:07:44.696  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 12:07:44.706  1017  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 12:07:44.706  6834  6842 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-02 12:07:44.706  6834  6842 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-02 12:07:44.706  6834  6842 I System.out: (HTTPLog)-Static: isShipBuild true
09-02 12:07:44.706  6834  6842 I System.out: (HTTPLog)-Thread-1229-751302487: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-02 12:07:44.706  6834  6842 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 12:07:44.726  6870  6870 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-02 12:07:44.726  6870  6870 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-02 12:07:44.726  6870  6870 D UserAnalysis: Create SecureDbHelper
,09-02 12:07:44.736  1962  2150 W GCoreFlp: No location to return for getLastLocation()
,09-02 12:07:44.736  6870  6870 D IntelligenceServiceApplication: onCreate()
,09-02 12:07:44.746  6870  6870 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-02 12:07:44.756  1017  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-02 12:07:44.756  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
09-02 12:07:44.756  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:44.756  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:44.756  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:44.756  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:44.756  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,09-02 12:07:44.776  6893  6893 E Zygote  : MountEmulatedStorage()
,09-02 12:07:44.776  6893  6893 E Zygote  : v2
09-02 12:07:44.776  6893  6893 I libpersona: KNOX_SDCARD checking this for 10105
09-02 12:07:44.776  6893  6893 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:44.776  6893  6893 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:44.776  6893  6893 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 12:07:44.776  1017  1480 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6893 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,09-02 12:07:44.786  6893  6893 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-02 12:07:44.786  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-02 12:07:44.786  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:44.786  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:07:44.786  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.786  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.786  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.786  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.786  6870  6870 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-02 12:07:44.786  6754  6754 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:07:44.806   278  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-02 12:07:44.806   278  1006 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-02 12:07:44.806   278  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-02 12:07:44.806   278  1006 D Netd    : getNetworkForDns: using netid 0 for uid 10011
09-02 12:07:44.806   278  1010 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:07:44.806  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:44.806  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-02 12:07:44.806  1017  1128 V NetworkStats: updateIfacesLocked()
09-02 12:07:44.806  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-02 12:07:44.806  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:07:44.806  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 12:07:44.806  1017  1718 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-02 12:07:44.806  1017  1718 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-02 12:07:44.806  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling,
09-02 12:07:44.806  1351  1351 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-02 12:07:44.816  6893  6893 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:44.816  6893  6893 D ActivityThread: Added TimaKeyStore provider
09-02 12:07:44.816  1017  1128 V NetworkStats: performPollLocked() took 13ms
09-02 12:07:44.816  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:44.816  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:44.816  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:07:44.816  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.816  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.816  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.816  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:44.826  6870  6870 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-02 12:07:44.836  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-02 12:07:44.836  1173  1707 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-02 12:07:44.836  1017  1718 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:07:44.836  4753  6819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-02 12:07:44.836  1017  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 12:07:44.836  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 12:07:44.836  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-02 12:07:44.836  1017  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-02 12:07:44.836  1457  1457 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 12:07:44.836  1457  1457 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 12:07:44.836  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-02 12:07:44.836  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-02 12:07:44.836  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:44.836  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 12:07:44.836  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.836  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:44.846  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:07:44.846  1017  1126 D SecContentProvider2: mCursor = null
09-02 12:07:44.846  1017  3339 D SSRM:n  : SIOP:: AP = 350
,09-02 12:07:44.846  3855  3855 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:44.846  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.846  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.846  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 12:07:44.846  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 12:07:44.846  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-02 12:07:44.856  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 12:07:44.856  1173  1173 D HotspotTile: onReceive : 0, 0
,09-02 12:07:44.866  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:44.866  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:44.866  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:44.866  1017  1123 V NetworkStats: updateIfacesLocked()
09-02 12:07:44.866  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:07:44.866  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 12:07:44.866  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 12:07:44.866  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-02 12:07:44.866  1017  1130 D Tethering: MasterInitialState.processMessage what=3
09-02 12:07:44.866  1017  1123 V NetworkStats: performPollLocked() took 5ms
,09-02 12:07:44.876  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-02 12:07:44.876  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:44.876  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-02 12:07:44.876  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-02 12:07:44.876  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 12:07:44.876  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-02 12:07:44.876  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-02 12:07:44.876  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-02 12:07:44.876  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
09-02 12:07:44.876  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-02 12:07:44.876  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:07:44.876  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:07:44.876  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-02 12:07:44.876  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:44.876  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:44.876  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:44.876  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:44.876  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:07:44.876  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:44.876  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:44.876  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:44.876  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:44.876  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:07:44.876  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:44.876  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:44.876  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-02 12:07:44.876  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:44.886  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:44.886  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:44.886  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-02 12:07:44.886  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-02 12:07:44.886  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-02 12:07:44.886  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:44.886  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 12:07:44.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.886  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:44.886  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-02 12:07:44.886  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:44.886  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:44.886  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:44.886  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:07:44.886  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:44.886  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:44.886  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:44.886  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:44.886  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:44.886  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:44.886  3176  3270 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 12:07:44.886  3176  3270 I bt_vendor: bluetooth satus is on
09-02 12:07:44.886  3176  3270 I bt_vendor: bt-vendor : resetting BT status
09-02 12:07:44.886  3176  3270 I bt_vendor: Starting hciattach daemon
09-02 12:07:44.886  3176  3270 I bt_vendor: try to set false
09-02 12:07:44.886  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:44.896  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:44.896  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:44.896  3176  3270 I bt_vendor: Starting hciattach daemon
09-02 12:07:44.896  3176  3270 I bt_vendor: try to set false
,09-02 12:07:44.896  3176  3270 I bt_vendor: cleanup
,09-02 12:07:44.896  3176  3299 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-02 12:07:44.906  3176  3270 I GKI_LINUX: GKI_exit_task 0 done
09-02 12:07:44.906  3176  3270 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-02 12:07:44.906  1351  1351 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 12:07:44.906  3176  3267 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-02 12:07:44.906  3176  3267 D BtConfig.SecureMode: isSecureModeOn:false
09-02 12:07:44.906  3176  3267 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-02 12:07:44.906  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 12:07:44.906  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-02 12:07:44.906  3176  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 12:07:44.906  1017  1212 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:44.906  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.906  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.906  1017  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:44.906  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:44.916  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 12:07:44.916  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-02 12:07:44.916  3176  3176 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:07:44.916  3176  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-02 12:07:44.916  3176  3176 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 12:07:44.916  3176  3176 D BtGatt.GattService: stop()
09-02 12:07:44.916  3176  3176 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 12:07:44.916  1017  4395 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-02 12:07:44.916  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.916  1017  4395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:44.916  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:44.926  1017  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:44.926  1017  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.926  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:44.926  1017  1500 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.926  1017  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:44.926  1017  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:44.926  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-02 12:07:44.926  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 12:07:44.926  3176  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-02 12:07:44.936  1017  4394 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:44.936  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.936  1017  4394 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:44.936  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:44.936  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:44.936  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.936  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:44.936  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:44.936  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:44.946  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-02 12:07:44.946  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 12:07:44.946  3176  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 12:07:44.946  1017  1210 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:44.946  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.946  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:44.946  1017  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:44.946  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:44.946  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-02 12:07:44.946  1017  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-02 12:07:44.946  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 12:07:44.946  3176  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 12:07:44.956  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.956  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:44.956  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:44.956  1017  4394 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:44.956  1017  4394 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.956  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.956  1017  4394 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:44.956  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:44.956  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-02 12:07:44.956  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 12:07:44.956  3176  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 12:07:44.956  1017  1212 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:44.956  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.956  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.956  1017  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:44.956  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:44.966  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 12:07:44.966  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 12:07:44.966  3176  3267 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 12:07:44.966  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:44.966  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.976  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.976  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:44.976  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:44.976  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-02 12:07:44.976  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 12:07:44.986  1351  1351 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-02 12:07:44.986  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
09-02 12:07:44.986  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 12:07:44.986  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
09-02 12:07:44.986  1017  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:44.986  3176  3267 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-02 12:07:44.986  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 12:07:44.986  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:44.986  1017  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:44.986  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 12:07:44.996  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:44.996  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:44.996  3176  3267 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:44.996  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:44.996  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-02 12:07:44.996  3176  3267 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:44.996  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,09-02 12:07:44.996  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-02 12:07:44.996  3176  3267 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-02 12:07:44.996  3176  3267 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,09-02 12:07:44.996  3176  3267 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-02 12:07:44.996  3176  3267 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-02 12:07:44.996  3176  3267 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-02 12:07:44.996  3176  3176 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-02 12:07:44.996  3176  3176 D HeadsetService: Received stop request...Stopping profile...
,09-02 12:07:45.006  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:45.006  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-02 12:07:45.006  1351  1351 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-02 12:07:45.006  1351  1351 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-02 12:07:45.006  1351  1351 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-02 12:07:45.006  1351  1351 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-02 12:07:45.006  1351  1351 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-02 12:07:45.006  3176  3176 D A2dpService: Received stop request...Stopping profile...
,09-02 12:07:45.006  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:45.016  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:45.016  3855  3855 D HeadsetProfile: Bluetooth service disconnected
,09-02 12:07:45.016  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:07:45.016  1017  1130 D Tethering: InitialState.processMessage what=4
,09-02 12:07:45.016  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:45.016  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:45.016  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:07:45.016  1017  1130 E Tethering: No numeric data
,09-02 12:07:45.026  3176  3288 D A2dpStateMachine: Exit Disconnected: -1
,09-02 12:07:45.026  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 12:07:45.026  1017  1130 D Tethering: clearTetheredNotification()
,09-02 12:07:45.026  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:45.026  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:45.026  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:45.026  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:07:45.026  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:45.026  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:07:45.026  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:07:45.026  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 12:07:45.036  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 12:07:45.036  1173  1173 D HotspotTile: updateTetherState():false, false
,09-02 12:07:45.036  1017  1017 D BluetoothA2dp: Proxy object disconnected
09-02 12:07:45.036  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-02 12:07:45.036  3176  3176 D HidService: Received stop request...Stopping profile...
09-02 12:07:45.036  3176  3176 D HidService: Stopping Bluetooth HidService
09-02 12:07:45.036  3176  3176 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:07:45.036  3176  3176 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-02 12:07:45.036  3176  3176 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:07:45.036  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:45.036  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:45.036  1017  1123 V NetworkStats: performPollLocked() took 8ms
09-02 12:07:45.036  3855  3855 D BluetoothA2dp: Proxy object disconnected
09-02 12:07:45.036  3855  3855 D A2dpProfile: Bluetooth service disconnected
,09-02 12:07:45.036  3176  3176 D HealthService: Received stop request...Stopping profile...
09-02 12:07:45.036  3855  3855 D BluetoothInputDevice: Proxy object disconnected
09-02 12:07:45.036  3855  3855 D HidProfile: Bluetooth service disconnected
09-02 12:07:45.046  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:45.046  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:45.046  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:45.046  4753  6829 D UdcContextInitService: registered all accounts: true
,09-02 12:07:45.046  3176  3176 D PanService: Received stop request...Stopping profile...
,09-02 12:07:45.046  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:45.046  1962  2153 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 12:07:45.046  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-02 12:07:45.056  3855  3855 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 12:07:45.056  3855  3855 D PanProfile: Bluetooth service disconnected
,09-02 12:07:45.056  3176  3176 D BluetoothMapService: Received stop request...Stopping profile...
,09-02 12:07:45.056  6915  6915 I dex2oat : ----------------------------------------------------
09-02 12:07:45.056  6915  6915 I dex2oat : <SS>: S T A R T I N G . . .
09-02 12:07:45.056  6915  6915 I dex2oat : <SS>: Zip is absent. Canceled.
,09-02 12:07:45.056  6915  6915 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-02 12:07:45.066   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb89b47c8,
09-02 12:07:45.066   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-02 12:07:45.066   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-02 12:07:45.066   272   322 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1197783752)
,09-02 12:07:45.096  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
09-02 12:07:45.096   295   295 E SMD     : DCD OFF
09-02 12:07:45.096  3176  3176 D SapService: Received stop request...Stopping profile...
09-02 12:07:45.096  3176  3176 D SapService: Stopping Bluetooth SapService
09-02 12:07:45.096  3176  3176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:45.106  3176  3176 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-02 12:07:45.106  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 12:07:45.106  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-02 12:07:45.116  3855  3855 D BluetoothMap: Proxy object disconnected
,09-02 12:07:45.116  3855  3855 D MapProfile: Bluetooth service disconnected
09-02 12:07:45.116  3855  3855 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-02 12:07:45.116  3855  3855 D SapProfile: Bluetooth service disconnected
,09-02 12:07:45.116   272   322 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-02 12:07:45.116   272   322 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-02 12:07:45.116   272   322 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1197783752) wakelock released: 1, error no: 0
09-02 12:07:45.116   272   322 I rmt_storage: 
,09-02 12:07:45.116   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb89b47c8
,09-02 12:07:45.126  1962  2172 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-02 12:07:45.126  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 12:07:45.146  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 12:07:45.146  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 12:07:45.146  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 12:07:45.146  6915  6915 I dex2oat : dex2oat took 88.367ms (threads: 4)
,09-02 12:07:45.146  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 12:07:45.146  3176  3176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 12:07:45.146  3176  3176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 12:07:45.146  3176  3176 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-02 12:07:45.146  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 12:07:45.146  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-02 12:07:45.146  3176  3176 D BluetoothA2dp: Proxy object disconnected
09-02 12:07:45.146  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.146  3176  3176 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-02 12:07:45.146  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 12:07:45.146  3176  3289 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 12:07:45.146  3176  3176 I GKI_LINUX: GKI_exit_task 2 done,
,09-02 12:07:45.146  3176  3176 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated,
09-02 12:07:45.146  3176  3176 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-02 12:07:45.146  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
,09-02 12:07:45.146  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService,
,09-02 12:07:45.156  1351  1351 I wpa_supplicant: Blacklist: Clear (all) 
09-02 12:07:45.156  3176  3176 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-02 12:07:45.156  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
,09-02 12:07:45.156  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-02 12:07:45.156  3176  3176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 12:07:45.156  3176  3176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:07:45.156  3176  3176 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true,
09-02 12:07:45.156  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 12:07:45.156  3176  3176 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 12:07:45.156  3176  3176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-02 12:07:45.156  3176  3176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 12:07:45.156  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.156  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 12:07:45.156  3176  3176 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-02 12:07:45.156  3176  3176 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 12:07:45.156  3176  3176 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-02 12:07:45.156  3176  3176 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-02 12:07:45.156  3176  3176 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,09-02 12:07:45.156  3176  3176 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-02 12:07:45.156  3176  3267 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-02 12:07:45.156  3176  3267 D BluetoothAdapterProperties: Setting state to 10
09-02 12:07:45.156  3176  3267 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-02 12:07:45.156  3176  3267 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 12:07:45.156  3176  3267 D BluetoothAdapterService: updateAdapterState state is 10
09-02 12:07:45.166  3176  6859 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:07:45.166  3855  6925 D BluetoothPbap: onBluetoothStateChange: up=false
,09-02 12:07:45.166  6834  6842 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 12:07:45.166  6834  6842 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 12:07:45.166  6834  6842 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 12:07:45.166  6834  6842 I Adreno-EGL: Local Branch: 
09-02 12:07:45.166  6834  6842 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 12:07:45.166  6834  6842 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 12:07:45.166  6834  6842 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 12:07:45.166  3855  3864 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 12:07:45.166  3855  3863 D Bluetoothsap: onBluetoothStateChange: up=false
09-02 12:07:45.166  3855  3863 D Bluetoothsap: Unbinding service...
,09-02 12:07:45.166  1962  2157 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:45.166  1962  2157 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:45.176  6754  6767 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 12:07:45.176  6754  6767 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:45.176  6754  6767 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-02 12:07:45.176  6754  6767 D BluetoothLeAdvertiser: Exit stop advertising
,09-02 12:07:45.176  6754  6767 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-02 12:07:45.176  6754  6767 D BluetoothLeScanner: Exiting stopAllScan
09-02 12:07:45.176  1457  1479 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:45.176  1457  1479 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:45.176  3176  3267 D BluetoothAdapterService: Autoconnection is available 
09-02 12:07:45.176  3176  3267 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-02 12:07:45.176  3176  3267 I BluetoothAdapterState: Entering OffState
,09-02 12:07:45.176  1441  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 12:07:45.176   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-02 12:07:45.176  1441  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 12:07:45.176   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 12:07:45.176  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.176  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 12:07:45.176  3855  6925 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 12:07:45.176  3855  6925 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 12:07:45.176  3176  3193 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 12:07:45.176  3176  3193 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:45.176  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.186  1173  4433 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 12:07:45.186  1173  4433 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 12:07:45.186  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 12:07:45.186  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 12:07:45.186  3855  6925 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:07:45.186  3855  3864 D BluetoothMap: onBluetoothStateChange: up=false
09-02 12:07:45.186  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 12:07:45.186  6893  6918 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
09-02 12:07:45.186  1432  1440 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 12:07:45.186  1432  1440 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 12:07:45.186  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 12:07:45.186  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.186  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 12:07:45.186  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-02 12:07:45.186  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 12:07:45.186  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 12:07:45.196  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 12:07:45.196  1351  1351 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-02 12:07:45.196  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:45.196  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:45.196  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:07:45.206  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 12:07:45.206  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 12:07:45.206  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:45.206  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
09-02 12:07:45.206  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 12:07:45.206  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.206  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 12:07:45.216  1173  1173 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
09-02 12:07:45.216  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 12:07:45.216  3176  3270 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-02 12:07:45.216  1173  1173 D BluetoothTile:  getBluetoothState : 10
09-02 12:07:45.216  1173  1732 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
09-02 12:07:45.216  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:45.216  1173  1732 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
09-02 12:07:45.216  3176  3176 I GKI_LINUX: GKI_exit_task 1 done
09-02 12:07:45.216  3176  3176 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-02 12:07:45.216  1915  1915 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-02 12:07:45.216  1017  1500 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 12:07:45.216  3176  3176 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 12:07:45.216  1173  1173 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
09-02 12:07:45.216  1173  1173 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
09-02 12:07:45.216  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.216  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 12:07:45.216  3855  3855 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:45.216  1017  4394 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 12:07:45.216  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 12:07:45.216  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.216  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 12:07:45.216  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:45.216  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.216  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:45.216  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:45.216  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:07:45.216  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:45.216  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:45.216  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:45.216  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:45.216  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:45.226  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:45.226  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 12:07:45.226  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 12:07:45.226  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 12:07:45.226  3176  3176 I art     : System.exit called, status: 0
09-02 12:07:45.226  3176  3176 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 12:07:45.226  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 12:07:45.226  1962  2159 D BluetoothAdapter: 242131902: getState() :  mService = null. Returning STATE_OFF
09-02 12:07:45.226  1017  4394 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:45.226  1962  2159 D BluetoothAdapter: 242131902: getState() :  mService = null. Returning STATE_OFF
09-02 12:07:45.226  1017  4394 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 12:07:45.236   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-02 12:07:45.236   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 12:07:45.236  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:45.236  1017  4394 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:45.236  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:45.236  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 12:07:45.246  6893  6918 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-02 12:07:45.286   290   290 I WVCdm   : CdmEngine::OpenSession
,09-02 12:07:45.286  1017  1383 I ActivityManager: Process com.android.bluetooth (pid 3176)(adj 0) has died(32,706)
,09-02 12:07:45.296  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-02 12:07:45.296  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 12:07:45.306  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:07:45.306  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-02 12:07:45.306  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:45.306  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:45.316  3855  3855 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-02 12:07:45.316  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:45.316  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:45.316  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 12:07:45.316  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-02 12:07:45.316  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:45.316  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 12:07:45.316  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:45.326  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:45.326  1962  2159 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:07:45.326  1173  1173 D HotspotTile: onReceive : 1, 0
,09-02 12:07:45.366  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:07:45.366  1017  1017 I ApplicationPolicy: updateDataUsageMap
,09-02 12:07:45.376  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:07:45.396  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:45.396  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:45.406  1017  1481 I ActivityManager: Killing 6452:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-02 12:07:45.466  1962  2172 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-02 12:07:45.506  6893  6893 D StrictMode: StrictMode policy violation; ~duration=322 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:45.506  6893  6893 D StrictMode: StrictMode policy violation; ~duration=319 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:45.506  6893  6893 D StrictMode: StrictMode policy violation; ~duration=318 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:45.506  6893  6893 D StrictMode: StrictMode policy violation; ~duration=306 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.e.b(PG:170)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:45.506  6893  6893 D StrictMode: StrictMode policy violation; ~duration=304 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.k.d(PG:583)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.e.b(PG:170)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:45.506  6893  6893 D StrictMode: StrictMode policy violation; ~duration=207 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:45.506  6893  6893 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:45.506  6893  6893 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:45.506  6893  6893 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:45.536  1962  2172 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
09-02 12:07:45.536  1017  1212 I ActivityManager: Killing 6345:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
09-02 12:07:45.546  1962  1962 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 12:07:45.546  1962  1962 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-02 12:07:45.546  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:45.546  1017  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:45.546  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-02 12:07:45.546  1017  1212 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-02 12:07:45.546  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:45.546  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:45.546  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:45.546  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:45.566  6959  6959 E Zygote  : MountEmulatedStorage()
09-02 12:07:45.566  6959  6959 E Zygote  : v2
09-02 12:07:45.566  6959  6959 I libpersona: KNOX_SDCARD checking this for 10102
09-02 12:07:45.566  6959  6959 I libpersona: KNOX_SDCARD not a persona
09-02 12:07:45.566  6959  6959 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:45.566  1017  1212 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6959 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-02 12:07:45.566  6959  6959 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:07:45.566  6959  6959 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-02 12:07:45.576  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-02 12:07:45.596  6959  6959 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:45.596  6959  6959 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:45.616  6959  6959 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-02 12:07:45.676  6893  6953 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-02 12:07:45.706  1017  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:45.706  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:45.706  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:45.706  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-02 12:07:45.816  1017  1044 D Tethering: interfaceRemoved wlan0
,09-02 12:07:45.816  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-02 12:07:45.816  6959  6981 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-02 12:07:45.816  6959  6981 I Babel_SMS: MmsConfig.loadMmsSettings
,09-02 12:07:45.826  6959  6981 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-02 12:07:45.826  6959  6981 I Babel_SMS: MmsConfig.loadFromDatabase
,09-02 12:07:45.846  6959  6981 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-02 12:07:45.846  6959  6981 I Babel_SMS: MmsConfig.loadFromResources
,09-02 12:07:45.846  6959  6981 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-02 12:07:45.846  6959  6981 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-02 12:07:45.866  1017  1476 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-02 12:07:45.866  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-02 12:07:45.866  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:45.866  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:45.866  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 12:07:45.886  6959  6959 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:07:45.896  6959  6959 I Babel_Crash: startup - clean
,09-02 12:07:45.906  1017  1044 D Tethering: interfaceRemoved p2p0,
09-02 12:07:45.906  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-02 12:07:45.926  1017  1471 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 12:07:45.926  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:07:45.926  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:45.926  1017  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:45.926  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:07:45.936  1593  1593 I Hs20UtilService: Starting #8
,09-02 12:07:45.936  1593  1636 I Hs20UtilService: Message received 5007
,09-02 12:07:45.936  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 12:07:45.936  6959  6959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 12:07:45.936  6959  6959 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 12:07:45.946  6959  6959 W AudioCapabilities: Unsupported mime audio/qcelp
,09-02 12:07:45.946  6959  6959 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-02 12:07:45.946  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:07:45.946  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 12:07:45.946  6959  6959 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-02 12:07:45.946  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 12:07:45.946  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:07:45.946  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 12:07:45.946  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:07:45.946  6959  6959 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-02 12:07:45.956  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 12:07:45.956  6959  6959 W AudioCapabilities: Unsupported mime audio/x-ima
,09-02 12:07:45.956  6959  6959 W AudioCapabilities: Unsupported mime audio/qcelp
,09-02 12:07:45.956  6959  6959 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 12:07:45.956  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:07:45.956  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 12:07:45.966  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 12:07:45.966  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:07:45.966  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 12:07:45.966  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:07:45.966  1017  1383 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-02 12:07:45.966  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:45.966  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:45.966  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:45.966  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:45.976  6984  6984 E Zygote  : MountEmulatedStorage(),
,09-02 12:07:45.986  6984  6984 E Zygote  : v2
09-02 12:07:45.986  6984  6984 I libpersona: KNOX_SDCARD checking this for 10064
09-02 12:07:45.986  6984  6984 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:45.986  6959  6959 W VideoCapabilities: Unsupported mime video/wvc1
09-02 12:07:45.986  6984  6984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:45.986  6959  6959 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
,09-02 12:07:45.986  6984  6984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:45.986  6984  6984 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:45.996  1017  1383 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6984 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 12:07:45.996  6959  6959 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-02 12:07:45.996  6959  6959 W VideoCapabilities: Unsupported mime video/wvc1
,09-02 12:07:46.006  6959  6959 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-02 12:07:46.006  6959  6959 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-02 12:07:46.006  6984  6984 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:46.006  6959  6959 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-02 12:07:46.006  6984  6984 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.016  6959  6959 W VideoCapabilities: Unsupported mime video/mp43
,09-02 12:07:46.016  6959  6959 W VideoCapabilities: Unsupported mime video/sorenson
,09-02 12:07:46.026  6959  6959 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-02 12:07:46.026  6984  6984 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 12:07:46.036  6959  6959 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-02 12:07:46.046  6984  6984 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 12:07:46.056  6984  6984 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-02 12:07:46.066  6959  6959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 12:07:46.066  6959  6959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 12:07:46.066  6959  6959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 12:07:46.076  6959  6959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 12:07:46.076  1017  1483 I ActivityManager: Killing 6492:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-02 12:07:46.076  6959  6959 I vclib   : onServiceConnected
,09-02 12:07:46.086  6984  6984 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 12:07:46.086  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-02 12:07:46.086  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.086  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.086  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.086  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.096  6999  6999 E Zygote  : MountEmulatedStorage()
09-02 12:07:46.096  6999  6999 I libpersona: KNOX_SDCARD checking this for 10065
09-02 12:07:46.096  6999  6999 E Zygote  : v2
09-02 12:07:46.096  6999  6999 I libpersona: KNOX_SDCARD not a persona
09-02 12:07:46.096  6999  6999 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:46.106  6999  6999 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 12:07:46.106  6999  6999 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:46.106  1017  1476 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6999 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:07:46.106  1017  1476 I ActivityManager: Killing 6483:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-02 12:07:46.126  6999  6999 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:46.126  6999  6999 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.146  6999  6999 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 12:07:46.146  1017  1212 I ActivityManager: Killing 6532:com.samsung.android.sm/1000 (adj 15): empty #21
,09-02 12:07:46.156  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 12:07:46.156  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:07:46.156  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:46.156  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.156  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:07:46.156  1593  1593 I Hs20UtilService: Starting #9
,09-02 12:07:46.156  1593  1636 I Hs20UtilService: Message received 5007
,09-02 12:07:46.166  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 12:07:46.166  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:07:46.166  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 12:07:46.166  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 12:07:46.166  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:07:46.166  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 12:07:46.166  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:07:46.166  1017  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 12:07:46.166  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:07:46.166  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:46.166  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.166  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:07:46.176  1593  1593 I Hs20UtilService: Starting #10
09-02 12:07:46.176  1593  1636 I Hs20UtilService: Message received 5011
,09-02 12:07:46.176  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 12:07:46.176  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-02 12:07:46.176  6582  6582 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 12:07:46.176  6582  6582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 12:07:46.186  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.186  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.186  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.196  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.196  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.196  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.196  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.196  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.196  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.196  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.206  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.206  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.206  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.206  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.206  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.206  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.206  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.206  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.206  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.206  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.206  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.216  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.216  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.216  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.216  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.216  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.216  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.216  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.216  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.216  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.216  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.216  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.216  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.226  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.226  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.226  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.226  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.226  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.226  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.226  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:46.226  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.226  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.226  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:46.226  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.226  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 12:07:46.236  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:07:46.236  1017  4394 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 12:07:46.236  1017  4394 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 12:07:46.236  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.236  1017  4394 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.236  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 12:07:46.246  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:07:46.246  3855  3855 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 12:07:46.246  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:46.246  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-02 12:07:46.246  1017  4395 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-02 12:07:46.256  1017  4395 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-02 12:07:46.256  1017  4395 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.256  1017  4395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.256  1017  4395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.266  7015  7015 E Zygote  : MountEmulatedStorage()
,09-02 12:07:46.266  7015  7015 E Zygote  : v2
09-02 12:07:46.266  7015  7015 I libpersona: KNOX_SDCARD checking this for 1002
09-02 12:07:46.266  7015  7015 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:46.266  7015  7015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:46.266  7015  7015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:07:46.266  1017  4395 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7015 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-02 12:07:46.266  7015  7015 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:46.286  7015  7015 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:46.286  7015  7015 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.316  7015  7015 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 12:07:46.316  7015  7015 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 12:07:46.336  7015  7015 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-02 12:07:46.366  7015  7015 D BtSettings.ProfileConfig: Adding GattService
,09-02 12:07:46.366  7015  7015 D BtSettings.ProfileConfig: Adding HeadsetService
09-02 12:07:46.366  7015  7015 D BtSettings.ProfileConfig: Adding A2dpService
,09-02 12:07:46.366  7015  7015 D BtSettings.ProfileConfig: Adding HidService
09-02 12:07:46.366  7015  7015 D BtSettings.ProfileConfig: Adding HealthService
09-02 12:07:46.366  7015  7015 D BtSettings.ProfileConfig: Adding PanService
09-02 12:07:46.366  7015  7015 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-02 12:07:46.376  7015  7015 D BtSettings.ProfileConfig: Adding SapService
,09-02 12:07:46.376  7015  7015 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-02 12:07:46.376  7015  7015 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-02 12:07:46.376  7015  7015 D BtSettings.ProfileConfig: Adding SapClientService
,09-02 12:07:46.376  7015  7015 D BtSettings.ProfileConfig: Adding HidDevService
09-02 12:07:46.376  7015  7015 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-02 12:07:46.376  1017  2016 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-02 12:07:46.376  1017  2016 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.376  1017  2016 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:46.376  1017  2016 D SettingsProvider: selectionArgs: false
09-02 12:07:46.376  1017  2016 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.376  1017  2016 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:46.376  1017  2016 D SettingsProvider: ret = -1
,09-02 12:07:46.376  1017  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-02 12:07:46.376  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.376  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:46.376  1017  1481 D SettingsProvider: selectionArgs: false
,09-02 12:07:46.376  1017  1481 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.376  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:46.376  1017  1481 D SettingsProvider: ret = -1
,09-02 12:07:46.376  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-02 12:07:46.376  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.376  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:46.376  1017  1030 D SettingsProvider: selectionArgs: false
,09-02 12:07:46.376  1017  1030 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.376  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:46.376  1017  1030 D SettingsProvider: ret = -1
,09-02 12:07:46.376  1017  4396 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-02 12:07:46.376  1017  4396 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.376  1017  4396 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:46.376  1017  4396 D SettingsProvider: selectionArgs: false
09-02 12:07:46.376  1017  4396 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.376  1017  4396 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:46.376  1017  4396 D SettingsProvider: ret = -1
,09-02 12:07:46.376  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-02 12:07:46.376  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 12:07:46.376  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:46.376  1017  1029 D SettingsProvider: selectionArgs: false
09-02 12:07:46.376  1017  1029 D SettingsProvider: selectionArgs: 1002
,09-02 12:07:46.386  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:46.386  1017  1029 D SettingsProvider: ret = -1
,09-02 12:07:46.386  1017  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-02 12:07:46.386  1017  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 12:07:46.386  1017  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:46.386  1017  1500 D SettingsProvider: selectionArgs: false
09-02 12:07:46.386  1017  1500 D SettingsProvider: selectionArgs: 1002
,09-02 12:07:46.386  1017  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:46.386  1017  1500 D SettingsProvider: ret = -1
,09-02 12:07:46.386  1017  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-02 12:07:46.386  1017  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.386  1017  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:46.386  1017  1471 D SettingsProvider: selectionArgs: false
09-02 12:07:46.386  1017  1471 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.386  1017  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:46.386  1017  1471 D SettingsProvider: ret = -1
,09-02 12:07:46.386  1017  4395 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-02 12:07:46.386  1017  4395 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.386  1017  4395 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 12:07:46.386  1017  4395 D SettingsProvider: selectionArgs: false
09-02 12:07:46.386  1017  4395 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.386  1017  4395 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:46.386  1017  4395 D SettingsProvider: ret = -1
,09-02 12:07:46.386  1017  1212 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:46.386  1017  1212 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.386  1017  1212 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:46.386  1017  1212 D SettingsProvider: selectionArgs: false
,09-02 12:07:46.386  1017  1212 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.386  1017  1212 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:46.386  1017  1212 D SettingsProvider: ret = -1
,09-02 12:07:46.386  1017  4394 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-02 12:07:46.386  1017  4394 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.386  1017  4394 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 12:07:46.386  1017  4394 D SettingsProvider: selectionArgs: false
09-02 12:07:46.386  1017  4394 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.386  1017  4394 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:46.386  1017  4394 D SettingsProvider: ret = -1
,09-02 12:07:46.386  1017  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,09-02 12:07:46.386  1017  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.386  1017  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:46.386  1017  1483 D SettingsProvider: selectionArgs: false
,09-02 12:07:46.396  1017  1483 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.396  1017  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:46.396  1017  1483 D SettingsProvider: ret = -1
,09-02 12:07:46.396  1017  1210 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-02 12:07:46.396  1017  1210 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:46.396  1017  1210 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 12:07:46.396  1017  1210 D SettingsProvider: selectionArgs: false
09-02 12:07:46.396  1017  1210 D SettingsProvider: selectionArgs: 1002
09-02 12:07:46.396  1017  1210 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:46.396  1017  1210 D SettingsProvider: ret = -1
,09-02 12:07:46.406  1017  2016 I ActivityManager: Killing 6550:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-02 12:07:46.406  1962  1962 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 12:07:46.406  1017  4396 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 12:07:46.406  1017  4396 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 12:07:46.406  1017  4396 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.406  1017  4396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 12:07:46.406  1017  4396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:46.416   290   693 I WVCdm   : CdmEngine::CloseSession
,09-02 12:07:46.426  1962  7031 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-02 12:07:46.426  1962  1962 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 12:07:46.426  1017  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:46.436  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:46.436  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:46.436  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:46.436  1017  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 12:07:46.436  1017  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 12:07:46.436  1017  1500 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:46.436  1017  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:46.436  1017  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:07:46.436  1593  1593 I Hs20UtilService: Starting #11
,09-02 12:07:46.446  1593  1636 I Hs20UtilService: Message received 5011
,09-02 12:07:46.446  1017  4394 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:46.446  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 12:07:46.446  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 12:07:46.446  6582  6582 D SecurityLogAgent: StateMachine : Current State = 1
09-02 12:07:46.446  6582  6582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 12:07:46.446  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:46.446  1017  4394 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:46.446  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:46.456  1962  7031 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-02 12:07:46.456  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-02 12:07:46.456  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.456  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.456  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.456  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.476  7033  7033 E Zygote  : MountEmulatedStorage(),
09-02 12:07:46.476  1017  1476 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7033 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-02 12:07:46.476  7033  7033 E Zygote  : v2
09-02 12:07:46.476  7033  7033 I libpersona: KNOX_SDCARD checking this for 1000
09-02 12:07:46.476  7033  7033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:46.476  7033  7033 I libpersona: KNOX_SDCARD not a persona
09-02 12:07:46.476   290   290 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-02 12:07:46.476  7033  7033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:46.476  7033  7033 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:46.476   290   290 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-02 12:07:46.476   290   290 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-02 12:07:46.476   290   290 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-02 12:07:46.486   290   290 D WVCdm   : PrepareKeyRequest: nonce=2186727472
,09-02 12:07:46.506  7033  7033 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-02 12:07:46.506  7033  7033 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.506   314   314 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 32.688ms,
,09-02 12:07:46.526   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.578ms
,09-02 12:07:46.526  7033  7033 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-02 12:07:46.526  7033  7033 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-02 12:07:46.526  7033  7033 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-02 12:07:46.536   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.526ms
,09-02 12:07:46.546  7033  7033 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-02 12:07:46.546  7033  7033 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-02 12:07:46.546  7033  7033 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-02 12:07:46.546  7033  7033 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:07:46.546  1017  1030 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-02 12:07:46.546  7033  7048 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-02 12:07:46.546  1017  1030 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-02 12:07:46.556  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-02 12:07:46.556  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.556  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.556  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.556  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-02 12:07:46.576  7050  7050 E Zygote  : MountEmulatedStorage(),
,09-02 12:07:46.576  7050  7050 E Zygote  : v2
09-02 12:07:46.576  7050  7050 I libpersona: KNOX_SDCARD checking this for 10001
09-02 12:07:46.576  7050  7050 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:46.576  7050  7050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:46.576  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7050 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:07:46.576  7050  7050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:46.586  7050  7050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:46.586  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
09-02 12:07:46.586  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-02 12:07:46.586  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.586  1785  1785 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-02 12:07:46.586  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.586  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
09-02 12:07:46.586  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-02 12:07:46.606  7061  7061 E Zygote  : MountEmulatedStorage()
,09-02 12:07:46.606  7061  7061 E Zygote  : v2
09-02 12:07:46.606  7061  7061 I libpersona: KNOX_SDCARD checking this for 10121
09-02 12:07:46.606  7061  7061 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:46.606  7061  7061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:46.606  1017  1042 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7061 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-02 12:07:46.606  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
09-02 12:07:46.606  7050  7050 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 12:07:46.606  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.606  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.606  7050  7050 D ActivityThread: Added TimaKeyStore provider
09-02 12:07:46.606  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.606  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.606  7061  7061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:46.606  7061  7061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:46.616  7074  7074 E Zygote  : MountEmulatedStorage()
,09-02 12:07:46.616  7074  7074 E Zygote  : v2
09-02 12:07:46.616  7074  7074 I libpersona: KNOX_SDCARD checking this for 10031
,09-02 12:07:46.616  7074  7074 I libpersona: KNOX_SDCARD not a persona,
09-02 12:07:46.616  7074  7074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:46.616  1017  1030 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7074 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-02 12:07:46.626  7074  7074 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-02 12:07:46.626  7074  7074 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:46.636  7061  7061 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:46.636  7061  7061 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.646  2489  2497 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,09-02 12:07:46.646  7074  7074 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:46.646  7074  7074 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.646  1785  1785 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-02 12:07:46.646  1785  1785 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-02 12:07:46.646  1785  1785 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-02 12:07:46.646  1785  1785 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-02 12:07:46.656  7061  7061 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 12:07:46.656  7061  7061 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-02 12:07:46.666  7061  7061 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 12:07:46.666  1785  1785 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-02 12:07:46.666  1785  1785 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-02 12:07:46.666  1017  1481 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-02 12:07:46.666  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.666  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.666  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.666  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.686  7095  7095 E Zygote  : MountEmulatedStorage(),
09-02 12:07:46.686  7095  7095 I libpersona: KNOX_SDCARD checking this for 10077
09-02 12:07:46.686  7095  7095 E Zygote  : v2
,09-02 12:07:46.686  7095  7095 I libpersona: KNOX_SDCARD not a persona
09-02 12:07:46.686  7095  7095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:46.686  1017  1481 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7095 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 12:07:46.686  7095  7095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 12:07:46.686  7095  7095 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-02 12:07:46.696  7061  7061 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:07:46.696  7061  7061 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-02 12:07:46.706  7095  7095 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:46.706  7095  7095 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.716  7061  7061 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-02 12:07:46.716  7074  7074 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-02 12:07:46.716  1017  1471 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-02 12:07:46.716  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.716  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.716  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.716  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.726  7110  7110 E Zygote  : MountEmulatedStorage(),
,09-02 12:07:46.726  7110  7110 I libpersona: KNOX_SDCARD checking this for 10141
09-02 12:07:46.726  7110  7110 E Zygote  : v2
,09-02 12:07:46.726  7110  7110 I libpersona: KNOX_SDCARD not a persona
09-02 12:07:46.726  7110  7110 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:46.736  1017  1471 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7110 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-02 12:07:46.736  7110  7110 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:07:46.736  1017  1471 I ActivityManager: Killing 6599:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
09-02 12:07:46.736  7110  7110 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 12:07:46.736  1017  1471 I ActivityManager: Killing 6616:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-02 12:07:46.756  7110  7110 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:46.756  7110  7110 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.766  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-02 12:07:46.766  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.766  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.766  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.766  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.766  2758  7127 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-02 12:07:46.766  2758  7127 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-02 12:07:46.776  2758  7127 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-02 12:07:46.776  7128  7128 E Zygote  : MountEmulatedStorage()
09-02 12:07:46.776  7128  7128 E Zygote  : v2
09-02 12:07:46.776  7128  7128 I libpersona: KNOX_SDCARD checking this for 10032
09-02 12:07:46.776  7128  7128 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:46.776  7128  7128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:46.776  2758  7127 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-02 12:07:46.776  2758  7127 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
09-02 12:07:46.776  1017  1030 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7128 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 12:07:46.786  7128  7128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:46.786  7128  7128 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-02 12:07:46.806  7110  7110 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-02 12:07:46.806  7110  7110 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 12:07:46.806  7110  7110 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 12:07:46.806  7110  7110 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 12:07:46.816  7128  7128 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:46.816  7128  7128 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.816  1017  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-02 12:07:46.826  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.826  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.826  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.826  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.836  7143  7143 E Zygote  : MountEmulatedStorage()
09-02 12:07:46.836  7143  7143 I libpersona: KNOX_SDCARD checking this for 1000
09-02 12:07:46.836  7143  7143 E Zygote  : v2
09-02 12:07:46.836  7143  7143 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:46.836  7143  7143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-02 12:07:46.836  1017  1481 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7143 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-02 12:07:46.836  1017  1481 I ActivityManager: Killing 6566:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-02 12:07:46.846  7143  7143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 12:07:46.846  7143  7143 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:46.866  7143  7143 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 12:07:46.866  7143  7143 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:46.886  1017  1383 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:07:46.906  1017  1210 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:07:46.916  7143  7143 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-02 12:07:46.926  7128  7160 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-02 12:07:46.926  7128  7160 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-02 12:07:46.946  7128  7160 D SPPClientService: PushLog.txt file is not deleted.
,09-02 12:07:46.946  7128  7128 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
09-02 12:07:46.946  7128  7160 D SPPClientService: PushLog.txt file is not deleted.
09-02 12:07:46.946  7128  7160 D SPPClientService: ============PushLog. stop!
,09-02 12:07:46.946  1017  4395 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-02 12:07:46.946  1017  4395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.946  1017  4395 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:46.946  1017  4395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.946  1017  4395 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:46.966  7166  7166 E Zygote  : MountEmulatedStorage(),
09-02 12:07:46.966  7166  7166 E Zygote  : v2
09-02 12:07:46.966  7166  7166 I libpersona: KNOX_SDCARD checking this for 10036
09-02 12:07:46.966  7166  7166 I libpersona: KNOX_SDCARD not a persona,
09-02 12:07:46.966  7166  7166 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 12:07:46.966  7166  7166 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-02 12:07:46.966  1017  4395 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7166 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:07:46.966  7166  7166 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
09-02 12:07:46.966  1017  4395 I ActivityManager: Killing 6640:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-02 12:07:46.966  1017  2016 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:07:46.976  1017  1483 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push,
09-02 12:07:46.976  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-02 12:07:46.976  1017  1483 W ActivityManager: userId = 0, bbcId = -10000,
09-02 12:07:46.976  1017  1483 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-02 12:07:46.976  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-02 12:07:47.006  7166  7166 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:47.006  7166  7166 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:47.006  1017  4395 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:07:47.056  7128  7181 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-02 12:07:47.076  7166  7166 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@7c8ed3e
,09-02 12:07:47.076  1017  1471 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-02 12:07:47.086  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-02 12:07:47.086  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:47.086  1017  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:47.086  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 12:07:47.086  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-02 12:07:47.086  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:47.096  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:47.096  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:47.096  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:47.096  7166  7166 I SA      : [SSP] onCreated,
,09-02 12:07:47.106  7185  7185 E Zygote  : MountEmulatedStorage(),
09-02 12:07:47.106  7185  7185 E Zygote  : v2
09-02 12:07:47.106  7185  7185 I libpersona: KNOX_SDCARD checking this for 10110
09-02 12:07:47.106  7185  7185 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:47.106  7185  7185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:47.116  7185  7185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:07:47.116  7185  7185 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 12:07:47.116  1017  1030 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7185 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 12:07:47.116  1017  1481 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
09-02 12:07:47.116  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-02 12:07:47.126  1017  1481 W ActivityManager: userId = 0, bbcId = -10000,
09-02 12:07:47.126  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 12:07:47.126  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,09-02 12:07:47.126  6959  7186 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-02 12:07:47.136  7185  7185 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:47.136  7185  7185 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:47.146  1017  4396 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-02 12:07:47.146  1017  4396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:47.146  1017  4396 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:47.146  1017  4396 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:47.146  1017  4396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:47.146   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
09-02 12:07:47.146  7166  7166 I SA      : [TPM] There is no property file
,09-02 12:07:47.156  7204  7204 E Zygote  : MountEmulatedStorage(),
,09-02 12:07:47.166  7204  7204 E Zygote  : v2
09-02 12:07:47.166  7204  7204 I libpersona: KNOX_SDCARD checking this for 10068
09-02 12:07:47.166  7204  7204 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:47.166  7204  7204 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:47.166  7166  7166 I SA      : [SCU] isHaveSA() - false
,09-02 12:07:47.166  7204  7204 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-02 12:07:47.166  1017  4396 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7204 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-02 12:07:47.166  7204  7204 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-02 12:07:47.166  1017  4394 I ActivityManager: Killing 6080:com.android.mms/u0a41 (adj 15): empty #21
09-02 12:07:47.166  7166  7166 I SA      : [TPM] getModelProperty : null
09-02 12:07:47.166  7166  7166 I SA      : [TPM] getCSCProperty : null
09-02 12:07:47.166  7166  7166 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-02 12:07:47.166  7166  7166 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-02 12:07:47.166  7166  7166 I SA      : [DM] TFT FEATURE: false
,09-02 12:07:47.176  7166  7166 I SA      : [DM] init START
,09-02 12:07:47.186  7143  7143 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-02 12:07:47.186  7204  7204 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:47.186  7204  7204 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:47.196  1017  1471 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:07:47.196  7143  7143 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-02 12:07:47.196  7143  7143 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:07:47.196  7143  7143 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-02 12:07:47.196  7143  7143 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-02 12:07:47.196  7143  7143 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-02 12:07:47.206  1017  1212 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-02 12:07:47.206  7166  7166 I SA      : [DM] This device is not a Vodafone
,09-02 12:07:47.206  1017  1483 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:07:47.206  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:47.206  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:47.206  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:47.206  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:47.226  7221  7221 E Zygote  : MountEmulatedStorage()
,09-02 12:07:47.226  7221  7221 E Zygote  : v2
09-02 12:07:47.226  7221  7221 I libpersona: KNOX_SDCARD checking this for 10008
09-02 12:07:47.226  7221  7221 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:47.226  7221  7221 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:47.226  1017  1212 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7221 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:07:47.226  1017  1212 I ActivityManager: Killing 6663:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-02 12:07:47.226  7221  7221 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:47.226  7221  7221 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-02 12:07:47.236  1017  1500 D CountryDetector: No listener is left
,09-02 12:07:47.246   314   314 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 813us total 23.878ms
,09-02 12:07:47.256  7221  7221 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 12:07:47.256  7221  7221 D ActivityThread: Added TimaKeyStore provider
09-02 12:07:47.256  7204  7204 D BadgeProvider: onCreate
,09-02 12:07:47.256  7204  7204 D BadgeProvider: DatabaseHelper
,09-02 12:07:47.266   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 17.481ms
,09-02 12:07:47.286   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.603ms
,09-02 12:07:47.286  1017  1383 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:07:47.296  7204  7218 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-02 12:07:47.296  7166  7166 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-02 12:07:47.306  7166  7166 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-02 12:07:47.306  7166  7166 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-02 12:07:47.316  7166  7166 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-02 12:07:47.316  7166  7166 I SA      : [SCU] isHaveSA() - false
09-02 12:07:47.316  7166  7166 I SA      : support phone number id : false
09-02 12:07:47.316  7166  7166 I SA      : [DM] Supports Ref Jpn : true
,09-02 12:07:47.316  7166  7166 I SA      : [DM] init END
,09-02 12:07:47.326  7166  7166 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-02 12:07:47.326  7166  7166 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-02 12:07:47.326  7166  7166 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-02 12:07:47.346  1017  1030 I ActivityManager: Killing 6680:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-02 12:07:47.346  2857  2857 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 12:07:47 GMT+02:00 2016
,09-02 12:07:47.356  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-02 12:07:47.356  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 12:07:47.356  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:47.356  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:47.356  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 12:07:47.356  7204  7218 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-02 12:07:47.356  7204  7218 D BadgeProvider: sendNotify, [notify] : null
09-02 12:07:47.356  7204  7218 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-02 12:07:47.356  7204  7218 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-02 12:07:47.356  7204  7218 D BadgeProvider: update, [UpdateCount] : 1
,09-02 12:07:47.356  1484  1484 D Launcher.Model: reloadBadges entered.
,09-02 12:07:47.366  2857  2857 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
09-02 12:07:47.366  7166  7166 I SA      : [SLFUCHKMGR] constructor called
,09-02 12:07:47.366  1017  1483 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:07:47.376  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-02 12:07:47.376  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:47.376  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:47.376  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:47.376  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:47.396  7239  7239 E Zygote  : MountEmulatedStorage()
09-02 12:07:47.396  7239  7239 I libpersona: KNOX_SDCARD checking this for 10009
09-02 12:07:47.396  7239  7239 E Zygote  : v2
09-02 12:07:47.396  7239  7239 I libpersona: KNOX_SDCARD not a persona
09-02 12:07:47.396  2857  2857 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-02 12:07:47.396  7239  7239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:07:47.396  2857  2857 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-02 12:07:47.396  7239  7239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:47.396  7239  7239 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-02 12:07:47.396  1017  1029 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7239 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-02 12:07:47.406  1017  2016 I ActivityManager: Killing 6513:com.android.calendar/u0a131 (adj 15): empty #21
,09-02 12:07:47.406  2857  2857 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-02 12:07:47.426  2857  7238 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 12:07:47.426  1017  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-02 12:07:47.426  1017  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 12:07:47.426  1017  1029 D SecContentProvider2: mCursor = null
,09-02 12:07:47.426  1017  1029 D WifiService: setWifiEnabled: true pid=6754, uid=10171
09-02 12:07:47.426  1017  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-02 12:07:47.426  1017  1029 W WifiService: Failed getting userId using ActivityManagerNative
09-02 12:07:47.426  1017  1029 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-02 12:07:47.426  1017  1029 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 12:07:47.426  1017  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 12:07:47.426  1017  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 12:07:47.426  1017  1029 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 12:07:47.426  1017  1029 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-02 12:07:47.426  1017  1029 D SettingsProvider: name = wifi_on
,09-02 12:07:47.426  7239  7239 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:47.436  2857  7238 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-02 12:07:47.436  7239  7239 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:47.436  2857  7238 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-02 12:07:47.436  2857  7238 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-02 12:07:47.436  2857  2857 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-02 12:07:47.436  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,09-02 12:07:47.576  1017  1481 I art     : Explicit concurrent mark sweep GC freed 54363(3MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.808ms total 215.272ms
,09-02 12:07:47.616  7166  7166 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-02 12:07:47.616  1017  1029 I ActivityManager: Killing 6043:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-02 12:07:47.636  7166  7166 I SA      : [OR] == isSIMCardReady false ==
,09-02 12:07:47.636  1017  1212 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-02 12:07:47.646  7166  7166 I SA      : [SCU] == networkStateCheck == false
09-02 12:07:47.646  7166  7166 I SA      : [OR] onReceive END
,09-02 12:07:47.646  1017  1483 I ActivityManager: Killing 6697:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-02 12:07:47.656  1962  2172 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-02 12:07:47.656  1962  2172 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,09-02 12:07:47.656  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:07:47.666  1017  1471 I ActivityManager: Killing 5858:com.android.vending/u0a26 (adj 15): empty #21
,09-02 12:07:47.676  1017  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 12:07:47.676  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-02 12:07:47.676  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:47.676  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 12:07:47.676  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:47.706  4753  7257 I iu.SyncManager: SYNC; picasa accounts
09-02 12:07:47.706  4753  4753 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-02 12:07:47.756  1017  4395 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-02 12:07:47.756  1017  4395 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-02 12:07:47.756  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-02 12:07:47.756  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-02 12:07:47.796  1962  2172 I art     : Explicit concurrent mark sweep GC freed 50414(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 11MB/18MB, paused 1.314ms total 84.707ms
,09-02 12:07:47.836   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-02 12:07:47.836   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 12:07:47.836  7185  7268 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-02 12:07:47.836   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-02 12:07:47.836   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 12:07:47.836  7185  7268 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-02 12:07:47.856  1017  1044 D Tethering: interfaceAdded wlan0
,09-02 12:07:47.866  1017  1130 E Tethering: No numeric data
,09-02 12:07:47.866  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
09-02 12:07:47.866  1017  1130 D Tethering: clearTetheredNotification()
09-02 12:07:47.866  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:47.866  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:47.866  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:07:47.866  1017  1130 D Tethering: InitialState.processMessage what=4
,09-02 12:07:47.866  1017  1130 E Tethering: No numeric data
,09-02 12:07:47.876  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:07:47.876  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:47.876  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-02 12:07:47.876  1017  1044 D Tethering: interfaceAdded p2p0
,09-02 12:07:47.876  1173  1173 D HotspotTile: updateTetherState():false, false
09-02 12:07:47.876  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-02 12:07:47.876  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 12:07:47.876  1017  1130 D Tethering: clearTetheredNotification()
,09-02 12:07:47.876  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 12:07:47.876  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 12:07:47.876  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 12:07:47.876  1173  1173 D HotspotTile: updateTetherState():false, false
,09-02 12:07:47.876  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 12:07:47.876  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 12:07:47.876  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-02 12:07:47.886  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:47.886  1017  1123 V NetworkStats: performPollLocked() took 11ms
,09-02 12:07:47.886  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:47.886  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:47.886  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:47.886  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-02 12:07:47.886  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:07:47.886  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 12:07:47.886  7185  7185 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-02 12:07:47.886  7185  7185 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-02 12:07:47.886  7185  7185 I GAv4    :   adb logcat -s GAv4
,09-02 12:07:47.886   278  1010 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-02 12:07:47.886   278  1010 D SoftapController: Softap fwReload - Ok
,09-02 12:07:47.886  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:47.886  1017  1123 V NetworkStats: performPollLocked() took 4ms
,09-02 12:07:47.886   278  1010 D CommandListener: Setting iface cfg
09-02 12:07:47.886   278  1010 D CommandListener: Trying to bring down wlan0
,09-02 12:07:47.896  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:47.896   278  1010 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:07:47.896  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:47.896   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-02 12:07:47.896   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 12:07:47.896  7185  7270 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-02 12:07:47.896  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
,09-02 12:07:47.896   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
,09-02 12:07:47.896   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
09-02 12:07:47.896  7185  7270 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,09-02 12:07:47.926  7185  7185 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-02 12:07:47.926  1017  1480 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-02 12:07:47.936  7272  7272 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-02 12:07:47.936  7272  7272 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 12:07:47.946  7272  7272 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-02 12:07:47.946  7185  7185 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-02 12:07:47.966  7185  7274 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-02 12:07:47.966  7272  7272 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-02 12:07:47.966   410   410 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7272,
09-02 12:07:47.966   410   410 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-02 12:07:47.966  7272  7272 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-02 12:07:47.966  7272  7272 I wpa_supplicant: ssSupport state is = 1
09-02 12:07:47.966  7272  7272 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-02 12:07:47.966  7272  7272 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-02 12:07:47.966   410   410 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7272
09-02 12:07:47.966   410   410 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-02 12:07:47.996  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-02 12:07:48.006  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:07:48.006  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-02 12:07:48.006  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 12:07:48.006  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:48.006  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 12:07:48.006  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:48.006  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:48.006  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 12:07:48.006  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 12:07:48.006  1173  1173 D HotspotTile: onReceive : 2, 0
09-02 12:07:48.006  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-02 12:07:48.016  3855  3855 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:48.016  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:48.016  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-02 12:07:48.096   290  6949 I WVCdm   : CdmEngine::CloseSession
,09-02 12:07:48.096   295   295 E SMD     : DCD OFF,
,09-02 12:07:48.096   290  6949 I WVCdm   : L3 Terminate.
,09-02 12:07:48.126  1017  2016 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-02 12:07:48.126  1017  2016 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-02 12:07:48.126  1017  2016 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:48.126  1017  2016 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:48.126  1017  2016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:48.146   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 12:07:48.156   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-02 12:07:48.156  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-02 12:07:48.176  1962  6831 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-02 12:07:48.176  1962  6831 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 12:07:48.176  1962  6831 I System.out: (HTTPLog)-Static: isShipBuild true
09-02 12:07:48.176  1962  6831 I System.out: (HTTPLog)-Thread-267-73101778: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-02 12:07:48.176  1962  6831 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 12:07:48.176   278  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,09-02 12:07:48.176   278  1006 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-02 12:07:48.176  1962  6831 W GLSUser : [AppCertManager] IOException while requesting key: 
,09-02 12:07:48.206  7272  7272 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 12:07:48.206  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-02 12:07:48.216  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-02 12:07:48.216   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7272
09-02 12:07:48.216   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-02 12:07:48.216  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-02 12:07:48.216  7272  7272 I wpa_supplicant: ssSupport state is = 1
,09-02 12:07:48.216  7272  7272 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-02 12:07:48.216  7272  7272 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-02 12:07:48.216  7272  7272 E wpa_supplicant: SIM READ ERROR
09-02 12:07:48.216  7272  7272 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-02 12:07:48.226  7272  7272 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 12:07:48.226  7272  7272 E wpa_supplicant: SIM READ ERROR
09-02 12:07:48.226  7272  7272 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 12:07:48.226  7272  7272 I wpa_supplicant: wpa_default_ap_write_once
09-02 12:07:48.226  7272  7272 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 12:07:48.226  7272  7272 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 12:07:48.226  7272  7272 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-02 12:07:48.226  7272  7272 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 12:07:48.226  7272  7272 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-02 12:07:48.226  7272  7272 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 12:07:48.226  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 12:07:48.226  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:48.226  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:07:48.236  1017  2016 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:48.236  7185  7185 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-02 12:07:48.236  1017  2016 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:48.236  1017  2016 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 12:07:48.236  1017  2016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-02 12:07:48.266  7185  7185 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5128-5130)
,09-02 12:07:48.266  7185  7185 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-02 12:07:48.266  7272  7272 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-02 12:07:48.276  7185  7185 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15be4f1}
,09-02 12:07:48.276  7185  7185 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-02 12:07:48.276  7185  7185 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 12:07:48.296  7185  7185 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-02 12:07:48.296  7185  7185 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 12:07:48.296  7185  7185 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 12:07:48.316  7185  7185 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 12:07:48.316  7185  7185 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 12:07:48.316  7185  7185 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 12:07:48.316  7185  7185 I Adreno-EGL: Local Branch: 
09-02 12:07:48.316  7185  7185 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 12:07:48.316  7185  7185 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 12:07:48.316  7185  7185 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 12:07:48.376  7185  7305 W cr.media: Requires BLUETOOTH permission
,09-02 12:07:48.386  7185  7185 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 12:07:48.396  7185  7185 I NSApplication: Starting up...
,09-02 12:07:48.396  1017  4395 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-02 12:07:48.406  1017  1483 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-02 12:07:48.416  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-02 12:07:48.416  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:48.416  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:48.416  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:48.416  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:48.426  1017  1029 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7310 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-02 12:07:48.436  7310  7310 E Zygote  : MountEmulatedStorage()
09-02 12:07:48.436  7310  7310 I libpersona: KNOX_SDCARD checking this for 10117
09-02 12:07:48.436  7310  7310 E Zygote  : v2
09-02 12:07:48.436  7310  7310 I libpersona: KNOX_SDCARD not a persona
09-02 12:07:48.436  7310  7310 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:48.436  1017  1029 I ActivityManager: Killing 6984:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-02 12:07:48.436  7310  7310 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:07:48.436  7310  7310 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 12:07:48.456  7272  7272 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-02 12:07:48.456  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-02 12:07:48.466  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-02 12:07:48.466   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7272
09-02 12:07:48.466   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-02 12:07:48.466  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-02 12:07:48.466  7272  7272 I wpa_supplicant: ssSupport state is = 1
,09-02 12:07:48.466  7272  7272 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-02 12:07:48.466  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-02 12:07:48.476  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-02 12:07:48.476   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7272
09-02 12:07:48.476  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 12:07:48.476   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-02 12:07:48.476  7272  7272 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-02 12:07:48.476  7272  7272 I wpa_supplicant: ssSupport state is = 1
,09-02 12:07:48.476  7272  7272 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 12:07:48.476  7272  7272 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 12:07:48.476  7272  7272 E wpa_supplicant: SIM READ ERROR
,09-02 12:07:48.476  7272  7272 I wpa_supplicant: wpa_default_ap_write_once
09-02 12:07:48.486  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 12:07:48.476  7272  7272 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 12:07:48.476  7272  7272 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 12:07:48.476  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 12:07:48.476  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
09-02 12:07:48.486  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,09-02 12:07:48.486  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-02 12:07:48.486  7310  7310 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 12:07:48.486  7310  7310 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:48.506  7310  7310 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 12:07:48.526  7272  7272 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-02 12:07:48.526  7272  7272 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-02 12:07:48.596  7272  7272 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-02 12:07:48.596  7272  7272 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-02 12:07:48.596  7272  7272 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 12:07:48.606  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-02 12:07:48.606  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 12:07:48.606  7272  7272 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-02 12:07:48.606  7272  7272 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-02 12:07:48.606  7272  7272 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 12:07:48.606  7272  7272 E wpa_supplicant: SIM READ ERROR
09-02 12:07:48.606  7272  7272 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 12:07:48.636  7272  7272 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-02 12:07:48.646  7272  7272 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-02 12:07:48.656  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,09-02 12:07:48.656  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:07:48.656  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:07:48.656  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:48.656  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:48.656  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:48.656  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:48.656  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:48.656  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-02 12:07:48.656  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:48.656  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 12:07:48.656  1173  1173 D HotspotTile: onReceive : 3, 0
,09-02 12:07:48.666  3855  3855 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:48.666  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:48.666  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:48.666  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:48.666  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:48.666  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:48.666  1017  1126 E WifiConfigStore: Not a HS20
09-02 12:07:48.666  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:48.676  1017  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-02 12:07:48.676  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:48.676  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-02 12:07:48.676  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-02 12:07:48.676  7272  7272 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-02 12:07:48.676  7272  7272 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 12:07:48.676  7272  7272 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 12:07:48.676  7272  7272 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 12:07:48.676  7272  7272 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-02 12:07:48.676  7272  7272 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-02 12:07:48.676  7272  7272 I wpa_supplicant: First Scan Start
09-02 12:07:48.676  7272  7272 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 12:07:48.676  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,09-02 12:07:48.686  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:07:48.686  1017  1126 I WifiNative-HAL: startHal
09-02 12:07:48.686  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9d54588c
09-02 12:07:48.686  1017  1126 I WifiNative-HAL: Could not start hal
,09-02 12:07:48.686  6959  6959 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:07:48.686  1017  1126 E WifiNative-wlan0: do suspend true
,09-02 12:07:48.686  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-02 12:07:48.686  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,09-02 12:07:48.686  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
09-02 12:07:48.686  1017  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:07:48.686  1017  1149 I WifiNative-HAL: startHal
09-02 12:07:48.686  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 12:07:48.686  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 12:07:48.686  1017  1126 E WifiNative-wlan0: invaild command id : 215
09-02 12:07:48.686  1017  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9eb019bc
,09-02 12:07:48.686  1017  1149 I WifiNative-HAL: Could not start hal
09-02 12:07:48.686  1017  1149 E WifiScanningService: could not start HAL
,09-02 12:07:48.686  1017  1017 D RttService: SCAN_AVAILABLE : 3
09-02 12:07:48.686   278  1010 D CommandListener: Setting iface cfg
09-02 12:07:48.686   278  1010 D CommandListener: Trying to bring up p2p0
09-02 12:07:48.696  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-02 12:07:48.696  1017  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:07:48.696  1017  1125 D WifiP2pService: P2pEnablingState
,09-02 12:07:48.696  7272  7272 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-02 12:07:48.696  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
09-02 12:07:48.696  7272  7272 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-02 12:07:48.696  1017  1125 D WifiP2pService: P2p socket connection successful
,09-02 12:07:48.696  7272  7272 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-02 12:07:48.696  1017  1125 D WifiP2pService: P2pEnabledState
09-02 12:07:48.696  1017  1126 E WifiStateMachine: Failed to set frequency band 0
,09-02 12:07:48.696  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 12:07:48.696  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:07:48.696  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-02 12:07:48.696  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-02 12:07:48.696  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:07:48.696  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-02 12:07:48.696  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 12:07:48.696  1017  1047 D WifiDisplayController: disconnect
,09-02 12:07:48.696  1017  1047 D WifiDisplayController: updateConnection
09-02 12:07:48.696  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 12:07:48.696  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 12:07:48.696  1017  1126 D SecContentProvider2: mCursor = null
09-02 12:07:48.696  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 12:07:48.706  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-02 12:07:48.706  1017  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 12:07:48.706  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,09-02 12:07:48.706  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-02 12:07:48.706  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-02 12:07:48.706  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 12:07:48.706  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-02 12:07:48.706  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 12:07:48.706  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 12:07:48.706  1017  1125 D WifiP2pService: DeviceAddress: 0a:76:28
,09-02 12:07:48.706  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  secondary type: null
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  wps: 0
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  grpcapab: 0
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  devcapab: 0
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  status: 3
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  wfdInfo: null
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  groupownerAddress: null
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  GOdeviceName: null
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  interfaceAddress: 
09-02 12:07:48.706  1017  1047 D WifiDisplayController:  SConnectInfo : null
,09-02 12:07:48.736  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-02 12:07:48.736  1017  1125 D WifiP2pService: InactiveState
09-02 12:07:48.736  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
09-02 12:07:48.736  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 12:07:48.736  7272  7272 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-02 12:07:48.736  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-02 12:07:48.736  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 12:07:48.866  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 12:07:48.866  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 12:07:48.866  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-02 12:07:48.866  1017  1030 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-02 12:07:48.866  1017  1030 I ActivityManager: Killing 6999:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,09-02 12:07:48.876  1017  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 12:07:48.876  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:07:48.876  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:48.876  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:48.876  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:07:48.886  1593  1593 I Hs20UtilService: Starting #12
,09-02 12:07:48.886  1593  1636 I Hs20UtilService: Message received 5011
,09-02 12:07:48.886  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 12:07:48.886  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 12:07:48.886  6582  6582 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 12:07:48.886  6582  6582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 12:07:48.896  1017  1383 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 12:07:48.896  1017  1383 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:07:48.906  1017  1383 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:48.906  1017  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:48.906  1017  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:07:48.906  1593  1593 I Hs20UtilService: Starting #13
,09-02 12:07:48.906  1593  1636 I Hs20UtilService: Message received 5011
,09-02 12:07:48.906  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 12:07:48.906  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 12:07:48.906  1017  1126 E WifiNative-wlan0: invaild command id : 215
,09-02 12:07:48.906  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 12:07:48.906  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 12:07:48.906  6582  6582 D SecurityLogAgent: StateMachine : Current State = 1
09-02 12:07:48.906  6582  6582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 12:07:48.916  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 12:07:48.916  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:07:48.916  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 12:07:48.916  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 12:07:48.916  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:07:48.916  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 12:07:48.916  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:07:48.916  1017  1471 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-02 12:07:48.926  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:48.926  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:48.926  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:48.926  1017  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:48.936  7337  7337 E Zygote  : MountEmulatedStorage()
,09-02 12:07:48.936  7337  7337 I libpersona: KNOX_SDCARD checking this for 10064
09-02 12:07:48.936  7337  7337 E Zygote  : v2
,09-02 12:07:48.936  7337  7337 I libpersona: KNOX_SDCARD not a persona
09-02 12:07:48.936  7337  7337 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:48.936  1017  1471 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7337 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:07:48.936  7337  7337 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-02 12:07:48.936  7337  7337 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:48.956  7337  7337 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 12:07:48.956  7337  7337 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:48.976  7337  7337 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 12:07:48.986  7337  7337 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 12:07:48.986  7337  7337 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-02 12:07:49.016  7337  7337 D FileShare-Client: Outbound.stopDelayTimer - ,
09-02 12:07:49.016  1017  1480 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-02 12:07:49.016  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:49.016  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:49.016  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:49.016  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:49.046  7353  7353 E Zygote  : MountEmulatedStorage(),
09-02 12:07:49.046  7353  7353 E Zygote  : v2
09-02 12:07:49.046  7353  7353 I libpersona: KNOX_SDCARD checking this for 10065,
09-02 12:07:49.046  7353  7353 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:49.046  1017  1480 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7353 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 12:07:49.046  7353  7353 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 12:07:49.056  1017  1480 I ActivityManager: Killing 6870:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21,
,09-02 12:07:49.056  7353  7353 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:07:49.056  7353  7353 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:49.076  7353  7353 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:49.076  7353  7353 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:49.096  7353  7353 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 12:07:49.106  1017  1481 I ActivityManager: Killing 7015:com.android.bluetooth/1002 (adj 15): empty #21
,09-02 12:07:49.156   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 12:07:49.406  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-02 12:07:49.406  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
,09-02 12:07:49.406  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-02 12:07:49.406  1017  1029 D BatteryService: stay LED for fully charged
09-02 12:07:49.406  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 12:07:49.406  1017  1017 I MotionRecognitionService: Plugged
,09-02 12:07:49.406  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 12:07:49.416  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-02 12:07:49.416  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 12:07:49.416  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-02 12:07:49.416  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-02 12:07:49.446  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-02 12:07:49.446  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-02 12:07:49.446  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:49.446  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:49.446  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:49.936  7272  7272 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
,09-02 12:07:49.936  7272  7272 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 12:07:49.946  1017  7329 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
09-02 12:07:49.946  7272  7272 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-02 12:07:49.946  7272  7272 I wpa_supplicant: Trying to associate with  'G700',
09-02 12:07:49.946  7272  7272 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,09-02 12:07:49.946  7272  7272 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-02 12:07:49.966  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:07:49.966  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:07:50.066  7272  7272 E wpa_supplicant: Cmd 35605 not handled,
09-02 12:07:50.066  7272  7272 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
09-02 12:07:50.066  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.066  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-02 12:07:50.066  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-02 12:07:50.066  7272  7272 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-02 12:07:50.066  7272  7272 I wpa_supplicant: Associated with F4.99.3E
09-02 12:07:50.066  7272  7272 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 12:07:50.066  7272  7272 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-02 12:07:50.066  7272  7272 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-02 12:07:50.066  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.066  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.066  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:07:50.066  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 12:07:50.066  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.066  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:07:50.066  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-02 12:07:50.066  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 12:07:50.066  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-02 12:07:50.076  7272  7272 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-02 12:07:50.076  7272  7272 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-02 12:07:50.076  1017  1130 E Tethering: No numeric data
,09-02 12:07:50.076  7272  7272 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-02 12:07:50.076  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 12:07:50.076  1017  1130 D Tethering: clearTetheredNotification()
09-02 12:07:50.076  7272  7272 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-02 12:07:50.076  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:50.076  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-02 12:07:50.076  7272  7272 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:07:50.076  7272  7272 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-02 12:07:50.076  7272  7272 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-02 12:07:50.076  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 12:07:50.076  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 12:07:50.086  7272  7272 I wpa_supplicant: Blacklist: Clear (temp) ,
09-02 12:07:50.086  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-02 12:07:50.086  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 12:07:50.086  1173  1173 D HotspotTile: updateTetherState():false, false
09-02 12:07:50.086  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
09-02 12:07:50.086  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-02 12:07:50.086  7272  7272 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-02 12:07:50.086  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:07:50.086  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:07:50.086  1017  1123 V NetworkStats: performPollLocked() took 11ms
09-02 12:07:50.086  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:50.096  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:50.096  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:50.096  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-02 12:07:50.106  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,09-02 12:07:50.106  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:50.106  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:07:50.106  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.106  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.106  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.106  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:50.106  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-02 12:07:50.106  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-02 12:07:50.106  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:07:50.106  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-02 12:07:50.116  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-02 12:07:50.116  1017  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 12:07:50.116  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:50.116  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 12:07:50.116  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:50.116  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 12:07:50.116  1593  1593 I Hs20UtilService: Starting #14
,09-02 12:07:50.116  1593  1636 I Hs20UtilService: Message received 5007
,09-02 12:07:50.126  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 12:07:50.126  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:07:50.126  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:07:50.126  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 12:07:50.126  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
09-02 12:07:50.126  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:07:50.126  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 12:07:50.126  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:07:50.146   278  1010 D CommandListener: Setting iface cfg,
,09-02 12:07:50.146  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,09-02 12:07:50.156  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:07:50.156  1017  1126 D SecContentProvider2: mCursor = null
09-02 12:07:50.156   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 12:07:50.156  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:07:50.156  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:07:50.166  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-02 12:07:50.166  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:07:50.166  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:50.166  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.166  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.166  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:50.176  1017  1126 E WifiNative-wlan0: do suspend false
,09-02 12:07:50.176  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-02 12:07:50.176  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 12:07:50.176  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 12:07:50.176  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:07:50.396  7372  7372 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-02 12:07:50.396  7372  7372 I dhcpcd  : version 5.5.6 starting,
,09-02 12:07:50.406  7372  7372 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-02 12:07:50.446  1017  1383 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-02 12:07:50.446  1017  1383 D WifiService: setWifiEnabled: false pid=6754, uid=10171
09-02 12:07:50.446  1017  1383 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 12:07:50.446  1017  1383 D SecContentProvider2: mCursor = null
09-02 12:07:50.446  1017  1383 D SettingsProvider: name = wifi_on
,09-02 12:07:50.456  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-02 12:07:50.466  7372  7372 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-02 12:07:50.466  7372  7372 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
09-02 12:07:50.466  7372  7372 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-02 12:07:50.476  7372  7372 I dhcpcd  : bssid match,
,09-02 12:07:50.476  7372  7372 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-02 12:07:50.486  1017  1126 E WifiNative-wlan0: do suspend true,
,09-02 12:07:50.506  1017  1125 D WifiP2pService: InactiveState{ what=143375 },
09-02 12:07:50.506  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 12:07:50.506  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-02 12:07:50.506  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:07:50.506  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.506  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.516  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 12:07:50.506  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.516  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-02 12:07:50.506  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.506   278  1010 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:07:50.516  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:07:50.516  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:07:50.516  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-02 12:07:50.516   278  1010 E Netd    : no such netId 503
,09-02 12:07:50.516  1017  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)',
09-02 12:07:50.516  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-02 12:07:50.516  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:50.516  1017  1128 V NetworkStats: updateIfacesLocked()
09-02 12:07:50.516  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 12:07:50.516  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-02 12:07:50.516  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 12:07:50.526  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:50.526  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:07:50.526  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.526  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.526  1017  1128 V NetworkStats: performPollLocked() took 6ms
09-02 12:07:50.526  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.526  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.526  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:50.526  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 12:07:50.526  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
,09-02 12:07:50.526  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
09-02 12:07:50.526  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-02 12:07:50.526  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 12:07:50.526  1017  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:07:50.526  1017  1017 D RttService: SCAN_AVAILABLE : 1
,09-02 12:07:50.526  1017  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:07:50.526  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-02 12:07:50.526  1017  7369 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:07:50.526  1017  7369 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-02 12:07:50.526  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-02 12:07:50.526  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
09-02 12:07:50.526  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-02 12:07:50.526  1017  1128 E ConnectivityService: updateNetworkInfo()
,09-02 12:07:50.526  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:07:50.526  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:50.526  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-02 12:07:50.526  1017  1212 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 12:07:50.526  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:50.526  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-02 12:07:50.526  1017  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:50.526  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 12:07:50.526  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
09-02 12:07:50.526  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-02 12:07:50.526  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 12:07:50.536  1017  1128 E ConnectivityService: updateNetworkInfo()
,09-02 12:07:50.536  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-02 12:07:50.536  1017  1125 D WifiP2pService: P2pDisablingState
09-02 12:07:50.536  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-02 12:07:50.536  1017  1125 D WifiP2pService: p2p socket connection lost
09-02 12:07:50.536  1017  1125 D WifiP2pService: P2pDisabledState
,09-02 12:07:50.536  1593  1593 I Hs20UtilService: Starting #15
09-02 12:07:50.536  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-02 12:07:50.536  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-02 12:07:50.536  1017  1126 E WifiNative-wlan0: do suspend true
09-02 12:07:50.536  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 12:07:50.536  1017  1047 D WifiDisplayController: disconnect
09-02 12:07:50.536  1017  1047 D WifiDisplayController: updateConnection
,09-02 12:07:50.536  1593  1636 I Hs20UtilService: Message received 5007
09-02 12:07:50.536  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 12:07:50.536  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 12:07:50.536  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 12:07:50.536  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-02 12:07:50.536  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 12:07:50.536  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 12:07:50.536  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 12:07:50.536  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-02 12:07:50.546  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-02 12:07:50.536  1017  4395 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 12:07:50.536  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-02 12:07:50.546  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 12:07:50.546  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 12:07:50.546  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:07:50.546  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 12:07:50.546  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:07:50.546  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 12:07:50.546  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:07:50.546  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 12:07:50.546  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 12:07:50.546  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:07:50.546  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 12:07:50.556  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:07:50.556  7337  7337 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
09-02 12:07:50.556  7337  7337 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-02 12:07:50.556  7337  7337 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 12:07:50.556  7353  7353 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 12:07:50.566  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-02 12:07:50.566  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,09-02 12:07:50.566  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:07:50.566  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:07:50.566  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:50.576  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.576   278  1010 D CommandListener: Clearing all IP addresses on wlan0
09-02 12:07:50.576  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.576  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:50.576  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 12:07:50.576  7372  7372 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,09-02 12:07:50.576  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:50.576  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 12:07:50.576  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.576  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.576  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:50.576  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.586  7272  7272 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-02 12:07:50.586  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 12:07:50.586  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:07:50.586  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:50.586  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:50.586  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 12:07:50.586  1593  1593 I Hs20UtilService: Starting #16
,09-02 12:07:50.586  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 12:07:50.586  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:07:50.596  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:07:50.596  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 12:07:50.596  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.596  1593  1636 I Hs20UtilService: Message received 5007
09-02 12:07:50.596  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.596  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.596  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:50.596  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 12:07:50.596  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-02 12:07:50.596  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:50.596  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 12:07:50.596  1173  1173 D HotspotTile: onReceive : 0, 0
,09-02 12:07:50.596  3855  3855 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:50.596  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 12:07:50.596  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:50.596  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:50.596  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:50.596  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:50.596  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:50.596  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:07:50.606  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 12:07:50.606  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:07:50.606  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 12:07:50.606  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 12:07:50.606  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:07:50.606  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 12:07:50.606  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:07:50.626  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 12:07:50.626  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:07:50.626  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:50.626  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:50.626  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:07:50.626  1593  1593 I Hs20UtilService: Starting #17
09-02 12:07:50.626  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 12:07:50.626  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 12:07:50.626  6582  6582 D SecurityLogAgent: StateMachine : Current State = 1
09-02 12:07:50.626  6582  6582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 12:07:50.626  7372  7372 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,09-02 12:07:50.636  1593  1636 I Hs20UtilService: Message received 5011
,09-02 12:07:50.746  7272  7272 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 12:07:50.916  7272  7272 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,09-02 12:07:50.916  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,09-02 12:07:50.916  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 12:07:50.916  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-02 12:07:50.956  7272  7272 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-02 12:07:50.956  7272  7272 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-02 12:07:50.956  7272  7272 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-02 12:07:50.956  7272  7272 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-02 12:07:50.956  7272  7272 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-02 12:07:50.956  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.956  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.956  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-02 12:07:50.956  1017  1130 D Tethering: InitialState.processMessage what=4
09-02 12:07:50.966  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.966  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.966  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:07:50.966  1017  1130 E Tethering: No numeric data
,09-02 12:07:50.966  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 12:07:50.966  1017  1130 D Tethering: clearTetheredNotification()
,09-02 12:07:50.966  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:07:50.966  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:50.966  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.966  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:50.966  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-02 12:07:50.966  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:07:50.966  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 12:07:50.966  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 12:07:50.966  1173  1173 D HotspotTile: updateTetherState():false, false
,09-02 12:07:50.976  1017  1123 V NetworkStats: performPollLocked() took 6ms
,09-02 12:07:50.976  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:50.976  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:50.976  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:07:51.056  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 12:07:51.056  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:51.056  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
,09-02 12:07:51.096   295   295 E SMD     : DCD OFF,
,09-02 12:07:51.156   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 12:07:51.166  7272  7272 I wpa_supplicant: Blacklist: Clear (all) ,
,09-02 12:07:51.246  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:07:51.246  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:07:51.246  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-02 12:07:51.246  7272  7272 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-02 12:07:51.356  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
,09-02 12:07:51.356  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21],
,09-02 12:07:51.356  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:07:51.356  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 12:07:51.356  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:51.356  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:07:51.356  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:51.356  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:07:51.366  6959  6959 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:07:51.366  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 12:07:51.366  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-02 12:07:51.366  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 12:07:51.366  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:51.366  1173  1173 D HotspotTile: onReceive : 1, 0
,09-02 12:07:51.366  1962  2159 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:07:51.366  3855  3855 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:07:51.376  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:51.376  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:51.376  1017  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-02 12:07:51.376  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:51.376  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 12:07:51.376  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:51.376  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 12:07:51.376  1593  1593 I Hs20UtilService: Starting #18
09-02 12:07:51.376  1593  1636 I Hs20UtilService: Message received 5011
,09-02 12:07:51.386  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 12:07:51.386  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 12:07:51.386  6582  6582 D SecurityLogAgent: StateMachine : Current State = 1
09-02 12:07:51.386  6582  6582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 12:07:51.466  1017  1030 I ActivityManager: Killing 6893:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-02 12:07:52.086   278  1004 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-02 12:07:52.086  1017  1044 D Tethering: interfaceRemoved wlan0
,09-02 12:07:52.086  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-02 12:07:52.156   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-02 12:07:52.206  1017  1044 D Tethering: interfaceRemoved p2p0
,09-02 12:07:52.206  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-02 12:07:53.026  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-02 12:07:53.116  1017  1500 I ActivityManager: Killing 7033:com.sec.pcw.device/1000 (adj 15): empty #21
,09-02 12:07:53.456  6754  6808 D BluetoothAdapter: enable()
,09-02 12:07:53.466  1017  4395 W ActivityManager: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-02 12:07:53.466  1017  4395 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-02 12:07:53.466  1017  4395 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-02 12:07:53.466  1017  4395 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 12:07:53.466  1017  4395 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-02 12:07:53.466  1017  4395 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-02 12:07:53.466  1017  4395 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-02 12:07:53.466  1017  4395 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 12:07:53.466  1017  4395 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 12:07:53.466  1017  4395 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 12:07:53.466  1017  4395 D SettingsProvider: name = bluetooth_on
,09-02 12:07:53.476  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 12:07:53.476  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 12:07:53.476  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-02 12:07:53.476  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-02 12:07:53.476  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:53.476  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:53.476  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:53.476  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:53.496  1017  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7402 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-02 12:07:53.496  7402  7402 E Zygote  : MountEmulatedStorage(),
,09-02 12:07:53.496  7402  7402 E Zygote  : v2
,09-02 12:07:53.496  7402  7402 I libpersona: KNOX_SDCARD checking this for 1002,
09-02 12:07:53.506  7402  7402 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:53.506  7402  7402 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 12:07:53.506  7402  7402 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 12:07:53.506  7402  7402 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:53.536  7402  7402 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:53.536  7402  7402 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:53.556  7402  7402 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 12:07:53.556  7402  7402 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 12:07:53.576  7402  7402 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-02 12:07:53.606  7402  7402 D BtSettings.ProfileConfig: Adding GattService
,09-02 12:07:53.606  7402  7402 D BtSettings.ProfileConfig: Adding HeadsetService
,09-02 12:07:53.606  7402  7402 D BtSettings.ProfileConfig: Adding A2dpService
09-02 12:07:53.606  7402  7402 D BtSettings.ProfileConfig: Adding HidService
09-02 12:07:53.606  7402  7402 D BtSettings.ProfileConfig: Adding HealthService
,09-02 12:07:53.606  7402  7402 D BtSettings.ProfileConfig: Adding PanService
09-02 12:07:53.616  7402  7402 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-02 12:07:53.616  7402  7402 D BtSettings.ProfileConfig: Adding SapService
09-02 12:07:53.616  7402  7402 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-02 12:07:53.616  7402  7402 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-02 12:07:53.616  7402  7402 D BtSettings.ProfileConfig: Adding SapClientService
09-02 12:07:53.616  7402  7402 D BtSettings.ProfileConfig: Adding HidDevService
09-02 12:07:53.616  7402  7402 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******,
,09-02 12:07:53.616  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-02 12:07:53.616  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.616  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.616  1017  1029 D SettingsProvider: selectionArgs: false
,09-02 12:07:53.616  1017  1029 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.616  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:53.616  1017  1029 D SettingsProvider: ret = -1
,09-02 12:07:53.616  1017  4396 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-02 12:07:53.616  1017  4396 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.616  1017  4396 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.616  1017  4396 D SettingsProvider: selectionArgs: false
09-02 12:07:53.616  1017  4396 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.616  1017  4396 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:53.616  1017  4396 D SettingsProvider: ret = -1
,09-02 12:07:53.616  1017  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-02 12:07:53.616  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.616  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.616  1017  1481 D SettingsProvider: selectionArgs: false
09-02 12:07:53.616  1017  1481 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.616  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:53.616  1017  1481 D SettingsProvider: ret = -1
,09-02 12:07:53.616  1017  1210 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-02 12:07:53.616  1017  1210 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 12:07:53.616  1017  1210 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.616  1017  1210 D SettingsProvider: selectionArgs: false
09-02 12:07:53.616  1017  1210 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.616  1017  1210 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:53.616  1017  1210 D SettingsProvider: ret = -1
,09-02 12:07:53.616  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-02 12:07:53.616  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 12:07:53.616  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.626  1017  1030 D SettingsProvider: selectionArgs: false
,09-02 12:07:53.626  1017  1030 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.626  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:53.626  1017  1030 D SettingsProvider: ret = -1
,09-02 12:07:53.626  1017  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-02 12:07:53.626  1017  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.626  1017  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.626  1017  1476 D SettingsProvider: selectionArgs: false
09-02 12:07:53.626  1017  1476 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.626  1017  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:53.626  1017  1476 D SettingsProvider: ret = -1
,09-02 12:07:53.626  1017  1383 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-02 12:07:53.626  1017  1383 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 12:07:53.626  1017  1383 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.626  1017  1383 D SettingsProvider: selectionArgs: false
09-02 12:07:53.626  1017  1383 D SettingsProvider: selectionArgs: 1002
,09-02 12:07:53.626  1017  1383 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:53.626  1017  1383 D SettingsProvider: ret = -1
,09-02 12:07:53.626  1017  1480 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-02 12:07:53.626  1017  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.626  1017  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.626  1017  1480 D SettingsProvider: selectionArgs: false
,09-02 12:07:53.626  1017  1480 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.626  1017  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:53.626  1017  1480 D SettingsProvider: ret = -1
,09-02 12:07:53.626  1017  1212 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 12:07:53.626  1017  1212 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.626  1017  1212 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.626  1017  1212 D SettingsProvider: selectionArgs: false
,09-02 12:07:53.626  1017  1212 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.626  1017  1212 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:53.626  1017  1212 D SettingsProvider: ret = -1
,09-02 12:07:53.636  1017  4394 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService,
09-02 12:07:53.636  1017  4394 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.636  1017  4394 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.636  1017  4394 D SettingsProvider: selectionArgs: false
09-02 12:07:53.636  1017  4394 D SettingsProvider: selectionArgs: 1002
,09-02 12:07:53.636  1017  4394 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:53.636  1017  4394 D SettingsProvider: ret = -1
09-02 12:07:53.636  1017  4395 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-02 12:07:53.636  1017  4395 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.636  1017  4395 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.636  1017  4395 D SettingsProvider: selectionArgs: false
09-02 12:07:53.636  1017  4395 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.636  1017  4395 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:53.636  1017  4395 D SettingsProvider: ret = -1
09-02 12:07:53.636  1017  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-02 12:07:53.636  1017  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.636  1017  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.636  1017  1471 D SettingsProvider: selectionArgs: false
09-02 12:07:53.636  1017  1471 D SettingsProvider: selectionArgs: 1002
09-02 12:07:53.636  1017  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:53.636  1017  1471 D SettingsProvider: ret = -1
,09-02 12:07:53.646  7402  7402 D BluetoothAdapterState: make
,09-02 12:07:53.646  7402  7402 I bluedroid: init
,09-02 12:07:53.656  7402  7417 I BluetoothAdapterState: Entering OffState
,09-02 12:07:53.656  7402  7402 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,09-02 12:07:53.656  7402  7402 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf,
09-02 12:07:53.656  7402  7402 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-02 12:07:53.656  7402  7402 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 12:07:53.656  7402  7402 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-02 12:07:53.656  7402  7402 I bluedroid: get_profile_interface socket
09-02 12:07:53.656  7402  7402 I bluedroid: get_profile_interface map_client
09-02 12:07:53.656  7402  7420 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-02 12:07:53.656  7402  7402 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-02 12:07:53.666  7402  7420 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-02 12:07:53.666  7402  7420 E BluetoothServiceJni: populateRssiValuesNative
09-02 12:07:53.666  7402  7420 I bluedroid: getModelRssiValues
,09-02 12:07:53.666  7402  7420 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 12:07:53.666  7402  7420 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 12:07:53.666  1017  1017 D SettingsProvider: name = bluetooth_name
,09-02 12:07:53.666  7402  7420 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-02 12:07:53.666  7402  7402 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,09-02 12:07:53.666  1017  4394 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 12:07:53.666  1017  4394 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 12:07:53.666  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:53.666  1017  4394 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:53.666  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:53.676  7402  7413 I bluedroid: config_hci_snoop_log
,09-02 12:07:53.676  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-02 12:07:53.676  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,09-02 12:07:53.676  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-02 12:07:53.676  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-02 12:07:53.676  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 12:07:53.686  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 12:07:53.686  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 12:07:53.686  7402  7402 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-02 12:07:53.686  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-02 12:07:53.686  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 12:07:53.686  7402  7417 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-02 12:07:53.686  7402  7417 D BluetoothAdapterProperties: Setting state to 11
09-02 12:07:53.686  7402  7417 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-02 12:07:53.686  7402  7417 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 12:07:53.686  7402  7417 D BluetoothAdapterService: updateAdapterState state is 11
,09-02 12:07:53.696  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:53.696  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,09-02 12:07:53.696  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 12:07:53.706  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:53.706  1173  1173 D BluetoothTile:  getBluetoothState : 11
,09-02 12:07:53.706  1915  1915 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 12:07:53.706  7402  7417 D BluetoothAdapterService: Autoconnection is available 
09-02 12:07:53.706  7402  7417 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-02 12:07:53.706  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
09-02 12:07:53.706  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 12:07:53.706  7402  7417 D BluetoothSecureManager: getInstant: null
09-02 12:07:53.706  7402  7417 D BluetoothSecureManager: calling getMethod for getService
,09-02 12:07:53.706  7402  7417 D BluetoothSecureManager: calling getService
,09-02 12:07:53.706  7402  7417 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@316e268f
09-02 12:07:53.706  1017  1212 D BluetoothSecureManagerService: isSecureModeEnabled
,09-02 12:07:53.706  1017  1212 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-02 12:07:53.706  7402  7417 D BtConfig.SecureMode: isSecureModeOn:false
09-02 12:07:53.706  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-02 12:07:53.706  7402  7417 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-02 12:07:53.706  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-02 12:07:53.706  1017  2016 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 12:07:53.706  1017  1210 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 12:07:53.706  7402  7417 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-02 12:07:53.706  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 12:07:53.706  7402  7417 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-02 12:07:53.706  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 12:07:53.716  3855  3855 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:53.716  7402  7417 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-02 12:07:53.716  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 12:07:53.716  7402  7417 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-02 12:07:53.716  1017  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:53.716  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 12:07:53.716  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 12:07:53.716  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 12:07:53.716  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.716  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:53.716  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:53.716  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:53.716  7402  7417 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-02 12:07:53.716  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 12:07:53.716  7402  7417 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-02 12:07:53.716  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 12:07:53.716  7402  7417 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-02 12:07:53.716  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 12:07:53.726  7402  7417 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:53.726  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:53.726  7402  7417 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:53.726  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 12:07:53.726  7402  7417 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-02 12:07:53.726  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 12:07:53.726  7402  7417 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-02 12:07:53.726  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:07:53.726  3855  3855 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 12:07:53.726  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:53.726  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-02 12:07:53.726  1017  1383 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-02 12:07:53.726  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:53.736  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:53.736  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:53.736  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:53.736  7402  7417 D BluetoothBondStateMachine: make
,09-02 12:07:53.736  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-02 12:07:53.736  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 12:07:53.736  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 12:07:53.746  7402  7423 I BluetoothBondStateMachine: StableState(): Entering Off State,
,09-02 12:07:53.746  7424  7424 E Zygote  : MountEmulatedStorage()
,09-02 12:07:53.746  7424  7424 E Zygote  : v2
09-02 12:07:53.746  7424  7424 I libpersona: KNOX_SDCARD checking this for 10055
09-02 12:07:53.746  7424  7424 I libpersona: KNOX_SDCARD not a persona,
,09-02 12:07:53.746  1017  1383 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7424 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-02 12:07:53.746  1017  1210 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:53.746  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 12:07:53.746  7424  7424 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-02 12:07:53.746  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.746  1017  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:53.746  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 12:07:53.756  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 12:07:53.756  1017  4395 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:53.756  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 12:07:53.756  1017  4395 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-02 12:07:53.756  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 12:07:53.756  7402  7402 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:07:53.756  7402  7402 D BtGatt.GattService: Received start request. Starting profile...
09-02 12:07:53.756  7402  7402 D BtGatt.GattService: start()
09-02 12:07:53.756  7402  7402 D BtGatt.GattService: start()
09-02 12:07:53.756  7402  7402 I bluedroid: get_profile_interface gatt
09-02 12:07:53.756  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
09-02 12:07:53.756  7402  7402 D BtGatt.AdvertiseManager: advertise manager created
,09-02 12:07:53.756  7424  7424 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:53.756  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.756  1017  4395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:53.756  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 12:07:53.756  7424  7424 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:07:53.766  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-02 12:07:53.766  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 12:07:53.766  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-02 12:07:53.766  1017  1212 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:53.766  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 12:07:53.766  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.766  1017  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:53.766  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:53.766  7402  7402 D BtGatt.GattService: mStartError = false
09-02 12:07:53.766  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:53.766  7402  7402 D HeadsetService: Received start request. Starting profile...
09-02 12:07:53.766  7402  7402 D HeadsetService: start()
,09-02 12:07:53.776  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-02 12:07:53.776  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 12:07:53.776  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-02 12:07:53.776  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:53.776  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-02 12:07:53.776  7402  7402 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 12:07:53.776  7402  7402 D HeadsetStateMachine: make
09-02 12:07:53.776  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.776  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:53.776  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:53.776  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-02 12:07:53.776  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 12:07:53.776  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 12:07:53.776  7402  7402 E HeadsetStateMachine: # of Max HF connection is 2
09-02 12:07:53.776  1017  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:53.776  1017  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-02 12:07:53.776  1017  1500 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.776  1017  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:53.776  1017  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:53.776  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-02 12:07:53.776  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 12:07:53.776  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-02 12:07:53.776  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:53.776  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-02 12:07:53.776  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.776  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:53.776  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:53.786  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 12:07:53.786  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 12:07:53.786  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 12:07:53.786  1017  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:53.786  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 12:07:53.786  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.786  1017  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:53.786  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:53.786  1017  1212 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-02 12:07:53.786  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-02 12:07:53.786  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.786  1017  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:53.786  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 12:07:53.786  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-02 12:07:53.786  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 12:07:53.786  7402  7417 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 12:07:53.786  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:53.786  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 12:07:53.796  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.796  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:53.796  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:53.796  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:53.796  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 12:07:53.796  1017  4396 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-02 12:07:53.796  7402  7417 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:53.796  1017  4396 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-02 12:07:53.796  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:53.796  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:53.796  7402  7417 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:53.796  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 12:07:53.796  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 12:07:53.796  7402  7417 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 12:07:53.796  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 12:07:53.796  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 12:07:53.796  7402  7417 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 12:07:53.796  7402  7417 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 12:07:53.796  1017  4396 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:53.796  1017  4396 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:53.796  1017  4396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-02 12:07:53.796  7402  7402 I bluedroid: get_profile_interface handsfree
,09-02 12:07:53.816  7402  7402 I DualScoManager: Instantiating Dual Sco Manager,
09-02 12:07:53.816  7402  7402 I DualScoManager: Set HeadsetServiceHelper
09-02 12:07:53.816  7402  7402 D BluetoothAtMessage: createCMTIContentObservers
,09-02 12:07:53.816  1017  1481 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-02 12:07:53.816  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:53.816  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:53.816  1017  1481 D SettingsProvider: selectionArgs: false
,09-02 12:07:53.816  1017  1481 D SettingsProvider: selectionArgs: 1002,
09-02 12:07:53.816  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:07:53.816  1017  1481 D SettingsProvider: ret = -1
,09-02 12:07:53.816  7402  7434 D HeadsetStateMachine: Enter Disconnected: -2
09-02 12:07:53.816  7402  7402 D HeadsetService: mStartError = false
09-02 12:07:53.816  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:53.816  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false,
,09-02 12:07:53.826  7402  7402 D A2dpService: Received start request. Starting profile...
09-02 12:07:53.826  7402  7402 D A2dpService: start()
,09-02 12:07:53.826  7424  7424 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:53.826  7424  7424 D ActivityThread: Added TimaKeyStore provider
09-02 12:07:53.826  7402  7402 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 12:07:53.826  7402  7402 I bluedroid: get_profile_interface avrcp
,09-02 12:07:53.826  7402  7434 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-02 12:07:53.826  7402  7434 D HeadsetStateMachine: map size, before remove : 0
09-02 12:07:53.826  7402  7434 D HeadsetStateMachine: map size, after remove: 0
,09-02 12:07:53.836  7402  7402 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 12:07:53.836  7402  7402 D Avrcp   : Initialize Media Controller
09-02 12:07:53.836  7402  7402 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-02 12:07:53.836  7402  7402 E Avrcp   : getActiveSessions
09-02 12:07:53.836  7402  7402 D Avrcp   : pick active media Controller
09-02 12:07:53.836  7402  7402 D Avrcp   : Get the active Media Controller 
,09-02 12:07:53.846  7402  7402 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-02 12:07:53.846  7402  7445 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-02 12:07:53.856  7402  7402 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:07:53.856  7402  7402 D A2dpStateMachine: make
,09-02 12:07:53.856  7402  7402 I bluedroid: get_profile_interface a2dp
,09-02 12:07:53.856  7402  7447 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 12:07:53.856  7402  7402 E bt-btif : warning : media task started media_task_refcnt 1 
,09-02 12:07:53.856  7424  7424 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-02 12:07:53.856  7402  7402 D A2dpService: mStartError = false
09-02 12:07:53.856  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:53.856  7402  7402 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 12:07:53.856  7402  7402 D HidService: Received start request. Starting profile...
09-02 12:07:53.856  7402  7402 D HidService: start()
,09-02 12:07:53.856  7402  7402 I bluedroid: get_profile_interface hidhost
09-02 12:07:53.856  7402  7402 D HidService: setHidService(): set to: null
09-02 12:07:53.856  7402  7402 D HidService: mStartError = false,
09-02 12:07:53.856  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
09-02 12:07:53.866  7402  7402 I BluetoothHealthServiceJni: classInitNative: succeeds
09-02 12:07:53.866  7402  7446 D A2dpStateMachine: Enter Disconnected: -2
,09-02 12:07:53.866  7402  7402 D HealthService: Received start request. Starting profile...
,09-02 12:07:53.866  7402  7402 D HealthService: start()
,09-02 12:07:53.866  7402  7402 I bluedroid: get_profile_interface health
,09-02 12:07:53.866  7402  7402 D HealthService: mStartError = false
09-02 12:07:53.866  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:53.866  7402  7402 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 12:07:53.866  7402  7402 D PanService: Received start request. Starting profile...
09-02 12:07:53.866  7402  7402 D PanService: start()
09-02 12:07:53.866  7402  7402 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 12:07:53.866  7402  7402 I bluedroid: get_profile_interface pan
,09-02 12:07:53.866  7402  7402 D PanService: mStartError = false
09-02 12:07:53.866  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:53.876  7402  7445 D BluetoothMediaBrowser: no now playing list
09-02 12:07:53.876  7402  7402 D BluetoothMapService: Received start request. Starting profile...
09-02 12:07:53.876  7402  7402 D BluetoothMapService: start()
,09-02 12:07:53.876  7402  7445 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-02 12:07:53.876  7402  7402 D BluetoothMapService: mStartError = false
,09-02 12:07:53.876  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:53.876  7402  7402 D HeadsetStateMachine: Try to query the phonestate on bind
,09-02 12:07:53.876  1432  3278 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 12:07:53.876  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-02 12:07:53.876  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 12:07:53.876  1432  3278 I Telecom : BluetoothPhoneService: Result of Message : true
,09-02 12:07:53.876  7402  7402 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-02 12:07:53.886  7402  7402 D SapService: Received start request. Starting profile...
09-02 12:07:53.886  7402  7402 D SapService: start()
09-02 12:07:53.886  7402  7402 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-02 12:07:53.886  7402  7402 I bluedroid: get_profile_interface sap
09-02 12:07:53.886  7402  7402 D SapService: mStartError = false
09-02 12:07:53.886  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
09-02 12:07:53.886  7402  7402 D HeadsetStateMachine: Proxy object connected
,09-02 12:07:53.886  7402  7402 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-02 12:07:53.886  7402  7402 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-02 12:07:53.886  7402  7434 D HeadsetStateMachine: Disconnected process message: 11
09-02 12:07:53.886  7402  7402 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-02 12:07:53.886  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-02 12:07:53.886  7402  7402 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-02 12:07:53.886  7402  7402 D BluetoothA2dp: Proxy object connected
09-02 12:07:53.886  7402  7402 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-02 12:07:53.886  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-02 12:07:53.886  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-02 12:07:53.886  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-02 12:07:53.886  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-02 12:07:53.886  7402  7434 D HeadsetStateMachine: Disconnected process message: 18
09-02 12:07:53.886  7402  7434 D HeadsetStateMachine: Disconnected process message: 10
09-02 12:07:53.886  7402  7434 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-02 12:07:53.886  7402  7434 D HeadsetStateMachine: Disconnected process message: 11
,09-02 12:07:53.886  7424  7424 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-02 12:07:53.896  7424  7424 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-02 12:07:53.896  7424  7424 D UserAnalysis: Create SecureDbHelper
,09-02 12:07:53.896  7424  7424 D IntelligenceServiceApplication: onCreate()
,09-02 12:07:53.906  7424  7424 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-02 12:07:53.906  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-02 12:07:53.916  7424  7424 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-02 12:07:53.916  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-02 12:07:53.916  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-02 12:07:53.926  1017  4394 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-02 12:07:53.926  1017  4394 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:53.926  1017  4394 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:53.926  1017  4394 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:07:53.926  1017  4394 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:07:53.926  7424  7424 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-02 12:07:53.936  1017  4394 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7452 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
09-02 12:07:53.936  7452  7452 E Zygote  : MountEmulatedStorage()
09-02 12:07:53.936  7452  7452 I libpersona: KNOX_SDCARD checking this for 10105
09-02 12:07:53.936  7452  7452 E Zygote  : v2,
09-02 12:07:53.936  7452  7452 I libpersona: KNOX_SDCARD not a persona
,09-02 12:07:53.946  7452  7452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:07:53.946  1017  1212 I ActivityManager: Killing 7050:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-02 12:07:53.946  7402  7417 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-02 12:07:53.946  7402  7417 I bluedroid: enable
,09-02 12:07:53.946  7402  7417 I bt_hci_bdroid: init
,09-02 12:07:53.946  7402  7458 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 12:07:53.946  7452  7452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:07:53.946  7452  7452 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 12:07:53.966  7402  7417 I bt_vendor: bt-vendor : init
09-02 12:07:53.966  7402  7417 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 12:07:53.966  7402  7417 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-02 12:07:53.966  7402  7417 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-02 12:07:53.966  7402  7417 D bt_userial_mct: userial_init
,09-02 12:07:53.966  7402  7417 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-02 12:07:53.966  7402  7417 I bt_vendor: Starting hciattach daemon
09-02 12:07:53.966  7402  7417 I bt_vendor: try to set false
,09-02 12:07:53.966  7402  7417 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-02 12:07:53.966  7402  7417 I bt_vendor: Starting hciattach daemon
,09-02 12:07:53.966  7402  7417 I bt_vendor: try to set true
09-02 12:07:53.966  7452  7452 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:07:53.966  7452  7452 D ActivityThread: Added TimaKeyStore provider
,09-02 12:07:53.996  7471  7471 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-02 12:07:54.056  7477  7477 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-02 12:07:54.056  7478  7478 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 12:07:54.076  7482  7482 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 12:07:54.086  7483  7483 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-02 12:07:54.086  7484  7484 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-02 12:07:54.096  7485  7485 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
09-02 12:07:54.096   295   295 E SMD     : DCD OFF
,09-02 12:07:54.156   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-02 12:07:54.156   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 12:07:54.156  7452  7488 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files,
,09-02 12:07:54.156   257   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-02 12:07:54.156   257   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 12:07:54.166  7452  7488 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-02 12:07:54.286  7452  7452 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-02 12:07:54.286  7452  7452 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-02 12:07:54.286  7452  7452 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:54.286  7452  7452 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.v.a(PG,:1161)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.e.b(PG:170)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:54.286  7452  7452 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.k.d(PG:583)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.e.b(PG:170)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a,(PG:48)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:54.286  7452  7452 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:54.286  7452  7452 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:54.286  7452  7452 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 12:07:54.286  7452  7452 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 12:07:54.296  1017  4394 I ActivityManager: Killing 7061:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
09-02 12:07:54.296  1962  1962 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-02 12:07:54.306  1962  1962 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 12:07:54.356  7452  7499 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-02 12:07:54.356  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,09-02 12:07:54.366  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 12:07:54.376  1017  2016 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:54.386  1017  2016 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.386  1017  2016 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:54.386  1017  2016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-02 12:07:54.426  7402  7417 I bt_vendor: bluetooth satus is on
09-02 12:07:54.426  7402  7468 D bt_userial_mct: userial_open(port:0)
09-02 12:07:54.426  7402  7468 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-02 12:07:54.426  7402  7468 I bt_vendor: Done intiailizing UART
,09-02 12:07:54.426  7402  7468 I bt_vendor: Done intiailizing UART
,09-02 12:07:54.426  7402  7468 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,09-02 12:07:54.436  7402  7468 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_GAP,
09-02 12:07:54.436  7402  7458 I         : BTE_InitTraceLevels -- TRC_PAN
,09-02 12:07:54.446  7402  7458 I         : BTE_InitTraceLevels -- TRC_SAP
09-02 12:07:54.446  7402  7458 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 12:07:54.446  7402  7458 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:07:54.446  7402  7458 I         : BTE_InitTraceLevels -- TRC_SMP
,09-02 12:07:54.446  7402  7458 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 12:07:54.446  7402  7458 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 12:07:54.446  7402  7458 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-02 12:07:54.446  7402  7506 D bt_userial_mct: Entering userial_read_thread()
,09-02 12:07:54.536  7402  7458 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-02 12:07:54.546  7402  7458 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa426ced1 
,09-02 12:07:54.546  7402  7458 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa426ced1 
,09-02 12:07:54.556  7402  7420 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-02 12:07:54.566  7402  7420 E bt-btif : Calling BTA_HhEnable
,09-02 12:07:54.566  7402  7420 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-02 12:07:54.566  7402  7420 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-02 12:07:54.566  7402  7420 E BluetoothServiceJni: populateRssiValuesNative
09-02 12:07:54.566  7402  7420 I bluedroid: getModelRssiValues
09-02 12:07:54.566  7402  7420 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 12:07:54.566  7402  7420 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-02 12:07:54.566  1017  1017 D SettingsProvider: name = bluetooth_name
09-02 12:07:54.566  7402  7420 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-02 12:07:54.576  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:54.576  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:54.576  7402  7420 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 12:07:54.576  7402  7420 D BluetoothAdapterProperties: Scan Mode:20
09-02 12:07:54.576  7402  7420 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 12:07:54.576  7402  7420 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-02 12:07:54.576  7402  7420 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-02 12:07:54.576  7402  7420 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-02 12:07:54.576  7402  7420 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-02 12:07:54.576  7402  7420 E bt-btif : btif_sock_init: !vhci_init
,09-02 12:07:54.576  7402  7420 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-02 12:07:54.586  7402  7420 D IOP_DB_BT: db_open: db_open : handle 2963820560l, read 13894 bytes onto local cache
09-02 12:07:54.586  7402  7420 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-02 12:07:54.586  7402  7506 E bt_mct  : hci lib postload completed
09-02 12:07:54.586  7402  7420 D IOP_DB_BT: db_query: result 1
09-02 12:07:54.586  7402  7420 I         : iop_db_open: iop_db_open status 0
,09-02 12:07:54.586  7402  7420 D bte_conf: Device ID record 1 : primary
,09-02 12:07:54.586  7402  7420 D bte_conf:   vendorId            = 0075
09-02 12:07:54.586  7402  7420 D bte_conf:   vendorIdSource      = 0001
09-02 12:07:54.586  7402  7420 D bte_conf:   product             = 0100
09-02 12:07:54.586  7402  7420 D bte_conf:   version             = 0200
09-02 12:07:54.586  7402  7420 D bte_conf:   clientExecutableURL = 
09-02 12:07:54.586  7402  7420 D bte_conf:   serviceDescription  = 
09-02 12:07:54.586  7402  7420 D bte_conf:   documentationURL    = 
09-02 12:07:54.586  7402  7420 D bte_conf: bte_load_did_conf no section named DID2.
,09-02 12:07:54.586  7402  7420 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 12:07:54.586  7402  7417 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-02 12:07:54.596  7402  7417 D BluetoothAdapterProperties: ScanMode =  20
,09-02 12:07:54.596  7402  7417 D BluetoothAdapterProperties: State =  11
,09-02 12:07:54.596  1017  1471 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 12:07:54.596  7402  7417 D BluetoothAdapterProperties: Setting state to 12
09-02 12:07:54.596  7402  7417 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-02 12:07:54.596  7402  7420 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 12:07:54.596  7402  7420 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:07:54.596  7402  7420 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 12:07:54.596  1017  4395 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-02 12:07:54.596  1017  4395 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:07:54.596  1017  4395 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:07:54.596  1017  4395 D SettingsProvider: selectionArgs: false
09-02 12:07:54.596  1017  4395 D SettingsProvider: selectionArgs: 1002
09-02 12:07:54.596  1017  4395 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:07:54.596  1017  4395 D SettingsProvider: ret = -1
,09-02 12:07:54.606  7402  7417 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 12:07:54.606  7402  7417 D BluetoothAdapterService: updateAdapterState state is 12
,09-02 12:07:54.606  1017  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:54.606  1017  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.606  1017  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.606  1017  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.606  1017  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.606  7402  7417 D BluetoothAdapterService: Autoconnection is available 
,09-02 12:07:54.616  7402  7417 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,09-02 12:07:54.616  7402  7417 D BluetoothAdapterService: starting service from this receiver
09-02 12:07:54.616  1017  1383 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:54.616  1017  1383 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.616  1017  1383 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.616  1017  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.616  1017  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.616  7402  7417 I BluetoothAdapterState: Entering On State from state = 11
,09-02 12:07:54.616  6754  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 12:07:54.626  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:54.626  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:54.626  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:54.626  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:54.626  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:54.626  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:54.626  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:54.626  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:54.626  1432  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:07:54.626  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 12:07:54.626  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 12:07:54.636  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:54.636  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.636  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:54.636  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-02 12:07:54.636  1432  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:07:54.636  7402  7402 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-02 12:07:54.636  7402  7416 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:07:54.636  3855  3863 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 12:07:54.636  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-02 12:07:54.636  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.646  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.646  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.646  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.646  3855  6925 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 12:07:54.646  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:54.646  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:54.646  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:54.646  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:54.646  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:07:54.646  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:54.646  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:54.646  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:54.646  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-02 12:07:54.646  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.646  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.646  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.646  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.646  7402  7402 I BluetoothPbapService: Handler(): got msg=1
09-02 12:07:54.646  1017  1046 D BluetoothPan: Binding service...
,09-02 12:07:54.646  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 12:07:54.646  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.656  1017  4394 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-02 12:07:54.656  3855  3864 D Bluetoothsap: onBluetoothStateChange: up=true
09-02 12:07:54.656  3855  3864 D Bluetoothsap: Binding service...
,09-02 12:07:54.656  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:54.656  3855  3864 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-02 12:07:54.656  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 12:07:54.656  3855  3855 D BluetoothPbap: Proxy object connected
09-02 12:07:54.656  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-02 12:07:54.656  3855  3855 D PbapServerProfile: Bluetooth service connected
09-02 12:07:54.656  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-02 12:07:54.656  3855  3855 D BluetoothInputDevice: Proxy object connected
09-02 12:07:54.656  3855  3855 D HidProfile: Bluetooth service connected
,09-02 12:07:54.666  7402  7510 V BluetoothPbapService: PBAP Service initSocket try: 0
09-02 12:07:54.666  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.666  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.666  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.666  3855  3864 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-02 12:07:54.666  1962  6728 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:07:54.666  1962  6728 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:07:54.666  6754  6767 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:07:54.666  6754  6767 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:07:54.666  3855  3855 D Bluetoothsap: BluetoothSAP Proxy object connected
09-02 12:07:54.666  3855  3855 D SapProfile: Bluetooth service connected
09-02 12:07:54.666  3855  3855 D Bluetoothsap: getConnectedDevices()
,09-02 12:07:54.666  1432  3278 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:07:54.676  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 12:07:54.676  7402  7510 D BluetoothSocket: bindListen(): myUserId = 0
09-02 12:07:54.676  7402  7510 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:07:54.676  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 12:07:54.676  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.676  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.676  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.676  1432  3278 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:07:54.676  7402  7416 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 12:07:54.676  7402  7416 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:07:54.676  7452  7469 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 12:07:54.676  7452  7469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 12:07:54.676  1457  1715 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 12:07:54.676  1457  1715 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 12:07:54.676  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-02 12:07:54.676  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 12:07:54.676  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 12:07:54.676  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:07:54.676  7402  7510 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-02 12:07:54.676  7402  7510 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 12:07:54.676  7402  7510 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-02 12:07:54.676  7402  7510 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11254203
09-02 12:07:54.676  7402  7510 D BluetoothSocket: channel: 19
09-02 12:07:54.676  7402  7510 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-02 12:07:54.676  1432  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:07:54.686  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 12:07:54.686  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 12:07:54.686  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.686  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:54.686  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.686  1432  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:07:54.686  1441  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:07:54.686  1441  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:07:54.686  3855  3864 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:07:54.686  3855  3864 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:07:54.686  3855  3863 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:07:54.696  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 12:07:54.696  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-02 12:07:54.696  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.696  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.696  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.696  3855  3863 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 12:07:54.696  3855  3855 D HeadsetProfile: Bluetooth service connected
,09-02 12:07:54.696  1457  1479 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:07:54.696  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 12:07:54.696  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 12:07:54.696  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.696  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.696  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.696  1457  1479 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:07:54.706  1173  2371 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:07:54.706  1173  2371 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 12:07:54.706  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 12:07:54.706  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:07:54.706  3855  3864 D BluetoothPan: Binding service...
,09-02 12:07:54.706  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-02 12:07:54.706  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.706  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.706  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.706  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.706  3855  3855 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:07:54.706  3855  3863 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:07:54.706  3855  3855 D PanProfile: Bluetooth service connected
,09-02 12:07:54.706  3855  3863 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:07:54.706  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 12:07:54.706  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.706  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 12:07:54.706  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.706  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.706  3855  3864 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 12:07:54.716  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-02 12:07:54.716  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.716  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.716  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:54.716  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.716  3855  3855 D BluetoothA2dp: Proxy object connected
,09-02 12:07:54.716  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 12:07:54.716  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-02 12:07:54.716  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 12:07:54.716  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.716  1017  1017 D BluetoothA2dp: Proxy object connected
09-02 12:07:54.716  1432  3278 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 12:07:54.716  1432  3278 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:07:54.716  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-02 12:07:54.716  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 12:07:54.716  3855  3855 D A2dpProfile: Bluetooth service connected
,09-02 12:07:54.716  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-02 12:07:54.716  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-02 12:07:54.716  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 12:07:54.726  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-02 12:07:54.726  1432  1432 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3a62186f, true
,09-02 12:07:54.726  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 12:07:54.726  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:54.726  1173  1173 D BluetoothTile:  getBluetoothState : 12
09-02 12:07:54.726  1915  1915 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 12:07:54.736  1432  1432 D BluetoothHeadset: registerMessageListener
09-02 12:07:54.736  1017  1383 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 12:07:54.736  1017  1481 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-02 12:07:54.736  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 12:07:54.736  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 12:07:54.736  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:54.736  1017  1212 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:54.736  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.746  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.746  1017  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:54.746  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:54.746  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:54.746  3855  3855 D BluetoothMap: Proxy object connected
09-02 12:07:54.746  3855  3855 D MapProfile: Bluetooth service connected
09-02 12:07:54.746  3855  3855 D BluetoothMap: getConnectedDevices()
09-02 12:07:54.746  7402  7421 D HeadsetService: registerMessageListener
09-02 12:07:54.746  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 12:07:54.746  7402  7421 D HeadsetService: registerMessageListener
09-02 12:07:54.746  7402  7434 D HeadsetStateMachine: Disconnected process message: 70
,09-02 12:07:54.746  7402  7434 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@384c3580
09-02 12:07:54.746  7402  7513 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-02 12:07:54.746  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-02 12:07:54.746  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 12:07:54.746  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 12:07:54.746  3855  3855 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:54.756  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-02 12:07:54.756  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-02 12:07:54.756  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-02 12:07:54.756  3855  3855 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-02 12:07:54.756  7402  7434 D HeadsetStateMachine: Disconnected process message: 9
,09-02 12:07:54.756  7402  7434 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
09-02 12:07:54.756  7402  7513 D BluetoothSocket: bindListen(): myUserId = 0
09-02 12:07:54.756  7402  7513 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:07:54.756  3855  3855 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-02 12:07:54.756  3855  3855 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-02 12:07:54.756  3855  3855 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-02 12:07:54.766  7402  7513 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-02 12:07:54.766  7402  7513 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 12:07:54.766  7402  7513 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 12:07:54.766  7402  7513 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11bff7b9
,09-02 12:07:54.766  7402  7513 D BluetoothSocket: channel: 5
,09-02 12:07:54.766   290   726 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-02 12:07:54.766   290   726 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-02 12:07:54.766   290   726 V voice   : voice_set_parameters: exit with code(-2)
09-02 12:07:54.766   290   726 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-02 12:07:54.766   290   726 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-02 12:07:54.766   290   726 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-02 12:07:54.766   290   726 V audio_hw_primary: adev_set_parameters: exit
09-02 12:07:54.766  7402  7434 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-02 12:07:54.776  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:07:54.776  1017  1483 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 12:07:54.776  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.776  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.776  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.776  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 12:07:54.786  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:07:54.786  3855  3855 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 12:07:54.786  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:54.786  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-02 12:07:54.796  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:54.796  7402  7402 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 12:07:54.796  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:54.796  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.796  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.796  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:54.796  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:54.816  1962  1962 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 12:07:54.816  1017  4394 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 12:07:54.816  1017  4394 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 12:07:54.816  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.816  1017  4394 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:54.816  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:54.826  1017  1480 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 12:07:54.836  1962  7521 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-02 12:07:54.836  1017  2016 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:54.836  1962  1962 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 12:07:54.836  1017  2016 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:54.836  1017  2016 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:54.836  1017  2016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:54.856  7402  7524 D BluetoothSocket: bindListen(): myUserId = 0
09-02 12:07:54.856  7402  7524 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:07:54.856  7402  7524 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-02 12:07:54.856  7402  7524 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 12:07:54.856  7402  7524 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 12:07:54.856  7402  7524 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2102ee7b
,09-02 12:07:54.856  1017  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:54.856  7402  7524 D BluetoothSocket: channel: 12
09-02 12:07:54.856  7402  7524 I BtOppRfcommListener: Accept thread started.
,09-02 12:07:54.866  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:54.866  1017  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:54.866  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:54.866  1962  7521 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-02 12:07:54.896  1017  3339 D SSRM:n  : SIOP:: AP = 350
,09-02 12:07:56.476  6754  6808 D BluetoothAdapter: disable()
09-02 12:07:56.476  1017  1212 D SettingsProvider: name = bluetooth_on
,09-02 12:07:56.486  7402  7417 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-02 12:07:56.486  7402  7417 D BluetoothAdapterProperties: Setting state to 13
09-02 12:07:56.486  7402  7417 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 12:07:56.486  7402  7417 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 12:07:56.486  7402  7417 D BluetoothAdapterService: updateAdapterState state is 13
09-02 12:07:56.486  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:56.486  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 12:07:56.486  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:56.486  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:56.486  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 12:07:56.486  7402  7402 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-02 12:07:56.496  7402  7417 D BluetoothAdapterService: Autoconnection is available 
09-02 12:07:56.496  7402  7417 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-02 12:07:56.496  7402  7417 D BluetoothAdapterService: terminating service from this receiver
,09-02 12:07:56.496  7402  7402 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@210b3498, channel: 19, state: LISTENING
09-02 12:07:56.496  1017  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 12:07:56.496  1017  1500 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:56.496  7402  7402 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@210b3498, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11254203, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15be4f1mSocket: android.net.LocalSocket@174818d6 impl:android.net.LocalSocketImpl@2cc7f757 fd:FileDescriptor[74]
09-02 12:07:56.496  1017  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:56.496  1017  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 12:07:56.496  7402  7402 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@174818d6 impl:android.net.LocalSocketImpl@2cc7f757 fd:FileDescriptor[74]
,09-02 12:07:56.496  7402  7417 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 12:07:56.496  7402  7417 D BluetoothAdapterProperties: mDiscovering is false
,09-02 12:07:56.496  1017  1471 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 12:07:56.496  7402  7417 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-02 12:07:56.496  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:56.496  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,09-02 12:07:56.506  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-02 12:07:56.506  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 12:07:56.516  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 12:07:56.516  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:56.516  1173  1173 D BluetoothTile:  getBluetoothState : 13
,09-02 12:07:56.516  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 12:07:56.516  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 12:07:56.516  1915  1915 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 12:07:56.516  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 12:07:56.516  3855  3855 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:56.526  1017  1483 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 12:07:56.526  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 12:07:56.526  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:56.526  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:56.526  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:56.526  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:56.526  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:56.526  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:56.526  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:56.526  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:56.526  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:56.526  1017  4395 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:56.536  1017  4395 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 12:07:56.536  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:56.536  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:56.536  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-02 12:07:56.536  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:56.536  1017  4395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:56.536  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:56.536  7402  7420 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 12:07:56.536  7402  7420 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:07:56.536  3855  3855 D BluetoothPbap: Proxy object disconnected
09-02 12:07:56.536  3855  3855 D PbapServerProfile: Bluetooth service disconnected
,09-02 12:07:56.536  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 12:07:56.536  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:07:56.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:07:56.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:07:56.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:07:56.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 12:07:56.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:07:56.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:07:56.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:07:56.546  6754  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 12:07:56.546  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:07:56.546  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:07:56.546  1017  1210 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 12:07:56.546  7402  7417 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 12:07:56.546  7402  7417 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-02 12:07:56.546  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-02 12:07:56.546  7402  7417 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-02 12:07:56.546  7402  7417 E bt-btif : cmd socket is not created
,09-02 12:07:56.556  7402  7417 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-02 12:07:56.556  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:56.556  1017  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:56.556  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 12:07:56.556  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:56.556  7402  7458 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-02 12:07:56.556  7402  7458 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-02 12:07:56.556  7402  7458 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:07:56.556  7402  7458 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:56.556  7402  7458 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:07:56.556  7402  7524 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-02 12:07:56.556  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:56.576  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:07:56.576  3855  3855 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 12:07:56.576  7402  7402 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22cb0244, channel: 5, state: LISTENING
,09-02 12:07:56.586  7402  7402 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@22cb0244, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11bff7b9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2fb8df2dmSocket: android.net.LocalSocket@2f84ec62 impl:android.net.LocalSocketImpl@316ab1f3 fd:FileDescriptor[76]
09-02 12:07:56.586  7402  7402 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2f84ec62 impl:android.net.LocalSocketImpl@316ab1f3 fd:FileDescriptor[76]
,09-02 12:07:56.586  7402  7402 I BtOppRfcommListener: stopping Accept Thread
,09-02 12:07:56.586  7402  7402 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2197feb0, channel: 12, state: LISTENING
09-02 12:07:56.586  7402  7402 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2197feb0, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2102ee7b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9714129mSocket: android.net.LocalSocket@15c96cae impl:android.net.LocalSocketImpl@22747a4f fd:FileDescriptor[80]
09-02 12:07:56.586  7402  7402 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15c96cae impl:android.net.LocalSocketImpl@22747a4f fd:FileDescriptor[80]
,09-02 12:07:56.586  7402  7524 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-02 12:07:56.586  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:56.586  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-02 12:07:56.606  7402  7402 V BluetoothOppManager: cleanUp...
,09-02 12:07:56.616  1962  1962 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 12:07:56.616  1962  1962 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 12:07:56.756  7402  7458 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 12:07:56.756  7402  7458 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:56.756  7402  7458 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:07:56.756  7402  7458 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:07:56.756  7402  7458 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:56.756  7402  7458 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:07:56.756  7402  7458 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 12:07:56.756  7402  7458 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 12:07:56.756  7402  7458 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 12:07:56.756  7402  7458 W bt-btif : ag scb idx 1 not allocated
09-02 12:07:56.756  7402  7458 W bt-btif : ag scb idx 2 not allocated
09-02 12:07:56.756  7402  7458 E bt-btif : BTA AG is already disabled, ignoring ...
09-02 12:07:56.756  7402  7506 I bt_userial_mct: exiting userial_read_thread
09-02 12:07:56.756  7402  7506 D bt_userial_mct: Leaving userial_evt_read_thread()
09-02 12:07:56.756  7402  7420 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-02 12:07:56.756  7402  7468 I bt_vendor: hw_epilog_process
09-02 12:07:56.756  7402  7420 D bt_userial_mct: userial_close
09-02 12:07:56.756  7402  7420 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-02 12:07:57.106   295   295 E SMD     : DCD OFF,
,09-02 12:07:57.246  7402  7420 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-02 12:07:57.246  7402  7420 I bt_vendor: bluetooth satus is on
09-02 12:07:57.246  7402  7420 I bt_vendor: bt-vendor : resetting BT status
09-02 12:07:57.246  7402  7420 I bt_vendor: Starting hciattach daemon,
09-02 12:07:57.246  7402  7420 I bt_vendor: try to set false
09-02 12:07:57.246  7402  7420 I bt_vendor: Starting hciattach daemon
,09-02 12:07:57.246  7402  7420 I bt_vendor: try to set false
,09-02 12:07:57.246  7402  7420 I bt_vendor: cleanup
09-02 12:07:57.246  7402  7458 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-02 12:07:57.246  7402  7420 I GKI_LINUX: GKI_exit_task 0 done
09-02 12:07:57.246  7402  7420 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-02 12:07:57.246  7402  7417 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 12:07:57.246  7402  7417 D BtConfig.SecureMode: isSecureModeOn:false
09-02 12:07:57.246  7402  7417 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-02 12:07:57.246  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 12:07:57.246  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 12:07:57.246  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 12:07:57.246  1017  4395 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:57.246  1017  4395 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.246  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:57.246  1017  4395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:57.246  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:57.256  7402  7402 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 12:07:57.256  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 12:07:57.256  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 12:07:57.256  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 12:07:57.256  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:57.256  7402  7402 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 12:07:57.256  7402  7402 D BtGatt.GattService: stop()
09-02 12:07:57.256  7402  7402 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 12:07:57.256  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.256  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:57.256  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:57.256  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:57.256  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-02 12:07:57.256  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:57.256  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 12:07:57.256  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-02 12:07:57.266  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:57.266  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.266  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:57.266  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:57.266  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:57.266  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-02 12:07:57.266  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 12:07:57.266  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 12:07:57.266  1017  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:57.266  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.266  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:57.266  1017  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:57.266  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:57.266  7402  7402 D HeadsetService: Received stop request...Stopping profile...
,09-02 12:07:57.276  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-02 12:07:57.276  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 12:07:57.276  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 12:07:57.276  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:57.276  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:57.276  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.276  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:57.276  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:57.276  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 12:07:57.276  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-02 12:07:57.276  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 12:07:57.276  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 12:07:57.276  1017  4396 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:57.276  1017  4396 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.276  1017  4396 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:57.276  1017  4396 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:57.276  1017  4396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 12:07:57.276  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 12:07:57.276  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 12:07:57.276  7402  7417 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 12:07:57.276  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:07:57.276  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.276  3855  3855 D HeadsetProfile: Bluetooth service disconnected
,09-02 12:07:57.286  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-02 12:07:57.286  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:57.286  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:57.286  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:57.286  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-02 12:07:57.286  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 12:07:57.286  7402  7417 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 12:07:57.286  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:07:57.286  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.286  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:57.286  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:07:57.286  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:07:57.296  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:57.296  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:57.296  7402  7417 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:07:57.296  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:57.296  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:57.296  7402  7417 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:07:57.296  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 12:07:57.296  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 12:07:57.296  7402  7417 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 12:07:57.296  7402  7417 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 12:07:57.296  7402  7417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 12:07:57.296  7402  7417 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 12:07:57.296  7402  7417 D BluetoothAdapterState: Stopping profile services that were post enabled
09-02 12:07:57.296  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-02 12:07:57.296  7402  7402 D A2dpService: Received stop request...Stopping profile...
,09-02 12:07:57.296  7402  7446 D A2dpStateMachine: Exit Disconnected: -1
,09-02 12:07:57.296  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:57.296  1017  1017 D BluetoothA2dp: Proxy object disconnected
,09-02 12:07:57.296  3855  3855 D BluetoothA2dp: Proxy object disconnected
09-02 12:07:57.296  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-02 12:07:57.296  3855  3855 D A2dpProfile: Bluetooth service disconnected
09-02 12:07:57.296  7402  7402 D HidService: Received stop request...Stopping profile...
09-02 12:07:57.296  7402  7402 D HidService: Stopping Bluetooth HidService
09-02 12:07:57.296  7402  7402 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 12:07:57.296  7402  7402 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-02 12:07:57.296  7402  7402 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 12:07:57.296  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:57.306  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-02 12:07:57.306  3855  3855 D BluetoothInputDevice: Proxy object disconnected
09-02 12:07:57.306  3855  3855 D HidProfile: Bluetooth service disconnected
09-02 12:07:57.306  7402  7402 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 12:07:57.306  7402  7402 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-02 12:07:57.306  7402  7402 D HealthService: Received stop request...Stopping profile...
09-02 12:07:57.306  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:57.306  7402  7402 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-02 12:07:57.306  7402  7402 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-02 12:07:57.306  7402  7402 D PanService: Received stop request...Stopping profile...
,09-02 12:07:57.306  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:57.306  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-02 12:07:57.306  7402  7402 D BluetoothMapService: Received stop request...Stopping profile...
09-02 12:07:57.306  3855  3855 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 12:07:57.306  3855  3855 D PanProfile: Bluetooth service disconnected
,09-02 12:07:57.316  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:57.316  7402  7402 D SapService: Received stop request...Stopping profile...
09-02 12:07:57.316  7402  7402 D SapService: Stopping Bluetooth SapService
09-02 12:07:57.316  7402  7402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:07:57.316  3855  3855 D BluetoothMap: Proxy object disconnected
09-02 12:07:57.316  3855  3855 D MapProfile: Bluetooth service disconnected
,09-02 12:07:57.316  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-02 12:07:57.316  7402  7402 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 12:07:57.316  7402  7402 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-02 12:07:57.316  7402  7402 D BluetoothA2dp: Proxy object disconnected
,09-02 12:07:57.316  7402  7402 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-02 12:07:57.326  7402  7447 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 12:07:57.326  7402  7402 I GKI_LINUX: GKI_exit_task 2 done
,09-02 12:07:57.326  7402  7402 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-02 12:07:57.326  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-02 12:07:57.326  7402  7402 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 12:07:57.326  7402  7402 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-02 12:07:57.326  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-02 12:07:57.326  7402  7402 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 12:07:57.326  7402  7402 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 12:07:57.326  7402  7402 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 12:07:57.326  7402  7402 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 12:07:57.326  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-02 12:07:57.326  7402  7402 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 12:07:57.326  7402  7402 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 12:07:57.326  7402  7402 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 12:07:57.326  7402  7402 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 12:07:57.326  3855  3855 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,09-02 12:07:57.326  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-02 12:07:57.326  7402  7402 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 12:07:57.326  7402  7402 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-02 12:07:57.326  7402  7402 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-02 12:07:57.326  7402  7402 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-02 12:07:57.326  7402  7402 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-02 12:07:57.326  7402  7417 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-02 12:07:57.326  7402  7417 D BluetoothAdapterProperties: Setting state to 10
09-02 12:07:57.326  7402  7417 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 12:07:57.326  7402  7417 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 12:07:57.326  7402  7417 D BluetoothAdapterService: updateAdapterState state is 10
,09-02 12:07:57.326  3855  3855 D SapProfile: Bluetooth service disconnected
09-02 12:07:57.326  7402  7417 D BluetoothAdapterService: Autoconnection is available 
09-02 12:07:57.326  7402  7417 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-02 12:07:57.326  7402  7417 I BluetoothAdapterState: Entering OffState
,09-02 12:07:57.326  7402  7413 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 12:07:57.326  3855  6925 D BluetoothPbap: onBluetoothStateChange: up=false
,09-02 12:07:57.336  3855  3864 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 12:07:57.336  3855  7511 D Bluetoothsap: onBluetoothStateChange: up=false
09-02 12:07:57.336  3855  7511 D Bluetoothsap: Unbinding service...
,09-02 12:07:57.336  1962  1979 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:57.336  1962  1979 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:57.336  6754  6767 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:57.336  6754  6767 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 12:07:57.336  6754  6767 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-02 12:07:57.336  6754  6767 D BluetoothLeAdvertiser: Exit stop advertising
09-02 12:07:57.336  6754  6767 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-02 12:07:57.336  6754  6767 D BluetoothLeScanner: Exiting stopAllScan
,09-02 12:07:57.336  7402  7421 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:57.336  7402  7421 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 12:07:57.336  7452  7466 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:57.336  7452  7466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 12:07:57.336  1457  1715 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 12:07:57.336  1457  1715 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:57.336  1441  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:57.336  1441  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:57.336  3855  3863 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:57.336  3855  3863 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:57.346  1173  2001 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:57.346  1173  2001 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:57.346  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 12:07:57.346  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:57.346  3855  7511 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 12:07:57.346  3855  3863 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 12:07:57.346  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 12:07:57.346  1432  1440 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 12:07:57.346  1432  1440 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 12:07:57.346  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-02 12:07:57.356  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 12:07:57.356  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:57.356  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
09-02 12:07:57.356  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 12:07:57.366  1173  1173 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
,09-02 12:07:57.366  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 12:07:57.366  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:57.366  1173  1173 D BluetoothTile:  getBluetoothState : 10
,09-02 12:07:57.366  1173  1732 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
,09-02 12:07:57.366  1173  1732 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
09-02 12:07:57.366  1173  1173 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
09-02 12:07:57.366  1173  1173 D BluetoothAdapter: 604928888: getState() :  mService = null. Returning STATE_OFF
,09-02 12:07:57.366  1017  1483 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 12:07:57.366  1915  1915 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 12:07:57.376  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 12:07:57.376  3855  3855 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:07:57.376  1962  2159 D BluetoothAdapter: 242131902: getState() :  mService = null. Returning STATE_OFF
,09-02 12:07:57.376  1962  2159 D BluetoothAdapter: 242131902: getState() :  mService = null. Returning STATE_OFF
,09-02 12:07:57.376  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 12:07:57.376  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:57.376  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:07:57.376  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.376  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:07:57.376  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:57.376  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:57.376  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:57.376  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:07:57.386  1017  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 12:07:57.386  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.386  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:57.386  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:07:57.386  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 12:07:57.386  7402  7420 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-02 12:07:57.386  7402  7402 I GKI_LINUX: GKI_exit_task 1 done
,09-02 12:07:57.386  7402  7402 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-02 12:07:57.386  7402  7402 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 12:07:57.396  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:07:57.396  3855  3855 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 12:07:57.396  7402  7402 I art     : System.exit called, status: 0
09-02 12:07:57.396  7402  7402 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 12:07:57.396  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:07:57.396  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-02 12:07:57.526  1017  1480 I ActivityManager: Process com.android.bluetooth (pid 7402)(adj 0) has died(48,711)
,09-02 12:07:57.536  1962  1962 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 12:07:57.536  1017  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
09-02 12:07:57.536  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 12:07:57.536  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:07:57.536  1017  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:57.536  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:57.546  1962  7540 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-02 12:07:57.546  1962  1962 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 12:07:57.556  1017  1210 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:07:57.556  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:07:57.556  1017  1210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:07:57.566  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:07:57.566  1962  7540 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-02 12:07:59.466  1017  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 12:07:59.466  1017  1471 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-02 12:07:59.466  1017  1471 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-02 12:07:59.466  1017  1471 D BatteryService: stay LED for fully charged
09-02 12:07:59.466  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-02 12:07:59.476  1017  1017 I MotionRecognitionService: Plugged
09-02 12:07:59.476  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 12:07:59.476  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-02 12:07:59.476  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate,
,09-02 12:07:59.476  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 12:07:59.476  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-02 12:07:59.486  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:07:59.486  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:07:59.506  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-02 12:07:59.506  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-02 12:07:59.506  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,09-02 12:07:59.506  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:59.506  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-02 12:07:59.876  1017  1049 I PowerManagerService: [PWL] Off : 75s ago,
09-02 12:07:59.876  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,09-02 12:07:59.876  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-02 12:07:59.876  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=14996)
,09-02 12:07:59.996  1017  1095 V AlarmManager: waitForAlarm result :8,
,09-02 12:08:00.106   295   295 E SMD     : DCD OFF,
,09-02 12:08:01.206  1017  1309 E Watchdog: !@Sync 4
,09-02 12:08:02.156   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 12:08:02.496  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:02.496  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10459f5f added. We now have 6 listener(s)
,09-02 12:08:02.496  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:02.506  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:02.506  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6adfdac added. We now have 7 listener(s)
,09-02 12:08:02.506  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:02.506  6754  6808 I System.out: IsBluetoothEnabled
,09-02 12:08:02.506  6754  6808 D BluetoothAdapter: disable()
,09-02 12:08:02.506  1017  2016 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-02 12:08:02.516  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:02.516  6754  6808 D BluetoothAdapter: enable()
,09-02 12:08:02.516  1017  1500 W ActivityManager: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-02 12:08:02.516  1017  1500 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-02 12:08:02.516  1017  1500 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-02 12:08:02.516  1017  1500 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 12:08:02.516  1017  1500 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-02 12:08:02.516  1017  1500 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-02 12:08:02.516  1017  1500 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-02 12:08:02.516  1017  1500 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 12:08:02.516  1017  1500 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 12:08:02.516  1017  1500 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 12:08:02.516  1017  1500 D SettingsProvider: name = bluetooth_on,
,09-02 12:08:02.526  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-02 12:08:02.526  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 12:08:02.536  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-02 12:08:02.536  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
09-02 12:08:02.536  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:02.536  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:02.536  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:02.536  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:02.556  7546  7546 E Zygote  : MountEmulatedStorage(),
09-02 12:08:02.556  7546  7546 E Zygote  : v2
09-02 12:08:02.556  7546  7546 I libpersona: KNOX_SDCARD checking this for 1002,
09-02 12:08:02.556  7546  7546 I libpersona: KNOX_SDCARD not a persona
09-02 12:08:02.556  7546  7546 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 12:08:02.556  7546  7546 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 12:08:02.556  1017  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7546 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-02 12:08:02.566  7546  7546 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-02 12:08:02.606  7546  7546 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:02.606  7546  7546 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:02.626  7546  7546 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-02 12:08:02.626  7546  7546 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 12:08:02.666  7546  7546 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-02 12:08:02.696  7546  7546 D BtSettings.ProfileConfig: Adding GattService
,09-02 12:08:02.696  7546  7546 D BtSettings.ProfileConfig: Adding HeadsetService
,09-02 12:08:02.696  7546  7546 D BtSettings.ProfileConfig: Adding A2dpService
,09-02 12:08:02.706  7546  7546 D BtSettings.ProfileConfig: Adding HidService
,09-02 12:08:02.706  7546  7546 D BtSettings.ProfileConfig: Adding HealthService
,09-02 12:08:02.706  7546  7546 D BtSettings.ProfileConfig: Adding PanService
,09-02 12:08:02.706  7546  7546 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-02 12:08:02.706  7546  7546 D BtSettings.ProfileConfig: Adding SapService
09-02 12:08:02.706  7546  7546 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-02 12:08:02.706  7546  7546 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-02 12:08:02.706  7546  7546 D BtSettings.ProfileConfig: Adding SapClientService
09-02 12:08:02.706  7546  7546 D BtSettings.ProfileConfig: Adding HidDevService
,09-02 12:08:02.706  7546  7546 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-02 12:08:02.706  1017  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
09-02 12:08:02.706  1017  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.706  1017  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.706  1017  1480 D SettingsProvider: selectionArgs: false
09-02 12:08:02.706  1017  1480 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.706  1017  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.706  1017  1480 D SettingsProvider: ret = -1
,09-02 12:08:02.706  1017  4394 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-02 12:08:02.706  1017  4394 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.706  1017  4394 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.706  1017  4394 D SettingsProvider: selectionArgs: false
09-02 12:08:02.706  1017  4394 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.706  1017  4394 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.706  1017  4394 D SettingsProvider: ret = -1
,09-02 12:08:02.716  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-02 12:08:02.716  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.716  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.716  1017  1030 D SettingsProvider: selectionArgs: false
09-02 12:08:02.716  1017  1030 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.716  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.716  1017  1030 D SettingsProvider: ret = -1
,09-02 12:08:02.716  1017  4396 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-02 12:08:02.716  1017  4396 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.716  1017  4396 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.716  1017  4396 D SettingsProvider: selectionArgs: false
09-02 12:08:02.716  1017  4396 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.716  1017  4396 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.716  1017  4396 D SettingsProvider: ret = -1
,09-02 12:08:02.716  1017  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-02 12:08:02.716  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.716  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.716  1017  1481 D SettingsProvider: selectionArgs: false
09-02 12:08:02.716  1017  1481 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.716  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.716  1017  1481 D SettingsProvider: ret = -1
,09-02 12:08:02.716  1017  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-02 12:08:02.716  1017  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.716  1017  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.716  1017  1483 D SettingsProvider: selectionArgs: false
,09-02 12:08:02.716  1017  1483 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.716  1017  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:08:02.716  1017  1483 D SettingsProvider: ret = -1
,09-02 12:08:02.716  1017  2016 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-02 12:08:02.716  1017  2016 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.716  1017  2016 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.716  1017  2016 D SettingsProvider: selectionArgs: false
09-02 12:08:02.716  1017  2016 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.716  1017  2016 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.716  1017  2016 D SettingsProvider: ret = -1
,09-02 12:08:02.716  1017  1210 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-02 12:08:02.716  1017  1210 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.716  1017  1210 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.716  1017  1210 D SettingsProvider: selectionArgs: false
09-02 12:08:02.716  1017  1210 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.716  1017  1210 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.716  1017  1210 D SettingsProvider: ret = -1
,09-02 12:08:02.716  1017  1383 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:08:02.716  1017  1383 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 12:08:02.716  1017  1383 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.716  1017  1383 D SettingsProvider: selectionArgs: false
09-02 12:08:02.716  1017  1383 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.716  1017  1383 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:08:02.716  1017  1383 D SettingsProvider: ret = -1
,09-02 12:08:02.726  1017  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:08:02.726  1017  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.726  1017  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.726  1017  1471 D SettingsProvider: selectionArgs: false
09-02 12:08:02.726  1017  1471 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.726  1017  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.726  1017  1471 D SettingsProvider: ret = -1
,09-02 12:08:02.726  1017  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-02 12:08:02.726  1017  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-02 12:08:02.726  1017  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.726  1017  1500 D SettingsProvider: selectionArgs: false
09-02 12:08:02.726  1017  1500 D SettingsProvider: selectionArgs: 1002
09-02 12:08:02.726  1017  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:08:02.726  1017  1500 D SettingsProvider: ret = -1
09-02 12:08:02.726  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-02 12:08:02.726  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.726  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:02.726  1017  1029 D SettingsProvider: selectionArgs: false
09-02 12:08:02.726  1017  1029 D SettingsProvider: selectionArgs: 1002,
09-02 12:08:02.726  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.726  1017  1029 D SettingsProvider: ret = -1
,09-02 12:08:02.736  7546  7546 D BluetoothAdapterState: make,
,09-02 12:08:02.736  7546  7546 I bluedroid: init,
09-02 12:08:02.736  7546  7561 I BluetoothAdapterState: Entering OffState
,09-02 12:08:02.746  7546  7546 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-02 12:08:02.746  7546  7546 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-02 12:08:02.746  7546  7546 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 12:08:02.746  7546  7546 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 12:08:02.746  7546  7546 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-02 12:08:02.746  7546  7546 I bluedroid: get_profile_interface socket
09-02 12:08:02.746  7546  7546 I bluedroid: get_profile_interface map_client
,09-02 12:08:02.746  7546  7564 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-02 12:08:02.746  7546  7546 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-02 12:08:02.746  7546  7564 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-02 12:08:02.746  7546  7564 E BluetoothServiceJni: populateRssiValuesNative
09-02 12:08:02.746  7546  7564 I bluedroid: getModelRssiValues
,09-02 12:08:02.746  7546  7564 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 12:08:02.746  7546  7564 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 12:08:02.746  1017  1017 D SettingsProvider: name = bluetooth_name
,09-02 12:08:02.756  7546  7564 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-02 12:08:02.756  7546  7546 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:08:02.756  1017  1383 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-02 12:08:02.756  1017  1383 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.756  1017  1383 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:02.756  1017  1383 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:02.756  1017  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:02.756  7546  7554 I bluedroid: config_hci_snoop_log
,09-02 12:08:02.766  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 12:08:02.766  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,09-02 12:08:02.766  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-02 12:08:02.766  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-02 12:08:02.766  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 12:08:02.766  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 12:08:02.766  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 12:08:02.766  7546  7546 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-02 12:08:02.776  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-02 12:08:02.776  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-02 12:08:02.776  7546  7561 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-02 12:08:02.776  7546  7561 D BluetoothAdapterProperties: Setting state to 11
09-02 12:08:02.776  7546  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 12:08:02.776  7546  7561 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 12:08:02.776  7546  7561 D BluetoothAdapterService: updateAdapterState state is 11
09-02 12:08:02.776  7546  7561 D BluetoothAdapterService: Autoconnection is available 
09-02 12:08:02.776  7546  7561 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-02 12:08:02.776  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:08:02.776  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,09-02 12:08:02.786  7546  7561 D BluetoothSecureManager: getInstant: null
09-02 12:08:02.786  7546  7561 D BluetoothSecureManager: calling getMethod for getService
,09-02 12:08:02.786  7546  7561 D BluetoothSecureManager: calling getService
,09-02 12:08:02.786  7546  7561 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@29a921ee
,09-02 12:08:02.786  1017  1030 D BluetoothSecureManagerService: isSecureModeEnabled
,09-02 12:08:02.786  1017  1030 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-02 12:08:02.786  7546  7561 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 12:08:02.786  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-02 12:08:02.786  7546  7561 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-02 12:08:02.786  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 12:08:02.786  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 12:08:02.786  7546  7561 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-02 12:08:02.786  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-02 12:08:02.786  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:08:02.786  7546  7561 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-02 12:08:02.786  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 12:08:02.786  1173  1173 D BluetoothTile:  getBluetoothState : 11
,09-02 12:08:02.786  1915  1915 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 12:08:02.796  7546  7561 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-02 12:08:02.796  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 12:08:02.796  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
09-02 12:08:02.796  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 12:08:02.796  3855  3855 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:08:02.796  7546  7561 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-02 12:08:02.796  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 12:08:02.796  7546  7561 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-02 12:08:02.796  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 12:08:02.796  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:02.796  7546  7561 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-02 12:08:02.796  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 12:08:02.796  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 12:08:02.796  7546  7561 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-02 12:08:02.796  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:08:02.796  1017  1383 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 12:08:02.796  1017  1383 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.796  7546  7561 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:08:02.796  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:08:02.806  1017  1383 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:02.806  1017  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 12:08:02.806  7546  7561 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:08:02.806  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-02 12:08:02.806  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 12:08:02.806  1017  1383 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:08:02.806  1017  1383 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 12:08:02.806  7546  7561 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-02 12:08:02.806  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-02 12:08:02.806  7546  7561 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-02 12:08:02.806  3855  3855 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 12:08:02.816  7546  7561 D BluetoothBondStateMachine: make
,09-02 12:08:02.816  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:08:02.816  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-02 12:08:02.816  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-02 12:08:02.816  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 12:08:02.816  7546  7561 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-02 12:08:02.816  7546  7567 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 12:08:02.826  1017  2016 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:08:02.826  1017  2016 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.826  1017  2016 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:02.826  1017  2016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:02.826  1017  2016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:02.826  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 12:08:02.826  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 12:08:02.826  7546  7561 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 12:08:02.826  1017  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:08:02.826  7546  7546 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 12:08:02.826  7546  7546 D BtGatt.GattService: Received start request. Starting profile...
09-02 12:08:02.826  7546  7546 D BtGatt.GattService: start()
09-02 12:08:02.826  7546  7546 D BtGatt.GattService: start()
09-02 12:08:02.826  7546  7546 I bluedroid: get_profile_interface gatt
,09-02 12:08:02.826  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
09-02 12:08:02.826  7546  7546 D BtGatt.AdvertiseManager: advertise manager created
,09-02 12:08:02.836  1017  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.836  1017  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:02.836  1017  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:02.836  1017  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:02.836  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-02 12:08:02.836  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 12:08:02.836  7546  7561 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-02 12:08:02.836  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:08:02.836  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.836  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:02.836  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:02.836  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:02.846  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-02 12:08:02.846  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 12:08:02.846  7546  7561 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 12:08:02.846  1017  4395 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:08:02.846  1017  4395 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.846  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:02.846  1017  4395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:02.846  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:02.856  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-02 12:08:02.856  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 12:08:02.856  7546  7561 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 12:08:02.856  7546  7546 D BtGatt.GattService: mStartError = false
,09-02 12:08:02.856  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:08:02.856  7546  7546 D HeadsetService: Received start request. Starting profile...
,09-02 12:08:02.856  7546  7546 D HeadsetService: start()
,09-02 12:08:02.856  7546  7546 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 12:08:02.856  7546  7546 D HeadsetStateMachine: make
,09-02 12:08:02.866  1017  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:08:02.866  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-02 12:08:02.866  7546  7546 E HeadsetStateMachine: # of Max HF connection is 2
,09-02 12:08:02.866  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:02.866  1017  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:02.866  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:02.866  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-02 12:08:02.866  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 12:08:02.866  7546  7561 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 12:08:02.866  1017  1210 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-02 12:08:02.866  1017  1210 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.866  1017  1210 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:02.876  1017  1210 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:02.876  1017  1210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 12:08:02.876  1017  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:08:02.876  1017  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.876  1017  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:02.876  1017  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:08:02.876  1017  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:02.876  1017  1480 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-02 12:08:02.876  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.876  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:02.876  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:08:02.876  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 12:08:02.876  7546  7546 I bluedroid: get_profile_interface handsfree
09-02 12:08:02.876  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-02 12:08:02.876  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 12:08:02.876  7546  7561 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 12:08:02.876  1962  1962 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 12:08:02.886  1017  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:08:02.886  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.886  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:02.886  1017  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:02.886  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:02.886  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-02 12:08:02.886  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 12:08:02.886  7546  7561 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 12:08:02.886  1017  1212 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:08:02.886  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 12:08:02.886  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:02.886  1017  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:02.886  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:02.896  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:08:02.896  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:08:02.896  7546  7561 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 12:08:02.896  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:08:02.896  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:08:02.896  7546  7561 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 12:08:02.896  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 12:08:02.896  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 12:08:02.896  7546  7561 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 12:08:02.896  7546  7561 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-02 12:08:02.896  7546  7561 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 12:08:02.896  7546  7561 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 12:08:02.896  7546  7561 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-02 12:08:02.896  1962  1962 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 12:08:02.906  7546  7546 I DualScoManager: Instantiating Dual Sco Manager
,09-02 12:08:02.906  7546  7546 I DualScoManager: Set HeadsetServiceHelper
,09-02 12:08:02.906  7546  7546 D BluetoothAtMessage: createCMTIContentObservers
,09-02 12:08:02.906  1017  1029 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-02 12:08:02.906  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:02.906  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-02 12:08:02.906  1017  1029 D SettingsProvider: selectionArgs: false
09-02 12:08:02.906  1017  1029 D SettingsProvider: selectionArgs: 1002
,09-02 12:08:02.906  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:02.906  1017  1029 D SettingsProvider: ret = -1
,09-02 12:08:02.906  7546  7570 D HeadsetStateMachine: Enter Disconnected: -2
,09-02 12:08:02.906  7546  7546 D HeadsetService: mStartError = false
09-02 12:08:02.906  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:08:02.916  7546  7546 D A2dpService: Received start request. Starting profile...
09-02 12:08:02.916  7546  7546 D A2dpService: start()
,09-02 12:08:02.916  7546  7570 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-02 12:08:02.916  7546  7570 D HeadsetStateMachine: map size, before remove : 0
09-02 12:08:02.916  7546  7570 D HeadsetStateMachine: map size, after remove: 0
,09-02 12:08:02.916  7546  7546 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 12:08:02.916  7546  7546 I bluedroid: get_profile_interface avrcp
,09-02 12:08:02.926  7546  7546 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 12:08:02.926  7546  7546 D Avrcp   : Initialize Media Controller
09-02 12:08:02.926  7546  7546 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-02 12:08:02.926  7546  7546 E Avrcp   : getActiveSessions
,09-02 12:08:02.926  7546  7546 D Avrcp   : pick active media Controller
09-02 12:08:02.926  7546  7546 D Avrcp   : Get the active Media Controller 
,09-02 12:08:02.936  7546  7546 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-02 12:08:02.946  7546  7546 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 12:08:02.946  7546  7546 D A2dpStateMachine: make
,09-02 12:08:02.946  7546  7546 I bluedroid: get_profile_interface a2dp
,09-02 12:08:02.946  7546  7574 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-02 12:08:02.946  7546  7576 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 12:08:02.946  7546  7546 E bt-btif : warning : media task started media_task_refcnt 1 
,09-02 12:08:02.946  7546  7546 D A2dpService: mStartError = false
09-02 12:08:02.946  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:08:02.946  7546  7546 I BluetoothHidServiceJni: classInitNative: succeeds
,09-02 12:08:02.946  7546  7546 D HidService: Received start request. Starting profile...
09-02 12:08:02.946  7546  7546 D HidService: start()
09-02 12:08:02.946  7546  7546 I bluedroid: get_profile_interface hidhost
09-02 12:08:02.946  7546  7546 D HidService: setHidService(): set to: null
09-02 12:08:02.946  7546  7546 D HidService: mStartError = false
09-02 12:08:02.946  7546  7575 D A2dpStateMachine: Enter Disconnected: -2
09-02 12:08:02.946  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:08:02.946  7546  7546 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-02 12:08:02.956  7546  7546 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 12:08:02.956  7546  7546 D HealthService: Received start request. Starting profile...
09-02 12:08:02.956  7546  7546 D HealthService: start()
,09-02 12:08:02.956  7546  7546 I bluedroid: get_profile_interface health
09-02 12:08:02.956  7546  7546 D HealthService: mStartError = false
09-02 12:08:02.956  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:08:02.956  7546  7546 D HeadsetStateMachine: Try to query the phonestate on bind
,09-02 12:08:02.956  1432  1440 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 12:08:02.956  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-02 12:08:02.956  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-02 12:08:02.956  1432  1440 I Telecom : BluetoothPhoneService: Result of Message : true
,09-02 12:08:02.956  7546  7574 D BluetoothMediaBrowser: no now playing list
,09-02 12:08:02.956  7546  7574 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-02 12:08:02.956  7546  7546 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 12:08:02.966  7546  7546 D PanService: Received start request. Starting profile...
,09-02 12:08:02.966  7546  7546 D PanService: start()
09-02 12:08:02.966  7546  7546 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 12:08:02.966  7546  7546 I bluedroid: get_profile_interface pan
,09-02 12:08:02.966  7546  7546 D PanService: mStartError = false
09-02 12:08:02.966  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:08:02.966  7546  7546 D HeadsetStateMachine: Proxy object connected
09-02 12:08:02.966  7546  7546 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-02 12:08:02.966  7546  7570 D HeadsetStateMachine: Disconnected process message: 11
,09-02 12:08:02.966  7546  7546 D BluetoothMapService: Received start request. Starting profile...
,09-02 12:08:02.966  7546  7546 D BluetoothMapService: start()
,09-02 12:08:02.966  7546  7546 D BluetoothMapService: mStartError = false
09-02 12:08:02.966  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:08:02.966  7546  7546 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-02 12:08:02.966  7546  7546 D SapService: Received start request. Starting profile...
09-02 12:08:02.966  7546  7546 D SapService: start()
09-02 12:08:02.966  7546  7546 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-02 12:08:02.966  7546  7546 I bluedroid: get_profile_interface sap
09-02 12:08:02.966  7546  7546 D SapService: mStartError = false
09-02 12:08:02.966  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
09-02 12:08:02.976  7546  7546 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-02 12:08:02.976  7546  7570 D HeadsetStateMachine: Disconnected process message: 18
09-02 12:08:02.976  7546  7546 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-02 12:08:02.976  7546  7546 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-02 12:08:02.976  7546  7546 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-02 12:08:02.976  7546  7546 D BluetoothA2dp: Proxy object connected
09-02 12:08:02.976  7546  7546 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-02 12:08:02.976  7546  7546 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,09-02 12:08:02.976  7546  7546 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-02 12:08:02.976  7546  7546 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-02 12:08:02.976  7546  7546 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-02 12:08:02.976  7546  7570 D HeadsetStateMachine: Disconnected process message: 10
,09-02 12:08:02.976  7546  7570 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-02 12:08:02.976  7546  7570 D HeadsetStateMachine: Disconnected process message: 11
,09-02 12:08:02.996  7546  7546 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-02 12:08:02.996  7546  7546 E BluetoothAdapterService(844832561): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-02 12:08:02.996  7546  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-02 12:08:02.996  7546  7561 I bluedroid: enable
,09-02 12:08:02.996  7546  7580 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-02 12:08:02.996  7546  7561 I bt_hci_bdroid: init
,09-02 12:08:03.006  7546  7561 I bt_vendor: bt-vendor : init
09-02 12:08:03.006  7546  7561 I bt_vendor: bt-vendor : get_bt_soc_type
09-02 12:08:03.006  7546  7561 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-02 12:08:03.006  7546  7561 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-02 12:08:03.006  7546  7561 D bt_userial_mct: userial_init
,09-02 12:08:03.006  7546  7561 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-02 12:08:03.006  7546  7561 I bt_vendor: Starting hciattach daemon
09-02 12:08:03.006  7546  7561 I bt_vendor: try to set false
,09-02 12:08:03.006  7546  7561 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-02 12:08:03.006  7546  7561 I bt_vendor: Starting hciattach daemon
,09-02 12:08:03.006  7546  7561 I bt_vendor: try to set true
,09-02 12:08:03.016  7584  7584 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-02 12:08:03.066  7590  7590 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-02 12:08:03.066  7591  7591 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 12:08:03.086  7593  7593 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 12:08:03.096  7594  7594 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-02 12:08:03.106  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-02 12:08:03.106   295   295 E SMD     : DCD OFF
,09-02 12:08:03.116  7596  7596 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-02 12:08:03.156   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 12:08:03.326  7599  7599 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,09-02 12:08:03.336  7600  7600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-02 12:08:03.366  7546  7561 I bt_vendor: bluetooth satus is on,
,09-02 12:08:03.366  7546  7582 D bt_userial_mct: userial_open(port:0),
09-02 12:08:03.366  7546  7582 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-02 12:08:03.366  7546  7582 I bt_vendor: Done intiailizing UART
09-02 12:08:03.366  7546  7582 I bt_vendor: Done intiailizing UART
09-02 12:08:03.366  7546  7582 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-02 12:08:03.366  7546  7582 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-02 12:08:03.366  7546  7602 D bt_userial_mct: Entering userial_read_thread()
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_SAP
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_BTIF
09-02 12:08:03.376  7546  7580 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-02 12:08:03.466  7546  7580 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-02 12:08:03.466  7546  7580 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4168ed1 
,09-02 12:08:03.466  7546  7580 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4168ed1 
,09-02 12:08:03.486  7546  7564 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-02 12:08:03.486  7546  7564 E bt-btif : Calling BTA_HhEnable
,09-02 12:08:03.486  7546  7564 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-02 12:08:03.486  7546  7564 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-02 12:08:03.486  7546  7564 E BluetoothServiceJni: populateRssiValuesNative
09-02 12:08:03.486  7546  7564 I bluedroid: getModelRssiValues
,09-02 12:08:03.486  7546  7564 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-02 12:08:03.486  7546  7564 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 12:08:03.496  1017  1017 D SettingsProvider: name = bluetooth_name
,09-02 12:08:03.496  7546  7564 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-02 12:08:03.496  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:03.496  7546  7564 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-02 12:08:03.496  7546  7564 D BluetoothAdapterProperties: Scan Mode:20
,09-02 12:08:03.496  7546  7564 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 12:08:03.506  7546  7564 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,09-02 12:08:03.506  7546  7564 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1,
09-02 12:08:03.506  7546  7564 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-02 12:08:03.506  7546  7564 E bt-btif : btif_sock_init: !radio_req && !rfc_init,
09-02 12:08:03.506  7546  7564 E bt-btif : btif_sock_init: !vhci_init
,09-02 12:08:03.506  7546  7564 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-02 12:08:03.506  7546  7564 D IOP_DB_BT: db_open: db_open : handle 3028426768l, read 13894 bytes onto local cache
,09-02 12:08:03.506  7546  7564 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-02 12:08:03.506  7546  7602 E bt_mct  : hci lib postload completed
,09-02 12:08:03.506  7546  7564 D IOP_DB_BT: db_query: result 1
,09-02 12:08:03.506  7546  7564 I         : iop_db_open: iop_db_open status 0
,09-02 12:08:03.506  7546  7564 D bte_conf: Device ID record 1 : primary
,09-02 12:08:03.506  7546  7564 D bte_conf:   vendorId            = 0075
09-02 12:08:03.506  7546  7564 D bte_conf:   vendorIdSource      = 0001
,09-02 12:08:03.506  7546  7564 D bte_conf:   product             = 0100
09-02 12:08:03.506  7546  7564 D bte_conf:   version             = 0200
09-02 12:08:03.506  7546  7564 D bte_conf:   clientExecutableURL = 
09-02 12:08:03.506  7546  7564 D bte_conf:   serviceDescription  = 
09-02 12:08:03.506  7546  7564 D bte_conf:   documentationURL    = 
09-02 12:08:03.506  7546  7564 D bte_conf: bte_load_did_conf no section named DID2.
09-02 12:08:03.506  7546  7564 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 12:08:03.516  7546  7561 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-02 12:08:03.516  7546  7561 D BluetoothAdapterProperties: ScanMode =  20
,09-02 12:08:03.516  7546  7561 D BluetoothAdapterProperties: State =  11
,09-02 12:08:03.516  1017  1210 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 12:08:03.516  7546  7561 D BluetoothAdapterProperties: Setting state to 12
,09-02 12:08:03.516  7546  7561 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-02 12:08:03.526  7546  7564 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 12:08:03.526  7546  7564 D BluetoothAdapterProperties: Scan Mode:21
09-02 12:08:03.526  7546  7564 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 12:08:03.526  1017  4395 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-02 12:08:03.526  1017  4395 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:03.526  1017  4395 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:03.526  1017  4395 D SettingsProvider: selectionArgs: false
,09-02 12:08:03.526  1017  4395 D SettingsProvider: selectionArgs: 1002
09-02 12:08:03.526  1017  4395 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-02 12:08:03.526  1017  4395 D SettingsProvider: ret = -1
,09-02 12:08:03.526  7546  7561 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-02 12:08:03.526  7546  7561 D BluetoothAdapterService: updateAdapterState state is 12
,09-02 12:08:03.536  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:08:03.536  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.536  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:03.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:03.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:03.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:03.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:03.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:03.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:03.536  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:03.536  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:03.536  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:08:03.536  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.546  7546  7561 D BluetoothAdapterService: Autoconnection is available 
09-02 12:08:03.546  1017  1212 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 12:08:03.546  7546  7561 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-02 12:08:03.546  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-02 12:08:03.546  7546  7561 D BluetoothAdapterService: starting service from this receiver
09-02 12:08:03.546  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.546  1017  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.546  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 12:08:03.546  7546  7561 I BluetoothAdapterState: Entering On State from state = 11
09-02 12:08:03.556  1432  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:08:03.556  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 12:08:03.556  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 12:08:03.556  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.556  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.556  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.556  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:03.556  1432  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:08:03.556  3855  3863 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 12:08:03.576  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:03.576  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:03.576  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:03.576  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 12:08:03.576  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:03.576  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:03.576  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:03.576  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:03.576  7546  7546 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-02 12:08:03.576  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:03.576  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:03.576  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a679a75 added. We now have 8 listener(s)
,09-02 12:08:03.576  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:03.586  1017  1480 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 12:08:03.586  1017  1480 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 12:08:03.586  1017  1480 D SecContentProvider2: mCursor = null
,09-02 12:08:03.586  1017  1480 D WifiService: setWifiEnabled: false pid=6754, uid=10171
,09-02 12:08:03.586  1017  1480 D SettingsProvider: name = wifi_on
,09-02 12:08:03.596  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:03.596  1017  1500 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 12:08:03.596  1017  1500 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 12:08:03.596  1017  1500 D SecContentProvider2: mCursor = null
,09-02 12:08:03.596  1017  1500 D WifiService: setWifiEnabled: true pid=6754, uid=10171
,09-02 12:08:03.596  1017  1500 W ActivityManager: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-02 12:08:03.596  1017  1500 W WifiService: Failed getting userId using ActivityManagerNative
09-02 12:08:03.596  1017  1500 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6754, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-02 12:08:03.596  1017  1500 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 12:08:03.596  1017  1500 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 12:08:03.596  1017  1500 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 12:08:03.596  1017  1500 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 12:08:03.596  1017  1500 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 12:08:03.596  1017  1500 D SettingsProvider: name = wifi_on
,09-02 12:08:03.606  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,09-02 12:08:03.746  1017  1046 I art     : Explicit concurrent mark sweep GC freed 74940(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 24MB/36MB, paused 2.591ms total 178.662ms
09-02 12:08:03.746  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-02 12:08:03.746  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.746  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.746  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.746  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.746  3855  7511 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 12:08:03.746  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-02 12:08:03.746  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.756  7546  7546 I BluetoothPbapService: Handler(): got msg=1
,09-02 12:08:03.756  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.756  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.756  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.756  1017  1046 D BluetoothPan: Binding service...
,09-02 12:08:03.756  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 12:08:03.756  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.756  1017  1483 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 12:08:03.756  3855  6925 D Bluetoothsap: onBluetoothStateChange: up=true
,09-02 12:08:03.756  3855  6925 D Bluetoothsap: Binding service...
,09-02 12:08:03.756  3855  6925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-02 12:08:03.756  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-02 12:08:03.756  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.756  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.756  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.756  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.756  3855  6925 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-02 12:08:03.766  1962  2157 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 12:08:03.766  1962  2157 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:08:03.766  6754  6768 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:08:03.766  6754  6768 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:08:03.766  3855  3855 D BluetoothPbap: Proxy object connected
09-02 12:08:03.766  3855  3855 D PbapServerProfile: Bluetooth service connected
,09-02 12:08:03.766  7546  7555 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:08:03.766  7546  7555 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 12:08:03.766  3855  3855 D BluetoothInputDevice: Proxy object connected
,09-02 12:08:03.766  3855  3855 D HidProfile: Bluetooth service connected
09-02 12:08:03.766  7546  7609 V BluetoothPbapService: PBAP Service initSocket try: 0
09-02 12:08:03.766  1432  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:08:03.766  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 12:08:03.766  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-02 12:08:03.766  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 12:08:03.766  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.766  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.766  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.766  1432  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:08:03.766  7452  7469 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 12:08:03.766  7452  7469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:08:03.776  1457  1871 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:08:03.776  1457  1871 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 12:08:03.776  7546  7609 D BluetoothSocket: bindListen(): myUserId = 0
09-02 12:08:03.776  7546  7609 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 12:08:03.776  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:08:03.776  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 12:08:03.776  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-02 12:08:03.776  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 12:08:03.776  7546  7554 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:08:03.776  1432  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:08:03.776  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 12:08:03.776  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 12:08:03.776  7546  7609 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-02 12:08:03.776  7546  7609 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 12:08:03.776  7546  7609 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 12:08:03.776  7546  7609 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11254203
09-02 12:08:03.776  7546  7609 D BluetoothSocket: channel: 19
09-02 12:08:03.776  7546  7609 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-02 12:08:03.786  3855  3855 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-02 12:08:03.786  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.786  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.786  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-02 12:08:03.786  3855  3855 D SapProfile: Bluetooth service connected
,09-02 12:08:03.786  3855  3855 D Bluetoothsap: getConnectedDevices()
09-02 12:08:03.786  1432  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:08:03.786  1441  1456 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 12:08:03.786  1441  1456 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:08:03.786  3855  6925 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:08:03.786  3855  6925 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:08:03.786  3855  3864 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:08:03.786  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 12:08:03.786  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 12:08:03.786  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:03.786  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.786  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.796  3855  3855 D HeadsetProfile: Bluetooth service connected
09-02 12:08:03.796  3855  3864 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:08:03.796  1457  1479 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:08:03.796  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 12:08:03.796  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 12:08:03.796  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:03.796  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:08:03.796  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.806  1457  1479 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 12:08:03.806  1173  1993 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:08:03.806  1173  1993 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 12:08:03.806  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 12:08:03.806  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 12:08:03.806  3855  7511 D BluetoothPan: Binding service...
,09-02 12:08:03.806  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 12:08:03.806  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.806  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.806  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.806  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.806  3855  3863 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:08:03.806  3855  3855 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 12:08:03.806  3855  3855 D PanProfile: Bluetooth service connected
,09-02 12:08:03.806  3855  3863 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 12:08:03.806  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 12:08:03.806  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.806  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.806  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.806  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.816  3855  6925 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 12:08:03.816  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-02 12:08:03.816  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.816  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.816  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.816  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.816  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 12:08:03.816  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-02 12:08:03.816  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 12:08:03.816  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.816  1017  1017 D BluetoothA2dp: Proxy object connected
09-02 12:08:03.816  1432  3278 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 12:08:03.816  1432  3278 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 12:08:03.816  3855  3855 D BluetoothA2dp: Proxy object connected
09-02 12:08:03.816  3855  3855 D A2dpProfile: Bluetooth service connected
,09-02 12:08:03.816  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-02 12:08:03.816  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 12:08:03.816  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:08:03.816  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-02 12:08:03.816  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 12:08:03.826  1432  1432 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1410697c, true
,09-02 12:08:03.826  1432  1432 D BluetoothHeadset: registerMessageListener
,09-02 12:08:03.826  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-02 12:08:03.826  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 12:08:03.826  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:08:03.826  1173  1173 D BluetoothTile:  getBluetoothState : 12
,09-02 12:08:03.826  1915  1915 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 12:08:03.836  1017  1480 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 12:08:03.836  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:03.836  1017  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:08:03.836  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.836  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 12:08:03.836  3855  3855 D BluetoothMap: Proxy object connected
,09-02 12:08:03.836  7546  7554 D HeadsetService: registerMessageListener
,09-02 12:08:03.836  7546  7554 D HeadsetService: registerMessageListener
09-02 12:08:03.836  7546  7570 D HeadsetStateMachine: Disconnected process message: 70
09-02 12:08:03.836  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-02 12:08:03.836  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
09-02 12:08:03.836  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-02 12:08:03.836  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 12:08:03.846  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 12:08:03.846  7546  7570 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@384c3580
09-02 12:08:03.846  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.846  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 12:08:03.846  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 12:08:03.846  3855  3855 D MapProfile: Bluetooth service connected
09-02 12:08:03.846  3855  3855 D BluetoothMap: getConnectedDevices()
,09-02 12:08:03.846  1173  1732 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 12:08:03.846  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-02 12:08:03.846  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-02 12:08:03.846  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-02 12:08:03.846  3855  3855 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 12:08:03.846  3855  3855 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-02 12:08:03.846  3855  3855 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-02 12:08:03.846  3855  3855 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-02 12:08:03.846  3855  3855 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-02 12:08:03.846  7546  7570 D HeadsetStateMachine: Disconnected process message: 9
,09-02 12:08:03.846  7546  7570 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-02 12:08:03.856  7546  7618 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-02 12:08:03.856   290   726 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-02 12:08:03.856   290   726 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-02 12:08:03.856   290   726 V voice   : voice_set_parameters: exit with code(-2)
09-02 12:08:03.856   290   726 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-02 12:08:03.856   290   726 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-02 12:08:03.856   290   726 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-02 12:08:03.856   290   726 V audio_hw_primary: adev_set_parameters: exit
,09-02 12:08:03.856  7546  7570 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-02 12:08:03.856  3855  3855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 12:08:03.856  1017  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 12:08:03.856  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.866  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.866  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.866  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 12:08:03.866  7546  7618 D BluetoothSocket: bindListen(): myUserId = 0
,09-02 12:08:03.866  7546  7618 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:08:03.866  7546  7618 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-02 12:08:03.866  7546  7618 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 12:08:03.866  7546  7618 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 12:08:03.866  7546  7618 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11bff7b9
09-02 12:08:03.866  7546  7618 D BluetoothSocket: channel: 5
,09-02 12:08:03.876  3855  3855 D DockEventReceiver: finishStartingService: stopping service
,09-02 12:08:03.876  3855  3855 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 12:08:03.886  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 12:08:03.886  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-02 12:08:03.886  7546  7546 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31
,09-02 12:08:03.886  7546  7546 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 12:08:03.896  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 12:08:03.896  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.896  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:03.896  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:03.896  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 12:08:03.916  1962  1962 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-02 12:08:03.916  1017  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:08:03.916  1017  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-02 12:08:03.916  1017  1471 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:03.916  1017  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 12:08:03.916  1017  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:08:03.916  1962  7624 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-02 12:08:03.926  1962  1962 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-02 12:08:03.926  1017  1483 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 12:08:03.926  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:08:03.926  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:03.926  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:08:03.936  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:08:03.936  1017  1044 D Tethering: interfaceAdded wlan0
,09-02 12:08:03.946  1017  1130 E Tethering: No numeric data
,09-02 12:08:03.946  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 12:08:03.946  1017  1130 D Tethering: clearTetheredNotification()
,09-02 12:08:03.946  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:08:03.946  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:03.946  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 12:08:03.946  1173  1173 D HotspotTile: updateTetherState():false, false
09-02 12:08:03.946  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 12:08:03.946  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 12:08:03.946  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:08:03.946  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:08:03.946  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:08:03.956  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 12:08:03.956  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:03.956  1017  1044 D Tethering: interfaceAdded p2p0
09-02 12:08:03.956  1017  1130 D Tethering: InitialState.processMessage what=4
09-02 12:08:03.956  1017  1123 V NetworkStats: performPollLocked() took 8ms
09-02 12:08:03.956  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:03.956  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:08:03.956  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-02 12:08:03.956  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
09-02 12:08:03.956   278  1010 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-02 12:08:03.956  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 12:08:03.956   278  1010 D SoftapController: Softap fwReload - Ok
,09-02 12:08:03.956  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 12:08:03.956  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-02 12:08:03.956   278  1010 D CommandListener: Setting iface cfg
09-02 12:08:03.956  1017  1130 E Tethering: No numeric data
09-02 12:08:03.956   278  1010 D CommandListener: Trying to bring down wlan0
,09-02 12:08:03.956   278  1010 D CommandListener: Clearing all IP addresses on wlan0
,09-02 12:08:03.966  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-02 12:08:03.966  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
09-02 12:08:03.966  1017  1130 D Tethering: clearTetheredNotification()
,09-02 12:08:03.976  7546  7628 D BluetoothSocket: bindListen(): myUserId = 0,
,09-02 12:08:03.976  7546  7628 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 12:08:03.976  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:03.976  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:08:03.976  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 12:08:03.976  1173  1173 D HotspotTile: updateTetherState():false, false
,09-02 12:08:03.976  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:08:03.976  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:03.976  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:03.976  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 12:08:03.976  1962  7624 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-02 12:08:03.976  7546  7628 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-02 12:08:03.976  7546  7628 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 12:08:03.976  7546  7628 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 12:08:03.976  7546  7628 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2102ee7b
,09-02 12:08:03.976  7546  7628 D BluetoothSocket: channel: 12
09-02 12:08:03.976  7546  7628 I BtOppRfcommListener: Accept thread started.
,09-02 12:08:03.976  1017  1123 V NetworkStats: performPollLocked() took 5ms
,09-02 12:08:03.976  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:03.986  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:03.986  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:04.006  7630  7630 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-02 12:08:04.006  7630  7630 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 12:08:04.006  7630  7630 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-02 12:08:04.016  7630  7630 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-02 12:08:04.016   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7630
,09-02 12:08:04.016   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-02 12:08:04.026  7630  7630 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-02 12:08:04.026  7630  7630 I wpa_supplicant: ssSupport state is = 1
,09-02 12:08:04.026  7630  7630 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-02 12:08:04.026  7630  7630 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-02 12:08:04.026   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7630,
09-02 12:08:04.026   410   410 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-02 12:08:04.066  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-02 12:08:04.076  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:08:04.076  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 12:08:04.076  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:04.076  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:04.076  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:04.076  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:04.076  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:08:04.076  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-02 12:08:04.076  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:08:04.076  1173  1173 D HotspotTile: onReceive : 2, 0
,09-02 12:08:04.086  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 12:08:04.086  3855  3855 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:08:04.086  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:04.086  1017  1212 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 12:08:04.086  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:08:04.086  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:04.086  1017  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:04.086  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:08:04.096  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 12:08:04.096  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 12:08:04.096  1593  1593 I Hs20UtilService: Starting #19
,09-02 12:08:04.096  6582  6582 D SecurityLogAgent: StateMachine : Current State = 1
09-02 12:08:04.096  6582  6582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 12:08:04.096  1593  1636 I Hs20UtilService: Message received 5011
,09-02 12:08:04.156   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 12:08:04.196   410   410 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-02 12:08:04.196  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-02 12:08:04.236  7630  7630 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-02 12:08:04.236  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 12:08:04.246  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-02 12:08:04.246   410   410 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7630,
09-02 12:08:04.246   410   410 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 12:08:04.246  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 12:08:04.246  7630  7630 I wpa_supplicant: ssSupport state is = 1
09-02 12:08:04.256  7630  7630 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 12:08:04.256  7630  7630 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-02 12:08:04.256  7630  7630 E wpa_supplicant: SIM READ ERROR
09-02 12:08:04.256  7630  7630 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 12:08:04.256  7630  7630 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 12:08:04.256  7630  7630 E wpa_supplicant: SIM READ ERROR
09-02 12:08:04.256  7630  7630 I wpa_supplicant: Blacklist: Clear (all) 
09-02 12:08:04.256  7630  7630 I wpa_supplicant: wpa_default_ap_write_once,
09-02 12:08:04.256  7630  7630 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 12:08:04.256  7630  7630 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 12:08:04.256  7630  7630 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-02 12:08:04.256  7630  7630 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 12:08:04.256  7630  7630 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-02 12:08:04.256  7630  7630 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 12:08:04.256  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-02 12:08:04.256  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:08:04.256  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:08:04.366  7630  7630 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-02 12:08:04.496  7630  7630 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-02 12:08:04.496  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 12:08:04.506  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
09-02 12:08:04.506   410   410 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7630
09-02 12:08:04.506   410   410 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 12:08:04.506  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 12:08:04.506  7630  7630 I wpa_supplicant: ssSupport state is = 1
,09-02 12:08:04.506  7630  7630 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 12:08:04.506  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 12:08:04.526  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-02 12:08:04.526   410   410 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7630
09-02 12:08:04.526   410   410 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-02 12:08:04.526  7630  7630 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 12:08:04.526  7630  7630 I wpa_supplicant: ssSupport state is = 1
09-02 12:08:04.526  7630  7630 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 12:08:04.526  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 12:08:04.526  7630  7630 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 12:08:04.526  7630  7630 E wpa_supplicant: SIM READ ERROR
09-02 12:08:04.526  7630  7630 I wpa_supplicant: wpa_default_ap_write_once
09-02 12:08:04.526  7630  7630 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 12:08:04.526  7630  7630 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 12:08:04.526  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 12:08:04.526  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
09-02 12:08:04.526  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 12:08:04.526  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 12:08:04.526  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-02 12:08:04.556  1017  1042 W ProcessCpuTracker: Skipping unknown process pid 7633,
,09-02 12:08:04.646  7630  7630 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-02 12:08:04.646  7630  7630 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-02 12:08:04.706  1017  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 12:08:04.806  7630  7630 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-02 12:08:04.806  7630  7630 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-02 12:08:04.806  7630  7630 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 12:08:04.816  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-02 12:08:04.816  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 12:08:04.816  7630  7630 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-02 12:08:04.816  7630  7630 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 12:08:04.816  7630  7630 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 12:08:04.816  7630  7630 E wpa_supplicant: SIM READ ERROR
09-02 12:08:04.816  7630  7630 I wpa_supplicant: Blacklist: Clear (all) ,
,09-02 12:08:04.826  7630  7630 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-02 12:08:04.836  7630  7630 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 12:08:04.836  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,09-02 12:08:04.836  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:08:04.836  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:08:04.836  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:04.836  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:04.836  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:04.836  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:04.846  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 12:08:04.846  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-02 12:08:04.846  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 12:08:04.846  1173  1732 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 12:08:04.846  1173  1173 D HotspotTile: onReceive : 3, 0
,09-02 12:08:04.846  3855  3855 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 12:08:04.856  1017  1126 E WifiConfigStore: Not a HS20
,09-02 12:08:04.856  1017  4395 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 12:08:04.856  1017  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-02 12:08:04.856  1017  4395 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:08:04.856  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:04.856  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:04.856  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:04.856  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:04.856  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:04.856  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:04.856  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:04.856  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:04.856  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:04.856  1017  4395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:04.856  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:08:04.866  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-02 12:08:04.866  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:04.866  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-02 12:08:04.866  7630  7630 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-02 12:08:04.866  7630  7630 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 12:08:04.866  7630  7630 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 12:08:04.866  7630  7630 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 12:08:04.866  7630  7630 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-02 12:08:04.866  7630  7630 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-02 12:08:04.866  7630  7630 I wpa_supplicant: First Scan Start
09-02 12:08:04.866  7630  7630 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 12:08:04.866  1593  1593 I Hs20UtilService: Starting #20
,09-02 12:08:04.866  1593  1636 I Hs20UtilService: Message received 5011
,09-02 12:08:04.876  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,09-02 12:08:04.876  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 12:08:04.876  6959  6959 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 12:08:04.876  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 12:08:04.876  1017  1126 I WifiNative-HAL: startHal
09-02 12:08:04.876  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9d54588c
09-02 12:08:04.876  1017  1126 I WifiNative-HAL: Could not start hal
,09-02 12:08:04.876  6582  6582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-02 12:08:04.876  6582  6582 D SecurityLogAgent: StateMachine : Current State = 1
09-02 12:08:04.876  6582  6582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 12:08:04.876  1017  1126 E WifiNative-wlan0: do suspend true
,09-02 12:08:04.876  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-02 12:08:04.876   278  1010 D CommandListener: Setting iface cfg
09-02 12:08:04.876   278  1010 D CommandListener: Trying to bring up p2p0
,09-02 12:08:04.886  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 12:08:04.886  1017  1125 D WifiP2pService: P2pEnablingState
09-02 12:08:04.886  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-02 12:08:04.886  1017  1125 D WifiP2pService: P2p socket connection successful
09-02 12:08:04.886  1017  1125 D WifiP2pService: P2pEnabledState
,09-02 12:08:04.886  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-02 12:08:04.886  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-02 12:08:04.886  1017  1128 E ConnectivityService: updateNetworkInfo()
,09-02 12:08:04.886  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-02 12:08:04.886  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-02 12:08:04.886  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 12:08:04.896  1017  1047 D WifiDisplayController: disconnect
,09-02 12:08:04.896  1017  1047 D WifiDisplayController: updateConnection
09-02 12:08:04.896  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-02 12:08:04.896  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 12:08:04.896  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 12:08:04.896  1017  1126 E WifiNative-wlan0: invaild command id : 215
09-02 12:08:04.896  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 12:08:04.896  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 12:08:04.896  1017  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:08:04.896  1017  1149 I WifiNative-HAL: startHal
09-02 12:08:04.896  1017  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9eb019bc
09-02 12:08:04.896  1017  1149 I WifiNative-HAL: Could not start hal
09-02 12:08:04.896  1017  1149 E WifiScanningService: could not start HAL
09-02 12:08:04.896  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-02 12:08:04.896  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 12:08:04.896  1017  1126 E WifiNative-wlan0: invaild command id : 215
,09-02 12:08:04.896  7630  7630 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 12:08:04.896  7630  7630 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-02 12:08:04.896  1017  1017 D RttService: SCAN_AVAILABLE : 3
09-02 12:08:04.896  1017  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 12:08:04.896  7630  7630 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-02 12:08:04.906  1017  1126 E WifiStateMachine: Failed to set frequency band 0
,09-02 12:08:04.906  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:08:04.906  1017  1126 D SecContentProvider2: mCursor = null
09-02 12:08:04.906  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 12:08:04.906  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-02 12:08:04.906  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 12:08:04.906  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 12:08:04.906  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,09-02 12:08:04.916  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
09-02 12:08:04.916  1017  3339 D SSRM:n  : SIOP:: AP = 330
,09-02 12:08:04.916  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-02 12:08:04.916  1017  1480 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 12:08:04.916  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 12:08:04.916  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 12:08:04.916  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:08:04.916  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:08:04.916  1017  1125 D WifiP2pService: DeviceAddress: 0a:76:28
,09-02 12:08:04.916  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:08:04.916  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 12:08:04.926  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 12:08:04.926  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:08:04.926  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 12:08:04.926  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:08:04.926  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  secondary type: null
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  wps: 0
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  grpcapab: 0
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  devcapab: 0
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  status: 3
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  wfdInfo: null
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  groupownerAddress: null
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  GOdeviceName: null
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  interfaceAddress: 
09-02 12:08:04.926  1017  1047 D WifiDisplayController:  SConnectInfo : null
,09-02 12:08:04.936  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 12:08:04.936  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 12:08:04.936  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-02 12:08:04.936  7337  7337 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 12:08:04.936  7337  7337 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-02 12:08:04.936  7337  7337 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 12:08:04.946  7353  7353 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 12:08:04.946  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
09-02 12:08:04.946  1017  1125 D WifiP2pService: InactiveState
,09-02 12:08:04.946  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-02 12:08:04.946  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 12:08:04.946  7630  7630 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 12:08:04.946  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-02 12:08:04.946  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 12:08:05.156   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 12:08:05.626  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:05.626  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:05.626  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:05.626  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:05.626  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:05.626  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:05.626  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:05.626  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:05.636  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:05.636  6754  6808 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-02 12:08:05.636  6754  6808 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 12:08:05.636  6754  6808 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a5a5887 Bundle[{}]
,09-02 12:08:05.646  6754  6808 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 12:08:05.646  6754  6808 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-02 12:08:05.646  6754  6808 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-02 12:08:05.646  6754  6808 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 12:08:05.646  6754  6808 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-02 12:08:05.646  6754  6808 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 12:08:05.656  6754  6808 I System.out: Running OutgoingSocketThread
,09-02 12:08:05.656  6754  7640 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1350)
,09-02 12:08:05.656  6754  7640 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57703
,09-02 12:08:05.656  6754  7640 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-02 12:08:05.836  1017  2065 V SAMP_SPCM_test: CSC File load.. 
,09-02 12:08:05.846  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-02 12:08:05.846  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,09-02 12:08:05.846  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-02 12:08:05.846  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-02 12:08:05.856  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-02 12:08:05.886  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-02 12:08:05.886  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-02 12:08:05.896  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
,09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,09-02 12:08:05.906  1017  2065 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-02 12:08:05.906  1017  2065 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,09-02 12:08:05.916  1017  2065 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:05.916  1017  2065 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:05.916  1017  2065 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:05.916  1017  2065 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:05.926  7641  7641 E Zygote  : MountEmulatedStorage()
09-02 12:08:05.926  7641  7641 E Zygote  : v2
09-02 12:08:05.926  7641  7641 I libpersona: KNOX_SDCARD checking this for 1000
,09-02 12:08:05.926  7641  7641 I libpersona: KNOX_SDCARD not a persona
,09-02 12:08:05.936  7641  7641 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 12:08:05.936  7641  7641 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:08:05.936  1017  2065 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7641 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-02 12:08:05.936  7641  7641 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-02 12:08:05.966  7641  7641 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:05.966  7641  7641 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:05.986  7641  7641 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 12:08:06.036  1017  2065 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-02 12:08:06.106  7630  7630 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
,09-02 12:08:06.106  7630  7630 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
09-02 12:08:06.106  7630  7630 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-02 12:08:06.106  7630  7630 I wpa_supplicant: Trying to associate with  'G700'
09-02 12:08:06.106  7630  7630 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-02 12:08:06.106  7630  7630 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-02 12:08:06.106   295   295 E SMD     : DCD OFF
09-02 12:08:06.106  1017  7635 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-02 12:08:06.126  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:08:06.126  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:08:06.156   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 12:08:06.226  7630  7630 E wpa_supplicant: Cmd 35605 not handled
,09-02 12:08:06.226  7630  7630 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-02 12:08:06.226  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:08:06.226  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 12:08:06.226  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:08:06.226  7630  7630 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,09-02 12:08:06.226  7630  7630 I wpa_supplicant: Associated with F4.99.3E
,09-02 12:08:06.236  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 12:08:06.236  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 12:08:06.236  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
09-02 12:08:06.236  7630  7630 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 12:08:06.236  7630  7630 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-02 12:08:06.236  7630  7630 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-02 12:08:06.236  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 12:08:06.236  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 12:08:06.236  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-02 12:08:06.236  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 12:08:06.236  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:08:06.246  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-02 12:08:06.246  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 12:08:06.246  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-02 12:08:06.246  7630  7630 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 12:08:06.246  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 12:08:06.246  1017  1126 D SecContentProvider2: mCursor = null
09-02 12:08:06.246  7630  7630 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-02 12:08:06.246  7630  7630 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
09-02 12:08:06.246  1017  1130 E Tethering: No numeric data
09-02 12:08:06.246  7630  7630 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-02 12:08:06.246  7630  7630 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 12:08:06.246  7630  7630 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-02 12:08:06.256  7630  7630 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-02 12:08:06.256  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-02 12:08:06.256  7630  7630 I wpa_supplicant: Blacklist: Clear (temp) 
09-02 12:08:06.256  7630  7630 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-02 12:08:06.256  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,09-02 12:08:06.256  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
09-02 12:08:06.256  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 12:08:06.256  1017  1130 D Tethering: clearTetheredNotification()
,09-02 12:08:06.256  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-02 12:08:06.256  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:08:06.256  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:06.256  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 12:08:06.256  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:08:06.256  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 12:08:06.266  1173  1173 D HotspotTile: updateTetherState():false, false
,09-02 12:08:06.266  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,09-02 12:08:06.266  1017  1123 V NetworkStats: performPollLocked() took 9ms
,09-02 12:08:06.266  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:06.266  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-02 12:08:06.276  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-02 12:08:06.276  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:08:06.276  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-02 12:08:06.276  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:08:06.276  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:08:06.276  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:06.276  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:06.276  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:06.276  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:06.286  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:08:06.286  1017  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 12:08:06.286  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:06.286  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 12:08:06.286  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:06.286  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:08:06.286  1593  1593 I Hs20UtilService: Starting #21
09-02 12:08:06.286  1593  1636 I Hs20UtilService: Message received 5007
,09-02 12:08:06.286  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:06.286  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:06.296  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 12:08:06.296  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:08:06.296  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 12:08:06.296  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 12:08:06.296  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 12:08:06.296  3855  3855 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 12:08:06.296  3855  3945 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 12:08:06.296  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 12:08:06.316   278  1010 D CommandListener: Setting iface cfg
,09-02 12:08:06.316  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,09-02 12:08:06.316  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:08:06.316  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:08:06.326  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:08:06.326  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 12:08:06.336  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:06.336  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:06.336  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:06.336  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:06.336  1017  1126 E WifiNative-wlan0: do suspend false
,09-02 12:08:06.336  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-02 12:08:06.336  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
09-02 12:08:06.336  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 12:08:06.336  1017  1126 D SecContentProvider2: mCursor = null
,09-02 12:08:06.556  7659  7659 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-02 12:08:06.556  7659  7659 I dhcpcd  : version 5.5.6 starting
,09-02 12:08:06.566  7659  7659 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-02 12:08:06.616  7659  7659 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-02 12:08:06.616  7659  7659 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-02 12:08:06.616  7659  7659 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-02 12:08:06.616  7659  7659 I dhcpcd  : bssid match
09-02 12:08:06.616  7659  7659 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-02 12:08:06.656  6754  6808 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1351)
,09-02 12:08:06.656  6754  6808 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1351)
,09-02 12:08:06.656  6754  6808 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1356)
,09-02 12:08:06.656  6754  6808 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-02 12:08:06.656  6754  6808 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1357)
,09-02 12:08:06.666  7659  7659 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-02 12:08:06.666  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 12:08:06.666  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aaa9a0a added. We now have 2 listener(s)
,09-02 12:08:06.676  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-02 12:08:06.676  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:08:06.676  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:08:06.676  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:06.676  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ed27b added. We now have 9 listener(s)
,09-02 12:08:06.676  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:06.676  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:08:06.676  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:08:06.686  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:06.686  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:06.686  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:06.686  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:06.686  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:06.686  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:06.686  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:06.686  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:06.686  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:06.686  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 12:08:06.686  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.696  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:06.696  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a468f1 added. We now have 3 listener(s)
,09-02 12:08:06.696  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.696  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-02 12:08:06.696  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:08:06.696  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:08:06.696  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:06.696  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26604cd6 added. We now have 10 listener(s)
,09-02 12:08:06.696  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:06.696  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 12:08:06.696  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:08:06.696  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:06.706  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.706  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:06.706  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aaa9a0a removed from the list
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:06.706  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ed27b removed from the list
09-02 12:08:06.706  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:08:06.706  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:06.706  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.706  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:06.706  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ed27b not in the list
09-02 12:08:06.706  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.706  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:06.706  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26604cd6 removed from the list
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:06.706  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.706  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:06.706  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a468f1 removed from the list
09-02 12:08:06.706  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:06.706  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ee1b57 added. We now have 2 listener(s)
,09-02 12:08:06.706  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-02 12:08:06.706  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:06.706  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:06.706  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:06.706  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b005644 added. We now have 9 listener(s)
09-02 12:08:06.706  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:06.706  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:08:06.716  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:08:06.716  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:06.716  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:06.716  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:06.716  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:06.716  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:06.716  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:06.716  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:06.716  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:06.716  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 12:08:06.716  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:08:06.716  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:06.716  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29ec6062 added. We now have 3 listener(s)
,09-02 12:08:06.716  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.726  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.726  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-02 12:08:06.726  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 12:08:06.726  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:06.726  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 12:08:06.726  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccf15f3 added. We now have 10 listener(s)
09-02 12:08:06.726  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:06.726  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 12:08:06.726  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:08:06.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 12:08:06.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:08:06.726  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 12:08:06.736  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:08:06.736  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:08:06.736  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:08:06.736  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 12:08:06.736  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:08:06.736  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 12:08:06.746  7659  7659 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-02 12:08:06.746  7546  7555 D BtGatt.GattService: registerClient() - UUID=2d9fb484-fbd1-4b5a-94dd-69aca2660478,
,09-02 12:08:06.786  7546  7564 D BtGatt.GattService: onClientRegistered() - UUID=2d9fb484-fbd1-4b5a-94dd-69aca2660478, clientIf=6
,09-02 12:08:06.796  6754  6767 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
09-02 12:08:06.796  7546  7616 D BtGatt.GattService: start scan with filters
,09-02 12:08:06.796  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 12:08:06.796  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:08:06.796  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:08:06.796  7546  7569 D BtGatt.ScanManager: handling starting scan
09-02 12:08:06.796  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:08:06.796  7546  7569 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@325b1f31,
,09-02 12:08:06.806  7546  7564 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 12:08:06.806  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:06.806  7546  7569 D BtGatt.ScanManager: allow scan with filters
09-02 12:08:06.806  7546  7569 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 12:08:06.806  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:08:06.806  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:08:06.806  7546  7569 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-02 12:08:06.806  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:08:06.806  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:08:06.806  7546  7564 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 12:08:06.806  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:06.806  7546  7569 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:08:06.806  7546  7569 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 12:08:06.816  6754  6808 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 12:08:06.816  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 12:08:06.816  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 12:08:06.816  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:06.816  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-02 12:08:06.816  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 12:08:06.816  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:08:06.816  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:08:06.816  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:08:06.816  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 12:08:06.816  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:08:06.816  7546  7564 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-02 12:08:06.816  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:08:06.816  7546  7617 D BtGatt.GattService: stopScan() - queue size =1
,09-02 12:08:06.816  7546  7616 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 12:08:06.826  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 12:08:06.826  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,09-02 12:08:06.826  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
09-02 12:08:06.826  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:08:06.826  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 12:08:06.826  7546  7564 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 12:08:06.826  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:06.826  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:08:06.826  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:08:06.826  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 12:08:06.826  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:08:06.826  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:06.836  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:08:06.836  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:08:06.836  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:08:06.836  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:08:06.836  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:08:06.836  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:08:06.836  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:06.836  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 12:08:06.836  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:06.836  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:06.836  7546  7569 D BtGatt.ScanManager: filter size is 1
09-02 12:08:06.836  7546  7569 D BtGatt.ScanManager: delete FilterIndex - 3
09-02 12:08:06.836  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31ee1b57 removed from the list
09-02 12:08:06.836  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:06.836  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b005644 removed from the list
09-02 12:08:06.836  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 12:08:06.836  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:06.836  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.836  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:06.836  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:08:06.846  7546  7564 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 12:08:06.846  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:06.846  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:06.846  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:06.846  7546  7569 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:08:06.846  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b005644 not in the list
,09-02 12:08:06.846  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.846  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:06.846  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-02 12:08:06.846  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:06.846  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:08:06.846  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccf15f3 removed from the list
09-02 12:08:06.846  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:06.846  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.846  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:06.846  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:06.846  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29ec6062 removed from the list
09-02 12:08:06.846  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:06.846  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19bb1e4f added. We now have 2 listener(s)
09-02 12:08:06.846  7546  7564 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 12:08:06.846  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:06.846  7546  7569 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-02 12:08:06.846  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-02 12:08:06.846  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:06.846  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 12:08:06.846  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:06.846  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@380229dc added. We now have 9 listener(s)
09-02 12:08:06.846  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:06.846  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:08:06.856  7546  7564 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 12:08:06.856  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:06.856  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:08:06.856  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:06.856  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:06.856  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:06.856  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:06.856  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:06.856  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:06.856  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:06.856  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:06.856  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:08:06.856  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-02 12:08:06.866  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:06.866  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2599ba added. We now have 3 listener(s)
,09-02 12:08:06.866  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.876  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:06.876  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-02 12:08:06.876  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:06.876  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:06.876  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:06.876  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b5506b added. We now have 10 listener(s)
09-02 12:08:06.876  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:06.876  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:08:06.876  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:08:06.876  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:08:06.876  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:08:06.876  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:08:06.876  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 12:08:06.876  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:08:06.896  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 12:08:06.896  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:08:06.906  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 12:08:06.906  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:08:06.906  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 12:08:06.906  7546  7555 D BtGatt.GattService: registerClient() - UUID=916b6bcb-2f86-45f7-9ae9-6e8702536249
,09-02 12:08:06.946  7546  7564 D BtGatt.GattService: onClientRegistered() - UUID=916b6bcb-2f86-45f7-9ae9-6e8702536249, clientIf=6
,09-02 12:08:06.946  6754  6767 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 12:08:06.946  7546  7617 D BtGatt.GattService: start scan with filters
,09-02 12:08:06.946  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 12:08:06.946  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 12:08:06.946  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 12:08:06.946  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 12:08:06.956  7546  7569 D BtGatt.ScanManager: handling starting scan,
09-02 12:08:06.956  1017  1126 E WifiNative-wlan0: do suspend true
09-02 12:08:06.956  7546  7564 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 12:08:06.956  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:06.956  7546  7569 D BtGatt.ScanManager: allow scan with filters
09-02 12:08:06.956  7546  7569 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 12:08:06.956  7546  7569 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-02 12:08:06.956  7546  7564 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 12:08:06.956  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:06.956  7546  7569 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:08:06.956  7546  7569 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 12:08:06.956  7546  7564 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 12:08:06.956  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:08:06.956  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:08:06.956  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 12:08:06.956  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:08:06.966  7546  7564 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 12:08:06.966  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:08:06.966  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:08:06.966  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 12:08:06.966  6754  6808 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-02 12:08:06.966  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:08:06.966  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:08:06.966  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:08:06.966  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:06.966  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.966  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:08:06.966  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:06.966  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19bb1e4f removed from the list
09-02 12:08:06.966  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:06.966  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@380229dc removed from the list
09-02 12:08:06.966  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:08:06.966  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:08:06.976  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.976  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-02 12:08:06.976  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:06.976  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 12:08:06.976  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 12:08:06.976  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:06.976  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 12:08:06.976  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@380229dc not in the list
,09-02 12:08:06.976  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:08:06.976  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 12:08:06.976  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 12:08:06.976  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 12:08:06.976  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 12:08:06.976  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-02 12:08:06.976  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 12:08:06.986  1017  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 12:08:06.986  1017  1126 E WifiStateMachine: VerifyingLinkState enter
,09-02 12:08:06.986  7546  7565 D BtGatt.GattService: stopScan() - queue size =1
,09-02 12:08:06.986  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:08:06.986  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:08:06.986  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:06.986  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:06.986  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:06.986  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:06.986  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:08:06.986  7546  7569 D BtGatt.ScanManager: filter size is 1
,09-02 12:08:06.986  7546  7569 D BtGatt.ScanManager: delete FilterIndex - 4
,09-02 12:08:06.996  7546  7564 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 12:08:06.996  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:08:06.996  7546  7569 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:08:06.996  7546  7555 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 12:08:06.996  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 12:08:06.996  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:08:06.996  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:08:06.996  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:08:06.996  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 12:08:06.996  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null,
09-02 12:08:06.996  1017  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-02 12:08:06.996  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 12:08:06.996  7546  7564 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 12:08:06.996  1017  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 12:08:06.996  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:08:06.996  1017  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-02 12:08:06.996  7546  7569 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 12:08:07.006  1017  1128 D ConnectivityService: Adding iface wlan0 to network 504,
,09-02 12:08:07.006  1017  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-02 12:08:07.006  1017  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-02 12:08:07.006  7546  7564 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
,09-02 12:08:07.006  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:07.006  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 12:08:07.006  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:08:07.006  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 12:08:07.016  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:08:07.016  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:08:07.016  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.016  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.016  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:07.016  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:07.016  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:07.016  1017  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-02 12:08:07.026  1017  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,09-02 12:08:07.026  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 12:08:07.026  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 12:08:07.026  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:07.026  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 12:08:07.026  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:08:07.026  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 12:08:07.026  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:08:07.026  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:07.026  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 12:08:07.026  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:08:07.026  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b5506b removed from the list
09-02 12:08:07.026  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:07.026  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:07.026  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:07.026  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:07.026  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2599ba removed from the list
09-02 12:08:07.036  1593  1593 I Hs20UtilService: Starting #22
09-02 12:08:07.036  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:07.036  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d68847 added. We now have 2 listener(s)
09-02 12:08:07.036  1593  1636 I Hs20UtilService: Message received 5007
09-02 12:08:07.036  1017  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-02 12:08:07.036  1017  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-02 12:08:07.036  1017  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-02 12:08:07.036  1017  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 12:08:07.036  1017  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-02 12:08:07.036  1017  1128 D ConnectivityService: LTETest block dns file not exists
,09-02 12:08:07.036  1017  1128 V NetworkStats: updateIfacesLocked()
09-02 12:08:07.036  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:07.036  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:08:07.046  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:08:07.046  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 12:08:07.046  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 12:08:07.046  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-02 12:08:07.046  1017  1128 V NetworkStats: performPollLocked() took 4ms
09-02 12:08:07.046  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:07.046  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:07.046  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:07.046  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:07.046  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ec7d874 added. We now have 9 listener(s)
09-02 12:08:07.046  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:07.056  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-02 12:08:07.056  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:08:07.056  1017  1128 E ConnectivityService: updateNetworkInfo()
09-02 12:08:07.056  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-02 12:08:07.056  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:07.056  1017  1128 V NetworkStats: updateIfacesLocked()
09-02 12:08:07.056  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:08:07.056  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:08:07.056  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 12:08:07.056  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 12:08:07.056  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 12:08:07.056  3855  3855 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-02 12:08:07.056  1017  1128 V NetworkStats: performPollLocked() took 6ms
,09-02 12:08:07.056  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:07.066  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:08:07.066  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 12:08:07.066  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:07.066  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.066  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.066  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.066  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:07.066  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:07.066  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 12:08:07.066  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 12:08:07.066  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-02 12:08:07.066  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
09-02 12:08:07.066  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,09-02 12:08:07.076  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:08:07.076  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 12:08:07.076  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:07.076  1017  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-02 12:08:07.076  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-02 12:08:07.076  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:08:07.076  1017  7657 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:08:07.076  1017  7657 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-02 12:08:07.076  1017  7657 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 12:08:07.076  1017  7657 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-02 12:08:07.076  1017  7657 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 12:08:07.076  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.076  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.076  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:07.076  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:07.076  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:07.076   278  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-02 12:08:07.076   278  1006 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-02 12:08:07.076  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:07.076  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:07.076  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:07.076  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:07.076  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:07.076  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:07.076  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:07.076  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 12:08:07.076  1017  1128 D ConnectivityService:    accepting network in place of null
09-02 12:08:07.076  1457  1457 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-02 12:08:07.076  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 12:08:07.076  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:08:07.076  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-02 12:08:07.076  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:07.076  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d71a612 added. We now have 3 listener(s)
,09-02 12:08:07.076  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 12:08:07.076  1457  1457 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 12:08:07.086  1017  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 12:08:07.086  1017  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,09-02 12:08:07.086  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-02 12:08:07.086  1017  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-02 12:08:07.086  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-02 12:08:07.086  1017  1130 D Tethering: MasterInitialState.processMessage what=3
,09-02 12:08:07.086  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-02 12:08:07.086  1017  1123 V NetworkStats: updateIfacesLocked()
09-02 12:08:07.086  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:07.086  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
09-02 12:08:07.086  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:08:07.086  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 12:08:07.096  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:07.096  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:07.096  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:07.096  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:07.096  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:07.096  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 12:08:07.096  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 12:08:07.096  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:08:07.096  1017  1123 V NetworkStats: performPollLocked() took 3ms
09-02 12:08:07.096  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:07.096  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-02 12:08:07.096  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:07.096  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:07.096  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:07.096  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2de961e3 added. We now have 10 listener(s)
09-02 12:08:07.096  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:07.096  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:08:07.096  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 12:08:07.096  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 12:08:07.096  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 12:08:07.096  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 12:08:07.096  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-02 12:08:07.096  1173  1707 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 12:08:07.096  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-02 12:08:07.096  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-02 12:08:07.096  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 12:08:07.096  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-02 12:08:07.096  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-02 12:08:07.096  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-02 12:08:07.096  4753  6819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 12:08:07.106  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
09-02 12:08:07.106  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:07.106  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-02 12:08:07.106  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:07.106  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:07.106  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:07.106  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:07.106  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 12:08:07.106  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:07.106  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:07.106  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-02 12:08:07.106  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:07.106  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:07.106  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:07.106  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:08:07.116  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:08:07.116  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-02 12:08:07.116  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-02 12:08:07.116  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-02 12:08:07.116  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 12:08:07.116  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 12:08:07.116  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 12:08:07.116  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 12:08:07.116  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.116  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.116  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:07.116  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:07.116  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:07.116  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:07.116  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 12:08:07.116  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 12:08:07.116  1593  1593 I Hs20UtilService: Starting #23
09-02 12:08:07.116  1593  1636 I Hs20UtilService: Message received 5007
,09-02 12:08:07.116  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 12:08:07.116  3855  3855 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 12:08:07.116  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-02 12:08:07.116  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 12:08:07.116  3855  3855 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-02 12:08:07.116  3855  3855 I NearbySettings: MountReceiver.onReceive - Keep current state
09-02 12:08:07.126  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 12:08:07.126  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 12:08:07.126  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 12:08:07.126  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 12:08:07.126  6754  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 12:08:07.126  1017  1212 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 12:08:07.126  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 12:08:07.126  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:07.126  1017  1212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:07.126  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 12:08:07.126  1593  1593 I Hs20UtilService: Starting #24
09-02 12:08:07.136  1593  1636 I Hs20UtilService: Message received 5007
,09-02 12:08:07.136  7546  7555 D BtGatt.GattService: registerClient() - UUID=17aaaaf4-ad2f-4d24-b431-cf98e34ad1ca
09-02 12:08:07.136  3855  3855 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 12:08:07.136  3855  3855 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-02 12:08:07.136  1017  1212 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-02 12:08:07.146  1017  1480 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,09-02 12:08:07.146  1017  1480 D SecContentProvider2: mCursor = null
,09-02 12:08:07.146  1017  1029 D SecContentProvider2: uri = 15 selection = getToastGravity
,09-02 12:08:07.146  1017  1029 D SecContentProvider2: mCursor = null
,09-02 12:08:07.146  1017  1481 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-02 12:08:07.146  1017  1481 D SecContentProvider2: mCursor = null
,09-02 12:08:07.146  1017  1383 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,09-02 12:08:07.146  1017  1383 D SecContentProvider2: mCursor = null
,09-02 12:08:07.156  1017  1483 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-02 12:08:07.156  1017  1483 D SecContentProvider2: mCursor = null
,09-02 12:08:07.156  1017  4395 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,09-02 12:08:07.156  1017  4395 D SecContentProvider2: mCursor = null
,09-02 12:08:07.156   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-02 12:08:07.176  7546  7564 D BtGatt.GattService: onClientRegistered() - UUID=17aaaaf4-ad2f-4d24-b431-cf98e34ad1ca, clientIf=6,
09-02 12:08:07.176  6754  6768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-02 12:08:07.176  7546  7616 D BtGatt.GattService: start scan with filters
,09-02 12:08:07.176  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 12:08:07.176  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
09-02 12:08:07.176  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 12:08:07.176  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 12:08:07.176  7546  7569 D BtGatt.ScanManager: handling starting scan
09-02 12:08:07.176  7546  7564 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-02 12:08:07.176  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:07.176  7546  7569 D BtGatt.ScanManager: allow scan with filters
,09-02 12:08:07.176  7546  7569 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 12:08:07.176  7546  7569 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-02 12:08:07.176  7546  7564 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 12:08:07.176  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:08:07.176  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 12:08:07.176  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 12:08:07.176  7546  7569 D BtGatt.ScanManager: Starting BLE batch scan
09-02 12:08:07.176  7546  7569 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-02 12:08:07.186  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 12:08:07.186   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
09-02 12:08:07.186  7546  7564 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-02 12:08:07.186  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 12:08:07.186  7546  7564 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-02 12:08:07.186  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:07.186  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 12:08:07.196  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-02 12:08:07.196  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:08:07.196  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:07.196  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 12:08:07.196  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28d68847 removed from the list
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:07.196  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ec7d874 removed from the list
09-02 12:08:07.196  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:07.196  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 12:08:07.196  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:07.196  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ec7d874 not in the list
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 12:08:07.196  7546  7617 D BtGatt.GattService: stopScan() - queue size =1
09-02 12:08:07.196  7546  7569 D BtGatt.ScanManager: filter size is 1
09-02 12:08:07.196  7546  7565 D BtGatt.GattService: unregisterClient() - clientIf=6
09-02 12:08:07.196  7546  7569 D BtGatt.ScanManager: delete FilterIndex - 5
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 12:08:07.196  7546  7564 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 12:08:07.196  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:07.196  7546  7569 D BtGatt.ScanManager: stopping BLe Batch
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:07.196  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:08:07.196  6754  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 12:08:07.196  6754  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:07.196  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2de961e3 removed from the list
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:07.196  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:07.196  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:07.196  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:07.196  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d71a612 removed from the list
09-02 12:08:07.196  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:07.196  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fc6393f added. We now have 2 listener(s)
,09-02 12:08:07.206  7546  7564 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 12:08:07.206  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:07.206  7546  7569 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 12:08:07.206  7546  7564 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 12:08:07.206  7546  7564 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 12:08:07.206  1017  1483 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
09-02 12:08:07.206  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-02 12:08:07.206  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:07.206  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:07.206  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:07.206  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1291c20c added. We now have 9 listener(s)
09-02 12:08:07.206  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 12:08:07.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 12:08:07.206  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 12:08:07.216  6754  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 12:08:07.216  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:07.216  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:07.216  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:07.216  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:07.216  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:07.216  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:07.216  6754  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 12:08:07.216  6754  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 12:08:07.216  6754  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 12:08:07.216  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 12:08:07.216  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7e56a added. We now have 3 listener(s)
,09-02 12:08:07.216  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-02 12:08:07.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-02 12:08:07.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 12:08:07.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 12:08:07.216  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 12:08:07.216  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@126f2a5b added. We now have 10 listener(s)
09-02 12:08:07.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 12:08:07.216  6754  6808 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 12:08:07.216  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 12:08:07.216  6754  6808 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 12:08:07.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:07.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:07.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 12:08:07.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:07.216  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fc6393f removed from the list
09-02 12:08:07.216  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:07.216  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1291c20c removed from the list
,09-02 12:08:07.216  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 12:08:07.216  6754  6808 D io.jxcore.node.ConnectivityMonitor: stop
09-02 12:08:07.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:07.216  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:07.216  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:07.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:07.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:07.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:07.226  6754  6808 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1291c20c not in the list
09-02 12:08:07.226  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:07.226  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 12:08:07.226  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 12:08:07.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 12:08:07.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 12:08:07.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 12:08:07.226  6754  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@126f2a5b removed from the list
09-02 12:08:07.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 12:08:07.226  6754  6808 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 12:08:07.226  6754  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 12:08:07.226  6754  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 12:08:07.226  6754  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7e56a removed from the list
,09-02 12:08:07.226  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-02 12:08:07.226  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 12:08:07.226  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-02 12:08:07.226  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 12:08:07.226  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 12:08:07.226  6754  6808 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 12:08:07.236  6754  7696 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1364, name: My test thread name)
,09-02 12:08:07.236  6754  7696 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1364, thread name: My test thread name)
,09-02 12:08:07.236  6754  7696 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1364, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 12:08:07.236  6754  7697 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1366, name: My test thread name)
,09-02 12:08:07.236  6754  7697 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1366, thread name: My test thread name)
09-02 12:08:07.236  6754  7697 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1366, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 12:08:07.236  6754  6808 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-02 12:08:07.236  6754  6808 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 12:08:07.236  6754  6808 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 12:08:07.236  6754  6808 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 12:08:07.236  6754  6808 D com.test.thalitest.ThaliTestRunner: Total duration: 23546 ms
09-02 12:08:07.236  6754  6808 I jxcore-log: *Native tests were executed*
09-02 12:08:07.236  6754  6808 I jxcore-log: 
09-02 12:08:07.236  6754  6808 I jxcore-log: Total number of executed tests:  80
09-02 12:08:07.236  6754  6808 I jxcore-log: 
09-02 12:08:07.236  6754  6808 I jxcore-log: Number of passed tests:  80
09-02 12:08:07.236  6754  6808 I jxcore-log: 
09-02 12:08:07.236  6754  6808 I jxcore-log: Number of failed tests:  0
09-02 12:08:07.236  6754  6808 I jxcore-log: 
09-02 12:08:07.236  6754  6808 I jxcore-log: Number of ignored tests:  0
09-02 12:08:07.236  6754  6808 I jxcore-log: 
09-02 12:08:07.236  6754  6808 I jxcore-log: Total duration:  23546
09-02 12:08:07.236  6754  6808 I jxcore-log: 
09-02 12:08:07.246  6754  6808 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 12:08:07.246  6754  6808 I jxcore-log: 
,09-02 12:08:07.246  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.246  6754  6808 I jxcore-log: 
09-02 12:08:07.246  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.246  6754  6808 I jxcore-log: 
09-02 12:08:07.256  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.256  6754  6808 I jxcore-log: 
09-02 12:08:07.256  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.256  6754  6808 I jxcore-log: 
09-02 12:08:07.256  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.256  6754  6808 I jxcore-log: 
09-02 12:08:07.256  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.256  6754  6808 I jxcore-log: 
09-02 12:08:07.256  6754  6754 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 12:08:07.256  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.256  6754  6808 I jxcore-log: 
,09-02 12:08:07.256  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.256  6754  6808 I jxcore-log: 
,09-02 12:08:07.256  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:08:07.256  6754  6808 I jxcore-log: 
,09-02 12:08:07.256  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.256  6754  6808 I jxcore-log: 
,09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.266  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:08:07.266  6754  6808 I jxcore-log: 
09-02 12:08:07.276  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.276  6754  6808 I jxcore-log: 
09-02 12:08:07.276  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 12:08:07.276  6754  6808 I jxcore-log: 
09-02 12:08:07.276  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.276  6754  6808 I jxcore-log: 
,09-02 12:08:07.336  6754  6754 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-02 12:08:07.336  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:08:07.336  6754  6808 I jxcore-log: 
,09-02 12:08:07.526  6754  6754 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:08:07.526  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:08:07.526  6754  6808 I jxcore-log: 
,09-02 12:08:07.536  7698  7698 D AndroidRuntime: 
09-02 12:08:07.536  7698  7698 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-02 12:08:07.536  7698  7698 D AndroidRuntime: CheckJNI is OFF
,09-02 12:08:07.536  7698  7698 D AndroidRuntime: readGMSProperty: start
09-02 12:08:07.536  7698  7698 D AndroidRuntime: readGMSProperty: already setted!!
09-02 12:08:07.536  7698  7698 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-02 12:08:07.536  7698  7698 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-02 12:08:07.536  7698  7698 D AndroidRuntime: readGMSProperty: end
09-02 12:08:07.536  7698  7698 D AndroidRuntime: addProductProperty: start,
,09-02 12:08:07.586  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:07.616  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-02 12:08:07.616  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 12:08:07.616  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 12:08:07.616  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 12:08:07.616  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 12:08:07.616  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:07.616  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 12:08:07.616  6754  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 12:08:07.616  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-02 12:08:07.616  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.616  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.616  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.616  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:07.616  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:07.616  6754  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 12:08:07.616  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 12:08:07.616  6754  6808 I jxcore-log: 
,09-02 12:08:07.626  7706  7706 E Zygote  : MountEmulatedStorage()
,09-02 12:08:07.626  7706  7706 E Zygote  : v2
09-02 12:08:07.626  7706  7706 I libpersona: KNOX_SDCARD checking this for 1000
09-02 12:08:07.626  7706  7706 I libpersona: KNOX_SDCARD not a persona
,09-02 12:08:07.626  7706  7706 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:08:07.626  1017  1042 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7706 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-02 12:08:07.636  7706  7706 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-02 12:08:07.636  7706  7706 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:08:07.656  1017  4394 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-02 12:08:07.656  1017  4394 D SecContentProvider2: mCursor = null
,09-02 12:08:07.666  7706  7706 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 12:08:07.666  7706  7706 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:07.666  7698  7698 E AffinityControl: AffinityControl: registerfunction enter
,09-02 12:08:07.686  7706  7706 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-02 12:08:07.686  7706  7706 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-02 12:08:07.686  7706  7706 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-02 12:08:07.696  7698  7698 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 12:08:07.696  6754  6754 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 12:08:07.696  6754  6808 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 12:08:07.696  6754  6808 I jxcore-log: 
,09-02 12:08:07.706  7706  7706 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-02 12:08:07.706  7706  7706 I PCWCLIENTTRACE_PushUtil: sales region : global
09-02 12:08:07.706  7706  7706 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-02 12:08:07.706  7706  7706 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:07.706  1017  1212 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
09-02 12:08:07.706  1017  1212 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-02 12:08:07.706  1017  1476 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-02 12:08:07.706  1017  1476 D PackageManager: START PACKAGE DELETE: observer{382587360}
09-02 12:08:07.706  1017  1476 D PackageManager: pkg{<packageName>}
09-02 12:08:07.706  1017  1476 D PackageManager: user{0}
09-02 12:08:07.706  1017  1476 D PackageManager: caller{2000}
09-02 12:08:07.706  1017  1476 D PackageManager: flags{2}
09-02 12:08:07.706  1017  1476 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-02 12:08:07.706  1017  1476 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-02 12:08:07.706  1017  1476 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-02 12:08:07.706  1017  1476 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-02 12:08:07.716  1017  1212 I ActivityManager: Killing 7074:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-02 12:08:07.726  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-02 12:08:07.726  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-02 12:08:07.726  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-02 12:08:07.726  1017  4395 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-02 12:08:07.726  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
09-02 12:08:07.726  1017  4395 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
09-02 12:08:07.726  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-02 12:08:07.726  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:07.726  1017  4395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:07.726  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-02 12:08:07.726  1017  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-02 12:08:07.726  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-02 12:08:07.726  1785  1785 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-02 12:08:07.726  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.726  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.726  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.726  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:07.746  7724  7724 E Zygote  : MountEmulatedStorage()
,09-02 12:08:07.746  7724  7724 E Zygote  : v2
09-02 12:08:07.746  7724  7724 I libpersona: KNOX_SDCARD checking this for 10121
09-02 12:08:07.746  7724  7724 I libpersona: KNOX_SDCARD not a persona
,09-02 12:08:07.746  7724  7724 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:08:07.746  1017  1042 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7724 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-02 12:08:07.746  7724  7724 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:08:07.746  7724  7724 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:08:07.766   314   314 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.353ms total 22.372ms
,09-02 12:08:07.776  7724  7724 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-02 12:08:07.776  7724  7724 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:07.786   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 18.718ms
,09-02 12:08:07.806   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 629us total 24.085ms,
,09-02 12:08:07.826  1017  1056 W PackageSettings: Skipping PackageSetting{e70f8e6 com.example.hello/10168} due to missing metadata
,09-02 12:08:07.856  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-02 12:08:07.856  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:07.856  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.856  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.856  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:07.866  7739  7739 E Zygote  : MountEmulatedStorage()
,09-02 12:08:07.866  7739  7739 E Zygote  : v2
09-02 12:08:07.866  7739  7739 I libpersona: KNOX_SDCARD checking this for 10001
09-02 12:08:07.866  7739  7739 I libpersona: KNOX_SDCARD not a persona
,09-02 12:08:07.866  7739  7739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:08:07.876  7739  7739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-02 12:08:07.876  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7739 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-02 12:08:07.876  7739  7739 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:08:07.886  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,09-02 12:08:07.886  1017  1042 I ActivityManager: Killing 6754:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-02 12:08:07.886  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{1703a48b u0 com.test.thalitest/.MainActivity t2}
,09-02 12:08:07.896  1017  1042 D InputDispatcher: Focus left window: 6754
,09-02 12:08:07.896   258  6013 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
09-02 12:08:07.896   258   438 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-02 12:08:07.916  1017  1042 D InputDispatcher: Focused application released
09-02 12:08:07.916  1017  1042 D FocusedStackFrame: Set to : 0
09-02 12:08:07.916  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 12:08:07.916  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 12:08:07.926  1017  1042 W ActivityManager: mDVFSHelper.acquire()
,09-02 12:08:07.926  7739  7739 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-02 12:08:07.926  7739  7739 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:07.926  1017  1042 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-02 12:08:07.946  1017  1212 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-02 12:08:07.946  2489  2498 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,09-02 12:08:07.946  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.946  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:07.946  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:07.946  1017  1212 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:07.966  1484  1484 D Launcher: onRestart, Launcher: 739343725,
,09-02 12:08:07.966  7754  7754 E Zygote  : MountEmulatedStorage()
,09-02 12:08:07.966  7754  7754 E Zygote  : v2
09-02 12:08:07.966  7754  7754 I libpersona: KNOX_SDCARD checking this for 10031
09-02 12:08:07.966  7754  7754 I libpersona: KNOX_SDCARD not a persona
,09-02 12:08:07.966  7754  7754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:08:07.966  7754  7754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-02 12:08:07.966  1017  1212 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7754 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-02 12:08:07.966  7754  7754 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:08:07.976  1484  1484 D Launcher: onStart, Launcher: 739343725
,09-02 12:08:07.976  1484  1484 D Launcher.HomeView: onStart
09-02 12:08:07.976  1484  1484 D Launcher: onResume, Launcher: 739343725
,09-02 12:08:07.986  1017  4396 D SettingsProvider: name = kids_home_mode
09-02 12:08:07.986  1017  4396 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 12:08:07.986  1017  4396 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 12:08:07.986  1017  4396 D SettingsProvider: selectionArgs: false
09-02 12:08:07.986  1017  4396 D SettingsProvider: selectionArgs: 10006
09-02 12:08:07.986  1017  4396 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 12:08:07.986  1017  4396 D SettingsProvider: ret = -1
,09-02 12:08:07.986  1017  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
09-02 12:08:07.986  1484  1484 D Launcher.HomeView: onResume
,09-02 12:08:07.986  1785  1785 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-02 12:08:07.986  1785  1785 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-02 12:08:07.986  1785  1785 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-02 12:08:07.986  1785  1785 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-02 12:08:07.996  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-02 12:08:08.016  7754  7754 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:08.016  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
09-02 12:08:08.016  7754  7754 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:08.026  7724  7724 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 12:08:08.026  7724  7724 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 12:08:08.026  7724  7724 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 12:08:08.046  1785  1785 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-02 12:08:08.046  2640  2640 I art     : Explicit concurrent mark sweep GC freed 19872(1134KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 996us total 48.562ms
,09-02 12:08:08.056  1785  1785 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-02 12:08:08.066  1484  1484 D MenuAppsGridFragment: onResume
,09-02 12:08:08.066  1484  1484 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
09-02 12:08:08.066  1484  1484 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-02 12:08:08.086  1017  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-02 12:08:08.096  7724  7724 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:08.096  4753  4753 I art     : Explicit concurrent mark sweep GC freed 23176(1391KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.492ms total 86.743ms
,09-02 12:08:08.116  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,09-02 12:08:08.126  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-02 12:08:08.126  1915  1915 E SamsungIME: mOCRHelper is null
,09-02 12:08:08.126  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-02 12:08:08.126  1017  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 12:08:08.126  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-02 12:08:08.126  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-02 12:08:08.136  1962  2153 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 12:08:08.146  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,09-02 12:08:08.146  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-02 12:08:08.156  1017  7657 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 12:08:08.166  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-02 12:08:08.166  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:08.166  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,09-02 12:08:08.166  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 12:08:08.166  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 12:08:08.166  1017  2016 D ActivityManager: handle home activity for 0
09-02 12:08:08.166  1017  2016 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-02 12:08:08.166  1017  2016 D KnoxTimeoutHandler: post home show event for user 0
09-02 12:08:08.166  1017  2016 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-02 12:08:08.166  1017  2016 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-02 12:08:08.166  1017  2016 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-02 12:08:08.166  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
09-02 12:08:08.166  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-02 12:08:08.166  1484  1484 D Launcher.HomeView: onPause
,09-02 12:08:08.166  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-02 12:08:08.176  1017  1123 V NetworkStats: performPollLocked() took 12ms
09-02 12:08:08.176  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:08.176  1017  1041 W TextServicesManagerService: no available spell checker services found
,09-02 12:08:08.196  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,09-02 12:08:08.196  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 12:08:08.196  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 12:08:08.196  7724  7724 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-02 12:08:08.196  1441  1441 D RegisteredServicesCache: empty dynamic service
,09-02 12:08:08.216   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,09-02 12:08:08.226  7724  7724 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-02 12:08:08.226  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-02 12:08:08.226  1017  1383 D InputDispatcher: Focus entered window: 1484
,09-02 12:08:08.236  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-02 12:08:08.236  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 12:08:08.236  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 12:08:08.236  1484  1484 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-02 12:08:08.246  7143  7143 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
09-02 12:08:08.246  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-02 12:08:08.246  1017  1030 D SecContentProvider2: mCursor = null
,09-02 12:08:08.246  7143  7143 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-02 12:08:08.246  7143  7143 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-02 12:08:08.246  7143  7143 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-02 12:08:08.246  1017  7657 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 10:08:08 GMT], X-Android-Received-Millis=[1472810888255], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472810888210]}
09-02 12:08:08.246  1017  7657 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 12:08:08.246  1017  7657 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-02 12:08:08.246  1017  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-02 12:08:08.246  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-02 12:08:08.246  1017  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-02 12:08:08.246  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-02 12:08:08.246  1017  4395 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
09-02 12:08:08.246  1017  4395 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-02 12:08:08.246  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-02 12:08:08.246  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:08.246  1017  4395 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:08:08.246  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,09-02 12:08:08.246  1173  1707 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 12:08:08.246  4753  6819 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-02 12:08:08.266  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.276  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.276  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:08:08.276  1484  1484 V ActivityThread: updateVisibility : ActivityRecord{27050d13 token=android.os.BinderProxy@3156533a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,09-02 12:08:08.286  1017  2016 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-02 12:08:08.286  1484  1484 D Launcher.HomeView: onStop
,09-02 12:08:08.286  1017  2016 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-02 12:08:08.286  1017  1029 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-02 12:08:08.286  1017  2016 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:08.286  1017  2016 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:08:08.286  1017  2016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 12:08:08.286  1017  1480 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 12:08:08.296  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.296  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-02 12:08:08.296  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-02 12:08:08.296  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 12:08:08.296  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-02 12:08:08.296  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-02 12:08:08.296  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-02 12:08:08.306  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,09-02 12:08:08.306  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
09-02 12:08:08.306  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-02 12:08:08.306  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-02 12:08:08.306  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-02 12:08:08.306  1017  7778 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 12:08:08.306  1017  1029 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6754 uid 10171
,09-02 12:08:08.306  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 12:08:08.316  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 12:08:08.316  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:08.316  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:08.316  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 12:08:08.316  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 12:08:08.316  1915  1915 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-02 12:08:08.326  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.326  7128  7128 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-02 12:08:08.326  2758  7780 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
09-02 12:08:08.326  2758  7780 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-02 12:08:08.326  2758  7780 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-02 12:08:08.336  6959  7779 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-02 12:08:08.336  6959  7779 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-02 12:08:08.336  6959  7779 I System.out: (HTTPLog)-Static: isShipBuild true
09-02 12:08:08.336  6959  7779 I System.out: (HTTPLog)-Thread-1260-280535400: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-02 12:08:08.336  6959  7779 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-02 12:08:08.336   278  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-02 12:08:08.336   278  1006 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,09-02 12:08:08.336  7239  7239 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-02 12:08:08.356  7166  7166 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-02 12:08:08.356  7166  7166 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-02 12:08:08.356  7166  7166 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-02 12:08:08.356  7166  7166 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-02 12:08:08.356  7166  7166 I SA      : [OR] == isSIMCardReady false ==
,09-02 12:08:08.376  6959  7779 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 12:08:08.376  1017  1047 W ActivityManager: mDVFSHelper.release()
09-02 12:08:08.376  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b76aeda u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:145248
,09-02 12:08:08.386  1017  1056 I art     : Explicit concurrent mark sweep GC freed 86467(5MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 25MB/37MB, paused 6.040ms total 334.337ms
,09-02 12:08:08.386  7166  7166 I SA      : [SCU] == networkStateCheck == true
,09-02 12:08:08.396  7166  7166 I SA      : [DM] getCountryCodeFromCSC : PL
09-02 12:08:08.396  7166  7166 I SA      : isChinaCountryCode : false
09-02 12:08:08.396  7166  7166 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-02 12:08:08.396  7166  7166 I SA      : [OR] == networkStateCheck true ==
,09-02 12:08:08.396  2758  7780 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-02 12:08:08.406  2758  7780 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-02 12:08:08.406  7166  7166 I SA      : [OR] GetMyCountryZoneTask
,09-02 12:08:08.406  2758  7780 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-02 12:08:08.406  7166  7166 I SA      : [OR] onReceive END
,09-02 12:08:08.406  2758  7780 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-02 12:08:08.406  2758  7780 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-02 12:08:08.406  2758  7780 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-02 12:08:08.406  2758  7780 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-02 12:08:08.416  2758  7780 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-02 12:08:08.426  2758  7780 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-02 12:08:08.426  7166  7786 I SA      : [SRS] prepareGetMyCountryZone
,09-02 12:08:08.436  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-02 12:08:08.436  1017  2016 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,09-02 12:08:08.436  1017  2016 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-02 12:08:08.436  1017  2016 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:08.436  1017  2016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:08.436  1017  2016 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-02 12:08:08.446  7166  7786 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-02 12:08:08.446  7166  7786 I SA      : [SSP] query invoked
,09-02 12:08:08.456  2758  7780 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-02 12:08:08.456  7166  7786 I SA      : [TPMU] GetMccFromDB : null
,09-02 12:08:08.456  7166  7786 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-02 12:08:08.466  7166  7786 I SA      : [LBE] isSupportCheckDomainRegion : false
,09-02 12:08:08.466  7166  7786 I SA      : [TPM] isNoProxy(default) : true
,09-02 12:08:08.476  7166  7786 E File    : fail readDirectory() errno=2
,09-02 12:08:08.486  6959  7779 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-02 12:08:08.496  1017  1500 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,09-02 12:08:08.496  1017  1500 D SecContentProvider2: mCursor = null
,09-02 12:08:08.506  1017  1030 I ActivityManager: Killing 7204:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-02 12:08:08.526  7221  7221 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-02 12:08:08.526  1017  1476 D PersonaManager: isKioskContainerExistOnDevice
,09-02 12:08:08.536  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-02 12:08:08.536  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-02 12:08:08.536  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-02 12:08:08.546  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-02 12:08:08.546  1017  1017 V EnterpriseBillingPolicy: uID is 10171
09-02 12:08:08.546  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-02 12:08:08.546  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-02 12:08:08.546  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,09-02 12:08:08.546  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-02 12:08:08.546  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-02 12:08:08.546  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-02 12:08:08.546  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-02 12:08:08.556  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-02 12:08:08.556  1017  1017 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-02 12:08:08.556  7221  7221 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-02 12:08:08.556  1017  1160 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,09-02 12:08:08.556  7221  7221 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-02 12:08:08.566  7221  7221 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-02 12:08:08.576  1017  1476 I ActivityManager: Killing 6834:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,09-02 12:08:08.596  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.596  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.606  2857  2857 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 12:08:08 GMT+02:00 2016
,09-02 12:08:08.606  1017  4395 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-02 12:08:08.606  1017  4395 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 12:08:08.606  1017  4395 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:08.606  1017  4395 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:08.606  1017  4395 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 12:08:08.616  2857  2857 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-02 12:08:08.616  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.616  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 12:08:08.616  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 12:08:08.616  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 12:08:08.616  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.636  2857  2857 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-02 12:08:08.636  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.636  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.646  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 12:08:08.646  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-02 12:08:08.646  2857  2857 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-02 12:08:08.646  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.646  2857  2857 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-02 12:08:08.646  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 12:08:08.646  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-02 12:08:08.656  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 12:08:08.656  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-02 12:08:08.656  2857  7792 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 12:08:08.656  2857  7792 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-02 12:08:08.656  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 12:08:08.656  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-02 12:08:08.656  1017  1056 D PackageManager: delete codoeFile: 
,09-02 12:08:08.656  2857  7792 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
09-02 12:08:08.656  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-02 12:08:08.666  2857  7792 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,09-02 12:08:08.666  2857  7792 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
09-02 12:08:08.666  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-02 12:08:08.686  1017  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-02 12:08:08.686  1017  1056 D PackageManager: result of delete: 1{382587360}
,09-02 12:08:08.696  7698  7698 D AndroidRuntime: Shutting down VM
,09-02 12:08:08.706  2857  7792 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,09-02 12:08:08.706  2857  7792 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-02 12:08:08.706  1017  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-02 12:08:08.706  1017  1056 D PackageManager: userId{-1}
09-02 12:08:08.706  1017  1056 D PackageManager: andCode{true}
,09-02 12:08:08.706  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-02 12:08:08.706  2857  2857 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-02 12:08:08.706  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.706  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.706  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.706  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:08.726  7793  7793 E Zygote  : MountEmulatedStorage()
,09-02 12:08:08.726  7793  7793 I libpersona: KNOX_SDCARD checking this for 10003
09-02 12:08:08.726  7793  7793 E Zygote  : v2
09-02 12:08:08.726  7793  7793 I libpersona: KNOX_SDCARD not a persona
09-02 12:08:08.726  7793  7793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:08:08.726  7793  7793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:08:08.726  7793  7793 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 12:08:08.736  1017  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7793 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-02 12:08:08.736  1017  1212 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
09-02 12:08:08.736  1017  1212 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-02 12:08:08.736  1017  1212 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:08.736  1017  1212 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,09-02 12:08:08.736  1017  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-02 12:08:08.746  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:08:08.746  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-02 12:08:08.746  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-02 12:08:08.756  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:08:08.756  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:08:08.756  7239  7239 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-02 12:08:08.756  7239  7239 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-02 12:08:08.756  7239  7239 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-02 12:08:08.766  7239  7239 D InitializeManagerStateMachine: exit::IDLE
09-02 12:08:08.766  7239  7239 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-02 12:08:08.766  4753  4753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 12:08:08.766  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-02 12:08:08.766  1017  1017 V EnterpriseBillingPolicy: uID is 10171
09-02 12:08:08.766  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-02 12:08:08.766  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-02 12:08:08.766  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-02 12:08:08.766  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-02 12:08:08.766  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-02 12:08:08.766  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-02 12:08:08.766  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-02 12:08:08.766  1017  3339 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-02 12:08:08.766  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
09-02 12:08:08.766  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-02 12:08:08.766  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-02 12:08:08.766  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-02 12:08:08.766   278  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-02 12:08:08.766   278  1006 D Netd    : getNetworkForDns: using netid 504 for uid 10011
09-02 12:08:08.766  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-02 12:08:08.776  7239  7239 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-02 12:08:08.776  7239  7239 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-02 12:08:08.776  7239  7239 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-02 12:08:08.776  7239  7239 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-02 12:08:08.776  7239  7239 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-02 12:08:08.776  7239  7239 D InitializeManagerStateMachine: entry::SUCCESS
,09-02 12:08:08.776  7239  7239 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-02 12:08:08.776  1173  1173 I StatusBar: Icon Only
09-02 12:08:08.776  7239  7239 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-02 12:08:08.776  7239  7239 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-02 12:08:08.776  7239  7239 D InitializeManagerStateMachine: exit::SUCCESS
09-02 12:08:08.776  7239  7239 D InitializeManagerStateMachine: entry::IDLE
,09-02 12:08:08.786  1484  1484 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3156533a time:145650
,09-02 12:08:08.786  1173  1173 D PanelView: There is/are notification(s) 
09-02 12:08:08.786  7793  7793 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:08.786  7793  7793 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:08.796  4753  7257 I iu.UploadsManager: num queued entries: 0
,09-02 12:08:08.796  4753  7257 I iu.UploadsManager: num updated entries: 0
,09-02 12:08:08.796  4753  7257 I iu.SyncManager: NEXT; no task
,09-02 12:08:08.816  1017  1042 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-02 12:08:08.816  1017  1029 I ActivityManager: Killing 7424:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-02 12:08:08.826  2857  2857 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 12:08:08 GMT+02:00 2016
,09-02 12:08:08.826  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-02 12:08:08.826  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 12:08:08.826  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:08.826  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:08.826  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 12:08:08.836  2857  2857 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-02 12:08:08.836  1017  1029 I ActivityManager: Killing 7452:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-02 12:08:08.836  2857  2857 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-02 12:08:08.836  1017  1029 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
09-02 12:08:08.836  1017  1029 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-02 12:08:08.836  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
09-02 12:08:08.836  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.836  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.836  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.836  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:08.846  2857  2857 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-02 12:08:08.846  2857  2857 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,09-02 12:08:08.846  2857  7811 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 12:08:08.846  7812  7812 E Zygote  : MountEmulatedStorage()
09-02 12:08:08.846  7812  7812 E Zygote  : v2
09-02 12:08:08.856  7812  7812 I libpersona: KNOX_SDCARD checking this for 10090
09-02 12:08:08.856  7812  7812 I libpersona: KNOX_SDCARD not a persona
09-02 12:08:08.856  2857  7811 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
09-02 12:08:08.856  7812  7812 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:08:08.856  2857  7811 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
09-02 12:08:08.856  7812  7812 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:08:08.856  2857  7811 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-02 12:08:08.856  7812  7812 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:08:08.866  1017  1029 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7812 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-02 12:08:08.876  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-02 12:08:08.876  1017  1476 I TactileAssist: enable value -1
09-02 12:08:08.876  1017  1476 I TactileAssist: internal enable value -1
09-02 12:08:08.876  1017  1476 I TactileAssist: intensity value -1
09-02 12:08:08.876  1017  1476 I TactileAssist: saveAppList value true
,09-02 12:08:08.876  1017  1476 I TactileAssist: List of disabled apps :
,09-02 12:08:08.876  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.876  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.876  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.876  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:08.886  7812  7812 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:08.886  7812  7812 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:08.896  7827  7827 E Zygote  : MountEmulatedStorage()
09-02 12:08:08.896  7827  7827 E Zygote  : v2
09-02 12:08:08.896  7827  7827 I libpersona: KNOX_SDCARD checking this for 1000
09-02 12:08:08.896  7827  7827 I libpersona: KNOX_SDCARD not a persona
09-02 12:08:08.896  7827  7827 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:08:08.896  1017  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7827 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-02 12:08:08.906  7698  7698 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-02 12:08:08.906  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
09-02 12:08:08.906  7827  7827 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:08:08.906  7827  7827 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 12:08:08.906  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.906  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.906  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.906  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:08.916  2857  7811 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-02 12:08:08.926  2857  7811 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest,
,09-02 12:08:08.926  2857  7811 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-02 12:08:08.946  7827  7827 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:08.946  7827  7827 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:08.946  7844  7844 E Zygote  : MountEmulatedStorage()
,09-02 12:08:08.946  7844  7844 E Zygote  : v2
09-02 12:08:08.946  7844  7844 I libpersona: KNOX_SDCARD checking this for 1000
09-02 12:08:08.946  7844  7844 I libpersona: KNOX_SDCARD not a persona
09-02 12:08:08.946  7844  7844 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:08:08.946  1017  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7844 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-02 12:08:08.946  7844  7844 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:08:08.956  7844  7844 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:08:08.966  1962  7805 I qtaguid : Tagging socket 47 with tag 1000040700000000{268436487,0} for uid -1, pid: 1962, getuid(): 10011
09-02 12:08:08.966  2857  2857 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-02 12:08:08.976  7844  7844 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:08.976  7844  7844 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:08.996  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-02 12:08:08.996  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.996  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.996  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:08.996  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:08.996  7812  7812 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-02 12:08:08.996  7812  7812 D elm:15121: ELMEngine.ELMEngine( context ).
,09-02 12:08:09.006  7812  7812 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-02 12:08:09.006  7862  7862 E Zygote  : MountEmulatedStorage(),
09-02 12:08:09.006  7862  7862 E Zygote  : v2
09-02 12:08:09.016  7862  7862 I libpersona: KNOX_SDCARD checking this for 10048
09-02 12:08:09.016  7862  7862 I libpersona: KNOX_SDCARD not a persona
09-02 12:08:09.016  7862  7862 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:08:09.016  1017  1030 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7862 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,09-02 12:08:09.016  1017  1030 I ActivityManager: Killing 6582:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
09-02 12:08:09.016  7862  7862 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:08:09.016  7862  7862 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-02 12:08:09.016  1017  4396 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm,
09-02 12:08:09.016  1017  4396 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-02 12:08:09.016  1017  4396 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:09.016  1017  4396 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:09.016  1017  4396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-02 12:08:09.026  7812  7812 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-02 12:08:09.036  7706  7706 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-02 12:08:09.036  7706  7706 I PCWCLIENTTRACE_PushUtil: sales region : global
09-02 12:08:09.036  7706  7706 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-02 12:08:09.036  7706  7706 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-02 12:08:09.036  1017  1383 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
09-02 12:08:09.036  7827  7827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
09-02 12:08:09.036  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.036  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.036  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.036  1017  1383 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.036  7844  7844 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
09-02 12:08:09.046  7862  7862 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:09.046  7862  7862 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:09.046  7812  7812 D elm:15121: ElmAgentService : onCreate()
,09-02 12:08:09.046  7812  7870 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-02 12:08:09.046  7812  7870 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-02 12:08:09.046  7812  7870 D elm:15121: MDMBridge.getInstance()
09-02 12:08:09.046  7812  7870 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-02 12:08:09.046  7812  7870 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-02 12:08:09.056  7166  7786 I SA      : [RC New] Execute method=[GET] start,
,09-02 12:08:09.066  7878  7878 E Zygote  : MountEmulatedStorage()
09-02 12:08:09.066  7878  7878 E Zygote  : v2
,09-02 12:08:09.066  1017  1383 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7878 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-02 12:08:09.066  7878  7878 I libpersona: KNOX_SDCARD checking this for 10029
09-02 12:08:09.066  7878  7878 I libpersona: KNOX_SDCARD not a persona
,09-02 12:08:09.066  1017  1480 D SecContentProvider2: uri = -1 selection = getSealedState
09-02 12:08:09.066  1017  1480 D SecContentProvider2: mCursor = null
09-02 12:08:09.066  7844  7844 I PopupuiReceiver_KNOX: getSealedState : true
09-02 12:08:09.066  1017  1500 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
09-02 12:08:09.066  1017  1500 D SecContentProvider2: mCursor = null
,09-02 12:08:09.066  7844  7844 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1,
09-02 12:08:09.076  1017  1481 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-02 12:08:09.076  1017  1481 D SecContentProvider2: mCursor = null
09-02 12:08:09.076  7844  7844 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
09-02 12:08:09.076  1017  4394 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-02 12:08:09.076  7844  7844 D PopupuiReceiver: Action package removed
09-02 12:08:09.076  1017  4394 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-02 12:08:09.076  1017  4394 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:09.076  1017  4394 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:09.076  1017  4394 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-02 12:08:09.076  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:09.076  1017  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-02 12:08:09.076  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 12:08:09.076  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
09-02 12:08:09.076  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 12:08:09.086  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-02 12:08:09.086  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.086  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-02 12:08:09.086  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.086  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:09.086  7878  7878 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 12:08:09.096  7878  7878 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 12:08:09.096  7878  7878 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 12:08:09.096  7166  7786 I SA      : [RC New] Security=[true]
,09-02 12:08:09.096  7166  7786 I System.out: Thread-1316(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,09-02 12:08:09.106  7166  7786 I System.out: Thread-1316(ApacheHTTPLog):isSBSettingEnabled false
09-02 12:08:09.106  7166  7786 I System.out: Thread-1316(ApacheHTTPLog):isShipBuild true
09-02 12:08:09.106  7166  7786 I System.out: Thread-1316(ApacheHTTPLog):SMARTBONDING_ENABLED is false
09-02 12:08:09.106  7166  7786 I System.out: Thread-1316(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-02 12:08:09.106   278  1006 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-02 12:08:09.106   278  1006 D Netd    : getNetworkForDns: using netid 504 for uid 10036
09-02 12:08:09.106  7862  7862 D Compatibility: onReceive() it will make start service
,09-02 12:08:09.106  7891  7891 E Zygote  : MountEmulatedStorage()
09-02 12:08:09.106  7891  7891 E Zygote  : v2
09-02 12:08:09.106  7891  7891 I libpersona: KNOX_SDCARD checking this for 10145
09-02 12:08:09.106  7891  7891 I libpersona: KNOX_SDCARD not a persona
,09-02 12:08:09.106  7891  7891 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:08:09.106  1017  1029 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7891 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 12:08:09.106  7891  7891 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:08:09.106   295   295 E SMD     : DCD OFF
09-02 12:08:09.116  1017  1029 I ActivityManager: Killing 7337:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
09-02 12:08:09.116  7891  7891 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 12:08:09.116  1017  2016 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-02 12:08:09.116  1017  2016 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
09-02 12:08:09.116  1017  2016 W ActivityManager: userId = 0, bbcId = -10000
09-02 12:08:09.116  1017  2016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 12:08:09.116  1017  2016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-02 12:08:09.116  7812  7812 D elm:15121: ElmAgentService : onDestroy().
09-02 12:08:09.116  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
09-02 12:08:09.116  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.116  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.116  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.116  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:09.126  7862  7903 D Compatibility: onHandleIntent(),
,09-02 12:08:09.126  7862  7903 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,09-02 12:08:09.126  7862  7903 D Compatibility: found: 2
,09-02 12:08:09.136  7891  7891 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:09.136  7891  7891 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:09.136  7878  7878 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 12:08:09.136  7912  7912 I libpersona: KNOX_SDCARD checking this for 1000
09-02 12:08:09.136  7912  7912 E Zygote  : MountEmulatedStorage()
09-02 12:08:09.136  7912  7912 I libpersona: KNOX_SDCARD not a persona
09-02 12:08:09.136  7912  7912 E Zygote  : v2
09-02 12:08:09.136  7878  7878 D ActivityThread: Added TimaKeyStore provider
09-02 12:08:09.136  7912  7912 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:08:09.146  7912  7912 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:08:09.146  7912  7912 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-02 12:08:09.146  7862  7903 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-02 12:08:09.146  1017  1029 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7912 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-02 12:08:09.146  1017  1029 I ActivityManager: Killing 7353:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
09-02 12:08:09.146  1017  2016 I ActivityManager: Killing 7641:com.samsung.android.sm/1000 (adj 15): empty #21
,09-02 12:08:09.166  1017  2016 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-02 12:08:09.166  1017  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.166  1017  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.166  1017  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 12:08:09.166  1017  2016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 12:08:09.166  7862  7903 D Compatibility: skipping ResolveInfo{138b0ec com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-02 12:08:09.166  7862  7903 D Compatibility: considering ResolveInfo{d936cb5 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-02 12:08:09.176  7862  7903 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-02 12:08:09.176  7862  7903 D Compatibility: enabling receiver ResolveInfo{3be29f4a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-02 12:08:09.176  7912  7912 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 12:08:09.176  7912  7912 D ActivityThread: Added TimaKeyStore provider
,09-02 12:08:09.176  7862  7903 D Compatibility: enabling receiver ResolveInfo{9428ebb com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-02 12:08:09.176  7928  7928 E Zygote  : MountEmulatedStorage()
09-02 12:08:09.176  7928  7928 E Zygote  : v2
09-02 12:08:09.176  7928  7928 I libpersona: KNOX_SDCARD checking this for 10052
09-02 12:08:09.176  7928  7928 I libpersona: KNOX_SDCARD not a persona
,09-02 12:08:09.186  7928  7928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 12:08:09.186  1017  2016 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7928 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-02 12:08:09.186  7862  7903 D Compatibility: enabling receiver ResolveInfo{1875efd8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-02 12:08:09.186  7928  7928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 12:08:09.196  7862  7903 D Compatibility: enabling receiver ResolveInfo{325b1f31 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-02 12:08:09.196  7928  7928 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL

```
