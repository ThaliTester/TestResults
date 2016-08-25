#### Test 823372352b31b5a_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-25 13:18:04.761  1014  4344 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-25 13:18:04.761  1014  4344 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 13:18:04.761  1014  4344 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 13:18:04.761  1014  4344 D BatteryService: stay LED for fully charged
08-25 13:18:04.761  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
08-25 13:18:04.771  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-25 13:18:04.771  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-25 13:18:04.771  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-25 13:18:04.771  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-25 13:18:04.781  3163  3163 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 13:18:04.781  3163  3271 D HeadsetStateMachine: Disconnected process message: 10
08-25 13:18:04.781  1014  1014 I MotionRecognitionService: Plugged
08-25 13:18:04.781  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
08-25 13:18:04.791  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-25 13:18:04.791  1176  1176 D SViewCoverView: level :100 plugged : 2
08-25 13:18:04.791  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 13:18:04.791  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 13:18:04.791  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:05.101  6749  6749 D AndroidRuntime: 
08-25 13:18:05.101  6749  6749 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 13:18:05.111  6749  6749 D AndroidRuntime: CheckJNI is OFF
08-25 13:18:05.111  6749  6749 D AndroidRuntime: readGMSProperty: start
08-25 13:18:05.111  6749  6749 D AndroidRuntime: readGMSProperty: already setted!!
08-25 13:18:05.111  6749  6749 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-25 13:18:05.111  6749  6749 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 13:18:05.111  6749  6749 D AndroidRuntime: readGMSProperty: end
08-25 13:18:05.111  6749  6749 D AndroidRuntime: addProductProperty: start
08-25 13:18:05.241  6749  6749 E AffinityControl: AffinityControl: registerfunction enter
08-25 13:18:05.271  6749  6749 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-25 13:18:05.291  1014  1452 E PersonaManagerService: inState():  stateMachine is null !!
08-25 13:18:05.291  1014  1452 I PersonaManagerService: PersonaId don't exist
08-25 13:18:05.291  1014  1452 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-25 13:18:05.291  1014  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 13:18:05.311  1014  1452 W ActivityManager: mDVFSHelper.acquire()
08-25 13:18:05.321   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-25 13:18:05.321   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-25 13:18:05.331  1014  1452 D FocusedStackFrame: Set to : 0
08-25 13:18:05.331  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:05.331  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:05.331  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:05.331  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:05.331  1014  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-25 13:18:05.331  1014  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-25 13:18:05.351  6760  6760 E Zygote  : MountEmulatedStorage()
08-25 13:18:05.351  6760  6760 E Zygote  : v2
08-25 13:18:05.351  6760  6760 I libpersona: KNOX_SDCARD checking this for 10171
08-25 13:18:05.351  6760  6760 I libpersona: KNOX_SDCARD not a persona
08-25 13:18:05.351  1014  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 13:18:05.351  1014  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-25 13:18:05.351   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-25 13:18:05.351  6760  6760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 13:18:05.351  1014  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-25 13:18:05.351  1014  1452 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6760 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 13:18:05.351  1014  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 13:18:05.361  6760  6760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 13:18:05.361  6760  6760 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-25 13:18:05.361  1014  1452 D InputDispatcher: Focused application set to: xxxx
08-25 13:18:05.361  1014  1452 D InputDispatcher: Focus left window: 1497
08-25 13:18:05.361  6749  6749 D AndroidRuntime: Shutting down VM
08-25 13:18:05.371  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 13:18:05.371  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 13:18:05.371   306   306 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 19.507ms
08-25 13:18:05.391  6760  6760 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 13:18:05.391  6760  6760 D ActivityThread: Added TimaKeyStore provider
08-25 13:18:05.391  1014  1244 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-25 13:18:05.391   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.526ms
08-25 13:18:05.401  1014  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-25 13:18:05.411   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 17.368ms
08-25 13:18:05.421  1014  1014 V ActivityManager: Display changed displayId=0
08-25 13:18:05.421  1014  1244 D PersonaManager: isKioskContainerExistOnDevice
08-25 13:18:05.431   257  1036 I SurfaceFlinger: id=6 Removed Mauncher (6/9)
08-25 13:18:05.431   257   447 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-25 13:18:05.441  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-25 13:18:05.441  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{33eeef7e token=android.os.BinderProxy@22cd6c36 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-25 13:18:05.451  1497  1497 D Launcher: onTrimMemory. Level: 20
08-25 13:18:05.541  6760  6760 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-25 13:18:05.551  6760  6760 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6935-6937)
08-25 13:18:05.551  6760  6760 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 13:18:05.571  6749  6749 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-25 13:18:05.591  6760  6760 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b7d7d2}
08-25 13:18:05.591  6760  6760 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 13:18:05.601  6760  6760 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 13:18:05.641  6760  6760 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-25 13:18:05.651  6760  6760 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 13:18:05.651  6760  6760 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 13:18:05.691  6760  6760 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 13:18:05.691  6760  6760 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 13:18:05.691  6760  6760 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 13:18:05.691  6760  6760 I Adreno-EGL: Local Branch: 
08-25 13:18:05.691  6760  6760 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 13:18:05.691  6760  6760 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 13:18:05.691  6760  6760 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-25 13:18:05.701   287   287 E SMD     : DCD OFF
08-25 13:18:05.801  6760  6760 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 13:18:05.811  6760  6760 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-25 13:18:05.811  6760  6760 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-25 13:18:05.821  6760  6760 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-25 13:18:05.821  6760  6760 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-25 13:18:05.931  1014  1041 W ActivityManager: Activity pause timeout for ActivityRecord{269e7063 u0 com.test.thalitest/.MainActivity t2}
08-25 13:18:05.931  6760  6760 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 13:18:05.951  6760  6760 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 13:18:05.961  6760  6760 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-25 13:18:05.961  6760  6760 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-25 13:18:05.971  6760  6760 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-25 13:18:05.971  6760  6760 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 13:18:05.971  6760  6760 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 13:18:06.041  6760  6801 D OpenGLRenderer: Render dirty regions requested: true
08-25 13:18:06.041  1014  1452 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-25 13:18:06.051  1014  1452 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 13:18:06.051  1014  1452 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-25 13:18:06.051  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 13:18:06.051  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-25 13:18:06.051  6760  6788 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-25 13:18:06.051  6760  6760 V ActivityThread: updateVisibility : ActivityRecord{2b67a732 token=android.os.BinderProxy@bd058e7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-25 13:18:06.061  6760  6760 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 13:18:06.061  6760  6760 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-25 13:18:06.071   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-25 13:18:06.081  1014  1495 D InputDispatcher: Focus entered window: 6760
08-25 13:18:06.091  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 13:18:06.091  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 13:18:06.091  6760  6760 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-25 13:18:06.091  6760  6801 I OpenGLRenderer: Initialized EGL, version 1.4
08-25 13:18:06.101  6760  6801 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-25 13:18:06.101  6760  6801 D OpenGLRenderer: Enabling debug mode 0
08-25 13:18:06.121  1014  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-25 13:18:06.131  1014  6805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-25 13:18:06.131  1176  1176 I StatusBar: Icon Only
08-25 13:18:06.131  1176  1176 D PanelView: There is/are notification(s) 
08-25 13:18:06.151  1014  1046 I ActivityManager: Displayed Component not be shown by security: +718ms (total +816ms)
08-25 13:18:06.151  1014  1046 W ActivityManager: mDVFSHelper.release()
08-25 13:18:06.151  1014  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{269e7063 u0 com.test.thalitest/.MainActivity t2} time:107533
08-25 13:18:06.151  6760  6760 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-25 13:18:06.161   257  1036 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-25 13:18:06.161   257  1037 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-25 13:18:06.161  6760  6760 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@bd058e7 time:107545
08-25 13:18:06.181  1885  1885 I SamsungIME: getCurrentCandidateView
08-25 13:18:06.261  1885  1885 D SamsungIME: Dismiss ExpandCandiate
08-25 13:18:06.271  6760  6760 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6760
08-25 13:18:06.411  1885  1885 I SamsungIME: getDebugLevel  : 0x4f4c
,08-25 13:18:06.441  1885  1885 I SamsungIME: getDebugLevel  : 0x4f4c
,08-25 13:18:06.461  1885  1885 I SamsungIME: KeybaordView init() : load resources
,08-25 13:18:06.481  6760  6760 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 13:18:06.481  1885  1885 I SamsungIME: getCurrentKeyboard
08-25 13:18:06.481  1885  1885 I SamsungIME: getTextKeyboard
,08-25 13:18:06.501  1885  1885 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-25 13:18:06.571  6760  6808 D jxcore_app_log: JniHelper::setJavaVM(0xb8eab2b0), pthread_self() = -1186755160
,08-25 13:18:06.571  6760  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 13:18:06.571  6760  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 13:18:06.571  6760  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 13:18:06.571  6760  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 13:18:06.571  6760  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 13:18:06.571  6760  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222f4d18 added. We now have 1 listener(s)
,08-25 13:18:06.581  6760  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-25 13:18:06.581  6760  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 13:18:06.581  6760  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 13:18:06.581  6760  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-25 13:18:06.581  6760  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33cb49d7 added. We now have 1 listener(s)
,08-25 13:18:06.591  6760  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:06.591  6760  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:18:06.591  6760  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 13:18:06.591  6760  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 13:18:06.591  6760  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-25 13:18:06.591  6760  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 13:18:06.591  6760  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:06.601  6760  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-25 13:18:06.601  6760  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 13:18:06.601  6760  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:06.601  6760  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:06.601  6760  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:06.601  6760  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:06.601  6760  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:06.601  6760  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:06.601  6760  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:06.601  6760  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:18:06.601  6760  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 13:18:06.601  6760  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:18:06.601  6760  6808 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 13:18:06.601  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:06.611  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-25 13:18:06.641  6760  6760 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 13:18:06.791  1014  1323 E Watchdog: !@Sync 3
,08-25 13:18:07.191  6760  6815 W jxcore-log: Initializing JXcore engine
08-25 13:18:07.191  6760  6815 W jxcore-log: JXcore engine is ready
,08-25 13:18:07.251  2030  2030 E audit   : type=1400 msg=audit(1472123887.251:205): avc:  denied  { ioctl } for  pid=6815 comm="Thread-1240" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-25 13:18:07.251  2030  2030 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-25 13:18:07.251  2030  2030 E audit   : type=1300 msg=audit(1472123887.251:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d1068f8 items=0 ppid=306 ppcomm=main pid=6815 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1240" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-25 13:18:07.251  2030  2030 E audit   : type=1320 msg=audit(1472123887.251:205): 
,08-25 13:18:07.261  6760  6815 W jxcore-log: Starting JXcore engine
,08-25 13:18:07.371  6760  6815 W jxcore-log: Platform android
08-25 13:18:07.371  6760  6815 W jxcore-log: 
08-25 13:18:07.371  6760  6815 W jxcore-log: Process ARCH arm
08-25 13:18:07.371  6760  6815 W jxcore-log: 
,08-25 13:18:07.571  6760  6815 I jxcore-log: JXcore Cordova bridge is ready!
08-25 13:18:07.571  6760  6815 I jxcore-log: 
,08-25 13:18:07.571  6760  6815 W jxcore-log: JXcore engine is started
,08-25 13:18:07.581  6760  6808 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 13:18:07.581  6760  6760 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 13:18:07.731   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-25 13:18:07.731   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-25 13:18:08.701   287   287 E SMD     : DCD OFF
,08-25 13:18:11.711   287   287 E SMD     : DCD OFF
,08-25 13:18:12.241  1014  1048 I PowerManagerService: [PWL] Off : 50s ago
,08-25 13:18:12.501  1014  3341 D SSRM:n  : SIOP:: AP = 330
,08-25 13:18:12.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 13:18:13.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:14.711   287   287 E SMD     : DCD OFF,
,08-25 13:18:14.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:14.821  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 13:18:14.821  1014  1026 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-25 13:18:14.821  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 13:18:14.821  1014  1026 D BatteryService: stay LED for fully charged
,08-25 13:18:14.821  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 13:18:14.821  1014  1014 I MotionRecognitionService: Plugged
,08-25 13:18:14.821  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 13:18:14.821  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 13:18:14.821  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 13:18:14.831  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 13:18:14.831  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 13:18:14.841  3163  3163 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 13:18:14.841  3163  3271 D HeadsetStateMachine: Disconnected process message: 10
,08-25 13:18:14.851  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 13:18:14.851  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-25 13:18:14.851  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:14.851  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:14.851  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:15.011  5656  5656 D FactoryTest: Not factory mode
,08-25 13:18:15.011  5656  5656 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-25 13:18:15.011  5656  5656 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-25 13:18:15.011  5656  5656 D MTPRx   : still no open session command from host, so toast
,08-25 13:18:15.011  5656  5656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-25 13:18:15.011  5656  5656 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-25 13:18:15.021  5656  5656 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116400
,08-25 13:18:15.021  1014  1133 E PersonaManagerService: inState():  stateMachine is null !!
,08-25 13:18:15.021  1014  1133 I PersonaManagerService: PersonaId don't exist
08-25 13:18:15.021  1014  1133 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-25 13:18:15.021  1014  1133 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 13:18:15.021  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:15.021  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:15.021  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-25 13:18:15.031  1014  1133 W ActivityManager: mDVFSHelper.acquire()
,08-25 13:18:15.041  1014  1133 D PersonaManager: isKioskContainerExistOnDevice
,08-25 13:18:15.051  1014  1133 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 13:18:15.051  1014  1133 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 13:18:15.051  1014  1133 D InputDispatcher: Focused application set to: xxxx
08-25 13:18:15.051  1014  1133 D InputDispatcher: Focus left window: 6760
,08-25 13:18:15.051  5656  5656 E MTPRx   : started activity for popup
,08-25 13:18:15.061  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-25 13:18:15.061  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 13:18:15.091  5656  5656 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-25 13:18:15.091  5656  5656 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-25 13:18:15.091  5656  5656 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-25 13:18:15.091  5656  5656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 13:18:15.091  5656  5656 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 13:18:15.091  5656  5656 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 13:18:15.111  5656  5656 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-25 13:18:15.111  1014  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 13:18:15.111  1014  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest,
08-25 13:18:15.111  1014  1487 D InputDispatcher: Focused application set to: xxxx
,08-25 13:18:15.111  1014  1487 D InputDispatcher: Focus entered window: 6760
,08-25 13:18:15.121  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 13:18:15.121  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 13:18:15.121  1014  1496 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,08-25 13:18:15.121  1014  1496 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@23bdd7a2 attribute=null, token = android.os.BinderProxy@296a0df2
,08-25 13:18:15.161  5656  5656 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-25 13:18:15.171  5656  5656 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-25 13:18:15.171  5656  5656 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-25 13:18:15.191  6760  6760 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 13:18:15.191  6760  6760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-25 13:18:15.191  6760  6760 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 13:18:15.191  6760  6760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-25 13:18:15.191  1014  1452 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-25 13:18:15.191  1014  1452 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 13:18:15.191  1014  1452 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-25 13:18:15.201  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-25 13:18:15.201  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-25 13:18:15.211  6760  6760 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 13:18:15.211  6760  6760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 13:18:15.211  6760  6760 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c1b6893 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@241a26b8, 16908290=android.view.AbsSavedState$1@241a26b8}, android:focusedViewId=100}]}]
08-25 13:18:15.211  6760  6760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-25 13:18:15.221  6760  6760 V ActivityThread: updateVisibility : ActivityRecord{2b67a732 token=android.os.BinderProxy@bd058e7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-25 13:18:15.221  6760  6760 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 13:18:15.221  6760  6760 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 13:18:15.221  6760  6760 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@bd058e7 time:116600
,08-25 13:18:15.221  1014  1133 D PersonaManager: isKioskContainerExistOnDevice
,08-25 13:18:15.381  1014  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-25 13:18:15.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:16.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 13:18:17.711   287   287 E SMD     : DCD OFF
,08-25 13:18:17.731   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-25 13:18:18.031  1014  1041 W ActivityManager: mDVFSHelper.release(),
,08-25 13:18:18.621  1014  1094 V AlarmManager: waitForAlarm result :4
,08-25 13:18:18.621  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-25 13:18:18.631  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-25 13:18:18.631  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
08-25 13:18:18.631  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-25 13:18:18.641  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-25 13:18:18.641  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 13:18:18.651  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-25 13:18:18.651  1994  1994 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-25 13:18:18.661  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,08-25 13:18:18.661  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 13:18:18.661  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-25 13:18:18.661  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,08-25 13:18:18.671  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-25 13:18:18.711  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 13:18:18.711  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 13:18:18.721  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 13:18:18.741  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 13:18:18.781  4815  4815 D ConnectivityManager: CallingUid : 10011, CallingPid : 4815
,08-25 13:18:18.781  1014  4344 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 13:18:18.791  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-25 13:18:18.791  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-25 13:18:18.791  1014  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-25 13:18:18.791  4815  6824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 13:18:18.791  1994  1994 I art     : Explicit concurrent mark sweep GC freed 55177(3MB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 10MB/17MB, paused 1.564ms total 100.622ms
,08-25 13:18:18.811  1014  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:18.811  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-25 13:18:18.811  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:18.811  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:18.811  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:18.871  4815  6825 W DriveInitializer: Background init thread started
,08-25 13:18:18.911   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-25 13:18:18.911   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:18:18.911  4815  6825 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-25 13:18:18.951  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:18.961  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-25 13:18:18.961  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:18.961  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:18.961  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:18.971  1014  1026 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-25 13:18:18.971  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-25 13:18:18.991  1014  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:18.991  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-25 13:18:18.991  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:18.991  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:18.991  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.011  4815  6825 W DriveInitializer: Background init thread ended
,08-25 13:18:19.031  4815  6833 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-25 13:18:19.031  4815  6833 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-25 13:18:19.051  1994  1994 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 13:18:19.081  1014  1041 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:19.081  1014  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.081  1014  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.151  1014  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:19.151  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-25 13:18:19.151  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:19.151  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.151  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.191  1014  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:19.191  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-25 13:18:19.191  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:19.191  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.191  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.261  1014  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:19.261  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:19.261  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.261  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.291  1014  1451 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:19.301  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:19.301  1014  1451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.301  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.381  1014  1451 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:19.381  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:19.381  1014  1451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.381  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.381  1014  1451 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:19.381  1014  1451 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:19.381  1014  1451 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:19.381  1014  1451 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:19.401  6838  6838 E Zygote  : MountEmulatedStorage()
08-25 13:18:19.401  6838  6838 I libpersona: KNOX_SDCARD checking this for 10011
,08-25 13:18:19.401  6838  6838 E Zygote  : v2
08-25 13:18:19.401  6838  6838 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:19.401  6838  6838 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 13:18:19.401  1014  1451 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6838 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-25 13:18:19.401  6838  6838 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 13:18:19.401  6838  6838 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 13:18:19.451  6838  6838 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:19.451  6838  6838 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:19.471  6838  6838 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-25 13:18:19.471  6838  6838 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 13:18:19.511  6838  6838 I MultiDex: VM with version 2.1.0 has multidex support
,08-25 13:18:19.511  6838  6838 I MultiDex: install
08-25 13:18:19.511  6838  6838 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 13:18:19.541  6838  6838 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-25 13:18:19.591  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-25 13:18:19.611  1014  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:19.611  6838  6838 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 13:18:19.611  6838  6838 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2119892e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-25 13:18:19.611  6838  6838 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-25 13:18:19.611  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:19.611  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.611  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.621  1014  1452 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:19.621  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:19.621  1014  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.621  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.651  6838  6838 D ChimeraCfgMgr: Reading stored module config
,08-25 13:18:19.681  1994  1994 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=0f091bfa-05e7-4b32-bf53-c7f0f281bc5a
,08-25 13:18:19.711  6838  6852 W art     : Suspending all threads took: 12.157ms
,08-25 13:18:19.721  6838  6852 I art     : Background sticky concurrent mark sweep GC freed 20670(1006KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 7MB/7MB, paused 17.536ms total 60.993ms
,08-25 13:18:19.761  6838  6858 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-25 13:18:19.781  6838  6838 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-25 13:18:19.791  6838  6838 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-25 13:18:19.851  1014  1460 I art     : Explicit concurrent mark sweep GC freed 34102(1905KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.494ms total 155.717ms
08-25 13:18:19.851  1014  1460 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-25 13:18:19.851  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-25 13:18:19.851  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:19.851  1014  1460 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.851  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.861  1994  1994 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 13:18:19.861  1994  1994 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 13:18:19.881  1014  1460 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:19.881  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:19.881  1014  1460 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:19.881  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:19.941   282   674 D WVCdm   : Instantiating CDM.
,08-25 13:18:19.941   282   282 I WVCdm   : CdmEngine::OpenSession
,08-25 13:18:19.941   282   282 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-25 13:18:19.961   282   282 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,08-25 13:18:19.981   282   282 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-25 13:18:20.031  4214  4254 I art     : Explicit concurrent mark sweep GC freed 1379(47KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 678us total 21.903ms
,08-25 13:18:20.041   282   282 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-25 13:18:20.041   282   674 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-25 13:18:20.041   282   674 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-25 13:18:20.041   282   674 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-25 13:18:20.051   282   674 D WVCdm   : PrepareKeyRequest: nonce=2577645188
,08-25 13:18:20.061  6838  6851 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-25 13:18:20.061  6838  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 13:18:20.061  6838  6851 I System.out: (HTTPLog)-Static: isShipBuild true
08-25 13:18:20.061  6838  6851 I System.out: (HTTPLog)-Thread-1220-259889251: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-25 13:18:20.061  6838  6851 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:20.071   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 13:18:20.071   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 13:18:20.081  1994  2148 W GCoreFlp: No location to return for getLastLocation()
,08-25 13:18:20.111  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:20.111  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:20.111  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.111  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.121  1014  1452 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 13:18:20.121  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:20.121  1014  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.121  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.121  6838  6851 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 13:18:20.121  6838  6851 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6838, getuid(): 10011
,08-25 13:18:20.131  1014  1244 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:20.131  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:20.131  1014  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.131  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.141  4815  6834 D UdcContextInitService: registered all accounts: true
,08-25 13:18:20.151  1994  2151 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 13:18:20.161  1994  2173 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-25 13:18:20.281  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:20.281  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-25 13:18:20.291  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:20.291  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.291  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.371  6838  6851 I qtaguid : Untagging socket 33
,08-25 13:18:20.491  1014  1460 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:20.491  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:20.491  1014  1460 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.491  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.501  1014  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:20.511  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:20.511  1014  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.511  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.531  1014  1452 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-25 13:18:20.531  1014  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-25 13:18:20.531  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:20.531  1014  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.531  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.581  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:20.581  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:20.581  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.581  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.581  1994  6868 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-25 13:18:20.581  1994  6866 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-25 13:18:20.591  1014  1451 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 13:18:20.591  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:20.591  1014  1451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.591  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.631  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:20.631  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:20.631  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 13:18:20.631  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.701  1994  2173 I art     : Explicit concurrent mark sweep GC freed 54860(3MB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 11MB/18MB, paused 1.455ms total 93.269ms
,08-25 13:18:20.701  1994  6868 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-25 13:18:20.701  1994  6866 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-25 13:18:20.701  1014  1244 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:20.701  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:20.701  1014  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 13:18:20.711  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.711   287   287 E SMD     : DCD OFF
,08-25 13:18:20.761  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:20.761  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:20.761  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.761  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.761  1994  6868 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-25 13:18:20.761  1994  6866 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-25 13:18:20.761  1994  6866 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-25 13:18:20.791  1014  1133 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-25 13:18:20.791  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-25 13:18:20.791  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:20.791  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:20.791  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:20.791  1994  6866 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-25 13:18:20.821  1014  1244 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-25 13:18:20.851  1994  2173 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-25 13:18:20.851  1994  2173 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:20.851  1994  2173 I System.out: (HTTPLog)-Static: isShipBuild true
08-25 13:18:20.851  1994  2173 I System.out: (HTTPLog)-Thread-193-922613524: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-25 13:18:20.851  1994  2173 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:20.851   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 13:18:20.851   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 13:18:20.851  1994  2173 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-25 13:18:20.851  1994  2173 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1994, getuid(): 10011
,08-25 13:18:20.901  1994  2173 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1994, getuid(): 10011
,08-25 13:18:20.911  1994  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:20.911   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 13:18:20.911   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 13:18:20.911  1994  6866 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 13:18:20.911  1994  6866 I qtaguid : Tagging socket 73 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1994, getuid(): 10011
,08-25 13:18:20.911  6870  6870 I dex2oat : ----------------------------------------------------
08-25 13:18:20.911  6870  6870 I dex2oat : <SS>: S T A R T I N G . . .
08-25 13:18:20.911  6870  6870 I dex2oat : <SS>: Zip is absent. Canceled.
,08-25 13:18:20.911  6870  6870 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 13:18:20.951  1994  6866 I qtaguid : Tagging socket 76 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1994, getuid(): 10011
,08-25 13:18:20.981  6870  6870 I dex2oat : dex2oat took 72.148ms (threads: 4)
,08-25 13:18:21.001  6838  6851 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 13:18:21.001  6838  6851 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 13:18:21.001  6838  6851 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 13:18:21.001  6838  6851 I Adreno-EGL: Local Branch: 
08-25 13:18:21.001  6838  6851 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 13:18:21.001  6838  6851 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 13:18:21.001  6838  6851 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 13:18:21.161  1014  3375 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-25 13:18:21.181  6838  6851 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 13:18:21.181  6838  6851 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 13:18:21.181  6838  6851 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 13:18:21.181  6838  6851 I Adreno-EGL: Local Branch: 
08-25 13:18:21.181  6838  6851 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 13:18:21.181  6838  6851 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 13:18:21.181  6838  6851 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 13:18:21.211  1014  1244 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-25 13:18:21.231  6838  6851 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 13:18:21.231  6838  6851 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 13:18:21.231  6838  6851 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 13:18:21.231  6838  6851 I Adreno-EGL: Local Branch: 
08-25 13:18:21.231  6838  6851 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 13:18:21.231  6838  6851 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 13:18:21.231  6838  6851 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 13:18:21.231  1994  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:21.231  1994  6866 I qtaguid : Tagging socket 73 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1994, getuid(): 10011
,08-25 13:18:21.391  1014  1451 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-25 13:18:21.401  1994  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:21.401  1994  6866 I qtaguid : Tagging socket 73 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1994, getuid(): 10011
,08-25 13:18:21.471  1994  6836 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:21.471  1994  6836 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 13:18:21.471  1994  6836 I qtaguid : Tagging socket 59 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1994, getuid(): 10011
,08-25 13:18:21.501  1994  6836 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1994, getuid(): 10011
,08-25 13:18:21.541  1014  1133 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-25 13:18:21.541  1994  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:21.541  1994  6866 I qtaguid : Tagging socket 73 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1994, getuid(): 10011
,08-25 13:18:21.621   282   688 I WVCdm   : CdmEngine::CloseSession
,08-25 13:18:21.631   282   688 I WVCdm   : L3 Terminate.
,08-25 13:18:21.671  1994  2173 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-25 13:18:21.681  1994  2173 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-25 13:18:21.691  1014  1460 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-25 13:18:21.691  1994  2173 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-25 13:18:20.361+0200, stopTime=2016-08-25 13:18:21.697+0200, duration=1336ms
,08-25 13:18:21.701  1994  6885 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:21.701   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 13:18:21.701   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 13:18:21.701  1994  6885 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 13:18:21.701  1994  6885 I qtaguid : Tagging socket 80 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1994, getuid(): 10011
,08-25 13:18:21.721  1994  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:21.721  1994  6866 I qtaguid : Tagging socket 73 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1994, getuid(): 10011
,08-25 13:18:21.741  1994  6885 I qtaguid : Tagging socket 82 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1994, getuid(): 10011
,08-25 13:18:21.761  1014  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-25 13:18:21.951  1994  6885 I qtaguid : Untagging socket 80
,08-25 13:18:21.951  1994  2173 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-25 13:18:22.441  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-25 13:18:22.441  6760  6815 I jxcore-log: 
,08-25 13:18:22.521  1014  3341 D SSRM:n  : SIOP:: AP = 350
,08-25 13:18:22.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 13:18:23.711   287   287 E SMD     : DCD OFF
,08-25 13:18:23.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:23.841  1994  6888 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:23.841  1994  6888 I qtaguid : Tagging socket 80 with tag 1000310200000000{268448002,0} for uid 10011, pid: 1994, getuid(): 10011
,08-25 13:18:24.111  1994  6888 I qtaguid : Untagging socket 80
,08-25 13:18:24.121  1994  2173 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-25 13:18:24.141  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-25 13:18:24.711  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-25 13:18:24.711  6760  6815 I jxcore-log: 
,08-25 13:18:24.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:24.751  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-25 13:18:24.751  6760  6815 I jxcore-log: 
,08-25 13:18:24.771  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
08-25 13:18:24.771  6760  6815 I jxcore-log: 
,08-25 13:18:24.801  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
08-25 13:18:24.801  6760  6815 I jxcore-log: 
,08-25 13:18:24.811  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
08-25 13:18:24.811  6760  6815 I jxcore-log: 
,08-25 13:18:24.881  1014  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 13:18:24.881  1014  1133 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 13:18:24.881  1014  1133 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-25 13:18:24.881  1014  1133 D BatteryService: stay LED for fully charged
08-25 13:18:24.881  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 13:18:24.891  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-25 13:18:24.891  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-25 13:18:24.891  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-25 13:18:24.891  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-25 13:18:24.891  1014  1014 I MotionRecognitionService: Plugged
,08-25 13:18:24.891  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 13:18:24.901  3163  3163 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 13:18:24.901  3163  3271 D HeadsetStateMachine: Disconnected process message: 10
,08-25 13:18:24.911  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-25 13:18:24.911  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-25 13:18:24.911  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-25 13:18:24.911  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:24.911  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:25.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 13:18:26.461  1014  1487 I ActivityManager: Killing 6466:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-25 13:18:26.711   287   287 E SMD     : DCD OFF,
,08-25 13:18:26.731   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:27.741   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-25 13:18:28.611  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 13:18:28.611  6760  6815 I jxcore-log: 
,08-25 13:18:28.611  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 13:18:28.611  6760  6815 I jxcore-log: 
,08-25 13:18:28.621  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:28.621  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:28.621  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:28.621  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:28.621  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:28.621  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:28.621  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:28.621  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:28.621  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:18:28.621  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 13:18:28.621  6760  6815 I jxcore-log: 
,08-25 13:18:28.621  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 13:18:28.621  6760  6815 I jxcore-log: 
,08-25 13:18:29.711   287   287 E SMD     : DCD OFF,
,08-25 13:18:32.551  1014  3341 D SSRM:n  : SIOP:: AP = 340
,08-25 13:18:32.711   287   287 E SMD     : DCD OFF
,08-25 13:18:33.461  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-25 13:18:33.461  6760  6815 I jxcore-log: 
,08-25 13:18:33.471  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-25 13:18:33.471  6760  6815 I jxcore-log: 
,08-25 13:18:33.481  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-25 13:18:33.481  6760  6815 I jxcore-log: 
,08-25 13:18:33.701  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
08-25 13:18:33.701  6760  6815 I jxcore-log: 
,08-25 13:18:34.761  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
08-25 13:18:34.761  6760  6815 I jxcore-log: 
,08-25 13:18:34.841  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js,
08-25 13:18:34.841  6760  6815 I jxcore-log: 
,08-25 13:18:34.851  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js,
08-25 13:18:34.851  6760  6815 I jxcore-log: 
,08-25 13:18:34.931  1014  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 13:18:34.931  1014  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 13:18:34.931  1014  1451 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-25 13:18:34.931  1014  1451 D BatteryService: stay LED for fully charged
08-25 13:18:34.931  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 13:18:34.931  1014  1014 I MotionRecognitionService: Plugged
08-25 13:18:34.931  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 13:18:34.941  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 13:18:34.941  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 13:18:34.941  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-25 13:18:34.941  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 13:18:34.941  3163  3163 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 13:18:34.951  3163  3271 D HeadsetStateMachine: Disconnected process message: 10
,08-25 13:18:34.961  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 13:18:34.961  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-25 13:18:34.961  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:34.961  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 13:18:34.961  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:35.111  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-25 13:18:35.111  6760  6815 I jxcore-log: 
,08-25 13:18:35.141  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-25 13:18:35.141  6760  6815 I jxcore-log: 
,08-25 13:18:35.151  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-25 13:18:35.151  6760  6815 I jxcore-log: 
,08-25 13:18:35.151  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-25 13:18:35.151  6760  6815 I jxcore-log: 
,08-25 13:18:35.171  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
08-25 13:18:35.171  6760  6815 I jxcore-log: 
,08-25 13:18:35.201  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
08-25 13:18:35.201  6760  6815 I jxcore-log: 
,08-25 13:18:35.311  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
08-25 13:18:35.311  6760  6815 I jxcore-log: 
,08-25 13:18:35.321  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
08-25 13:18:35.321  6760  6815 I jxcore-log: 
,08-25 13:18:35.351  6760  6815 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
08-25 13:18:35.351  6760  6815 I jxcore-log: 
,08-25 13:18:35.371  6760  6815 D ExecuteNativeTests: Running unit tests,
,08-25 13:18:35.461  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:18:35.461  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 added. We now have 2 listener(s)
,08-25 13:18:35.461  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 13:18:35.461  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:18:35.461  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 13:18:35.461  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:35.461  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 added. We now have 2 listener(s)
08-25 13:18:35.461  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:35.461  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:18:35.471  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:35.471  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:35.471  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:35.471  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:35.471  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:35.471  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-25 13:18:35.471  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:35.471  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:35.471  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:35.471  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:35.471  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:18:35.471  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:35.471  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 13:18:35.471  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 13:18:35.471  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 13:18:35.471  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:35.481  6760  6815 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-25 13:18:35.481  6760  6815 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 13:18:35.481  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 13:18:35.481  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 13:18:35.481  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.481  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.481  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.481  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.481  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:35.481  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 removed from the list
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.481  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 removed from the list
,08-25 13:18:35.481  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.481  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.481  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.481  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.481  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.481  6760  6815 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 13:18:35.481  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.481  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.481  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.481  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.481  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.481  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.481  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.481  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.481  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.481  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.481  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.481  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.481  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.481  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnect,ions: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 13:18:35.491  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.491  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.491  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.491  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.491  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.491  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.491  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.491  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.491  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.491  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.491  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.491  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.491  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.491  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.491  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.491  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.491  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.491  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.491  6760  6815 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 13:18:35.491  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:35.501  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:35.501  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:35.501  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:35.501  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:35.501  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:35.501  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:35.501  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:35.501  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:18:35.501  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:35.501  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:18:35.501  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:18:35.501  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:18:35.501  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:18:35.501  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:35.501  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:18:35.501  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:35.501  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 13:18:35.501  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:35.511  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 13:18:35.521  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:18:35.521  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-25 13:18:35.521  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-25 13:18:35.521  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 13:18:35.521  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 13:18:35.521  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 13:18:35.551  3163  3373 D BtGatt.GattService: registerClient() - UUID=f8cf40c9-cc7c-4918-bf37-25489c8a7dc9
,08-25 13:18:35.591  3163  3255 D BtGatt.GattService: onClientRegistered() - UUID=f8cf40c9-cc7c-4918-bf37-25489c8a7dc9, clientIf=6
,08-25 13:18:35.601  6760  6768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 13:18:35.601  3163  3171 D BtGatt.GattService: start scan with filters
,08-25 13:18:35.601  3163  3269 D BtGatt.ScanManager: handling starting scan
,08-25 13:18:35.601  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 13:18:35.601  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 13:18:35.601  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 13:18:35.611  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:18:35.611  3163  3269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:35.611  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:18:35.611  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:18:35.621  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 13:18:35.621  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-25 13:18:35.621  3163  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 13:18:35.631  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.631  3163  3269 D BtGatt.ScanManager: allow scan with filters
08-25 13:18:35.631  3163  3269 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 13:18:35.631  6760  6815 I io.jxcore.node.ConnectionHelper: start: OK
08-25 13:18:35.631  3163  3269 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-25 13:18:35.631  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:35.631  6760  6815 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 13:18:35.631  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.631  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 13:18:35.631  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.631  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 13:18:35.631  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 13:18:35.631  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:35.631  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:35.631  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:18:35.631  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:18:35.631  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 13:18:35.631  3163  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 13:18:35.631  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.641  3163  3173 D BtGatt.GattService: stopScan() - queue size =1
08-25 13:18:35.641  3163  3269 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 13:18:35.641  3163  3171 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 13:18:35.641  3163  3269 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 13:18:35.641  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 13:18:35.641  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 13:18:35.641  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:18:35.641  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 13:18:35.641  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 13:18:35.641  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:35.641  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:18:35.641  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 13:18:35.641  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 13:18:35.641  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:18:35.641  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,08-25 13:18:35.641  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:35.641  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:35.641  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.641  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 13:18:35.641  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:18:35.641  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.641  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:35.651  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.651  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.651  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.651  6760  6815 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 13:18:35.651  3163  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 13:18:35.651  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.651  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:35.661  3163  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 13:18:35.661  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.661  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-25 13:18:35.661  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:35.661  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:35.661  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:35.661  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:35.661  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:35.661  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:35.661  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:35.661  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:18:35.661  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:18:35.661  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:18:35.661  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:18:35.661  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:18:35.661  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:35.661  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 13:18:35.671  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:35.671  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:35.671  3163  3269 D BtGatt.ScanManager: filter size is 1
08-25 13:18:35.671  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 13:18:35.671  3163  3269 D BtGatt.ScanManager: delete FilterIndex - 3
,08-25 13:18:35.681  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:18:35.681  3163  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 13:18:35.681  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.681  3163  3269 D BtGatt.ScanManager: stopping BLe Batch
,08-25 13:18:35.681  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:18:35.681  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 13:18:35.681  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 13:18:35.681  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 13:18:35.691  3163  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 13:18:35.691  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.691  3163  3269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 13:18:35.691  3163  3373 D BtGatt.GattService: registerClient() - UUID=cfab563e-525f-4f8b-bb4f-a106ae7aaf98
,08-25 13:18:35.691  3163  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 13:18:35.691  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.721   287   287 E SMD     : DCD OFF
,08-25 13:18:35.731  3163  3255 D BtGatt.GattService: onClientRegistered() - UUID=cfab563e-525f-4f8b-bb4f-a106ae7aaf98, clientIf=6
,08-25 13:18:35.731  6760  6771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 13:18:35.731  3163  3173 D BtGatt.GattService: start scan with filters
,08-25 13:18:35.731  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 13:18:35.731  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:18:35.731  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 13:18:35.731  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:18:35.731  3163  3269 D BtGatt.ScanManager: handling starting scan
,08-25 13:18:35.741  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:18:35.741  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:18:35.741  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 13:18:35.741  3163  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 13:18:35.741  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:35.741  3163  3269 D BtGatt.ScanManager: allow scan with filters
,08-25 13:18:35.741  3163  3269 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 13:18:35.741  3163  3269 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-25 13:18:35.741  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 13:18:35.751  3163  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 13:18:35.751  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.751  3163  3269 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 13:18:35.751  3163  3269 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 13:18:35.751  6760  6815 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 13:18:35.761  3163  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 13:18:35.761  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.761  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:35.761  6760  6815 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 13:18:35.761  3163  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 13:18:35.761  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.771  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.771  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 13:18:35.771  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.771  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 13:18:35.771  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 13:18:35.771  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:35.771  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:35.771  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:18:35.771  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:18:35.771  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 13:18:35.771  3163  3171 D BtGatt.GattService: stopScan() - queue size =1
,08-25 13:18:35.771  3163  3373 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 13:18:35.771  3163  3269 D BtGatt.ScanManager: filter size is 1
08-25 13:18:35.771  3163  3269 D BtGatt.ScanManager: delete FilterIndex - 4
,08-25 13:18:35.771  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:18:35.771  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 13:18:35.771  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:18:35.771  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 13:18:35.771  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 13:18:35.771  3163  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 13:18:35.771  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:35.771  3163  3269 D BtGatt.ScanManager: stopping BLe Batch
,08-25 13:18:35.771  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 13:18:35.771  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:18:35.771  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-25 13:18:35.771  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 13:18:35.781  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:35.781  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:18:35.781  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:35.781  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:35.781  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.781  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:35.781  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:18:35.781  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.781  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.781  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.781  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.781  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.781  3163  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 13:18:35.781  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.781  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 13:18:35.781  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.781  3163  3269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-25 13:18:35.781  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:35.781  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.781  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.781  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.781  6760  6815 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 13:18:35.781  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:35.791  3163  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 13:18:35.791  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.791  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:35.791  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:35.791  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:35.791  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:35.791  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:35.791  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:35.791  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:35.791  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:35.791  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:18:35.791  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:18:35.801  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:35.801  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:35.801  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 13:18:35.801  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:18:35.801  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 13:18:35.801  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:35.801  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 13:18:35.811  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 13:18:35.811  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:18:35.811  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:18:35.821  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 13:18:35.821  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 13:18:35.821  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 13:18:35.821  3163  3373 D BtGatt.GattService: registerClient() - UUID=d04c23c7-89b8-4b16-9b52-0446bb971d9d
,08-25 13:18:35.861  3163  3255 D BtGatt.GattService: onClientRegistered() - UUID=d04c23c7-89b8-4b16-9b52-0446bb971d9d, clientIf=6
,08-25 13:18:35.861  6760  6771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 13:18:35.861  3163  3171 D BtGatt.GattService: start scan with filters
,08-25 13:18:35.861  3163  3269 D BtGatt.ScanManager: handling starting scan
,08-25 13:18:35.871  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 13:18:35.871  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:18:35.871  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 13:18:35.871  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:18:35.871  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-25 13:18:35.871  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:18:35.871  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 13:18:35.871  3163  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-25 13:18:35.871  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.881  3163  3269 D BtGatt.ScanManager: allow scan with filters
08-25 13:18:35.881  3163  3269 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 13:18:35.881  3163  3269 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-25 13:18:35.881  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 13:18:35.881  6760  6815 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 13:18:35.881  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:35.881  6760  6815 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 13:18:35.881  3163  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 13:18:35.881  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.881  3163  3269 D BtGatt.ScanManager: Starting BLE batch scan
08-25 13:18:35.881  3163  3269 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 13:18:35.881  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:18:35.881  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 13:18:35.891  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.891  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 13:18:35.891  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 13:18:35.891  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:35.891  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:35.891  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 13:18:35.891  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:18:35.891  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 13:18:35.891  3163  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 13:18:35.891  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.891  3163  3173 D BtGatt.GattService: stopScan() - queue size =1
,08-25 13:18:35.891  3163  3373 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 13:18:35.901  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 13:18:35.901  3163  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 13:18:35.901  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.901  3163  3269 D BtGatt.ScanManager: filter size is 1
,08-25 13:18:35.901  3163  3269 D BtGatt.ScanManager: delete FilterIndex - 5
,08-25 13:18:35.901  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 13:18:35.901  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:18:35.901  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 13:18:35.901  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 13:18:35.911  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 13:18:35.911  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 13:18:35.911  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 13:18:35.911  3163  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 13:18:35.911  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:35.911  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 13:18:35.911  3163  3269 D BtGatt.ScanManager: stopping BLe Batch
,08-25 13:18:35.911  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:35.911  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:18:35.911  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:18:35.911  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:35.911  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.911  6760  6815 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 13:18:35.911  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.911  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.911  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.911  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.911  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:18:35.911  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.911  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.911  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.911  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.911  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.911  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.911  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.921  3163  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.921  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.921  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:35.921  3163  3269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-25 13:18:35.921  6760  6815 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-25 13:18:35.921  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.921  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.921  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.921  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.921  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.921  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.921  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.921  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.921  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.921  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.921  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.921  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.921  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.921  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 13:18:35.921  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.921  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:18:35.921  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.921  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.921  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.921  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.921  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.921  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.921  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.921  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 13:18:35.921  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.921  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.921  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.921  6760  6815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 13:18:35.921  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:35.921  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.921  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.921  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:35.921  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.921  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.921  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.921  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.921  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 13:18:35.921  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.921  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.921  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:35.921  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.921  3163  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 13:18:35.921  3163  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:35.931  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list,
08-25 13:18:35.931  6760  6815 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-25 13:18:35.931  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.931  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.931  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:18:35.931  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.931  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 13:18:35.931  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list,
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:35.931  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.931  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.931  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:35.931  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.931  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.931  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.931  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 13:18:35.931  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 13:18:35.931  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 13:18:35.931  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 13:18:35.931  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.931  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.931  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.931  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.931  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.931  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.931  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.931  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.931  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.931  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.931  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.931  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.931  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.931  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.931  6760  6815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:18:35.931  6760  6815 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 13:18:35.931  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 13:18:35.941  6760  6815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:18:35.941  6760  6815 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
,08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 13:18:35.941  6760  6815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 13:18:35.941  6760  6815 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 13:18:35.941  6760  6815 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 13:18:35.941  6760  6815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:18:35.941  6760  6815 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 13:18:35.941  6760  6815 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 13:18:35.941  6760  6815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:18:35.941  6760  6815 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 13:18:35.941  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 13:18:35.941  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 13:18:35.941  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-25 13:18:35.941  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 13:18:35.941  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 13:18:35.941  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 13:18:35.941  6760  6815 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 13:18:35.941  6760  6815 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:18:35.941  6760  6815 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 13:18:35.941  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.941  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.941  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.941  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.941  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:35.941  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.941  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 13:18:35.941  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.941  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.941  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.941  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.941  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.941  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.941  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.941  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.951  6760  6900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1304
08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.951  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.951  6760  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1304)
08-25 13:18:35.951  6760  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1304)
,08-25 13:18:35.951  6760  6815 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 13:18:35.951  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.951  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.951  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.951  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.951  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.951  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
,08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.951  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.951  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.951  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.951  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.951  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.951  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.951  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.951  6760  6815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 13:18:35.951  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.951  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.951  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.951  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.951  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.951  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.951  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.951  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.951  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.951  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.951  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.951  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.951  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.951  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.961  6760  6815 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 13:18:35.961  6760  6815 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 13:18:35.961  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-25 13:18:35.961  6760  6815 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 13:18:35.961  6760  6815 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 13:18:35.961  6760  6815 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 13:18:35.961  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 13:18:35.961  6760  6815 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 13:18:35.961  6760  6815 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-25 13:18:35.961  6760  6815 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 13:18:35.961  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 13:18:35.961  6760  6815 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 13:18:35.961  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.961  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.961  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.961  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.961  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.961  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.961  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.961  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.961  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.961  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.961  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.961  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.961  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.961  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.961  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.961  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.961  6760  6815 W org.thali,project.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.961  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.961  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-25 13:18:35.961  6760  6815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 13:18:35.961  6760  6760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 13:18:35.961  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-25 13:18:35.971  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:18:35.971  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.971  6760  6760 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:35.971  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.971  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.971  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.971  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.971  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.971  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:35.971  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.971  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.971  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:35.971  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.971  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.971  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.971  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.971  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.971  6760  6815 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-25 13:18:35.971  6760  6815 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 13:18:35.971  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 13:18:35.971  6760  6901 D BluetoothSocket: bindListen(): myUserId = 0
08-25 13:18:35.971  6760  6901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:18:35.971  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.971  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.971  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.971  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.971  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.971  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.971  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.971  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.971  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.971  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.971  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.981  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.981  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.981  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.981  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.981  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.981  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.981  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.981  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.981  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.981  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.981  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.981  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.981  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.981  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.981  6760  6901 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-25 13:18:35.981  6760  6901 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 13:18:35.981  6760  6901 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 13:18:35.981  6760  6901 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d6f6118
08-25 13:18:35.981  6760  6901 D BluetoothSocket: channel: 6
08-25 13:18:35.981  6760  6901 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@891d771, channel: 6, state: LISTENING
08-25 13:18:35.981  6760  6901 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@891d771, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d6f6118, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28235956mSocket: android.net.LocalSocket@ac96dd7 impl:android.net.LocalSocketImpl@28576c4 fd:FileDescriptor[106]
08-25 13:18:35.981  6760  6901 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@ac96dd7 impl:android.net.LocalSocketImpl@28576c4 fd:FileDescriptor[106]
08-25 13:18:35.981  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:35.981  6760  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 13:18:35.981  6760  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 13:18:35.981  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:35.981  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:35.981  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.981  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.981  6760  6815 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1276ec01 not in the list
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.981  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
08-25 13:18:35.981  6760  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 13:18:35.981  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:35.981  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:35.981  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.981  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release,: The given listener does not exist in the list - probably already removed
08-25 13:18:35.981  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:35.981  6760  6760 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:35.981  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:35.981  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2250faa6 not in the list
,08-25 13:18:35.991  6760  6815 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 13:18:35.991  6760  6815 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 13:18:35.991  6760  6815 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-25 13:18:35.991  6760  6815 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 13:18:35.991  6760  6815 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 13:18:35.991  6760  6815 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 13:18:35.991  6760  6815 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-25 13:18:35.991  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:35.991  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c9b79ad added. We now have 2 listener(s)
08-25 13:18:35.991  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:35.991  6760  6815 D BluetoothAdapter: enable()
,08-25 13:18:35.991  6760  6815 D BluetoothAdapter: enable(): BT is already enabled..!
,08-25 13:18:36.001  1014  1452 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-25 13:18:36.001  1014  1452 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 13:18:36.001  1014  1452 D SecContentProvider2: mCursor = null
,08-25 13:18:36.001  1014  1452 D WifiService: setWifiEnabled: true pid=6760, uid=10171
,08-25 13:18:36.001  1014  1452 W ActivityManager: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 13:18:36.001  1014  1452 W WifiService: Failed getting userId using ActivityManagerNative
08-25 13:18:36.001  1014  1452 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 13:18:36.001  1014  1452 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 13:18:36.001  1014  1452 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 13:18:36.001  1014  1452 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 13:18:36.001  1014  1452 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 13:18:36.001  1014  1452 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 13:18:36.001  1014  1452 D SettingsProvider: name = wifi_on
,08-25 13:18:36.001  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-25 13:18:36.001  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1613b4e2 added. We now have 3 listener(s)
08-25 13:18:36.001  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:36.011  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-25 13:18:36.011  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@304d1073 added. We now have 4 listener(s)
08-25 13:18:36.011  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:36.011  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:18:36.011  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37c53b30 added. We now have 5 listener(s)
08-25 13:18:36.011  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:36.011  1014  1244 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 13:18:36.011  1014  1244 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 13:18:36.011  1014  1244 D SecContentProvider2: mCursor = null
08-25 13:18:36.011  1014  1244 D WifiService: setWifiEnabled: false pid=6760, uid=10171
08-25 13:18:36.011  1014  1244 D SettingsProvider: name = wifi_on
,08-25 13:18:36.021  6760  6815 D BluetoothAdapter: disable()
,08-25 13:18:36.021  1014  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 13:18:36.021  1351  1351 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 13:18:36.021  1351  1351 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-25 13:18:36.031  1351  1351 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-25 13:18:36.031  1014  1027 D SettingsProvider: name = bluetooth_on
08-25 13:18:36.031  1351  1351 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 13:18:36.031  3163  3252 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-25 13:18:36.031  3163  3252 D BluetoothAdapterProperties: Setting state to 13
08-25 13:18:36.031  3163  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 13:18:36.031  3163  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 13:18:36.031  3163  3252 D BluetoothAdapterService: updateAdapterState state is 13
,08-25 13:18:36.041  1014  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:36.041  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:36.041  1014  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.041  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:36.041  1014  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.041  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.041  3163  3163 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-25 13:18:36.041  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 13:18:36.041  3163  3252 D BluetoothAdapterService: Autoconnection is available 
08-25 13:18:36.041  3163  3252 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-25 13:18:36.041  3163  3252 D BluetoothAdapterService: terminating service from this receiver
,08-25 13:18:36.041  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-25 13:18:36.041  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.041  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.041  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.041  3163  3163 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2aebc4f4, channel: 19, state: LISTENING
08-25 13:18:36.041  3163  3163 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2aebc4f4, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ef7065c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@251d641dmSocket: android.net.LocalSocket@d72a692 impl:android.net.LocalSocketImpl@f7d9863 fd:FileDescriptor[74]
08-25 13:18:36.041  3163  3163 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d72a692 impl:android.net.LocalSocketImpl@f7d9863 fd:FileDescriptor[74]
,08-25 13:18:36.041  3163  3252 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 13:18:36.041  3163  3252 D BluetoothAdapterProperties: mDiscovering is false
08-25 13:18:36.051  1014  1514 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-25 13:18:36.051  3163  3252 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-25 13:18:36.051  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:36.051  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-25 13:18:36.051  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:36.051  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:36.051  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:36.051  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:36.051  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:36.051  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:36.051  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:36.051  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:36.051  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:36.051  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:36.051  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:36.051  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:18:36.051  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:36.061  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-25 13:18:36.061  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:36.061  1885  1885 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 13:18:36.061  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 13:18:36.061  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:36.061  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-25 13:18:36.061  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 13:18:36.061  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:36.061  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 13:18:36.071  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
08-25 13:18:36.071  1014  1452 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-25 13:18:36.071  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 13:18:36.071  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 13:18:36.071  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:36.071  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:36.071  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:36.071  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:36.071  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:36.071  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:36.071  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:36.071  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:36.071  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:36.071  1014  1125 E WifiNative-wlan0: do suspend true
,08-25 13:18:36.081  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:36.081  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:36.081  1014  1451 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 13:18:36.081  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.081  3163  3255 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 13:18:36.081  3163  3255 D BluetoothAdapterProperties: Scan Mode:20
,08-25 13:18:36.081  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.081  1014  1451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:36.081  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:36.081  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:36.081  3163  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 13:18:36.081  3163  3252 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-25 13:18:36.081  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:36.091  3163  3252 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-25 13:18:36.091  3163  3252 E bt-btif : BTM_SEC_CLR[17]: id 57
08-25 13:18:36.091  3163  5233 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:18:36.091  3163  3295 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-25 13:18:36.091  3163  3295 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 13:18:36.091  3163  3252 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 13:18:36.091  3163  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 13:18:36.091  3163  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:36.091  3163  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:18:36.101  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:36.101  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:18:36.101  1014  1451 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 13:18:36.101  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.101  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.101  1014  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.101  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 13:18:36.101  1296  1296 D BluetoothPbap: Proxy object disconnected
08-25 13:18:36.101  1296  1296 D PbapServerProfile: Bluetooth service disconnected
,08-25 13:18:36.111  3163  3163 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c7a3c60, channel: 5, state: LISTENING
08-25 13:18:36.111  3163  3163 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c7a3c60, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a45ed65, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@30b12519mSocket: android.net.LocalSocket@3f1099de impl:android.net.LocalSocketImpl@8a757bf fd:FileDescriptor[76]
08-25 13:18:36.111  3163  3163 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3f1099de impl:android.net.LocalSocketImpl@8a757bf fd:FileDescriptor[76]
,08-25 13:18:36.111  3163  3163 I BtOppRfcommListener: stopping Accept Thread
08-25 13:18:36.111  3163  3163 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@8b6be8c, channel: 12, state: LISTENING
08-25 13:18:36.111  3163  3163 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@8b6be8c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@59c56c7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1025f9d5mSocket: android.net.LocalSocket@20875ea impl:android.net.LocalSocketImpl@e83b0db fd:FileDescriptor[79]
08-25 13:18:36.111  3163  3163 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@20875ea impl:android.net.LocalSocketImpl@e83b0db fd:FileDescriptor[79]
08-25 13:18:36.111  3163  5233 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 13:18:36.111  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:36.121  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 13:18:36.121  3163  3163 V BluetoothOppManager: cleanUp...
,08-25 13:18:36.121  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:36.131  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 13:18:36.131  1014  1487 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-25 13:18:36.131  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:36.131  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:36.131  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:36.131  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:36.141  6909  6909 E Zygote  : MountEmulatedStorage()
,08-25 13:18:36.151  6909  6909 I libpersona: KNOX_SDCARD checking this for 10055
08-25 13:18:36.141  6909  6909 E Zygote  : v2
08-25 13:18:36.151  6909  6909 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:36.151  6909  6909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 13:18:36.151  1014  1487 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6909 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-25 13:18:36.151  6909  6909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:36.151  6909  6909 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:36.191  6909  6909 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:36.191  6909  6909 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:36.221  6909  6909 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-25 13:18:36.251  6909  6909 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-25 13:18:36.251  6909  6909 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-25 13:18:36.251  6909  6909 D UserAnalysis: Create SecureDbHelper
,08-25 13:18:36.261  6909  6909 D IntelligenceServiceApplication: onCreate()
,08-25 13:18:36.261  1014  1452 I ActivityManager: Killing 6358:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-25 13:18:36.271  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-25 13:18:36.271  6909  6909 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-25 13:18:36.271  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:36.271  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:36.271  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:36.271  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:36.281  1014  1027 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6927 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
08-25 13:18:36.281  6927  6927 E Zygote  : MountEmulatedStorage()
08-25 13:18:36.281  6927  6927 I libpersona: KNOX_SDCARD checking this for 10105
08-25 13:18:36.281  6927  6927 E Zygote  : v2
08-25 13:18:36.281  6927  6927 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:36.291  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-25 13:18:36.291  6909  6909 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-25 13:18:36.291  6927  6927 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:36.291  3163  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:18:36.291  3163  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:36.291  3163  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:18:36.291  3163  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:18:36.291  3163  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:36.291  3163  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:18:36.291  3163  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:18:36.291  3163  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:36.291  3163  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:18:36.291  3163  3295 W bt-btif : ag scb idx 1 not allocated
08-25 13:18:36.291  3163  3295 W bt-btif : ag scb idx 2 not allocated
08-25 13:18:36.291  3163  3295 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 13:18:36.291  3163  3346 I bt_userial_mct: exiting userial_read_thread
08-25 13:18:36.291  3163  3346 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 13:18:36.291  3163  3255 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 13:18:36.291  3163  3297 I bt_vendor: hw_epilog_process
08-25 13:18:36.291  3163  3255 D bt_userial_mct: userial_close
08-25 13:18:36.291  3163  3255 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 13:18:36.291  6909  6909 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-25 13:18:36.291  6927  6927 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:36.301  6927  6927 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 13:18:36.321  6927  6927 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:36.321  6927  6927 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:36.451   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 13:18:36.451   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:18:36.451  6927  6947 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 13:18:36.461   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 13:18:36.461   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:18:36.461  6927  6947 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 13:18:36.471  6760  6760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 13:18:36.551  3163  3255 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 13:18:36.551  3163  3255 I bt_vendor: bluetooth satus is on
08-25 13:18:36.551  3163  3255 I bt_vendor: bt-vendor : resetting BT status
08-25 13:18:36.551  3163  3255 I bt_vendor: Starting hciattach daemon
08-25 13:18:36.551  3163  3255 I bt_vendor: try to set false
,08-25 13:18:36.551  3163  3255 I bt_vendor: Starting hciattach daemon
08-25 13:18:36.551  3163  3255 I bt_vendor: try to set false
,08-25 13:18:36.551  3163  3255 I bt_vendor: cleanup
,08-25 13:18:36.551  3163  3295 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 13:18:36.551  3163  3255 I GKI_LINUX: GKI_exit_task 0 done
08-25 13:18:36.551  3163  3255 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-25 13:18:36.551  3163  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-25 13:18:36.551  3163  3252 D BtConfig.SecureMode: isSecureModeOn:false
08-25 13:18:36.551  3163  3252 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-25 13:18:36.551  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 13:18:36.551  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 13:18:36.551  3163  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 13:18:36.551  1014  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:36.551  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.551  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.551  1014  1460 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.561  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.561  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 13:18:36.561  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:36.561  3163  3163 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 13:18:36.561  3163  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:36.561  3163  3163 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 13:18:36.561  3163  3163 D BtGatt.GattService: stop()
08-25 13:18:36.561  1014  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:36.561  3163  3163 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 13:18:36.561  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.561  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.561  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.561  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.561  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 13:18:36.561  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 13:18:36.561  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:36.561  3163  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-25 13:18:36.561  3163  3163 D HeadsetService: Received stop request...Stopping profile...
,08-25 13:18:36.561  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:36.561  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.561  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.561  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.561  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.561  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-25 13:18:36.561  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 13:18:36.561  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:36.571  3163  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 13:18:36.571  1014  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:36.571  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.571  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.571  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.571  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.571  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-25 13:18:36.571  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 13:18:36.571  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 13:18:36.571  3163  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 13:18:36.571  1296  1296 D HeadsetProfile: Bluetooth service disconnected
,08-25 13:18:36.571  1014  4344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:36.571  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.571  1014  4344 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.571  1014  4344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.571  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.571  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 13:18:36.571  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 13:18:36.571  3163  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 13:18:36.581  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:36.581  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-25 13:18:36.581  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.581  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.581  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.581  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 13:18:36.581  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:36.581  3163  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 13:18:36.581  1014  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:36.581  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-25 13:18:36.581  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.581  1014  1460 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.581  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.581  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-25 13:18:36.581  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 13:18:36.581  3163  3252 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 13:18:36.581  1014  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:36.581  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.581  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.581  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.581  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:36.581  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:36.581  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 13:18:36.581  3163  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:36.581  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:36.581  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 13:18:36.591  3163  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:36.591  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 13:18:36.591  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 13:18:36.591  3163  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 13:18:36.591  3163  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 13:18:36.591  3163  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 13:18:36.591  1351  1351 I wpa_supplicant: nl80211: Received scan results (16 BSSes)
,08-25 13:18:36.591  3163  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-25 13:18:36.591  3163  3252 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 13:18:36.591  3163  3163 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-25 13:18:36.591  3163  3163 D A2dpService: Received stop request...Stopping profile...
,08-25 13:18:36.591  3163  3279 D A2dpStateMachine: Exit Disconnected: -1
,08-25 13:18:36.591  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:36.591  1014  1014 D BluetoothA2dp: Proxy object disconnected
,08-25 13:18:36.591  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 13:18:36.601  3163  3163 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-25 13:18:36.601  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 13:18:36.601  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 13:18:36.601  1014  1124 D WifiP2pService: InactiveState{ what=147461 }
08-25 13:18:36.601  1014  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-25 13:18:36.601  1014  1124 D WifiP2pService: DefaultState{ what=147461 }
08-25 13:18:36.601  1296  1296 D BluetoothA2dp: Proxy object disconnected
08-25 13:18:36.601  3163  3163 D HidService: Received stop request...Stopping profile...
08-25 13:18:36.601  3163  3163 D HidService: Stopping Bluetooth HidService
08-25 13:18:36.601  3163  3163 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 13:18:36.601  3163  3163 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-25 13:18:36.601  3163  3163 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 13:18:36.601  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:36.601  1296  1296 D A2dpProfile: Bluetooth service disconnected
,08-25 13:18:36.601   277  1013 D CommandListener: Clearing all IP addresses on wlan0,
08-25 13:18:36.601  1994  3020 V NativeCrypto: Read error: ssl=0xb93a1ef0: I/O error during system call, Connection timed out
08-25 13:18:36.601  1994  3020 V NativeCrypto: SSL shutdown failed: ssl=0xb93a1ef0: I/O error during system call, Broken pipe
,08-25 13:18:36.601  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:36.611  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 13:18:36.611  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.611  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.611  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.611  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:36.611  1994  3020 E GCM     : Wifi connection closed with errorCode 20
,08-25 13:18:36.611  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
08-25 13:18:36.611  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
08-25 13:18:36.611  1296  1296 D BluetoothInputDevice: Proxy object disconnected
08-25 13:18:36.611  1296  1296 D HidProfile: Bluetooth service disconnected
,08-25 13:18:36.611  1014  1495 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-25 13:18:36.611  3163  3163 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 13:18:36.611  3163  3163 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 13:18:36.611  1014  1127 E ConnectivityService: updateNetworkInfo()
,08-25 13:18:36.611  3163  3163 D HealthService: Received stop request...Stopping profile...
08-25 13:18:36.611  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
08-25 13:18:36.611  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 13:18:36.621  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:36.621  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-25 13:18:36.621  1014  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:36.621  1014  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:36.621  1014  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 13:18:36.621  1014  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:36.621  1014  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-25 13:18:36.621  3163  3163 D PanService: Received stop request...Stopping profile...
08-25 13:18:36.621  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
08-25 13:18:36.621  1014  1763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 13:18:36.621  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 13:18:36.621  1014  1763 I qtaguid : Tagging socket 354 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1014, getuid(): 1000
,08-25 13:18:36.631  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:36.631  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:36.631  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
08-25 13:18:36.631  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:36.631  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-25 13:18:36.631  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.631  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.631  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.631  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-25 13:18:36.631  3163  3163 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 13:18:36.631  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 13:18:36.641  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,08-25 13:18:36.641  1296  1296 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 13:18:36.641  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-25 13:18:36.641  1296  1296 D PanProfile: Bluetooth service disconnected
08-25 13:18:36.641  1014  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:36.641  1014  1149 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 13:18:36.641  1014  1763 I qtaguid : Untagging socket 354
08-25 13:18:36.641  1014  1763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 13:18:36.641  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 13:18:36.641  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:36.651  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 13:18:36.651  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-25 13:18:36.651  1296  1296 D BluetoothMap: Proxy object disconnected
,08-25 13:18:36.651  1296  1296 D MapProfile: Bluetooth service disconnected
,08-25 13:18:36.651  3163  3163 D SapService: Received stop request...Stopping profile...
,08-25 13:18:36.651  3163  3163 D SapService: Stopping Bluetooth SapService
08-25 13:18:36.661  3163  3163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
08-25 13:18:36.661  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 13:18:36.661  1014  1124 D WifiP2pService: P2pDisablingState
08-25 13:18:36.661  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-25 13:18:36.661  1014  1124 D WifiP2pService: p2p socket connection lost
08-25 13:18:36.661  1014  1124 D WifiP2pService: P2pDisabledState
08-25 13:18:36.661  1014  1125 E WifiNative-wlan0: do suspend true
,08-25 13:18:36.661  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-25 13:18:36.661  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
08-25 13:18:36.661  1296  1296 D SapProfile: Bluetooth service disconnected
08-25 13:18:36.661  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
08-25 13:18:36.661  3163  3163 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-25 13:18:36.661  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 13:18:36.661  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 13:18:36.661  3163  3163 D BluetoothA2dp: Proxy object disconnected
08-25 13:18:36.661  6927  6927 D StrictMode: StrictMode policy violation; ~duration=199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145),
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:36.661  3163  3163 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-25 13:18:36.661  6927  6927 D StrictMode: StrictMode policy violation; ~duration=198 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
,08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:36.661  6927  6927 D StrictMode: StrictMode policy violation; ~duration=197 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
,08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:36.661  6927  6927 D StrictMode: ,	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 13:18:36.671  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 13:18:36.661  6927  6927 D StrictMode: StrictMode policy violation; ~duration=195 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 13:18:36.671  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 13:18:36.661  6927  6927 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.k.d(PG:583)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.v.a(PG:1161)
,08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
,08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:36.671  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-25 13:18:36.661  6927  6927 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:36.661  6927  6927 D StrictMode: ,	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020),
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:36.671  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 13:18:36.661  6927  6927 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:36.671  1014  1046 D WifiDisplayController: disconnect
08-25 13:18:36.661  6927  6927 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.StrictMode$A,ndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:36.661  6927  6927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:36.671  1014  1046 D WifiDisplayController: updateConnection
08-25 13:18:36.671  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-25 13:18:36.671  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 13:18:36.671  3163  3280 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 13:18:36.671  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 13:18:36.671  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:36.671  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
08-25 13:18:36.671  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:36.671  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 13:18:36.671  1176  1176 D StatusBar.NetworkController: refres,hNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.671  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 13:18:36.671  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.671  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 13:18:36.671  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.671  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-25 13:18:36.671  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.671  1014  1460 I ActivityManager: Killing 6497:com.google.android.gms:car/u0a11 (adj 15): empty #21
08-25 13:18:36.671  3163  3163 I GKI_LINUX: GKI_exit_task 2 done
08-25 13:18:36.681  1014  4344 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 13:18:36.671  3163  3163 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 13:18:36.681  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-25 13:18:36.671  3163  3163 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-25 13:18:36.671  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:36.671  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:36.671  3163  3163 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-25 13:18:36.671  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:36.671  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:36.671  3163  3163 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 13:18:36.671  3163  3163 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 13:18:36.671  3163  3163 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-25 13:18:36.671  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:36.671  3163  3163 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:36.681  3163  3163 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 13:18:36.681  3163  3163 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 13:18:36.681  3163  3163 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-25 13:18:36.681  3163  3163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 13:18:36.681  3163  3163 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-25 13:18:36.681  3163  3163 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-25 13:18:36.681  3163  3163 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-25 13:18:36.681  3163  3163 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-25 13:18:36.681  3163  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-25 13:18:36.681  3163  3252 D BluetoothAdapterProperties: Setting state to 10
08-25 13:18:36.681  3163  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 13:18:36.681  3163  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 13:18:36.681  3163  3252 D BluetoothAdapterService: updateAdapterState state is 10
08-25 13:18:36.681  1994  1994 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 13:18:36.691  3163  3252 D BluetoothAdapterService: Autoconnection is available 
08-25 13:18:36.691  3163  3252 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 13:18:36.691  3163  3252 I BluetoothAdapterState: Entering OffState
08-25 13:18:36.691  3163  3373 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:36.691  3163  3373 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 13:18:36.691  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 13:18:36.691  1994  1994 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-25 13:18:36.691  1296  1311 D BluetoothMap: onBluetoothStateChange: up=false
08-25 13:18:36.701  1014  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 13:18:36.701  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 13:18:36.701  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.711  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:36.711  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 13:18:36.711   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 13:18:36.711   277  1009 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-25 13:18:36.711   277  1013 D CommandListener: Clearing all IP addresses on wlan0
08-25 13:18:36.711  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.711  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-25 13:18:36.711  1616  1616 I Hs20UtilService: Starting #8
08-25 13:18:36.711  1014  1127 V NetworkStats: updateIfacesLocked()
08-25 13:18:36.711  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:36.711  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
08-25 13:18:36.711  1014  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 13:18:36.711  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:36.711  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 13:18:36.711  1616  1645 I Hs20UtilService: Message received 5007
08-25 13:18:36.711  1014  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-25 13:18:36.711  1014  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-25 13:18:36.711  1994  2005 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:36.711  1994  2005 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 13:18:36.711  1296  1311 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:36.711  1296  1311 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 13:18:36.711  1296  1317 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 13:18:36.711  1014  1127 V NetworkStats: performPollLocked() took 6ms
08-25 13:18:36.711  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.721  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 13:18:36.721  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 13:18:36.721  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 13:18:36.721  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-25 13:18:36.721  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:36.721  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 13:18:36.721  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 13:18:36.721  1351  1351 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-25 13:18:36.721  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 13:18:36.721  6760  6768 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:36.721  6760  6768 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 13:18:36.721  6760  6768 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-25 13:18:36.721  6760  6768 D BluetoothLeAdvertiser: Exit stop advertising
08-25 13:18:36.721  6760  6768 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-25 13:18:36.721  6760  6768 D BluetoothLeScanner: Exiting stopAllScan
08-25 13:18:36.721  1296  1311 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 13:18:36.731  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.731  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-25 13:18:36.731  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.731  1176  1747 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 13:18:36.731  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:36.731  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:36.731  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.731  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.731  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.731  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.731  4815  6824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 13:18:36.731  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:36.731  1014  1125 D SecContentProvider2: mCursor = null
08-25 13:18:36.741  1014  1763 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:36.741  1014  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:18:36.741  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 13:18:36.741  1475  1475 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 13:18:36.741  1475  1475 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:18:36.741  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:36.741  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 13:18:36.741  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.741  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.741  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.741  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.741  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-25 13:18:36.741  1014  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-25 13:18:36.741  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 13:18:36.741  6927  6957 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-25 13:18:36.741  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:36.741  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-25 13:18:36.751  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 13:18:36.751  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:36.751  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:36.751  1176  1176 D HotspotTile: onReceive : 0, 0
08-25 13:18:36.761  1456  1472 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:36.761  1456  1472 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:36.761  3163  3173 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 13:18:36.761  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-25 13:18:36.771  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-25 13:18:36.771  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,08-25 13:18:36.771  1014  1122 V NetworkStats: updateIfacesLocked()
08-25 13:18:36.771  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.771  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-25 13:18:36.771  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:36.771  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:36.771  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:36.771  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:36.771  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:36.771  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:36.771  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:36.771  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:36.771  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:36.771  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:36.771  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 13:18:36.771  1176  1176 D StatusBar.NetworkController: EthernetConnected: false,
08-25 13:18:36.771  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 13:18:36.771  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-25 13:18:36.771  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-25 13:18:36.771  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0,
08-25 13:18:36.771  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-25 13:18:36.771  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:36.771  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:18:36.771  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:36.771  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:36.771  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-25 13:18:36.771  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.771  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.781  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:36.781  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:18:36.781  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 13:18:36.781  1014  1122 V NetworkStats: performPollLocked() took 11ms
08-25 13:18:36.781  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:36.781  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:36.781  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:36.781  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:36.781  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:36.781  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:36.781  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:36.781  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:18:36.781  1014  1452 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-25 13:18:36.781  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-25 13:18:36.781  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.781  1014  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:36.781  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-25 13:18:36.781  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 13:18:36.781  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:36.781  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 13:18:36.781  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:36.781  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.781  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:36.781  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.781  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:36.781  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.781  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:36.781  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:36.781  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:36.781  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:18:36.781  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
,08-25 13:18:36.781  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-25 13:18:36.781  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:36.781  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:36.781  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:36.791  6966  6966 E Zygote  : MountEmulatedStorage()
08-25 13:18:36.791  6966  6966 E Zygote  : v2
08-25 13:18:36.791  6966  6966 I libpersona: KNOX_SDCARD checking this for 10102
,08-25 13:18:36.791  6966  6966 I libpersona: KNOX_SDCARD not a persona
08-25 13:18:36.791  1014  1323 E Watchdog: !@Sync 4
08-25 13:18:36.791  1014  1452 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6966 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 13:18:36.791  6966  6966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:36.801  1351  1351 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 13:18:36.801  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.801  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:36.801  6966  6966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:36.801  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 13:18:36.801  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:36.801  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:36.801  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-25 13:18:36.801  6966  6966 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 13:18:36.801  1475  1671 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:36.801  1475  1671 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 13:18:36.801  1296  1311 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 13:18:36.801  1442  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:36.801  1442  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:36.801  1176  3217 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:36.801  1176  3217 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 13:18:36.811  1296  6964 D Bluetoothsap: onBluetoothStateChange: up=false
08-25 13:18:36.811  1296  6964 D Bluetoothsap: Unbinding service...
,08-25 13:18:36.821  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 13:18:36.821  6966  6966 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:36.821  6966  6966 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:36.821  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 13:18:36.831  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:36.831  1014  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-25 13:18:36.831  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-25 13:18:36.831  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 13:18:36.841  1176  1176 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
08-25 13:18:36.841  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 13:18:36.841  1176  1775 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
,08-25 13:18:36.841  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:36.841  1176  1176 D BluetoothTile:  getBluetoothState : 10
08-25 13:18:36.841  1176  1775 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
,08-25 13:18:36.841  1176  1176 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
08-25 13:18:36.841  1176  1176 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
,08-25 13:18:36.841  1014  1451 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 13:18:36.841  1014  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 13:18:36.841  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 13:18:36.841  1885  1885 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 13:18:36.841  1994  2157 D BluetoothAdapter: 1059663781: getState() :  mService = null. Returning STATE_OFF
08-25 13:18:36.851  1994  2157 D BluetoothAdapter: 1059663781: getState() :  mService = null. Returning STATE_OFF
,08-25 13:18:36.851  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:36.851  1014  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 13:18:36.851  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 13:18:36.851  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:36.851  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:36.851  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:36.851  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:36.851  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:36.851  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:36.851  6966  6966 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 13:18:36.861  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 13:18:36.861  1351  1351 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-25 13:18:36.871  3163  3255 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 13:18:36.871  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 13:18:36.871  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 13:18:36.871  3163  3163 I GKI_LINUX: GKI_exit_task 1 done
08-25 13:18:36.871  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 13:18:36.871  3163  3163 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-25 13:18:36.871  3163  3163 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 13:18:36.881  3163  3163 I art     : System.exit called, status: 0
,08-25 13:18:36.881  3163  3163 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 13:18:36.891  1351  1351 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-25 13:18:36.891  1351  1351 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-25 13:18:36.891  1351  1351 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-25 13:18:36.891  1351  1351 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-25 13:18:36.891  1351  1351 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-25 13:18:36.891  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:36.891  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 13:18:36.891  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:36.891  1014  1128 D Tethering: InitialState.processMessage what=4
,08-25 13:18:36.891  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:36.891  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 13:18:36.891  1014  1128 E Tethering: No numeric data
,08-25 13:18:36.901  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.901  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:36.901  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 13:18:36.901  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 13:18:36.901  1014  1128 D Tethering: clearTetheredNotification()
,08-25 13:18:36.901  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.901  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:36.901  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 13:18:36.901  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 13:18:36.901  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 13:18:36.901  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:36.901  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 13:18:36.901  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:36.901  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.901  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-25 13:18:36.911  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:36.911  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 13:18:36.911  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 13:18:36.911  1176  1176 D HotspotTile: updateTetherState():false, false
,08-25 13:18:36.911  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.911  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.911  1014  1122 V NetworkStats: performPollLocked() took 4ms
,08-25 13:18:36.911  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.911  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.911  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:36.911  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.911  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.911  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.921  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.921  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.921  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.921  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.921  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.921  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.921  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.921  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.921  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.931  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 13:18:36.931  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.931  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.931  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.931  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.931  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 13:18:36.931  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.931  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.931  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.941  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 13:18:36.941  1475  1475 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 13:18:36.941  1014  1460 I ActivityManager: Process com.android.bluetooth (pid 3163)(adj 0) has died(28,712)
,08-25 13:18:36.941  1475  1475 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 13:18:36.951   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7c7e7c8
08-25 13:18:36.951   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,08-25 13:18:36.951   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-25 13:18:36.951   271   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1211635576)
,08-25 13:18:36.991   271   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-25 13:18:36.991   271   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-25 13:18:36.991   271   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1211635576) wakelock released: 1, error no: 0
08-25 13:18:36.991   271   343 I rmt_storage: 
,08-25 13:18:36.991   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7c7e7c8
,08-25 13:18:37.071  6966  7008 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 13:18:37.071  6966  7008 I Babel_SMS: MmsConfig.loadMmsSettings
,08-25 13:18:37.071  6966  7008 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-25 13:18:37.071  6966  7008 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 13:18:37.101  6966  7008 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-25 13:18:37.101  6966  7008 I Babel_SMS: MmsConfig.loadFromResources
,08-25 13:18:37.101  6966  7008 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-25 13:18:37.101  6966  7008 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-25 13:18:37.121  1014  1460 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-25 13:18:37.121  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-25 13:18:37.121  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:37.121  1014  1460 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:37.121  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 13:18:37.151  6966  6966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:18:37.151  6966  6966 I Babel_Crash: startup - clean
,08-25 13:18:37.171  1351  1351 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 13:18:37.191  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 13:18:37.191  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 13:18:37.191  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 13:18:37.201  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 13:18:37.201  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:37.201  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 13:18:37.201  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 13:18:37.201  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-25 13:18:37.201  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:37.201  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:37.201  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:37.201  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:37.211  6966  6966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:37.211  6966  6966 W AudioCapabilities: Unsupported mime audio/evrc,
,08-25 13:18:37.211  6966  6966 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 13:18:37.211  7011  7011 E Zygote  : MountEmulatedStorage()
08-25 13:18:37.211  7011  7011 E Zygote  : v2
08-25 13:18:37.211  7011  7011 I libpersona: KNOX_SDCARD checking this for 10064
08-25 13:18:37.211  7011  7011 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:37.211  7011  7011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:37.221  7011  7011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 13:18:37.221  7011  7011 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:37.221  1014  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7011 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:18:37.221  6966  6966 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-25 13:18:37.221  6966  6966 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-25 13:18:37.231  6966  6966 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-25 13:18:37.231  6966  6966 W AudioCapabilities: Unsupported mime audio/x-ima
,08-25 13:18:37.231  6966  6966 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 13:18:37.231  6966  6966 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 13:18:37.241  1014  1048 I PowerManagerService: [PWL] Off : 75s ago,
08-25 13:18:37.241  1014  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-25 13:18:37.241  1014  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-25 13:18:37.241  1014  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=458),
,08-25 13:18:37.241  7011  7011 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 13:18:37.241  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 13:18:37.241  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:37.241  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:37.241  1351  1351 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 13:18:37.241  7011  7011 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:37.251  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-25 13:18:37.251  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 13:18:37.261  6966  6966 W VideoCapabilities: Unsupported mime video/wvc1
,08-25 13:18:37.261  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:37.261  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 13:18:37.261  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:37.261  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:37.261  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:37.261  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:37.261  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:37.261  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-25 13:18:37.261  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 13:18:37.261  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:18:37.261  7011  7011 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 13:18:37.271  6966  6966 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 13:18:37.271  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:37.271  1994  2157 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:18:37.271  1176  1176 D HotspotTile: onReceive : 1, 0
,08-25 13:18:37.271  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:37.271  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:37.271  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:37.281  1014  1014 I ApplicationPolicy: updateDataUsageMap
,08-25 13:18:37.291  7011  7011 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 13:18:37.301  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:37.301  6966  6981 W art     : Suspending all threads took: 8.066ms
,08-25 13:18:37.301  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:37.301  7011  7011 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 13:18:37.311  6966  6966 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-25 13:18:37.311  6966  6966 W VideoCapabilities: Unsupported mime video/wvc1
,08-25 13:18:37.311  6966  6966 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 13:18:37.311  6966  6966 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-25 13:18:37.311  6966  6966 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-25 13:18:37.321  1014  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:37.321  6966  6966 W VideoCapabilities: Unsupported mime video/mp43
,08-25 13:18:37.321  6966  6966 W VideoCapabilities: Unsupported mime video/sorenson
,08-25 13:18:37.331  6966  6966 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-25 13:18:37.331  7011  7011 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 13:18:37.341  1014  1452 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-25 13:18:37.341  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:37.341  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:37.341  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:37.341  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:37.351  6966  6966 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 13:18:37.361  7026  7026 E Zygote  : MountEmulatedStorage(),
08-25 13:18:37.361  7026  7026 E Zygote  : v2
08-25 13:18:37.361  7026  7026 I libpersona: KNOX_SDCARD checking this for 10065
08-25 13:18:37.361  7026  7026 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:37.361  7026  7026 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:37.361  7026  7026 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 13:18:37.361  1014  1452 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7026 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 13:18:37.371  7026  7026 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 13:18:37.371  1014  1452 I ActivityManager: Killing 6529:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-25 13:18:37.381  7026  7026 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 13:18:37.381  7026  7026 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:37.401  6966  6966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:37.411  6966  6966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:37.411  6966  6966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:37.421  6966  6966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:37.421  7026  7026 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 13:18:37.431  1014  1514 I ActivityManager: Killing 6583:com.samsung.android.sm/1000 (adj 15): empty #21
,08-25 13:18:37.441  6966  6966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:18:37.441  1014  1026 I ActivityManager: Killing 6560:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-25 13:18:37.441  6966  6966 I vclib   : onServiceConnected
,08-25 13:18:37.441  1014  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 13:18:37.441  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:37.441  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:37.451  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:37.451  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 13:18:37.451  1616  1616 I Hs20UtilService: Starting #9
,08-25 13:18:37.451  1616  1645 I Hs20UtilService: Message received 5007
,08-25 13:18:37.451  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 13:18:37.451  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 13:18:37.451  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 13:18:37.451  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 13:18:37.451  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:37.451  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 13:18:37.451  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 13:18:37.461  1014  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 13:18:37.461  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:37.461  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:37.461  1014  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:37.461  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 13:18:37.461  1616  1616 I Hs20UtilService: Starting #10
,08-25 13:18:37.471  1616  1645 I Hs20UtilService: Message received 5011
,08-25 13:18:37.471  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 13:18:37.471  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 13:18:37.471  6614  6614 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 13:18:37.471  6614  6614 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 13:18:37.481  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:37.481  1014  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:37.481  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:37.741   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 13:18:37.751  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:37.751  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:37.751  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:37.751  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:37.751  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:37.751  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:37.751  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:37.751  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:37.751  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:37.761  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:37.761  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:37.761  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:37.761  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:18:37.761  1014  1495 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 13:18:37.761  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 13:18:37.761  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:37.761  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:37.761  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 13:18:37.771  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:37.771  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 13:18:37.781  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:37.781  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-25 13:18:37.781  1014  1487 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-25 13:18:37.781  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:37.781  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:37.781  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:37.781  1014  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:37.801  7043  7043 E Zygote  : MountEmulatedStorage(),
,08-25 13:18:37.801  7043  7043 E Zygote  : v2,
08-25 13:18:37.801  7043  7043 I libpersona: KNOX_SDCARD checking this for 1002
08-25 13:18:37.801  7043  7043 I libpersona: KNOX_SDCARD not a persona
08-25 13:18:37.801  1014  1487 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7043 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-25 13:18:37.801  7043  7043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:37.811  7043  7043 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 13:18:37.811  7043  7043 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:37.831  7043  7043 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:37.831  7043  7043 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:37.841  1014  1043 D Tethering: interfaceRemoved wlan0
,08-25 13:18:37.841  1014  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 13:18:37.851  7043  7043 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 13:18:37.851  7043  7043 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 13:18:37.881  7043  7043 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding GattService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding HeadsetService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding A2dpService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding HidService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding HealthService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding PanService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding SapService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-25 13:18:37.931  7043  7043 D BtSettings.ProfileConfig: Adding SapClientService
,08-25 13:18:37.941  7043  7043 D BtSettings.ProfileConfig: Adding HidDevService
,08-25 13:18:37.941  7043  7043 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 13:18:37.941  1014  4344 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-25 13:18:37.941  1014  4344 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.941  1014  4344 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 13:18:37.941  1014  4344 D SettingsProvider: selectionArgs: false
08-25 13:18:37.941  1014  4344 D SettingsProvider: selectionArgs: 1002
,08-25 13:18:37.941  1014  4344 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:37.941  1014  4344 D SettingsProvider: ret = -1
,08-25 13:18:37.941  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:37.941  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 13:18:37.951  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:37.951  1014  1026 D SettingsProvider: selectionArgs: false
08-25 13:18:37.951  1014  1026 D SettingsProvider: selectionArgs: 1002
,08-25 13:18:37.951  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:37.951  1014  1026 D SettingsProvider: ret = -1
,08-25 13:18:37.951  1014  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-25 13:18:37.951  1014  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.951  1014  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 13:18:37.951  1014  1133 D SettingsProvider: selectionArgs: false
08-25 13:18:37.951  1014  1133 D SettingsProvider: selectionArgs: 1002
08-25 13:18:37.951  1014  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:37.951  1014  1133 D SettingsProvider: ret = -1
,08-25 13:18:37.951  1014  1244 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-25 13:18:37.951  1014  1244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.951  1014  1244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:37.951  1014  1244 D SettingsProvider: selectionArgs: false
,08-25 13:18:37.951  1014  1244 D SettingsProvider: selectionArgs: 1002
08-25 13:18:37.951  1014  1244 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:37.951  1014  1244 D SettingsProvider: ret = -1
,08-25 13:18:37.951  1014  1460 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-25 13:18:37.951  1014  1460 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.951  1014  1460 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 13:18:37.961  1014  1460 D SettingsProvider: selectionArgs: false
08-25 13:18:37.961  1014  1460 D SettingsProvider: selectionArgs: 1002
,08-25 13:18:37.961  1014  1460 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:37.961  1014  1460 D SettingsProvider: ret = -1
,08-25 13:18:37.961  1014  1451 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
08-25 13:18:37.961  1014  1451 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.961  1014  1451 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:37.961  1014  1451 D SettingsProvider: selectionArgs: false
,08-25 13:18:37.961  1014  1451 D SettingsProvider: selectionArgs: 1002
,08-25 13:18:37.961  1014  1451 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:37.961  1014  1451 D SettingsProvider: ret = -1
08-25 13:18:37.961  1014  1452 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-25 13:18:37.961  1014  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.961  1014  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:37.961  1014  1452 D SettingsProvider: selectionArgs: false
08-25 13:18:37.961  1014  1452 D SettingsProvider: selectionArgs: 1002
,08-25 13:18:37.961  1014  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:37.961  1014  1452 D SettingsProvider: ret = -1
08-25 13:18:37.961  1014  1487 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 13:18:37.961  1014  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.961  1014  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:37.961  1014  1487 D SettingsProvider: selectionArgs: false
08-25 13:18:37.961  1014  1487 D SettingsProvider: selectionArgs: 1002
08-25 13:18:37.961  1014  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:37.961  1014  1487 D SettingsProvider: ret = -1
08-25 13:18:37.961  1014  1514 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:37.961  1014  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.961  1014  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:37.961  1014  1514 D SettingsProvider: selectionArgs: false
08-25 13:18:37.961  1014  1514 D SettingsProvider: selectionArgs: 1002
08-25 13:18:37.961  1014  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:37.961  1014  1514 D SettingsProvider: ret = -1
08-25 13:18:37.961  1014  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:37.961  1014  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.961  1014  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-25 13:18:37.961  1014  1495 D SettingsProvider: selectionArgs: false
08-25 13:18:37.961  1014  1495 D SettingsProvider: selectionArgs: 1002
08-25 13:18:37.961  1014  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:37.961  1014  1495 D SettingsProvider: ret = -1
08-25 13:18:37.961  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-25 13:18:37.961  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.961  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:37.961  1014  1027 D SettingsProvider: selectionArgs: false,
08-25 13:18:37.961  1014  1027 D SettingsProvider: selectionArgs: 1002
08-25 13:18:37.961  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:37.961  1014  1027 D SettingsProvider: ret = -1
08-25 13:18:37.961  1014  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-25 13:18:37.961  1014  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:37.961  1014  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:37.961  1014  1496 D SettingsProvider: selectionArgs: false
08-25 13:18:37.961  1014  1496 D SettingsProvider: selectionArgs: 1002
08-25 13:18:37.961  1014  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:37.961  1014  1496 D SettingsProvider: ret = -1
,08-25 13:18:37.981  1014  1026 I ActivityManager: Killing 6633:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-25 13:18:37.981  1994  1994 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:37.981  1014  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:37.981  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 13:18:37.991  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:37.991  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 13:18:37.991  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:38.001  1994  1994 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 13:18:38.001  1994  7059 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 13:18:38.001  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.001  1014  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:38.001  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.001  1014  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:38.011  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:38.011  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:38.011  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:38.021  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.021  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:38.021  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.021  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.021  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:38.021  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.031  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.031  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:38.031  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.031  1014  1451 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:38.031  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.031  1014  1451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:38.031  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:38.041  1994  7059 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-25 13:18:38.041  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:38.041  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:38.041  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.041  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.051  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:38.051  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.051  1014  1043 D Tethering: interfaceRemoved p2p0
,08-25 13:18:38.051  1014  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 13:18:38.051  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.051  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:38.051  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.051  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.051  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:38.051  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.061  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.061  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:38.061  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.071  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:38.071  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:38.071  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 13:18:38.071  1014  1451 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 13:18:38.071  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:38.081  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:38.081  1014  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:38.081  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 13:18:38.081  1616  1616 I Hs20UtilService: Starting #11
,08-25 13:18:38.081  1616  1645 I Hs20UtilService: Message received 5011
,08-25 13:18:38.081  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 13:18:38.081  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 13:18:38.081  6614  6614 D SecurityLogAgent: StateMachine : Current State = 1
08-25 13:18:38.081  6614  6614 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 13:18:38.091  1014  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast,
08-25 13:18:38.091  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-25 13:18:38.091  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.091  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.091  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.101  7060  7060 E Zygote  : MountEmulatedStorage()
,08-25 13:18:38.101  7060  7060 E Zygote  : v2
08-25 13:18:38.101  7060  7060 I libpersona: KNOX_SDCARD checking this for 1000
08-25 13:18:38.101  7060  7060 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:38.101  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.111  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 13:18:38.111  1014  1495 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7060 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 13:18:38.111  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.131  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:38.131  7060  7060 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.161  7060  7060 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-25 13:18:38.161  7060  7060 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-25 13:18:38.161  7060  7060 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 13:18:38.181  7060  7060 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-25 13:18:38.181  7060  7060 I PCWCLIENTTRACE_PushUtil: sales region : global
08-25 13:18:38.181  7060  7060 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-25 13:18:38.181  7060  7060 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:38.181  1014  4344 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-25 13:18:38.181  1014  4344 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-25 13:18:38.191  7060  7075 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-25 13:18:38.191  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-25 13:18:38.201  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.201  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.201  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.201  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.211  7077  7077 E Zygote  : MountEmulatedStorage(),
,08-25 13:18:38.211  7077  7077 E Zygote  : v2
08-25 13:18:38.211  7077  7077 I libpersona: KNOX_SDCARD checking this for 10001,
08-25 13:18:38.211  7077  7077 I libpersona: KNOX_SDCARD not a persona
08-25 13:18:38.211  7077  7077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 13:18:38.211  7077  7077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 13:18:38.221  7077  7077 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-25 13:18:38.221  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7077 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:18:38.221  1014  4344 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-25 13:18:38.231  1690  1690 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-25 13:18:38.231  1014  4344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.231  1014  4344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.231  1014  4344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.231  1014  4344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.241  7077  7077 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-25 13:18:38.241  7092  7092 E Zygote  : MountEmulatedStorage(),
08-25 13:18:38.241  7092  7092 I libpersona: KNOX_SDCARD checking this for 10031
08-25 13:18:38.241  7092  7092 E Zygote  : v2
08-25 13:18:38.241  7092  7092 I libpersona: KNOX_SDCARD not a persona,
08-25 13:18:38.241  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.251  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 13:18:38.251  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 13:18:38.251  1014  4344 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7092 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-25 13:18:38.251  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-25 13:18:38.251  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-25 13:18:38.251  7077  7077 D ActivityThread: Added TimaKeyStore provider
08-25 13:18:38.251  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.251  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.251  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.261  2466  2752 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-25 13:18:38.271  7104  7104 E Zygote  : MountEmulatedStorage()
,08-25 13:18:38.271  7104  7104 E Zygote  : v2
08-25 13:18:38.271  7104  7104 I libpersona: KNOX_SDCARD checking this for 10121
08-25 13:18:38.271  7104  7104 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:38.271  7104  7104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 13:18:38.271  1014  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7104 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-25 13:18:38.271  1690  1690 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-25 13:18:38.271  1690  1690 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-25 13:18:38.271  1690  1690 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-25 13:18:38.271  1690  1690 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
08-25 13:18:38.271  7104  7104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:38.281  7104  7104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.281  1690  1690 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 13:18:38.291  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 13:18:38.291  1690  1690 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
08-25 13:18:38.291  7092  7092 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.301  1014  1460 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-25 13:18:38.301   306   306 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 634us total 26.509ms
,08-25 13:18:38.301  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.301  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.301  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.301  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.301  7104  7104 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:38.301  7104  7104 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.311   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.299ms
,08-25 13:18:38.331   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.341ms
,08-25 13:18:38.341  7122  7122 E Zygote  : MountEmulatedStorage(),
08-25 13:18:38.341  7122  7122 E Zygote  : v2
08-25 13:18:38.341  7122  7122 I libpersona: KNOX_SDCARD checking this for 10077
,08-25 13:18:38.341  7122  7122 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:38.341  7122  7122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.351  7122  7122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:38.351  7122  7122 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.351  1014  1460 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7122 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:18:38.371  7122  7122 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:38.371  7122  7122 D ActivityThread: Added TimaKeyStore provider
08-25 13:18:38.371  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
08-25 13:18:38.371  7104  7104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:18:38.371  7104  7104 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-25 13:18:38.371  7104  7104 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 13:18:38.371  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.371  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.371  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.371  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.391  7104  7104 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:38.391  7139  7139 E Zygote  : MountEmulatedStorage()
,08-25 13:18:38.391  7139  7139 E Zygote  : v2
08-25 13:18:38.391  7139  7139 I libpersona: KNOX_SDCARD checking this for 1000
08-25 13:18:38.391  7139  7139 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:38.391  7139  7139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.391  1014  1026 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7139 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 13:18:38.391  1014  1026 I ActivityManager: Killing 6648:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-25 13:18:38.391  7139  7139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:38.401  7104  7104 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-25 13:18:38.401  7139  7139 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.411  7104  7104 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-25 13:18:38.411  1014  1244 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-25 13:18:38.411  7092  7092 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-25 13:18:38.411  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.411  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.411  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.411  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.421  7139  7139 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 13:18:38.421  7139  7139 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.431  7154  7154 E Zygote  : MountEmulatedStorage()
,08-25 13:18:38.431  7154  7154 E Zygote  : v2
08-25 13:18:38.431  7154  7154 I libpersona: KNOX_SDCARD checking this for 10141
08-25 13:18:38.431  7154  7154 I libpersona: KNOX_SDCARD not a persona
08-25 13:18:38.431  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.431  1014  1244 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7154 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-25 13:18:38.431  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 13:18:38.431  1014  1244 I ActivityManager: Killing 6598:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-25 13:18:38.431  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.441  1014  1244 I ActivityManager: Killing 6665:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-25 13:18:38.451  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:38.451  7154  7154 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.461  2758  7168 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-25 13:18:38.461  2758  7168 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-25 13:18:38.461  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-25 13:18:38.461  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.461  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.461  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.461  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.471  2758  7168 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-25 13:18:38.471  2758  7168 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-25 13:18:38.471  2758  7168 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-25 13:18:38.481  7170  7170 E Zygote  : MountEmulatedStorage()
,08-25 13:18:38.481  7170  7170 E Zygote  : v2
08-25 13:18:38.481  7170  7170 I libpersona: KNOX_SDCARD checking this for 10032
08-25 13:18:38.481  7170  7170 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:38.481  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.481  1014  1026 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7170 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 13:18:38.481  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:38.481  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.501  7139  7139 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-25 13:18:38.501  7154  7154 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-25 13:18:38.501  7154  7154 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:18:38.501  7154  7154 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 13:18:38.501  7154  7154 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-25 13:18:38.521  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:38.521  7170  7170 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.571  1014  1460 D RCPManagerService: exchangeData() failure , invalid userId,
,08-25 13:18:38.581  7170  7185 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-25 13:18:38.581  7170  7185 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-25 13:18:38.581  1014  1496 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 13:18:38.591  7170  7170 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-25 13:18:38.591  1014  1244 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-25 13:18:38.591  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.591  7170  7185 D SPPClientService: PushLog.txt file is not deleted.
08-25 13:18:38.591  7170  7185 D SPPClientService: PushLog.txt file is not deleted.
08-25 13:18:38.591  7170  7185 D SPPClientService: ============PushLog. stop!
08-25 13:18:38.591  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.591  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.591  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.601  7190  7190 E Zygote  : MountEmulatedStorage(),
08-25 13:18:38.601  7190  7190 E Zygote  : v2
08-25 13:18:38.601  7190  7190 I libpersona: KNOX_SDCARD checking this for 10036
08-25 13:18:38.601  7190  7190 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:38.611  7190  7190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.611  7190  7190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 13:18:38.611  7190  7190 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.621  1014  1244 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7190 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:18:38.621  1014  1244 I ActivityManager: Killing 6683:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-25 13:18:38.621  1014  1487 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-25 13:18:38.621  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-25 13:18:38.621  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:38.621  1014  1487 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-25 13:18:38.621  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-25 13:18:38.631  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:38.631  7190  7190 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.651  1014  1451 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 13:18:38.661  7139  7139 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-25 13:18:38.661  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 13:18:38.671  7139  7139 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-25 13:18:38.671  7139  7139 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
08-25 13:18:38.671  7170  7202 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-25 13:18:38.671  7139  7139 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-25 13:18:38.671  7139  7139 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-25 13:18:38.671  7139  7139 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-25 13:18:38.671  1014  4344 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-25 13:18:38.691  1014  4344 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-25 13:18:38.691  1014  4344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.691  1014  4344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.691  1014  4344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.701  7190  7190 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1c6537a
,08-25 13:18:38.711  7190  7190 I SA      : [SSP] onCreated,
,08-25 13:18:38.721  7211  7211 E Zygote  : MountEmulatedStorage()
08-25 13:18:38.721  7211  7211 E Zygote  : v2
08-25 13:18:38.721  7211  7211 I libpersona: KNOX_SDCARD checking this for 10008
08-25 13:18:38.721  7211  7211 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:38.721   287   287 E SMD     : DCD OFF
08-25 13:18:38.721  7211  7211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.721  7211  7211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:38.721  1014  4344 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7211 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:18:38.721  7211  7211 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.741  1014  1487 I ActivityManager: Killing 6074:com.android.mms/u0a41 (adj 15): empty #21
,08-25 13:18:38.741   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:38.741  1014  1027 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-25 13:18:38.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.751  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.751  1014  4344 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 13:18:38.761  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:38.761  7211  7211 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.761  7231  7231 E Zygote  : MountEmulatedStorage()
08-25 13:18:38.761  7190  7190 I SA      : [TPM] There is no property file
08-25 13:18:38.761  7231  7231 I libpersona: KNOX_SDCARD checking this for 10068
08-25 13:18:38.761  7231  7231 E Zygote  : v2
08-25 13:18:38.761  7231  7231 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:38.761  1014  1133 D RCPManagerService: exchangeData() failure , invalid userId
08-25 13:18:38.761  7231  7231 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.771  7190  7190 I SA      : [SCU] isHaveSA() - false
,08-25 13:18:38.771  7231  7231 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 13:18:38.771  1014  1027 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7231 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-25 13:18:38.771  7231  7231 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-25 13:18:38.771  7190  7190 I SA      : [TPM] getModelProperty : null
08-25 13:18:38.771  7190  7190 I SA      : [TPM] getCSCProperty : null
08-25 13:18:38.771  7190  7190 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-25 13:18:38.771  7190  7190 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-25 13:18:38.771  7190  7190 I SA      : [DM] TFT FEATURE: false
,08-25 13:18:38.781  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 13:18:38.781  7190  7190 I SA      : [DM] init START
,08-25 13:18:38.791  7190  7190 I SA      : [DM] This device is not a Vodafone
,08-25 13:18:38.791  1014  1452 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 13:18:38.791  7231  7231 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:38.801  7231  7231 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.801  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-25 13:18:38.801  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 13:18:38.801  1014  1487 D CountryDetector: No listener is left
,08-25 13:18:38.801  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:38.801  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:38.801  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 13:18:38.811  1014  1514 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 13:18:38.811  7190  7190 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-25 13:18:38.811  7190  7190 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-25 13:18:38.811  7190  7190 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-25 13:18:38.811  7190  7190 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-25 13:18:38.811  7190  7190 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-25 13:18:38.811  1014  1460 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-25 13:18:38.811  7190  7190 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-25 13:18:38.811  7190  7190 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-25 13:18:38.811  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.811  7190  7190 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 13:18:38.821  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.821  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.821  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75),
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-25 13:18:38.831  1014  1460 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7248 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75),
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75),
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-25 13:18:38.831  7190  7190 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-25 13:18:38.841  1014  1460 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast,
,08-25 13:18:38.841  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.841  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:38.841  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.841  1014  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:38.841  7248  7248 E Zygote  : MountEmulatedStorage()
08-25 13:18:38.841  7248  7248 E Zygote  : v2
08-25 13:18:38.841  7248  7248 I libpersona: KNOX_SDCARD checking this for 10110
08-25 13:18:38.841  7248  7248 I libpersona: KNOX_SDCARD not a persona
08-25 13:18:38.841  7248  7248 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 13:18:38.841  7231  7231 D BadgeProvider: onCreate
08-25 13:18:38.841  7231  7231 D BadgeProvider: DatabaseHelper
,08-25 13:18:38.851  7248  7248 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:38.851  7248  7248 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.871  7190  7190 I SA      : [SCU] isHaveSA() - false,
08-25 13:18:38.871  7190  7190 I SA      : support phone number id : false
08-25 13:18:38.871  7190  7190 I SA      : [DM] Supports Ref Jpn : true,
08-25 13:18:38.871  7190  7190 I SA      : [DM] init END,
08-25 13:18:38.871  7190  7190 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-25 13:18:38.871  7190  7190 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-25 13:18:38.871  7190  7190 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-25 13:18:38.881  7263  7263 E Zygote  : MountEmulatedStorage(),
08-25 13:18:38.881  7263  7263 E Zygote  : v2
08-25 13:18:38.881  7263  7263 I libpersona: KNOX_SDCARD checking this for 10009
08-25 13:18:38.881  7263  7263 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:38.881  7263  7263 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:38.881  7190  7190 I SA      : [SLFUCHKMGR] constructor called
,08-25 13:18:38.881  7263  7263 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:38.891  7248  7248 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:38.891  7263  7263 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-25 13:18:38.891  7248  7248 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.891  1014  1460 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7263 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-25 13:18:38.891  1014  1460 I ActivityManager: Killing 6720:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-25 13:18:38.901  1014  1460 I ActivityManager: Killing 6703:com.sec.esdk.elm/u0a90 (adj 15): empty #22
,08-25 13:18:38.901  7190  7190 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-25 13:18:38.901  7190  7190 I SA      : [OR] == isSIMCardReady false ==
,08-25 13:18:38.931  7263  7263 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 13:18:38.931  7263  7263 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:38.931  1014  1487 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-25 13:18:38.931  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 13:18:38.931  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:38.931  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:38.931  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 13:18:38.941  6966  7247 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 13:18:38.951  7190  7190 I SA      : [SCU] == networkStateCheck == false
08-25 13:18:38.951  1014  1452 I ActivityManager: Killing 6537:com.android.calendar/u0a131 (adj 15): empty #21
08-25 13:18:38.951  7190  7190 I SA      : [OR] onReceive END
08-25 13:18:38.951  1014  1452 I ActivityManager: Killing 6034:com.android.defcontainer/u0a3 (adj 15): empty #21
08-25 13:18:38.951  1223  1223 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
08-25 13:18:38.961  1014  1244 I ActivityManager: Killing 5840:com.android.vending/u0a26 (adj 15): empty #21
,08-25 13:18:38.971  2914  2914 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Aug 25 13:18:38 GMT+02:00 2016
,08-25 13:18:38.971  1014  1451 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-25 13:18:38.971  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-25 13:18:38.971  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:38.971  1014  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:38.971  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-25 13:18:38.971  2914  2914 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-25 13:18:38.981  2914  2914 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-25 13:18:38.981  2914  2914 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-25 13:18:38.991  2914  2914 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-25 13:18:38.991  2914  7280 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-25 13:18:38.991  2914  7280 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-25 13:18:39.001  2914  7280 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-25 13:18:39.001  2914  7280 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-25 13:18:39.001  2914  2914 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-25 13:18:39.051  1014  1514 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 13:18:39.051  1014  1514 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 13:18:39.051  1014  1514 D SecContentProvider2: mCursor = null
,08-25 13:18:39.071  1014  1496 I ActivityManager: Killing 6838:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-25 13:18:39.081  1014  1452 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 13:18:39.081  1014  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-25 13:18:39.081  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:39.081  1014  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:39.081  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:39.101  4815  7283 I iu.SyncManager: SYNC; picasa accounts
,08-25 13:18:39.131  1014  1514 D WifiService: setWifiEnabled: true pid=6760, uid=10171
,08-25 13:18:39.131  1014  1514 W ActivityManager: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 13:18:39.141  1014  1514 W WifiService: Failed getting userId using ActivityManagerNative
08-25 13:18:39.141  1014  1514 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 13:18:39.141  1014  1514 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 13:18:39.141  1014  1514 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 13:18:39.141  1014  1514 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 13:18:39.141  1014  1514 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 13:18:39.141  1014  1514 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 13:18:39.141  1014  1514 D SettingsProvider: name = wifi_on
,08-25 13:18:39.141  4815  4815 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-25 13:18:39.181  1014  1460 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 13:18:39.181  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-25 13:18:39.201  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-25 13:18:39.201  1014  4344 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-25 13:18:39.201  1014  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-25 13:18:39.201  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
08-25 13:18:39.201  1014  1027 I art     : Explicit concurrent mark sweep GC freed 62896(3MB) AllocSpace objects, 9(192KB) LOS objects, 33% free, 24MB/36MB, paused 30.761ms total 306.248ms
,08-25 13:18:39.221  7231  7242 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-25 13:18:39.261  7231  7242 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-25 13:18:39.261  7231  7242 D BadgeProvider: sendNotify, [notify] : null
08-25 13:18:39.261  7231  7242 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-25 13:18:39.261  7231  7242 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-25 13:18:39.261  7231  7242 D BadgeProvider: update, [UpdateCount] : 1
,08-25 13:18:39.261  1497  1497 D Launcher.Model: reloadBadges entered.
,08-25 13:18:39.341  7248  7248 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 13:18:39.341  7248  7248 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 13:18:39.341  7248  7248 I GAv4    :   adb logcat -s GAv4
,08-25 13:18:39.341   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 13:18:39.341   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:18:39.341  7248  7288 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 13:18:39.351   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 13:18:39.351   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:18:39.351  7248  7288 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 13:18:39.361   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 13:18:39.361   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:18:39.361  7248  7290 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 13:18:39.361  7248  7248 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-25 13:18:39.361  1014  1514 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 13:18:39.361   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 13:18:39.361   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:18:39.371  7248  7290 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 13:18:39.371  7248  7248 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 13:18:39.381  7248  7291 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 13:18:39.551  1014  1043 D Tethering: interfaceAdded wlan0
,08-25 13:18:39.561  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 13:18:39.561  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 13:18:39.571  1014  1128 E Tethering: No numeric data
,08-25 13:18:39.571  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:39.571  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-25 13:18:39.571  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 13:18:39.571  1176  1176 D HotspotTile: updateTetherState():false, false
,08-25 13:18:39.571  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:39.571  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 13:18:39.571  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 13:18:39.571  1014  1128 D Tethering: clearTetheredNotification()
,08-25 13:18:39.571   277  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-25 13:18:39.571   277  1013 D SoftapController: Softap fwReload - Ok
,08-25 13:18:39.571  1014  1128 D Tethering: InitialState.processMessage what=4
08-25 13:18:39.571  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:39.581   277  1013 D CommandListener: Setting iface cfg
,08-25 13:18:39.581   277  1013 D CommandListener: Trying to bring down wlan0
08-25 13:18:39.581  1014  1122 V NetworkStats: performPollLocked() took 9ms
08-25 13:18:39.581  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:39.581   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,08-25 13:18:39.581  1014  1128 E Tethering: No numeric data
,08-25 13:18:39.581  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:39.581  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:39.581  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 13:18:39.581  1014  1128 D Tethering: clearTetheredNotification()
08-25 13:18:39.581  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 13:18:39.581  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 13:18:39.581  1176  1176 D HotspotTile: updateTetherState():false, false,
08-25 13:18:39.581  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
08-25 13:18:39.581  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 13:18:39.581  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:39.581  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-25 13:18:39.581  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:39.581  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 13:18:39.581  1014  1043 D Tethering: interfaceAdded p2p0
,08-25 13:18:39.591  1014  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-25 13:18:39.591  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
08-25 13:18:39.591  1014  1122 V NetworkStats: performPollLocked() took 4ms
08-25 13:18:39.591  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:39.591  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:39.591  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:39.591  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-25 13:18:39.591  1014  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-25 13:18:39.601  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:39.601  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 13:18:39.601  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 13:18:39.601  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:39.601  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 13:18:39.601  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:39.601  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:39.601  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:39.601  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-25 13:18:39.601  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:39.601  1176  1176 D HotspotTile: onReceive : 2, 0
,08-25 13:18:39.601  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:39.611  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:39.611  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:39.621  1014  1244 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:39.621  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:39.631  1014  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:39.631  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-25 13:18:39.651  7312  7312 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-25 13:18:39.651  7312  7312 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 13:18:39.651  7312  7312 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-25 13:18:39.661  7248  7248 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-25 13:18:39.681  7248  7248 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 1061-1063),
08-25 13:18:39.681  7248  7248 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 13:18:39.691  7312  7312 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-25 13:18:39.691   350   350 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7312
,08-25 13:18:39.691   350   350 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C,
08-25 13:18:39.691  7312  7312 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 13:18:39.691  7312  7312 I wpa_supplicant: ssSupport state is = 1
08-25 13:18:39.691  7312  7312 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-25 13:18:39.691  7312  7312 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-25 13:18:39.691   350   350 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7312
08-25 13:18:39.691   350   350 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-25 13:18:39.711  7248  7248 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {251d641d},
08-25 13:18:39.711  7248  7248 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 13:18:39.711  7248  7248 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 13:18:39.731  7248  7248 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,08-25 13:18:39.731  7248  7248 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 13:18:39.731  7248  7248 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-25 13:18:39.741   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 13:18:39.751  7248  7248 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-25 13:18:39.751  7248  7248 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 13:18:39.751  7248  7248 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 13:18:39.751  7248  7248 I Adreno-EGL: Local Branch: 
08-25 13:18:39.751  7248  7248 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 13:18:39.751  7248  7248 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 13:18:39.751  7248  7248 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 13:18:39.861   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-25 13:18:39.861  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-25 13:18:39.881  7248  7248 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 13:18:39.891  7248  7248 I NSApplication: Starting up...
,08-25 13:18:39.891  1014  1514 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 13:18:39.891  7248  7328 W cr.media: Requires BLUETOOTH permission
,08-25 13:18:39.891  1014  1495 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 13:18:39.891  1014  1244 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-25 13:18:39.901  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:39.901  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:39.901  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:39.901  1014  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:39.911  7333  7333 E Zygote  : MountEmulatedStorage(),
,08-25 13:18:39.911  7333  7333 E Zygote  : v2
08-25 13:18:39.911  7333  7333 I libpersona: KNOX_SDCARD checking this for 10117
08-25 13:18:39.911  7333  7333 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:39.911  7333  7333 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:39.911  7312  7312 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-25 13:18:39.911  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 13:18:39.911  1014  1244 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7333 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-25 13:18:39.911  7333  7333 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 13:18:39.911  7333  7333 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-25 13:18:39.911  1014  1244 I ActivityManager: Killing 7011:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-25 13:18:39.931  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-25 13:18:39.931   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7312
08-25 13:18:39.931   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 13:18:39.931  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 13:18:39.931  7312  7312 I wpa_supplicant: ssSupport state is = 1
08-25 13:18:39.931  7312  7312 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-25 13:18:39.931  7312  7312 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 13:18:39.931  7312  7312 E wpa_supplicant: SIM READ ERROR
08-25 13:18:39.931  7312  7312 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 13:18:39.931  7312  7312 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 13:18:39.931  7312  7312 E wpa_supplicant: SIM READ ERROR
08-25 13:18:39.931  7312  7312 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 13:18:39.931  7312  7312 I wpa_supplicant: wpa_default_ap_write_once
08-25 13:18:39.931  7312  7312 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 13:18:39.931  7312  7312 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 13:18:39.931  7312  7312 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-25 13:18:39.931  7312  7312 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 13:18:39.931  7312  7312 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 13:18:39.931  7312  7312 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 13:18:39.931  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:39.931  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 13:18:39.931  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:39.941  7333  7333 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:39.941  7333  7333 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:39.971  7312  7312 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-25 13:18:39.971  7333  7333 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 13:18:40.011  1014  1041 W ProcessCpuTracker: Skipping unknown process pid 7011
,08-25 13:18:40.111  7312  7312 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-25 13:18:40.121  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 13:18:40.131  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 13:18:40.131   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7312
08-25 13:18:40.131   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-25 13:18:40.131  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 13:18:40.131  7312  7312 I wpa_supplicant: ssSupport state is = 1
,08-25 13:18:40.131  7312  7312 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 13:18:40.131  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 13:18:40.141  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 13:18:40.141   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7312
08-25 13:18:40.141   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-25 13:18:40.141  7312  7312 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 13:18:40.141  7312  7312 I wpa_supplicant: ssSupport state is = 1
08-25 13:18:40.141  7312  7312 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 13:18:40.141  7312  7312 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 13:18:40.141  7312  7312 E wpa_supplicant: SIM READ ERROR
08-25 13:18:40.141  7312  7312 I wpa_supplicant: wpa_default_ap_write_once,
08-25 13:18:40.141  7312  7312 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 13:18:40.141  7312  7312 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 13:18:40.141  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 13:18:40.141  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 13:18:40.141  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 13:18:40.151  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 13:18:40.151  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 13:18:40.151  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 13:18:40.221  7312  7312 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-25 13:18:40.221  7312  7312 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 13:18:40.301  1014  1460 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-25 13:18:40.301  1014  1460 I ActivityManager: Killing 7026:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-25 13:18:40.311  1014  4344 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 13:18:40.311  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:40.311  1014  4344 W ActivityManager: userId = 0, bbcId = -10000,
,08-25 13:18:40.311  1014  4344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:40.311  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 13:18:40.311  1616  1616 I Hs20UtilService: Starting #12
08-25 13:18:40.311  1616  1645 I Hs20UtilService: Message received 5011
,08-25 13:18:40.321  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 13:18:40.321  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found ,
08-25 13:18:40.321  6614  6614 D SecurityLogAgent: StateMachine : Current State = 1
08-25 13:18:40.321  6614  6614 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-25 13:18:40.321  7312  7312 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-25 13:18:40.321  7312  7312 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-25 13:18:40.321  7312  7312 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 13:18:40.561  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-25 13:18:40.561  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
08-25 13:18:40.561  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 13:18:40.611  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-25 13:18:40.611  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 13:18:40.611  7312  7312 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-25 13:18:40.611  7312  7312 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 13:18:40.611  7312  7312 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 13:18:40.611  7312  7312 E wpa_supplicant: SIM READ ERROR
08-25 13:18:40.611  7312  7312 I wpa_supplicant: Blacklist: Clear (all) ,
,08-25 13:18:40.631  7312  7312 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-25 13:18:40.641  7312  7312 I wpa_supplicant: Skip scan - bUseNetwork false,
08-25 13:18:40.641  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
08-25 13:18:40.651  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:40.651  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:40.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:40.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:40.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:40.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:40.651  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:40.651  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-25 13:18:40.651  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:40.651  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 13:18:40.651  1176  1176 D HotspotTile: onReceive : 3, 0
,08-25 13:18:40.651  1014  1125 E WifiConfigStore: Not a HS20,
,08-25 13:18:40.651  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:40.651  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:40.651  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:40.651  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:40.651  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:40.651  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:40.651  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:40.651  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:40.651  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:40.651  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:40.651  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:40.651  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:40.661  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 13:18:40.661  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:40.661  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:40.661  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:40.661  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:40.661  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:40.661  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:40.661  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:40.661  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:40.661  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:40.661  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:40.661  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:40.661  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-25 13:18:40.671  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 13:18:40.671  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:40.671  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:40.671  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:40.671  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 13:18:40.671  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-25 13:18:40.671  7312  7312 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-25 13:18:40.671  7312  7312 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 13:18:40.671  7312  7312 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 13:18:40.671  7312  7312 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 13:18:40.671  7312  7312 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 13:18:40.671  7312  7312 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-25 13:18:40.671  7312  7312 I wpa_supplicant: First Scan Start
,08-25 13:18:40.671  7312  7312 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 13:18:40.671  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-25 13:18:40.671  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 13:18:40.671  1014  1125 I WifiNative-HAL: startHal
08-25 13:18:40.671  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d40688c
08-25 13:18:40.671  1014  1125 I WifiNative-HAL: Could not start hal
,08-25 13:18:40.671  6966  6966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:18:40.671  1014  1125 E WifiNative-wlan0: do suspend true
,08-25 13:18:40.681  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
08-25 13:18:40.681  1616  1616 I Hs20UtilService: Starting #13
,08-25 13:18:40.681  1616  1645 I Hs20UtilService: Message received 5011
,08-25 13:18:40.681   277  1013 D CommandListener: Setting iface cfg
08-25 13:18:40.681   277  1013 D CommandListener: Trying to bring up p2p0
,08-25 13:18:40.681  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 13:18:40.681  1014  1124 D WifiP2pService: P2pEnablingState
08-25 13:18:40.681  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-25 13:18:40.681  1014  1124 D WifiP2pService: P2p socket connection successful
,08-25 13:18:40.681  1014  1124 D WifiP2pService: P2pEnabledState
08-25 13:18:40.681  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 13:18:40.681  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 13:18:40.681  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:40.681  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 13:18:40.681  6614  6614 D SecurityLogAgent: StateMachine : Current State = 1
08-25 13:18:40.681  6614  6614 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-25 13:18:40.681  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-25 13:18:40.681  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 13:18:40.681  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-25 13:18:40.681  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 13:18:40.681  1014  1046 D WifiDisplayController: disconnect
08-25 13:18:40.681  1014  1046 D WifiDisplayController: updateConnection
08-25 13:18:40.681  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 13:18:40.681  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 13:18:40.681  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 13:18:40.691  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,08-25 13:18:40.691  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 13:18:40.691  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:40.691  1014  1148 I WifiNative-HAL: startHal
08-25 13:18:40.691  1014  1014 D RttService: SCAN_AVAILABLE : 3
,08-25 13:18:40.691  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 13:18:40.691  1014  1125 E WifiNative-wlan0: invaild command id : 215
,08-25 13:18:40.691  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e3b09bc,
08-25 13:18:40.691  1014  1148 I WifiNative-HAL: Could not start hal
08-25 13:18:40.691  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
08-25 13:18:40.691  1014  1148 E WifiScanningService: could not start HAL
08-25 13:18:40.691  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28,
,08-25 13:18:40.701  7312  7312 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 13:18:40.701  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:18:40.701  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
08-25 13:18:40.701  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 13:18:40.701  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 13:18:40.701  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 13:18:40.701  7312  7312 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-25 13:18:40.701  1014  1125 E WifiStateMachine: Failed to set frequency band 0
08-25 13:18:40.701  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-25 13:18:40.701  1014  1124 D WifiP2pService: DeviceAddress: 0a:76:28
08-25 13:18:40.701  1014  1460 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 13:18:40.701  1014  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  secondary type: null
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  wps: 0
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  grpcapab: 0
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  devcapab: 0
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  status: 3
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  wfdInfo: null
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  groupownerAddress: null
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  GOdeviceName: null
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  interfaceAddress: 
08-25 13:18:40.701  1014  1046 D WifiDisplayController:  SConnectInfo : null
08-25 13:18:40.701  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 13:18:40.701  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 13:18:40.701  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 13:18:40.701  1014  1125 E WifiNative-wlan0: invaild command id : 215
08-25 13:18:40.701  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:40.701  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:40.711  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 13:18:40.711  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:40.711  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:40.711  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 13:18:40.711  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 13:18:40.711  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 13:18:40.711  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:40.711  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 13:18:40.711  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 13:18:40.711  1014  1452 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-25 13:18:40.711  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:40.711  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:40.711  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:40.711  1014  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:40.721  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-25 13:18:40.731  7364  7364 E Zygote  : MountEmulatedStorage()
08-25 13:18:40.731  7364  7364 I libpersona: KNOX_SDCARD checking this for 10064
08-25 13:18:40.731  7364  7364 E Zygote  : v2
08-25 13:18:40.731  7364  7364 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:40.731  7364  7364 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 13:18:40.731  1014  1452 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7364 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:18:40.731  7364  7364 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 13:18:40.731  1014  1124 D WifiP2pService: InactiveState
,08-25 13:18:40.731  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
08-25 13:18:40.731  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 13:18:40.731  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-25 13:18:40.731  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
08-25 13:18:40.731  7364  7364 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 13:18:40.731  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 13:18:40.741   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:40.751   306   306 I art     : Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 24.922ms
,08-25 13:18:40.761  7364  7364 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:40.761  7364  7364 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:40.771   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 18.341ms
,08-25 13:18:40.771  7364  7364 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 13:18:40.781  7364  7364 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 13:18:40.791  7364  7364 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 13:18:40.791   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 680us total 17.108ms
,08-25 13:18:40.821  7364  7364 D FileShare-Client: Outbound.stopDelayTimer - ,
08-25 13:18:40.821  1014  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
08-25 13:18:40.821  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:40.821  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:40.821  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:40.821  1014  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:40.831  7379  7379 E Zygote  : MountEmulatedStorage(),
08-25 13:18:40.831  7379  7379 E Zygote  : v2
08-25 13:18:40.831  7379  7379 I libpersona: KNOX_SDCARD checking this for 10065,
08-25 13:18:40.831  7379  7379 I libpersona: KNOX_SDCARD not a persona
08-25 13:18:40.831  1014  1496 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7379 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:18:40.831  1014  1496 I ActivityManager: Killing 6909:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-25 13:18:40.841  7379  7379 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:40.841  7379  7379 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:40.841  7379  7379 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:40.861  7379  7379 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:40.861  7379  7379 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:40.891  7379  7379 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 13:18:40.891  1014  1495 I ActivityManager: Killing 7043:com.android.bluetooth/1002 (adj 15): empty #21
,08-25 13:18:41.161  1014  3375 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 13:18:41.351  1014  2071 V SAMP_SPCM_test: CSC File load.. 
,08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account,
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-25 13:18:41.371  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-25 13:18:41.401  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
,08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-25 13:18:41.411  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-25 13:18:41.421  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-25 13:18:41.421  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-25 13:18:41.421  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-25 13:18:41.421  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-25 13:18:41.421  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-25 13:18:41.421  1014  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-25 13:18:41.421  1014  2071 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,08-25 13:18:41.421  1014  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:41.421  1014  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:41.421  1014  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:41.421  1014  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:41.441  1014  2071 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7394 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-25 13:18:41.441  7394  7394 E Zygote  : MountEmulatedStorage(),
08-25 13:18:41.441  7394  7394 E Zygote  : v2
,08-25 13:18:41.441  7394  7394 I libpersona: KNOX_SDCARD checking this for 1000
08-25 13:18:41.441  7394  7394 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:41.441  7394  7394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:41.451  7394  7394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 13:18:41.451  7394  7394 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 13:18:41.471  7394  7394 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:41.471  7394  7394 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:41.481  7394  7394 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 13:18:41.521  1014  1014 I ActivityManager: Killing 6927:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-25 13:18:41.521  1014  2071 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-25 13:18:41.721   287   287 E SMD     : DCD OFF
,08-25 13:18:41.741   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:41.961  7312  7312 I wpa_supplicant: nl80211: Received scan results (22 BSSes)
08-25 13:18:41.961  7312  7312 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-25 13:18:41.961  7312  7312 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-25 13:18:41.961  7312  7312 I wpa_supplicant: Trying to associate with  'G700'
08-25 13:18:41.961  7312  7312 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-25 13:18:41.961  7312  7312 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-25 13:18:41.971  1014  7360 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 13:18:41.981  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-25 13:18:41.981  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:42.081  7312  7312 E wpa_supplicant: Cmd 35605 not handled
,08-25 13:18:42.081  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:42.081  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:42.081  7312  7312 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 13:18:42.081  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 13:18:42.081  7312  7312 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-25 13:18:42.081  7312  7312 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-25 13:18:42.081  7312  7312 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-25 13:18:42.081  7312  7312 I wpa_supplicant: Associated with F4.99.3E
08-25 13:18:42.081  7312  7312 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 13:18:42.081  7312  7312 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-25 13:18:42.081  7312  7312 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-25 13:18:42.081  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:42.081  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:42.081  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:42.081  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:42.081  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:42.081  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:42.081  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 13:18:42.081  1014  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-25 13:18:42.091  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-25 13:18:42.091  1014  1128 E Tethering: No numeric data,
08-25 13:18:42.091  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 13:18:42.091  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
08-25 13:18:42.091  1014  1128 D Tethering: clearTetheredNotification()
08-25 13:18:42.091  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:42.091  7312  7312 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-25 13:18:42.091  7312  7312 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-25 13:18:42.091  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-25 13:18:42.091  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:42.091  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 13:18:42.091  1014  1125 D SecContentProvider2: mCursor = null
08-25 13:18:42.101  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 13:18:42.091  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:42.101  1014  1122 V NetworkStats: performPollLocked() took 12ms
08-25 13:18:42.101  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 13:18:42.101  7312  7312 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-25 13:18:42.101  7312  7312 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-25 13:18:42.101  7312  7312 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 13:18:42.101  7312  7312 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-25 13:18:42.101  7312  7312 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-25 13:18:42.101  7312  7312 I wpa_supplicant: Blacklist: Clear (temp) 
08-25 13:18:42.101  7312  7312 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-25 13:18:42.101  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 13:18:42.101  1014  1043 D Tethering: interfaceStatusChanged wlan0, true
08-25 13:18:42.101  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:42.111  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:42.111  1014  1125 D SecContentProvider2: mCursor = null
08-25 13:18:42.111  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:42.111  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:42.111  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 13:18:42.121  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-25 13:18:42.121  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-25 13:18:42.121  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-25 13:18:42.121  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:18:42.121  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:42.121  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:42.121  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:42.121  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.121  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.121  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.121  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.121  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:18:42.131  1014  1244 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 13:18:42.131  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:42.131  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:42.131  1014  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:42.131  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 13:18:42.131  1616  1616 I Hs20UtilService: Starting #14
,08-25 13:18:42.141  1616  1645 I Hs20UtilService: Message received 5007
,08-25 13:18:42.141  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-25 13:18:42.141  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 13:18:42.141  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:18:42.141  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 13:18:42.141  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 13:18:42.141  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:42.141  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 13:18:42.141  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 13:18:42.161   277  1013 D CommandListener: Setting iface cfg,
,08-25 13:18:42.161  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,08-25 13:18:42.171  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-25 13:18:42.171  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:42.171  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:42.171  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:42.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.181  1014  1125 E WifiNative-wlan0: do suspend false,
,08-25 13:18:42.181  1014  1514 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-25 13:18:42.181  1014  1514 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
08-25 13:18:42.181  1014  1514 D SecContentProvider2: mCursor = null
08-25 13:18:42.191  1014  1514 D WifiService: setWifiEnabled: false pid=6760, uid=10171
,08-25 13:18:42.191  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:42.191  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
08-25 13:18:42.191  1014  1125 D SecContentProvider2: mCursor = null
08-25 13:18:42.191  1014  1514 D SettingsProvider: name = wifi_on
08-25 13:18:42.191  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 13:18:42.201  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:18:42.211  1014  1125 E WifiNative-wlan0: do suspend true,
,08-25 13:18:42.231  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
08-25 13:18:42.231  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 13:18:42.231  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 13:18:42.231  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:42.231  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.231  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.231  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.231  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.231   277  1013 D CommandListener: Clearing all IP addresses on wlan0,
,08-25 13:18:42.241  1014  1127 E ConnectivityService: updateNetworkInfo(),
08-25 13:18:42.241  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:18:42.241   277  1013 E Netd    : no such netId 503
08-25 13:18:42.241  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-25 13:18:42.241  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:42.241  1014  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-25 13:18:42.241  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-25 13:18:42.241  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-25 13:18:42.241  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:42.241  1014  1127 V NetworkStats: updateIfacesLocked()
08-25 13:18:42.241  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 13:18:42.241  1014  1127 V NetworkStats: performPollLocked(flags=0x1),
08-25 13:18:42.251  1014  1127 V NetworkStats: performPollLocked() took 5ms
08-25 13:18:42.251  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:42.251  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 13:18:42.251  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:42.251  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.251  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.251  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
08-25 13:18:42.251  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.251  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-25 13:18:42.251  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.251  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-25 13:18:42.251  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-25 13:18:42.251  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-25 13:18:42.251  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-25 13:18:42.251  1014  1127 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 13:18:42.261  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:42.261  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-25 13:18:42.261  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,08-25 13:18:42.261  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 13:18:42.261  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:42.261  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-25 13:18:42.261  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 13:18:42.261  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:42.261  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:42.261  1014  4344 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 13:18:42.261  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 13:18:42.261  1014  4344 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:42.261  1014  4344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:42.261  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 13:18:42.261  1616  1616 I Hs20UtilService: Starting #15
,08-25 13:18:42.261  1616  1645 I Hs20UtilService: Message received 5007
,08-25 13:18:42.261  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:18:42.261  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
08-25 13:18:42.261  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 13:18:42.261  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 13:18:42.271  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 13:18:42.271  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 13:18:42.271  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:42.271  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-25 13:18:42.271  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-25 13:18:42.271  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-25 13:18:42.271  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 13:18:42.271  1014  1046 D WifiDisplayController: disconnect
08-25 13:18:42.271  1014  1046 D WifiDisplayController: updateConnection
08-25 13:18:42.271  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 13:18:42.271  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 13:18:42.271  1014  1124 D WifiP2pService: P2pDisablingState
08-25 13:18:42.271  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-25 13:18:42.271  1014  1124 D WifiP2pService: p2p socket connection lost
08-25 13:18:42.271  1014  1124 D WifiP2pService: P2pDisabledState
,08-25 13:18:42.271  1014  1125 E WifiNative-wlan0: do suspend true
,08-25 13:18:42.271  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
08-25 13:18:42.271  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
08-25 13:18:42.271  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 13:18:42.271  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 13:18:42.271  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 13:18:42.271  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 13:18:42.271  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-25 13:18:42.271  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:42.271  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 13:18:42.271  1014  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 13:18:42.281  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 13:18:42.281  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 13:18:42.281  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 13:18:42.281  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 13:18:42.281  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 13:18:42.281  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 13:18:42.281  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:42.281  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 13:18:42.281  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 13:18:42.291  7364  7364 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 13:18:42.291  7364  7364 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-25 13:18:42.291  7364  7364 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 13:18:42.291  7379  7379 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 13:18:42.291  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-25 13:18:42.291  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
08-25 13:18:42.301   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:42.301  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.301  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:42.301  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.301  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:42.311  7312  7312 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-25 13:18:42.311  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 13:18:42.311  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:42.311  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:42.311  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:42.311  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 13:18:42.311  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:42.311  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:42.311  1616  1616 I Hs20UtilService: Starting #16
08-25 13:18:42.311  1616  1645 I Hs20UtilService: Message received 5007
,08-25 13:18:42.321  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:42.321  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 13:18:42.321  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.321  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.321  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.321  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:42.321  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:42.321  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-25 13:18:42.321  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:42.321  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 13:18:42.321  1176  1176 D HotspotTile: onReceive : 0, 0
,08-25 13:18:42.321  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:42.321  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:42.321  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.321  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:42.321  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:42.321  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:42.321  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.321  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:42.331  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 13:18:42.331  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 13:18:42.331  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 13:18:42.331  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 13:18:42.331  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:42.331  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 13:18:42.331  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 13:18:42.341  1014  1514 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 13:18:42.341  1014  1514 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:42.341  1014  1514 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:42.341  1014  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:42.341  1014  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 13:18:42.351  1616  1616 I Hs20UtilService: Starting #17
,08-25 13:18:42.351  1616  1645 I Hs20UtilService: Message received 5011
08-25 13:18:42.351  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 13:18:42.351  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 13:18:42.351  6614  6614 D SecurityLogAgent: StateMachine : Current State = 1
08-25 13:18:42.351  6614  6614 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 13:18:42.401  7413  7413 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-25 13:18:42.411  7413  7413 I dhcpcd  : version 5.5.6 starting,
,08-25 13:18:42.411  7413  7413 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-25 13:18:42.471  7413  7413 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-25 13:18:42.471  7413  7413 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-25 13:18:42.471  7413  7413 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,08-25 13:18:42.471  7413  7413 I dhcpcd  : bssid match
,08-25 13:18:42.471  7413  7413 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-25 13:18:42.511  7312  7312 I wpa_supplicant: Blacklist: Clear (all) ,
,08-25 13:18:42.521  7413  7413 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-25 13:18:42.561  1014  3341 D SSRM:n  : SIOP:: AP = 350,
,08-25 13:18:42.631  7413  7413 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
08-25 13:18:42.631  7312  7312 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-25 13:18:42.631  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-25 13:18:42.631  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 13:18:42.631  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 13:18:42.661  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:42.661  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-25 13:18:42.661  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:42.661  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:42.661  1014  1128 D Tethering: InitialState.processMessage what=4
08-25 13:18:42.661  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
08-25 13:18:42.661  7312  7312 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
,08-25 13:18:42.671  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 13:18:42.661  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:42.671  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 13:18:42.661  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:42.671  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 13:18:42.661  1014  1128 E Tethering: No numeric data
08-25 13:18:42.671  1014  1122 V NetworkStats: performPollLocked() took 8ms
08-25 13:18:42.661  7312  7312 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-25 13:18:42.661  7312  7312 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-25 13:18:42.661  7312  7312 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-25 13:18:42.661  7312  7312 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-25 13:18:42.661  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 13:18:42.661  1014  1128 D Tethering: clearTetheredNotification()
08-25 13:18:42.661  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:42.671  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:42.671  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 13:18:42.671  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:42.671  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:42.671  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:42.671  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:42.671  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:42.741   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-25 13:18:42.971  7312  7312 I wpa_supplicant: Blacklist: Clear (all) ,
,08-25 13:18:43.051  1014  4344 I ActivityManager: Killing 7060:com.sec.pcw.device/1000 (adj 15): empty #21
,08-25 13:18:43.071  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:43.071  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 13:18:43.071  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:43.071  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 13:18:43.071  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:43.071  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:43.071  7312  7312 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-25 13:18:43.171  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-25 13:18:43.171  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
,08-25 13:18:43.181  6966  6966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-25 13:18:43.181  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 13:18:43.181  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-25 13:18:43.181  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:43.181  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:43.191  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:43.191  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:43.191  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:43.191  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-25 13:18:43.191  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 13:18:43.191  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:43.191  1994  2157 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:18:43.201  1176  1176 D HotspotTile: onReceive : 1, 0
,08-25 13:18:43.201  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:43.201  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:43.201  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:43.211  1014  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 13:18:43.211  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:43.211  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:43.211  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:43.211  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 13:18:43.221  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 13:18:43.221  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-25 13:18:43.221  6614  6614 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 13:18:43.221  6614  6614 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 13:18:43.221  1616  1616 I Hs20UtilService: Starting #18
,08-25 13:18:43.221  1616  1645 I Hs20UtilService: Message received 5011
,08-25 13:18:44.051   277  1007 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-25 13:18:44.051  1014  1043 D Tethering: interfaceRemoved wlan0
08-25 13:18:44.051  1014  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 13:18:44.331  1014  1043 D Tethering: interfaceRemoved p2p0
,08-25 13:18:44.331  1014  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 13:18:44.721   287   287 E SMD     : DCD OFF,
,08-25 13:18:45.001  1014  1452 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 13:18:45.001  1014  1452 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-25 13:18:45.001  1014  1452 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-25 13:18:45.001  1014  1452 D BatteryService: stay LED for fully charged
08-25 13:18:45.011  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 13:18:45.011  1014  1014 I MotionRecognitionService: Plugged
,08-25 13:18:45.011  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 13:18:45.011  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 13:18:45.011  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 13:18:45.011  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 13:18:45.021  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 13:18:45.041  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 13:18:45.041  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-25 13:18:45.041  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:45.041  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:45.041  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:45.111  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 13:18:45.191  6760  6815 D BluetoothAdapter: enable()
,08-25 13:18:45.201  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 13:18:45.201  1014  1026 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-25 13:18:45.201  1014  1026 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 13:18:45.201  1014  1026 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 13:18:45.201  1014  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-25 13:18:45.201  1014  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-25 13:18:45.201  1014  1026 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 13:18:45.201  1014  1026 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 13:18:45.201  1014  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 13:18:45.201  1014  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 13:18:45.211  1014  1026 D SettingsProvider: name = bluetooth_on,
,08-25 13:18:45.231  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-25 13:18:45.231  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 13:18:45.241  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-25 13:18:45.241  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-25 13:18:45.241  1014  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:45.241  1014  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:45.241  1014  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:45.241  1014  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:45.261  7443  7443 E Zygote  : MountEmulatedStorage(),
08-25 13:18:45.261  7443  7443 E Zygote  : v2
08-25 13:18:45.261  7443  7443 I libpersona: KNOX_SDCARD checking this for 1002
,08-25 13:18:45.261  7443  7443 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 13:18:45.261  7443  7443 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:45.261  1014  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7443 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-25 13:18:45.261  7443  7443 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:45.261  7443  7443 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:45.291  7443  7443 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:45.291  7443  7443 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:45.311  7443  7443 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 13:18:45.311  7443  7443 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 13:18:45.341  7443  7443 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding GattService
,08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding HeadsetService
,08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding A2dpService
08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding HidService
,08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding HealthService
08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding PanService
08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding SapService
08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding SapClientService
08-25 13:18:45.371  7443  7443 D BtSettings.ProfileConfig: Adding HidDevService
,08-25 13:18:45.371  7443  7443 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 13:18:45.371  1014  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-25 13:18:45.381  1014  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1133 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1133 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1133 D SettingsProvider: ret = -1
,08-25 13:18:45.381  1014  1244 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-25 13:18:45.381  1014  1244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  1244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1244 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1244 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1244 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1244 D SettingsProvider: ret = -1
,08-25 13:18:45.381  1014  1460 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-25 13:18:45.381  1014  1460 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  1460 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1460 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1460 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1460 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1460 D SettingsProvider: ret = -1
,08-25 13:18:45.381  1014  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-25 13:18:45.381  1014  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1496 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1496 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1496 D SettingsProvider: ret = -1
,08-25 13:18:45.381  1014  1451 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-25 13:18:45.381  1014  1451 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  1451 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1451 D SettingsProvider: selectionArgs: false
,08-25 13:18:45.381  1014  1451 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1451 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1451 D SettingsProvider: ret = -1
08-25 13:18:45.381  1014  1487 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-25 13:18:45.381  1014  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1487 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1487 D SettingsProvider: selectionArgs: 1002
,08-25 13:18:45.381  1014  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1487 D SettingsProvider: ret = -1
08-25 13:18:45.381  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-25 13:18:45.381  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1027 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1027 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1027 D SettingsProvider: ret = -1
08-25 13:18:45.381  1014  1026 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 13:18:45.381  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 13:18:45.381  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1026 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1026 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1026 D SettingsProvider: ret = -1
,08-25 13:18:45.381  1014  4344 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:45.381  1014  4344 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  4344 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-25 13:18:45.381  1014  4344 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  4344 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  4344 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  4344 D SettingsProvider: ret = -1
08-25 13:18:45.381  1014  1514 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:45.381  1014  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1514 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1514 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
,08-25 13:18:45.381  1014  1514 D SettingsProvider: ret = -1
08-25 13:18:45.381  1014  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-25 13:18:45.381  1014  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.381  1014  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 13:18:45.381  1014  1495 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1495 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1495 D SettingsProvider: ret = -1
08-25 13:18:45.381  1014  1452 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-25 13:18:45.381  1014  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 13:18:45.381  1014  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.381  1014  1452 D SettingsProvider: selectionArgs: false
08-25 13:18:45.381  1014  1452 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.381  1014  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.381  1014  1452 D SettingsProvider: ret = -1
,08-25 13:18:45.401  7443  7443 D BluetoothAdapterState: make,
,08-25 13:18:45.411  7443  7443 I bluedroid: init,
08-25 13:18:45.411  7443  7458 I BluetoothAdapterState: Entering OffState,
,08-25 13:18:45.411  7443  7443 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 13:18:45.411  7443  7443 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 13:18:45.411  7443  7443 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 13:18:45.411  7443  7443 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 13:18:45.421  7443  7443 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-25 13:18:45.421  7443  7443 I bluedroid: get_profile_interface socket
08-25 13:18:45.421  7443  7443 I bluedroid: get_profile_interface map_client
08-25 13:18:45.421  7443  7461 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 13:18:45.421  7443  7443 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
08-25 13:18:45.421  7443  7461 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 13:18:45.421  7443  7461 E BluetoothServiceJni: populateRssiValuesNative
,08-25 13:18:45.421  7443  7461 I bluedroid: getModelRssiValues
,08-25 13:18:45.421  7443  7461 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-25 13:18:45.421  7443  7461 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 13:18:45.431  7443  7461 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
08-25 13:18:45.431  1014  1014 D SettingsProvider: name = bluetooth_name
,08-25 13:18:45.431  7443  7443 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:45.431  1014  1133 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 13:18:45.431  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 13:18:45.431  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:45.431  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.431  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:45.441  7443  7451 I bluedroid: config_hci_snoop_log
,08-25 13:18:45.441  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-25 13:18:45.441  1014  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-25 13:18:45.441  1014  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-25 13:18:45.441  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-25 13:18:45.451  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 13:18:45.451  7443  7443 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-25 13:18:45.461  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 13:18:45.461  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 13:18:45.461  1014  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-25 13:18:45.461  7443  7458 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-25 13:18:45.461  7443  7458 D BluetoothAdapterProperties: Setting state to 11
,08-25 13:18:45.471  7443  7458 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 13:18:45.471  7443  7458 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 13:18:45.471  7443  7458 D BluetoothAdapterService: updateAdapterState state is 11
08-25 13:18:45.471  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 13:18:45.471  7443  7458 D BluetoothAdapterService: Autoconnection is available 
08-25 13:18:45.471  7443  7458 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-25 13:18:45.471  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:45.471  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-25 13:18:45.471  7443  7458 D BluetoothSecureManager: getInstant: null
,08-25 13:18:45.471  7443  7458 D BluetoothSecureManager: calling getMethod for getService
08-25 13:18:45.471  7443  7458 D BluetoothSecureManager: calling getService
08-25 13:18:45.471  7443  7458 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@281a8f2a
,08-25 13:18:45.471  1014  1026 D BluetoothSecureManagerService: isSecureModeEnabled
08-25 13:18:45.471  1014  1026 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-25 13:18:45.471  7443  7458 D BtConfig.SecureMode: isSecureModeOn:false
08-25 13:18:45.471  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 13:18:45.471  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-25 13:18:45.471  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:45.471  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-25 13:18:45.471  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 13:18:45.471  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-25 13:18:45.471  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 13:18:45.481  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-25 13:18:45.481  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 13:18:45.481  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-25 13:18:45.481  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 13:18:45.481  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-25 13:18:45.481  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 13:18:45.481  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-25 13:18:45.481  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 13:18:45.481  1885  1885 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 13:18:45.481  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 13:18:45.481  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:45.481  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-25 13:18:45.491  7443  7458 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-25 13:18:45.491  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 13:18:45.491  7443  7458 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:45.491  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 13:18:45.491  1014  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 13:18:45.491  7443  7458 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:45.491  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 13:18:45.491  1014  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-25 13:18:45.491  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:45.491  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 13:18:45.491  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
08-25 13:18:45.491  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 13:18:45.491  7443  7458 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-25 13:18:45.491  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-25 13:18:45.491  1014  1244 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:45.491  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-25 13:18:45.501  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:45.501  7443  7458 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-25 13:18:45.501  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:45.501  1014  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:45.501  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:45.511  7443  7458 D BluetoothBondStateMachine: make
,08-25 13:18:45.511  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 13:18:45.511  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:45.511  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:45.511  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 13:18:45.511  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 13:18:45.511  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 13:18:45.511  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-25 13:18:45.511  7443  7464 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 13:18:45.521  1014  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:45.521  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 13:18:45.521  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:45.521  1014  1460 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:45.521  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:45.521  1014  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-25 13:18:45.521  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:45.521  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:45.521  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:45.521  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:45.521  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:45.521  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 13:18:45.521  7443  7443 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 13:18:45.531  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 13:18:45.531  7443  7443 D BtGatt.GattService: Received start request. Starting profile...
08-25 13:18:45.531  7443  7443 D BtGatt.GattService: start()
08-25 13:18:45.531  7443  7443 D BtGatt.GattService: start()
08-25 13:18:45.531  7443  7443 I bluedroid: get_profile_interface gatt
08-25 13:18:45.531  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
08-25 13:18:45.531  7443  7443 D BtGatt.AdvertiseManager: advertise manager created
,08-25 13:18:45.541  7466  7466 E Zygote  : MountEmulatedStorage()
08-25 13:18:45.541  7466  7466 I libpersona: KNOX_SDCARD checking this for 10055
08-25 13:18:45.541  7466  7466 E Zygote  : v2
08-25 13:18:45.541  7466  7466 I libpersona: KNOX_SDCARD not a persona
08-25 13:18:45.541  7466  7466 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 13:18:45.541  1014  1495 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7466 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-25 13:18:45.541  7466  7466 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 13:18:45.541  1014  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:45.541  7466  7466 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 13:18:45.541  1014  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-25 13:18:45.541  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:45.541  1014  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.541  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:45.551  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 13:18:45.551  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 13:18:45.551  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 13:18:45.551  1014  4344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:45.551  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 13:18:45.551  1014  4344 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:45.551  1014  4344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.551  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 13:18:45.551  7443  7443 D BtGatt.GattService: mStartError = false
08-25 13:18:45.551  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
08-25 13:18:45.551  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-25 13:18:45.551  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 13:18:45.551  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 13:18:45.551  1014  1451 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:45.551  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 13:18:45.551  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:45.551  1014  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.551  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 13:18:45.551  7443  7443 D HeadsetService: Received start request. Starting profile...
08-25 13:18:45.551  7443  7443 D HeadsetService: start()
,08-25 13:18:45.551  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 13:18:45.551  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 13:18:45.551  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 13:18:45.551  7443  7443 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 13:18:45.551  7443  7443 D HeadsetStateMachine: make
,08-25 13:18:45.551  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:45.551  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 13:18:45.561  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:45.561  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.561  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:45.561  7443  7443 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 13:18:45.561  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 13:18:45.561  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 13:18:45.561  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 13:18:45.561  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:45.561  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 13:18:45.561  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:45.561  1014  1514 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-25 13:18:45.561  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.561  1014  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-25 13:18:45.561  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 13:18:45.561  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 13:18:45.561  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:45.561  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 13:18:45.571  1014  1514 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:45.571  1014  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.571  1014  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-25 13:18:45.571  1014  4344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:45.571  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 13:18:45.571  1014  4344 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:45.571  1014  4344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.571  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:45.571  1014  1460 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-25 13:18:45.571  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-25 13:18:45.571  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:45.571  1014  1460 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.571  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 13:18:45.571  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-25 13:18:45.571  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 13:18:45.571  7443  7458 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 13:18:45.571  7443  7443 I bluedroid: get_profile_interface handsfree
08-25 13:18:45.571  1014  1451 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:45.571  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 13:18:45.571  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:45.571  1014  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:45.571  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:45.581  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:45.581  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:45.581  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:45.581  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:45.581  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:45.581  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:45.581  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 13:18:45.581  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 13:18:45.581  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 13:18:45.581  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 13:18:45.581  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 13:18:45.581  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 13:18:45.581  7443  7458 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-25 13:18:45.581  7466  7466 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:45.581  7466  7466 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:45.591  7443  7443 I DualScoManager: Instantiating Dual Sco Manager
,08-25 13:18:45.591  7443  7443 I DualScoManager: Set HeadsetServiceHelper
,08-25 13:18:45.601  7443  7443 D BluetoothAtMessage: createCMTIContentObservers
,08-25 13:18:45.601  1014  1027 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-25 13:18:45.601  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:45.601  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:45.601  1014  1027 D SettingsProvider: selectionArgs: false
08-25 13:18:45.601  1014  1027 D SettingsProvider: selectionArgs: 1002
08-25 13:18:45.601  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:45.601  1014  1027 D SettingsProvider: ret = -1
,08-25 13:18:45.601  7443  7475 D HeadsetStateMachine: Enter Disconnected: -2
,08-25 13:18:45.601  7443  7443 D HeadsetService: mStartError = false
08-25 13:18:45.601  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
08-25 13:18:45.601  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-25 13:18:45.601  7443  7443 D A2dpService: Received start request. Starting profile...
08-25 13:18:45.601  7443  7443 D A2dpService: start()
,08-25 13:18:45.601  7443  7475 D HeadsetStateMachine: Clear mHeadsetBrsf
08-25 13:18:45.601  7443  7475 D HeadsetStateMachine: map size, before remove : 0
08-25 13:18:45.601  7443  7475 D HeadsetStateMachine: map size, after remove: 0
,08-25 13:18:45.611  7443  7443 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 13:18:45.611  7443  7443 I bluedroid: get_profile_interface avrcp
,08-25 13:18:45.611  7443  7443 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 13:18:45.611  7443  7443 D Avrcp   : Initialize Media Controller
08-25 13:18:45.611  7443  7443 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-25 13:18:45.621  7443  7443 E Avrcp   : getActiveSessions
08-25 13:18:45.621  7443  7443 D Avrcp   : pick active media Controller
08-25 13:18:45.621  7443  7443 D Avrcp   : Get the active Media Controller 
,08-25 13:18:45.621  7466  7466 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-25 13:18:45.631  7443  7443 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-25 13:18:45.631  7443  7486 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-25 13:18:45.631  7443  7443 I BluetoothA2dpServiceJni: classInitNative: succeeds,
08-25 13:18:45.631  7443  7443 D A2dpStateMachine: make
,08-25 13:18:45.641  7443  7443 I bluedroid: get_profile_interface a2dp
,08-25 13:18:45.641  7443  7488 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 13:18:45.641  7443  7443 E bt-btif : warning : media task started media_task_refcnt 1 
,08-25 13:18:45.641  7443  7443 D A2dpService: mStartError = false
08-25 13:18:45.641  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:45.641  7443  7443 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 13:18:45.641  7443  7487 D A2dpStateMachine: Enter Disconnected: -2
,08-25 13:18:45.641  7443  7443 D HidService: Received start request. Starting profile...
,08-25 13:18:45.641  7443  7443 D HidService: start()
08-25 13:18:45.641  7443  7443 I bluedroid: get_profile_interface hidhost
08-25 13:18:45.641  7443  7443 D HidService: setHidService(): set to: null
08-25 13:18:45.641  7443  7443 D HidService: mStartError = false
08-25 13:18:45.641  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:45.641  7443  7443 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 13:18:45.641  7443  7443 D HealthService: Received start request. Starting profile...
,08-25 13:18:45.641  7443  7443 D HealthService: start()
,08-25 13:18:45.651  7443  7443 I bluedroid: get_profile_interface health
,08-25 13:18:45.651  7443  7443 D HealthService: mStartError = false
,08-25 13:18:45.651  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
08-25 13:18:45.651  7443  7443 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 13:18:45.651  7466  7466 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-25 13:18:45.651  7443  7443 D PanService: Received start request. Starting profile...
,08-25 13:18:45.651  7443  7443 D PanService: start()
08-25 13:18:45.651  7443  7443 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 13:18:45.651  7443  7443 I bluedroid: get_profile_interface pan
08-25 13:18:45.651  7466  7466 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-25 13:18:45.651  7466  7466 D UserAnalysis: Create SecureDbHelper
,08-25 13:18:45.651  7443  7443 D PanService: mStartError = false
08-25 13:18:45.651  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:45.651  7443  7443 D HeadsetStateMachine: Try to query the phonestate on bind
,08-25 13:18:45.651  1442  1457 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 13:18:45.661  1442  1442 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-25 13:18:45.661  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 13:18:45.661  1442  1457 I Telecom : BluetoothPhoneService: Result of Message : true
,08-25 13:18:45.661  7466  7466 D IntelligenceServiceApplication: onCreate()
,08-25 13:18:45.661  7443  7443 D BluetoothMapService: Received start request. Starting profile...
08-25 13:18:45.661  7443  7443 D BluetoothMapService: start()
,08-25 13:18:45.661  1014  1514 I ActivityManager: Killing 7077:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-25 13:18:45.671  7443  7443 D BluetoothMapService: mStartError = false
08-25 13:18:45.671  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:45.671  7443  7443 D HeadsetStateMachine: Proxy object connected
,08-25 13:18:45.671  7443  7443 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-25 13:18:45.671  7443  7486 D BluetoothMediaBrowser: no now playing list
,08-25 13:18:45.671  7443  7443 D SapService: Received start request. Starting profile...
08-25 13:18:45.671  7443  7443 D SapService: start()
08-25 13:18:45.671  7466  7466 D IntelligenceServiceApplication: no applications having user consent for prediction
08-25 13:18:45.671  7443  7443 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-25 13:18:45.671  7443  7443 I bluedroid: get_profile_interface sap
08-25 13:18:45.671  7443  7443 D SapService: mStartError = false
08-25 13:18:45.671  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:45.671  7443  7443 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-25 13:18:45.671  7443  7486 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-25 13:18:45.671  7443  7443 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-25 13:18:45.671  7443  7475 D HeadsetStateMachine: Disconnected process message: 11
08-25 13:18:45.671  7443  7443 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-25 13:18:45.671  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-25 13:18:45.671  7443  7443 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 13:18:45.671  7443  7443 D BluetoothA2dp: Proxy object connected
08-25 13:18:45.671  7443  7475 D HeadsetStateMachine: Disconnected process message: 18
08-25 13:18:45.671  7443  7475 D HeadsetStateMachine: Disconnected process message: 10
08-25 13:18:45.671  7443  7443 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-25 13:18:45.671  7443  7475 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 13:18:45.671  7443  7475 D HeadsetStateMachine: Disconnected process message: 11
,08-25 13:18:45.671  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-25 13:18:45.671  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-25 13:18:45.671  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-25 13:18:45.671  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 13:18:45.681  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-25 13:18:45.681  7466  7466 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-25 13:18:45.681  7466  7466 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-25 13:18:45.701  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-25 13:18:45.701  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 13:18:45.701  1014  1133 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-25 13:18:45.711  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:45.711  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:45.711  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:45.711  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:45.721  7493  7493 E Zygote  : MountEmulatedStorage(),
,08-25 13:18:45.721  7493  7493 E Zygote  : v2
08-25 13:18:45.721  7493  7493 I libpersona: KNOX_SDCARD checking this for 10105,
08-25 13:18:45.721  7493  7493 I libpersona: KNOX_SDCARD not a persona
08-25 13:18:45.721  7493  7493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:45.721  7493  7493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 13:18:45.721  1014  1133 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7493 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-25 13:18:45.721  7493  7493 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-25 13:18:45.721  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-25 13:18:45.721  7443  7458 I bluedroid: enable
08-25 13:18:45.721  7443  7458 I bt_hci_bdroid: init
08-25 13:18:45.721  7443  7499 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-25 13:18:45.731  7443  7458 I bt_vendor: bt-vendor : init
08-25 13:18:45.731  7443  7458 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 13:18:45.731  7443  7458 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 13:18:45.731  7443  7458 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-25 13:18:45.731  7443  7458 D bt_userial_mct: userial_init
,08-25 13:18:45.731  7443  7458 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 13:18:45.731  7443  7458 I bt_vendor: Starting hciattach daemon
08-25 13:18:45.731  7443  7458 I bt_vendor: try to set false
,08-25 13:18:45.731  7443  7458 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 13:18:45.731  7443  7458 I bt_vendor: Starting hciattach daemon
08-25 13:18:45.731  7443  7458 I bt_vendor: try to set true
,08-25 13:18:45.751  7508  7508 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 13:18:45.761  7493  7493 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:45.761  7493  7493 D ActivityThread: Added TimaKeyStore provider,
,08-25 13:18:45.801  7519  7519 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-25 13:18:45.811  7520  7520 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 13:18:45.831  7522  7522 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 13:18:45.831  7523  7523 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-25 13:18:45.841  7524  7524 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 13:18:45.851  7525  7525 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-25 13:18:45.911   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 13:18:45.911   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:18:45.911  7493  7530 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 13:18:45.921   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 13:18:45.921   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 13:18:45.921  7493  7530 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 13:18:46.081  7493  7493 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 13:18:46.081  7493  7493 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:46.081  7493  7493 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:46.081  7493  7493 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:46.081  7493  7493 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.k.d(PG:583)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:46.081  7493  7493 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:46.081  7493  7493 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:46.081  7493  7493 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 13:18:46.081  7493  7493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 13:18:46.081  1014  4344 I ActivityManager: Killing 7092:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-25 13:18:46.091  1994  1994 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 13:18:46.091  1994  1994 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-25 13:18:46.121  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-25 13:18:46.131  7543  7543 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 13:18:46.141  7443  7458 I bt_vendor: bluetooth satus is on
08-25 13:18:46.141  7443  7504 D bt_userial_mct: userial_open(port:0)
08-25 13:18:46.141  7443  7504 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-25 13:18:46.141  7443  7504 I bt_vendor: Done intiailizing UART
08-25 13:18:46.151  7443  7504 I bt_vendor: Done intiailizing UART
08-25 13:18:46.151  7443  7504 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-25 13:18:46.151  7443  7504 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 13:18:46.151  7443  7545 D bt_userial_mct: Entering userial_read_thread()
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_SAP
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 13:18:46.151  7443  7499 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-25 13:18:46.161  7493  7531 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 13:18:46.181  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:46.181  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:46.181  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:46.191  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-25 13:18:46.241  7443  7499 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-25 13:18:46.251  7443  7499 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa427eed1 
,08-25 13:18:46.251  7443  7499 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa427eed1 
,08-25 13:18:46.261  7443  7461 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-25 13:18:46.271  7443  7461 E bt-btif : Calling BTA_HhEnable
,08-25 13:18:46.271  7443  7461 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 13:18:46.271  7443  7461 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 13:18:46.271  7443  7461 E BluetoothServiceJni: populateRssiValuesNative
,08-25 13:18:46.271  7443  7461 I bluedroid: getModelRssiValues
08-25 13:18:46.271  7443  7461 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-25 13:18:46.271  7443  7461 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 13:18:46.281  1014  1014 D SettingsProvider: name = bluetooth_name
,08-25 13:18:46.281  7443  7461 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 13:18:46.281  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:46.291  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:46.291  7443  7461 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 13:18:46.291  7443  7461 D BluetoothAdapterProperties: Scan Mode:20
,08-25 13:18:46.291  7443  7461 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 13:18:46.291  7443  7461 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-25 13:18:46.291  7443  7461 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-25 13:18:46.291  7443  7461 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-25 13:18:46.291  7443  7461 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-25 13:18:46.291  7443  7461 E bt-btif : btif_sock_init: !vhci_init
,08-25 13:18:46.291  7443  7461 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-25 13:18:46.291  7443  7545 E bt_mct  : hci lib postload completed
,08-25 13:18:46.301  7443  7461 D IOP_DB_BT: db_open: db_open : handle 3028086800l, read 13894 bytes onto local cache
,08-25 13:18:46.301  7443  7461 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-25 13:18:46.301  7443  7461 D IOP_DB_BT: db_query: result 1
,08-25 13:18:46.301  7443  7461 I         : iop_db_open: iop_db_open status 0
,08-25 13:18:46.301  7443  7461 D bte_conf: Device ID record 1 : primary
,08-25 13:18:46.301  7443  7461 D bte_conf:   vendorId            = 0075
,08-25 13:18:46.301  7443  7461 D bte_conf:   vendorIdSource      = 0001
,08-25 13:18:46.301  7443  7461 D bte_conf:   product             = 0100
08-25 13:18:46.301  7443  7461 D bte_conf:   version             = 0200
,08-25 13:18:46.301  7443  7461 D bte_conf:   clientExecutableURL = 
08-25 13:18:46.301  7443  7461 D bte_conf:   serviceDescription  = 
,08-25 13:18:46.311  7443  7461 D bte_conf:   documentationURL    = 
08-25 13:18:46.311  7443  7461 D bte_conf: bte_load_did_conf no section named DID2.
,08-25 13:18:46.311  7443  7461 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 13:18:46.311  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 13:18:46.311  7443  7458 D BluetoothAdapterProperties: ScanMode =  20
08-25 13:18:46.311  7443  7458 D BluetoothAdapterProperties: State =  11
,08-25 13:18:46.311  1014  1451 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 13:18:46.311  7443  7461 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 13:18:46.311  7443  7461 D BluetoothAdapterProperties: Scan Mode:21
08-25 13:18:46.311  7443  7458 D BluetoothAdapterProperties: Setting state to 12
08-25 13:18:46.311  7443  7458 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 13:18:46.311  7443  7461 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 13:18:46.321  1014  1027 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-25 13:18:46.321  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 13:18:46.321  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 13:18:46.321  1014  1027 D SettingsProvider: selectionArgs: false
08-25 13:18:46.321  1014  1027 D SettingsProvider: selectionArgs: 1002
,08-25 13:18:46.321  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:46.321  1014  1027 D SettingsProvider: ret = -1
,08-25 13:18:46.321  7443  7458 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-25 13:18:46.321  7443  7458 D BluetoothAdapterService: updateAdapterState state is 12
,08-25 13:18:46.321  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:46.331  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.331  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:46.331  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:46.331  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.331  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 13:18:46.331  1014  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:46.331  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 13:18:46.331  7443  7458 D BluetoothAdapterService: Autoconnection is available 
08-25 13:18:46.331  7443  7458 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 13:18:46.331  7443  7458 D BluetoothAdapterService: starting service from this receiver
,08-25 13:18:46.331  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.341  1014  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:46.341  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.341  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.341  1014  1014 D BluetoothA2dp: Proxy object connected
08-25 13:18:46.341  1014  1460 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.341  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 13:18:46.341  1442  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:46.351  7443  7458 I BluetoothAdapterState: Entering On State from state = 11
,08-25 13:18:46.361  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 13:18:46.361  7443  7443 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-25 13:18:46.361  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:46.361  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:46.361  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:46.361  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:46.361  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:46.361  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:46.361  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:46.361  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:46.371  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3,
,08-25 13:18:46.371  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.371  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.371  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.371  1442  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:46.371  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:46.371  7493  7507 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:46.371  7493  7507 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
,08-25 13:18:46.371  1296  1317 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 13:18:46.371  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-25 13:18:46.371  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.381  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.381  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.381  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.381  7443  7443 I BluetoothPbapService: Handler(): got msg=1
,08-25 13:18:46.381  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:46.381  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:46.381  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:46.381  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:46.381  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:46.381  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:46.381  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:46.381  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:46.381  1014  1027 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 13:18:46.381  1442  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:46.381  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:18:46.381  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 13:18:46.381  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 13:18:46.381  7443  7551 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-25 13:18:46.381  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.381  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.381  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.391  1442  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:46.391  1296  1296 D BluetoothMap: Proxy object connected
08-25 13:18:46.391  1296  1296 D MapProfile: Bluetooth service connected
08-25 13:18:46.391  1296  1296 D BluetoothMap: getConnectedDevices()
,08-25 13:18:46.391  7443  7454 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:46.391  7443  7454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:46.391  1296  1311 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:46.391  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 13:18:46.391  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 13:18:46.401  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.401  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.401  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-25 13:18:46.401  1296  1311 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:46.401  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:46.401  1014  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 13:18:46.401  1296  1296 D HeadsetProfile: Bluetooth service connected
08-25 13:18:46.401  1994  2005 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:46.401  1994  2005 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:46.401  1296  6964 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:46.401  1296  6964 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 13:18:46.401  7443  7551 D BluetoothSocket: bindListen(): myUserId = 0
08-25 13:18:46.401  1296  1317 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 13:18:46.401  7443  7551 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:18:46.401  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-25 13:18:46.401  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.401  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.401  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.401  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.401  6760  6771 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:46.401  6760  6771 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:46.401  1296  6964 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 13:18:46.401  7443  7551 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-25 13:18:46.401  7443  7551 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 13:18:46.401  7443  7551 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 13:18:46.401  7443  7551 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@273f9ccf
08-25 13:18:46.401  7443  7551 D BluetoothSocket: channel: 19
08-25 13:18:46.401  7443  7551 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-25 13:18:46.401  1296  1296 D BluetoothPbap: Proxy object connected
,08-25 13:18:46.401  1296  6964 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-25 13:18:46.411  1296  1296 D PbapServerProfile: Bluetooth service connected
,08-25 13:18:46.411  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 13:18:46.411  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.411  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:46.411  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:46.411  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.411  1296  1296 D BluetoothA2dp: Proxy object connected
08-25 13:18:46.411  1296  1296 D A2dpProfile: Bluetooth service connected
,08-25 13:18:46.411  7443  7454 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 13:18:46.411  1442  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
08-25 13:18:46.411  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 13:18:46.411  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 13:18:46.411  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.411  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.411  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth,
08-25 13:18:46.411  1442  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:46.411  1296  1311 D BluetoothPan: Binding service...
,08-25 13:18:46.411  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 13:18:46.411  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.421  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.421  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.421  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.421  1456  1800 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 13:18:46.421  1456  1800 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:46.421  1296  1296 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 13:18:46.421  1014  1045 D BluetoothPan: Binding service...
08-25 13:18:46.421  1296  1296 D PanProfile: Bluetooth service connected
08-25 13:18:46.421  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 13:18:46.421  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-25 13:18:46.421  1014  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:46.421  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 13:18:46.421  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 13:18:46.421  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 13:18:46.421  1014  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:46.421  1475  1671 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:46.421  1014  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 13:18:46.421  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 13:18:46.431  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.431  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.431  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.431  1475  1671 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:46.431  1475  2047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:46.431  1475  2047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 13:18:46.431  1296  6964 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 13:18:46.431  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-25 13:18:46.431  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-25 13:18:46.431  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.431  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.431  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.431  1442  7552 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 13:18:46.431  1442  7552 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:46.431  1176  3371 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 13:18:46.431  1176  3371 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:46.431  1296  1317 D Bluetoothsap: onBluetoothStateChange: up=true
08-25 13:18:46.431  1296  1296 D BluetoothInputDevice: Proxy object connected
08-25 13:18:46.431  1296  1296 D HidProfile: Bluetooth service connected
,08-25 13:18:46.431  1296  1317 D Bluetoothsap: Binding service...
,08-25 13:18:46.441  1296  1317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-25 13:18:46.441  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-25 13:18:46.441  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.441  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:46.441  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.441  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.451  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-25 13:18:46.451  1296  1296 D SapProfile: Bluetooth service connected
08-25 13:18:46.451  1296  1296 D Bluetoothsap: getConnectedDevices()
,08-25 13:18:46.451  1296  1317 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-25 13:18:46.451  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 13:18:46.451  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 13:18:46.451  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:46.451  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
,08-25 13:18:46.451  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 13:18:46.461  1442  1442 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2b3e18fb, true,
08-25 13:18:46.461  1176  1176 D BluetoothTile:  onBluetoothStateChange:
08-25 13:18:46.461  1442  1442 D BluetoothHeadset: registerMessageListener
,08-25 13:18:46.461  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 13:18:46.461  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:46.461  1176  1176 D BluetoothTile:  getBluetoothState : 12
,08-25 13:18:46.461  1885  1885 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 13:18:46.461  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:46.461  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 13:18:46.471  1014  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:46.471  7443  7451 D HeadsetService: registerMessageListener
,08-25 13:18:46.471  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.471  7443  7451 D HeadsetService: registerMessageListener
,08-25 13:18:46.471  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.471  1014  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:46.471  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:46.471  7443  7475 D HeadsetStateMachine: Disconnected process message: 70
08-25 13:18:46.471  7443  7475 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2ef7065c
,08-25 13:18:46.471  1442  1442 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-25 13:18:46.471  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 13:18:46.471  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 13:18:46.471  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:46.481  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 13:18:46.481  1296  1296 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-25 13:18:46.481  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:46.481  1296  1296 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-25 13:18:46.481  1296  1296 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-25 13:18:46.481  1296  1296 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-25 13:18:46.481  1442  1442 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-25 13:18:46.481  1442  1442 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-25 13:18:46.481  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-25 13:18:46.481  1014  1244 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 13:18:46.481  1014  1496 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-25 13:18:46.481  7443  7475 D HeadsetStateMachine: Disconnected process message: 9
,08-25 13:18:46.481  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 13:18:46.481  7443  7475 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 13:18:46.491  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:18:46.491  1014  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 13:18:46.491  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.491  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.491  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.491  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 13:18:46.491  7443  7554 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-25 13:18:46.491   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-25 13:18:46.491   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-25 13:18:46.491   282   282 V voice   : voice_set_parameters: exit with code(-2)
08-25 13:18:46.491   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-25 13:18:46.491   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-25 13:18:46.491   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-25 13:18:46.491   282   282 V audio_hw_primary: adev_set_parameters: exit
,08-25 13:18:46.501  7443  7475 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-25 13:18:46.501  7443  7554 D BluetoothSocket: bindListen(): myUserId = 0
08-25 13:18:46.501  7443  7554 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:18:46.501  7443  7554 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-25 13:18:46.501  7443  7554 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 13:18:46.501  7443  7554 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 13:18:46.501  7443  7554 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a45ed65
08-25 13:18:46.501  7443  7554 D BluetoothSocket: channel: 5
,08-25 13:18:46.501  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:46.511  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 13:18:46.511  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:46.511  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 13:18:46.521  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:46.521  7443  7443 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 13:18:46.521  1014  1244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:46.521  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 13:18:46.521  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:46.521  1014  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:46.521  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:46.531  1994  1994 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:46.531  1014  1244 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-25 13:18:46.531  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-25 13:18:46.531  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:46.541  1014  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:46.541  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:46.551  1994  7560 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 13:18:46.551  1994  1994 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 13:18:46.711  1014  4344 I art     : Explicit concurrent mark sweep GC freed 72110(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 2.397ms total 158.074ms
08-25 13:18:46.711  1014  4344 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:46.711  1014  4344 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:46.711  1014  4344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:46.711  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:46.721  1014  1451 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 13:18:46.731  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:46.731  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:46.731  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:46.731  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:46.741  7443  7564 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 13:18:46.741  7443  7564 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:18:46.741  7443  7564 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-25 13:18:46.741  7443  7564 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 13:18:46.741  7443  7564 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 13:18:46.741  7443  7564 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@59c56c7
,08-25 13:18:46.741  7443  7564 D BluetoothSocket: channel: 12
08-25 13:18:46.741  7443  7564 I BtOppRfcommListener: Accept thread started.
,08-25 13:18:46.741  1994  7560 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-25 13:18:47.721   287   287 E SMD     : DCD OFF
,08-25 13:18:48.241  6760  6815 D BluetoothAdapter: disable()
,08-25 13:18:48.241  1014  1514 D SettingsProvider: name = bluetooth_on
,08-25 13:18:48.251  7443  7458 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-25 13:18:48.251  7443  7458 D BluetoothAdapterProperties: Setting state to 13
,08-25 13:18:48.251  7443  7458 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 13:18:48.251  7443  7458 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-25 13:18:48.251  7443  7458 D BluetoothAdapterService: updateAdapterState state is 13
,08-25 13:18:48.261  1014  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:48.261  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-25 13:18:48.261  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:48.261  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.261  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:48.261  7443  7443 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-25 13:18:48.261  7443  7458 D BluetoothAdapterService: Autoconnection is available 
08-25 13:18:48.261  7443  7458 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-25 13:18:48.261  7443  7458 D BluetoothAdapterService: terminating service from this receiver
,08-25 13:18:48.261  7443  7443 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2aebc4f4, channel: 19, state: LISTENING
08-25 13:18:48.261  7443  7443 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2aebc4f4, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@273f9ccf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@251d641dmSocket: android.net.LocalSocket@d72a692 impl:android.net.LocalSocketImpl@f7d9863 fd:FileDescriptor[74]
08-25 13:18:48.261  7443  7443 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d72a692 impl:android.net.LocalSocketImpl@f7d9863 fd:FileDescriptor[74]
,08-25 13:18:48.261  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.271  1014  4344 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:48.271  1014  4344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.271  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:48.271  7443  7458 D BluetoothAdapterProperties: onBluetoothDisable(),
08-25 13:18:48.271  7443  7458 D BluetoothAdapterProperties: mDiscovering is false
08-25 13:18:48.271  1014  1026 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 13:18:48.271  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:48.271  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-25 13:18:48.281  7443  7458 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-25 13:18:48.281  1296  1296 D BluetoothPbap: Proxy object disconnected
,08-25 13:18:48.281  1296  1296 D PbapServerProfile: Bluetooth service disconnected
,08-25 13:18:48.291  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-25 13:18:48.291  1885  1885 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 13:18:48.301  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 13:18:48.301  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:48.301  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-25 13:18:48.301  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 13:18:48.301  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:48.301  1014  1460 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:48.301  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.301  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:48.301  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:48.301  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:48.301  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:48.301  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:48.301  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:48.301  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:48.301  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:48.301  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:48.301  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:48.301  1014  1460 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:48.301  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:48.311  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:48.311  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:48.311  7443  7461 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 13:18:48.311  7443  7461 D BluetoothAdapterProperties: Scan Mode:20
,08-25 13:18:48.311  1014  4344 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 13:18:48.311  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:48.311  1014  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 13:18:48.311  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:48.311  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:48.311  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:48.311  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:48.311  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:48.311  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:48.311  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:48.311  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:48.311  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 13:18:48.311  6760  6760 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:48.311  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:48.311  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-25 13:18:48.321  7443  7458 E bt-btif : btif_dm_generic_evtnup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-25 13:18:48.321  7443  7458 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-25 13:18:48.321  7443  7458 E bt-btif : cmd socket is not created
,08-25 13:18:48.321  7443  7458 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 13:18:48.321  7443  7499 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-25 13:18:48.321  7443  7499 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 13:18:48.321  7443  7499 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:18:48.321  7443  7499 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:48.321  7443  7499 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 13:18:48.321  7443  7564 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 13:18:48.321  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 13:18:48.321  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:48.321  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 13:18:48.331  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:48.331  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:18:48.331  7443  7443 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30b12519, channel: 5, state: LISTENING
08-25 13:18:48.331  1014  1451 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 13:18:48.331  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-25 13:18:48.331  7443  7443 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30b12519, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a45ed65, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f1099demSocket: android.net.LocalSocket@8a757bf impl:android.net.LocalSocketImpl@8b6be8c fd:FileDescriptor[76]
08-25 13:18:48.331  7443  7443 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@8a757bf impl:android.net.LocalSocketImpl@8b6be8c fd:FileDescriptor[76]
,08-25 13:18:48.331  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:48.331  1014  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.331  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-25 13:18:48.331  7443  7443 I BtOppRfcommListener: stopping Accept Thread
08-25 13:18:48.331  7443  7443 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1025f9d5, channel: 12, state: LISTENING
08-25 13:18:48.331  7443  7443 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1025f9d5, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@59c56c7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@20875eamSocket: android.net.LocalSocket@e83b0db impl:android.net.LocalSocketImpl@32573778 fd:FileDescriptor[80]
08-25 13:18:48.331  7443  7443 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@e83b0db impl:android.net.LocalSocketImpl@32573778 fd:FileDescriptor[80]
,08-25 13:18:48.331  7443  7564 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 13:18:48.341  7443  7443 V BluetoothOppManager: cleanUp...
,08-25 13:18:48.341  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:48.351  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 13:18:48.351  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:48.351  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 13:18:48.371  1994  1994 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:48.381  1994  1994 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 13:18:48.521  7443  7499 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 13:18:48.521  7443  7499 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 13:18:48.521  7443  7499 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:18:48.521  7443  7499 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 13:18:48.521  7443  7499 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:48.521  7443  7499 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 13:18:48.521  7443  7499 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 13:18:48.521  7443  7499 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:48.521  7443  7499 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 13:18:48.521  7443  7499 W bt-btif : ag scb idx 1 not allocated
,08-25 13:18:48.521  7443  7499 W bt-btif : ag scb idx 2 not allocated
08-25 13:18:48.521  7443  7499 E bt-btif : BTA AG is already disabled, ignoring ...
,08-25 13:18:48.521  7443  7545 I bt_userial_mct: exiting userial_read_thread
,08-25 13:18:48.521  7443  7545 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-25 13:18:48.521  7443  7461 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-25 13:18:48.521  7443  7504 I bt_vendor: hw_epilog_process
,08-25 13:18:48.531  7443  7461 D bt_userial_mct: userial_close,
08-25 13:18:48.531  7443  7461 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 13:18:48.811  7443  7461 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 13:18:48.811  7443  7461 I bt_vendor: bluetooth satus is on
08-25 13:18:48.811  7443  7461 I bt_vendor: bt-vendor : resetting BT status
08-25 13:18:48.811  7443  7461 I bt_vendor: Starting hciattach daemon
08-25 13:18:48.811  7443  7461 I bt_vendor: try to set false
,08-25 13:18:48.811  7443  7461 I bt_vendor: Starting hciattach daemon
,08-25 13:18:48.811  7443  7461 I bt_vendor: try to set false
,08-25 13:18:48.811  7443  7461 I bt_vendor: cleanup
,08-25 13:18:48.811  7443  7499 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-25 13:18:48.811  7443  7461 I GKI_LINUX: GKI_exit_task 0 done
,08-25 13:18:48.811  7443  7461 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-25 13:18:48.811  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-25 13:18:48.811  7443  7458 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 13:18:48.811  7443  7458 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-25 13:18:48.821  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 13:18:48.821  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 13:18:48.821  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 13:18:48.821  1014  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:48.821  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.821  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:48.821  1014  1460 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:48.821  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:48.821  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:48.821  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:48.821  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:48.821  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:48.821  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.831  7443  7443 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 13:18:48.831  7443  7443 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 13:18:48.831  7443  7443 D BtGatt.GattService: stop()
08-25 13:18:48.831  7443  7443 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 13:18:48.831  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:48.831  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.831  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 13:18:48.831  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 13:18:48.831  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 13:18:48.831  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-25 13:18:48.831  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:48.831  1014  1451 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:48.831  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.831  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:48.831  1014  1451 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.831  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:48.831  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-25 13:18:48.831  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 13:18:48.831  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 13:18:48.831  1014  4344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:48.831  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.841  7443  7443 D HeadsetService: Received stop request...Stopping profile...
,08-25 13:18:48.841  1014  4344 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:48.841  1014  4344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.841  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:48.841  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-25 13:18:48.841  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 13:18:48.841  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 13:18:48.841  1014  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:48.841  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.841  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
08-25 13:18:48.841  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:48.841  1014  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.841  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:48.841  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-25 13:18:48.841  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 13:18:48.841  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 13:18:48.841  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 13:18:48.851  1296  1296 D HeadsetProfile: Bluetooth service disconnected
08-25 13:18:48.851  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:48.851  1014  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:48.851  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.851  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
08-25 13:18:48.851  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 13:18:48.851  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 13:18:48.851  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:48.851  7443  7458 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 13:18:48.851  1014  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:48.851  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.851  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:48.851  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:48.851  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:48.851  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-25 13:18:48.851  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 13:18:48.851  7443  7458 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 13:18:48.851  1014  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:48.851  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.861  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:48.861  1014  1460 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.861  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:48.861  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:48.861  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:48.861  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:48.861  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:48.861  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:48.861  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:48.861  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 13:18:48.861  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 13:18:48.861  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 13:18:48.861  7443  7458 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 13:18:48.861  7443  7458 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 13:18:48.861  7443  7458 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 13:18:48.861  7443  7458 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 13:18:48.861  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-25 13:18:48.861  7443  7443 D A2dpService: Received stop request...Stopping profile...
08-25 13:18:48.861  7443  7487 D A2dpStateMachine: Exit Disconnected: -1
,08-25 13:18:48.861  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:48.861  1014  1014 D BluetoothA2dp: Proxy object disconnected
,08-25 13:18:48.861  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-25 13:18:48.861  1296  1296 D BluetoothA2dp: Proxy object disconnected
08-25 13:18:48.861  1296  1296 D A2dpProfile: Bluetooth service disconnected
08-25 13:18:48.861  7443  7443 D HidService: Received stop request...Stopping profile...
08-25 13:18:48.861  7443  7443 D HidService: Stopping Bluetooth HidService
08-25 13:18:48.861  7443  7443 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-25 13:18:48.861  7443  7443 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-25 13:18:48.861  7443  7443 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 13:18:48.861  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:48.871  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-25 13:18:48.871  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 13:18:48.871  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-25 13:18:48.871  7443  7443 D HealthService: Received stop request...Stopping profile...
08-25 13:18:48.871  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:48.871  1296  1296 D BluetoothInputDevice: Proxy object disconnected
08-25 13:18:48.871  1296  1296 D HidProfile: Bluetooth service disconnected
08-25 13:18:48.871  7443  7443 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 13:18:48.871  7443  7443 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 13:18:48.871  7443  7443 D PanService: Received stop request...Stopping profile...
,08-25 13:18:48.871  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:48.871  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 13:18:48.871  1296  1296 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 13:18:48.871  1296  1296 D PanProfile: Bluetooth service disconnected
,08-25 13:18:48.881  7443  7443 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 13:18:48.881  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d
,08-25 13:18:48.881  1296  1296 D BluetoothMap: Proxy object disconnected
08-25 13:18:48.881  1296  1296 D MapProfile: Bluetooth service disconnected
,08-25 13:18:48.881  7443  7443 D SapService: Received stop request...Stopping profile...,
08-25 13:18:48.881  7443  7443 D SapService: Stopping Bluetooth SapService
08-25 13:18:48.881  7443  7443 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3adf925d,
08-25 13:18:48.881  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-25 13:18:48.881  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 13:18:48.881  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 13:18:48.881  7443  7443 D BluetoothA2dp: Proxy object disconnected
08-25 13:18:48.881  7443  7443 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-25 13:18:48.881  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-25 13:18:48.881  1296  1296 D SapProfile: Bluetooth service disconnected
08-25 13:18:48.881  7443  7488 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-25 13:18:48.881  7443  7443 I GKI_LINUX: GKI_exit_task 2 done
08-25 13:18:48.881  7443  7443 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 13:18:48.881  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-25 13:18:48.881  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:48.881  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:48.881  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-25 13:18:48.881  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:48.881  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:48.881  7443  7443 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 13:18:48.881  7443  7443 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-25 13:18:48.881  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-25 13:18:48.881  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:48.881  7443  7443 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:48.881  7443  7443 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 13:18:48.881  7443  7443 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 13:18:48.891  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-25 13:18:48.891  7443  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 13:18:48.891  7443  7443 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-25 13:18:48.891  7443  7443 E BluetoothAdapterService(987730525): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-25 13:18:48.891  7443  7443 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-25 13:18:48.891  7443  7443 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-25 13:18:48.891  7443  7458 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-25 13:18:48.891  7443  7458 D BluetoothAdapterProperties: Setting state to 10
08-25 13:18:48.891  7443  7458 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-25 13:18:48.891  7443  7458 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 13:18:48.891  7443  7458 D BluetoothAdapterService: updateAdapterState state is 10
,08-25 13:18:48.891  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 13:18:48.891  7443  7458 D BluetoothAdapterService: Autoconnection is available 
,08-25 13:18:48.891  7443  7458 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 13:18:48.891  7443  7458 I BluetoothAdapterState: Entering OffState
,08-25 13:18:48.891  7493  7503 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:48.891  7493  7503 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:48.891  1296  6964 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 13:18:48.901  7443  7454 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 13:18:48.901  7443  7454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:48.901  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 13:18:48.901  1014  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:48.901  1994  2155 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:48.901  1994  2155 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:48.901  1296  1317 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:48.901  1296  1317 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:48.901  1296  6964 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 13:18:48.901  6760  6771 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 13:18:48.901  6760  6771 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 13:18:48.901  6760  6771 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-25 13:18:48.901  6760  6771 D BluetoothLeAdvertiser: Exit stop advertising
08-25 13:18:48.901  6760  6771 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-25 13:18:48.901  6760  6771 D BluetoothLeScanner: Exiting stopAllScan
,08-25 13:18:48.901  1296  1311 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 13:18:48.901  7443  7553 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 13:18:48.901  1456  1800 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 13:18:48.911  1456  1800 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:48.911  1475  1488 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 13:18:48.911  1475  1488 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:48.911  1296  6964 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 13:18:48.911  1442  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 13:18:48.911  1442  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:48.911  1176  3217 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 13:18:48.911  1176  3217 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 13:18:48.911  1296  1311 D Bluetoothsap: onBluetoothStateChange: up=false
08-25 13:18:48.911  1296  1311 D Bluetoothsap: Unbinding service...
,08-25 13:18:48.911  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 13:18:48.911  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 13:18:48.921  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:48.921  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-25 13:18:48.921  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 13:18:48.921  1176  1176 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
08-25 13:18:48.921  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 13:18:48.921  1176  1775 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
,08-25 13:18:48.921  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:48.921  1176  1176 D BluetoothTile:  getBluetoothState : 10
08-25 13:18:48.921  1176  1775 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
08-25 13:18:48.931  1014  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 13:18:48.921  1176  1176 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
08-25 13:18:48.921  1176  1176 D BluetoothAdapter: 205574612: getState() :  mService = null. Returning STATE_OFF
08-25 13:18:48.931  7443  7461 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 13:18:48.931  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-25 13:18:48.931  1885  1885 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 13:18:48.931  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 13:18:48.931  7443  7443 I GKI_LINUX: GKI_exit_task 1 done
08-25 13:18:48.931  7443  7443 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 13:18:48.931  7443  7443 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 13:18:48.931  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:48.931  1994  2157 D BluetoothAdapter: 1059663781: getState() :  mService = null. Returning STATE_OFF
08-25 13:18:48.931  1994  2157 D BluetoothAdapter: 1059663781: getState() :  mService = null. Returning STATE_OFF
,08-25 13:18:48.931  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:48.931  7443  7443 I art     : System.exit called, status: 0
08-25 13:18:48.931  7443  7443 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 13:18:48.931  1014  1451 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 13:18:48.931  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.931  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:48.931  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:48.931  1014  1451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:48.931  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:48.941  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:18:48.941  1014  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 13:18:48.941  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 13:18:48.941  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:48.941  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:48.941  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 13:18:48.951  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:48.951  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 13:18:48.951  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:48.951  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-25 13:18:48.961  1014  1026 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-25 13:18:48.961  1014  1026 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-25 13:18:48.961  1014  1026 W BroadcastQueue: android.os.TransactionTooLargeException
08-25 13:18:48.961  1014  1026 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 13:18:48.961  1014  1026 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 13:18:48.961  1014  1026 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-25 13:18:48.961  1014  1026 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-25 13:18:48.961  1014  1026 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-25 13:18:48.961  1014  1026 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-25 13:18:48.961  1014  1026 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-25 13:18:48.961  1014  1026 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-25 13:18:48.961  1014  1026 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 13:18:48.961  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-25 13:18:48.961  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:48.961  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:48.961  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:48.961  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:48.981  7579  7579 E Zygote  : MountEmulatedStorage(),
,08-25 13:18:48.981  7579  7579 E Zygote  : v2
08-25 13:18:48.981  7579  7579 I libpersona: KNOX_SDCARD checking this for 1002
08-25 13:18:48.981  7579  7579 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:48.981  7579  7579 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 13:18:48.981  1014  1026 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7579 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-25 13:18:48.981  7579  7579 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:48.981  7579  7579 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 13:18:49.001  7579  7579 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:49.001  7579  7579 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:49.011  7579  7579 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 13:18:49.011  7579  7579 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 13:18:49.031  7579  7579 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 13:18:49.061  7579  7579 D BtSettings.ProfileConfig: Adding GattService
,08-25 13:18:49.061  7579  7579 D BtSettings.ProfileConfig: Adding HeadsetService
08-25 13:18:49.061  7579  7579 D BtSettings.ProfileConfig: Adding A2dpService
,08-25 13:18:49.061  7579  7579 D BtSettings.ProfileConfig: Adding HidService
08-25 13:18:49.061  7579  7579 D BtSettings.ProfileConfig: Adding HealthService
08-25 13:18:49.061  7579  7579 D BtSettings.ProfileConfig: Adding PanService
,08-25 13:18:49.061  7579  7579 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-25 13:18:49.061  7579  7579 D BtSettings.ProfileConfig: Adding SapService
,08-25 13:18:49.071  7579  7579 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-25 13:18:49.071  7579  7579 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-25 13:18:49.071  7579  7579 D BtSettings.ProfileConfig: Adding SapClientService
,08-25 13:18:49.071  7579  7579 D BtSettings.ProfileConfig: Adding HidDevService
08-25 13:18:49.071  7579  7579 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 13:18:49.071  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-25 13:18:49.071  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.071  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.071  1014  1027 D SettingsProvider: selectionArgs: false
08-25 13:18:49.071  1014  1027 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.071  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:49.071  1014  1027 D SettingsProvider: ret = -1
,08-25 13:18:49.071  1014  1451 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:49.071  1014  1451 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.071  1014  1451 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.071  1014  1451 D SettingsProvider: selectionArgs: false
,08-25 13:18:49.071  1014  1451 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.071  1014  1451 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:49.071  1014  1451 D SettingsProvider: ret = -1
,08-25 13:18:49.071  1014  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-25 13:18:49.071  1014  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.071  1014  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.071  1014  1496 D SettingsProvider: selectionArgs: false
08-25 13:18:49.071  1014  1496 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.071  1014  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:49.071  1014  1496 D SettingsProvider: ret = -1
,08-25 13:18:49.071  1014  1460 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-25 13:18:49.071  1014  1460 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.071  1014  1460 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.071  1014  1460 D SettingsProvider: selectionArgs: false
,08-25 13:18:49.071  1014  1460 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.071  1014  1460 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:49.071  1014  1460 D SettingsProvider: ret = -1
,08-25 13:18:49.081  1014  1514 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-25 13:18:49.081  1014  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.081  1014  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.081  1014  1514 D SettingsProvider: selectionArgs: false
08-25 13:18:49.081  1014  1514 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.081  1014  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:49.081  1014  1514 D SettingsProvider: ret = -1
,08-25 13:18:49.081  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-25 13:18:49.081  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.081  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 13:18:49.081  1014  1026 D SettingsProvider: selectionArgs: false
08-25 13:18:49.081  1014  1026 D SettingsProvider: selectionArgs: 1002
,08-25 13:18:49.081  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:49.081  1014  1026 D SettingsProvider: ret = -1
,08-25 13:18:49.081  1014  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-25 13:18:49.081  1014  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.081  1014  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.081  1014  1133 D SettingsProvider: selectionArgs: false
08-25 13:18:49.081  1014  1133 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.081  1014  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:49.081  1014  1133 D SettingsProvider: ret = -1
,08-25 13:18:49.081  1014  1244 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 13:18:49.081  1014  1244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.081  1014  1244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.081  1014  1244 D SettingsProvider: selectionArgs: false
08-25 13:18:49.081  1014  1244 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.081  1014  1244 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:49.081  1014  1244 D SettingsProvider: ret = -1
,08-25 13:18:49.081  1014  1452 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:49.081  1014  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.081  1014  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 13:18:49.081  1014  1452 D SettingsProvider: selectionArgs: false
,08-25 13:18:49.081  1014  1452 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.081  1014  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:49.081  1014  1452 D SettingsProvider: ret = -1
,08-25 13:18:49.091  1014  1487 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-25 13:18:49.091  1014  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.091  1014  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.091  1014  1487 D SettingsProvider: selectionArgs: false
,08-25 13:18:49.091  1014  1487 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.091  1014  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:49.091  1014  1487 D SettingsProvider: ret = -1
,08-25 13:18:49.091  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-25 13:18:49.091  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.091  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.091  1014  1027 D SettingsProvider: selectionArgs: false
,08-25 13:18:49.091  1014  1027 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.091  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:49.091  1014  1027 D SettingsProvider: ret = -1
,08-25 13:18:49.091  1014  1451 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-25 13:18:49.091  1014  1451 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:49.091  1014  1451 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:49.091  1014  1451 D SettingsProvider: selectionArgs: false
,08-25 13:18:49.091  1014  1451 D SettingsProvider: selectionArgs: 1002
08-25 13:18:49.091  1014  1451 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 13:18:49.091  1014  1451 D SettingsProvider: ret = -1
,08-25 13:18:49.111  1994  1994 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:49.111  1014  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:49.111  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 13:18:49.111  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:49.111  1014  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:49.111  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:49.121  1994  7595 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 13:18:49.121  1994  1994 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 13:18:49.121  1014  1451 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:49.131  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:49.131  1014  1451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:49.131  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:49.131  1994  7595 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-25 13:18:50.731   287   287 E SMD     : DCD OFF
,08-25 13:18:51.251  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 13:18:51.251  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:52.601  1014  3341 D SSRM:n  : SIOP:: AP = 330
,08-25 13:18:53.731   287   287 E SMD     : DCD OFF,
,08-25 13:18:54.151  1014  1460 I ActivityManager: Killing 7104:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-25 13:18:54.261  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:18:54.261  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dbc3d2e added. We now have 6 listener(s)
08-25 13:18:54.261  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-25 13:18:54.261  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:54.261  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@135e40cf added. We now have 7 listener(s),
08-25 13:18:54.261  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:54.261  6760  6815 I System.out: IsBluetoothEnabled
,08-25 13:18:54.261  6760  6815 D BluetoothAdapter: disable()
08-25 13:18:54.261  1014  1514 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-25 13:18:54.271  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:54.271  6760  6815 D BluetoothAdapter: enable()
,08-25 13:18:54.271  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 13:18:54.271  1014  1027 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-25 13:18:54.271  1014  1027 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 13:18:54.271  1014  1027 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 13:18:54.271  1014  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-25 13:18:54.271  1014  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-25 13:18:54.271  1014  1027 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 13:18:54.271  1014  1027 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 13:18:54.271  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 13:18:54.271  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 13:18:54.281  1014  1027 D SettingsProvider: name = bluetooth_on
,08-25 13:18:54.281  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 13:18:54.281  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 13:18:54.291  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-25 13:18:54.291  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-25 13:18:54.311  7579  7579 D BluetoothAdapterState: make
,08-25 13:18:54.311  7579  7579 I bluedroid: init
,08-25 13:18:54.321  7579  7601 I BluetoothAdapterState: Entering OffState
,08-25 13:18:54.321  7579  7579 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 13:18:54.321  7579  7579 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 13:18:54.321  7579  7579 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 13:18:54.321  7579  7579 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 13:18:54.321  7579  7579 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-25 13:18:54.321  7579  7579 I bluedroid: get_profile_interface socket
,08-25 13:18:54.321  7579  7579 I bluedroid: get_profile_interface map_client
08-25 13:18:54.321  7579  7604 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-25 13:18:54.331  7579  7579 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-25 13:18:54.331  7579  7604 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 13:18:54.331  7579  7604 E BluetoothServiceJni: populateRssiValuesNative
,08-25 13:18:54.331  7579  7604 I bluedroid: getModelRssiValues
08-25 13:18:54.331  7579  7604 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 13:18:54.331  7579  7604 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 13:18:54.331  1014  1014 D SettingsProvider: name = bluetooth_name
,08-25 13:18:54.341  7579  7604 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 13:18:54.341  7579  7579 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:54.341  1014  1026 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 13:18:54.341  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.341  1014  1026 W ActivityManager: userId = 0, bbcId = -10000,
,08-25 13:18:54.351  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:54.351  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:54.351  7579  7589 I bluedroid: config_hci_snoop_log
,08-25 13:18:54.351  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 13:18:54.351  1014  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-25 13:18:54.351  1014  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-25 13:18:54.361  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-25 13:18:54.361  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 13:18:54.361  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 13:18:54.361  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 13:18:54.361  7579  7579 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-25 13:18:54.361  1014  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-25 13:18:54.371  7579  7601 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-25 13:18:54.371  7579  7601 D BluetoothAdapterProperties: Setting state to 11
,08-25 13:18:54.371  7579  7601 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 13:18:54.371  7579  7601 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 13:18:54.371  7579  7601 D BluetoothAdapterService: updateAdapterState state is 11
,08-25 13:18:54.371  7579  7601 D BluetoothAdapterService: Autoconnection is available 
08-25 13:18:54.371  7579  7601 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-25 13:18:54.371  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:54.371  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-25 13:18:54.381  7579  7601 D BluetoothSecureManager: getInstant: null
08-25 13:18:54.381  7579  7601 D BluetoothSecureManager: calling getMethod for getService
08-25 13:18:54.381  7579  7601 D BluetoothSecureManager: calling getService
,08-25 13:18:54.381  7579  7601 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2d7412b8
,08-25 13:18:54.381  1014  1244 D BluetoothSecureManagerService: isSecureModeEnabled
08-25 13:18:54.381  1014  1244 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-25 13:18:54.381  7579  7601 D BtConfig.SecureMode: isSecureModeOn:false
08-25 13:18:54.381  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 13:18:54.381  7579  7601 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-25 13:18:54.381  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 13:18:54.381  7579  7601 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-25 13:18:54.381  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 13:18:54.381  1885  1885 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 13:18:54.381  7579  7601 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-25 13:18:54.381  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 13:18:54.391  7579  7601 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-25 13:18:54.391  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 13:18:54.391  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 13:18:54.391  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:54.391  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-25 13:18:54.391  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:54.401  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:54.401  1014  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 13:18:54.401  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.401  7579  7601 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-25 13:18:54.401  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 13:18:54.401  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-25 13:18:54.401  7579  7601 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-25 13:18:54.401  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:54.401  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:54.401  1014  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:54.401  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:54.401  7579  7601 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-25 13:18:54.401  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 13:18:54.401  7579  7601 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-25 13:18:54.401  1014  4344 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 13:18:54.401  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:54.401  1014  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-25 13:18:54.401  7579  7601 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:54.401  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:54.401  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 13:18:54.401  7579  7601 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:54.401  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 13:18:54.401  7579  7601 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-25 13:18:54.401  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 13:18:54.401  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
08-25 13:18:54.401  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 13:18:54.401  7579  7601 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-25 13:18:54.401  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 13:18:54.401  7579  7601 D BluetoothBondStateMachine: make
,08-25 13:18:54.411  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:54.411  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-25 13:18:54.411  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
08-25 13:18:54.411  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 13:18:54.411  7579  7601 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 13:18:54.411  7579  7607 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 13:18:54.421  1014  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:54.421  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.421  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:54.421  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:54.421  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:54.421  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-25 13:18:54.421  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 13:18:54.421  7579  7601 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 13:18:54.421  7579  7579 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 13:18:54.421  7579  7579 D BtGatt.GattService: Received start request. Starting profile...
08-25 13:18:54.421  7579  7579 D BtGatt.GattService: start()
08-25 13:18:54.421  7579  7579 D BtGatt.GattService: start()
08-25 13:18:54.421  7579  7579 I bluedroid: get_profile_interface gatt
,08-25 13:18:54.421  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
08-25 13:18:54.421  7579  7579 D BtGatt.AdvertiseManager: advertise manager created
,08-25 13:18:54.421  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:54.421  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.431  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:54.431  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:54.431  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:54.441  7579  7579 D BtGatt.GattService: mStartError = false
,08-25 13:18:54.441  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 13:18:54.441  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:54.441  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 13:18:54.441  7579  7601 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 13:18:54.441  1014  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:54.441  1014  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.441  1014  1496 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:54.441  7579  7579 D HeadsetService: Received start request. Starting profile...
08-25 13:18:54.441  7579  7579 D HeadsetService: start()
,08-25 13:18:54.441  7579  7579 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 13:18:54.441  7579  7579 D HeadsetStateMachine: make
08-25 13:18:54.441  1014  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:54.441  1014  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:54.451  7579  7579 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 13:18:54.451  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-25 13:18:54.451  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 13:18:54.451  7579  7601 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 13:18:54.451  1014  1244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:54.451  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.451  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:54.451  1014  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:54.451  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:54.451  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 13:18:54.451  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 13:18:54.451  7579  7601 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 13:18:54.451  1014  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:54.451  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.461  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:54.461  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:54.461  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:54.461  1014  1452 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-25 13:18:54.461  1014  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.461  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 13:18:54.461  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 13:18:54.461  7579  7601 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 13:18:54.461  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:54.461  1014  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:54.461  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 13:18:54.471  1014  1244 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-25 13:18:54.471  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.471  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:54.471  1014  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:54.471  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 13:18:54.471  7579  7579 I bluedroid: get_profile_interface handsfree
,08-25 13:18:54.471  1014  4344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:54.471  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.471  1014  4344 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:54.471  1014  4344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:54.471  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:54.471  1994  1994 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:54.471  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 13:18:54.471  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 13:18:54.471  7579  7601 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 13:18:54.481  1994  1994 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 13:18:54.481  1014  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:54.481  1014  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.491  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:54.491  1014  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:54.491  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:54.491  7579  7579 I DualScoManager: Instantiating Dual Sco Manager
08-25 13:18:54.491  7579  7579 I DualScoManager: Set HeadsetServiceHelper
,08-25 13:18:54.491  7579  7579 D BluetoothAtMessage: createCMTIContentObservers
,08-25 13:18:54.491  1014  1514 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-25 13:18:54.491  1014  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:54.491  1014  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:54.491  1014  1514 D SettingsProvider: selectionArgs: false
08-25 13:18:54.491  1014  1514 D SettingsProvider: selectionArgs: 1002
08-25 13:18:54.491  1014  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:54.491  1014  1514 D SettingsProvider: ret = -1
,08-25 13:18:54.491  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-25 13:18:54.491  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 13:18:54.491  7579  7601 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 13:18:54.501  7579  7610 D HeadsetStateMachine: Enter Disconnected: -2
,08-25 13:18:54.501  7579  7579 D HeadsetService: mStartError = false
08-25 13:18:54.501  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:54.501  1014  1244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:54.501  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 13:18:54.501  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:54.501  1014  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:54.501  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:54.501  7579  7610 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-25 13:18:54.501  7579  7610 D HeadsetStateMachine: map size, before remove : 0
,08-25 13:18:54.501  7579  7610 D HeadsetStateMachine: map size, after remove: 0
,08-25 13:18:54.501  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:54.501  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 13:18:54.501  7579  7601 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 13:18:54.501  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-25 13:18:54.501  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:54.511  7579  7601 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 13:18:54.511  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService,
,08-25 13:18:54.511  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 13:18:54.511  7579  7601 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 13:18:54.511  7579  7601 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-25 13:18:54.511  7579  7601 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 13:18:54.511  7579  7601 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
,08-25 13:18:54.511  7579  7579 E BluetoothAdapterService(276107427): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-25 13:18:54.511  7579  7601 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 13:18:54.511  7579  7579 D A2dpService: Received start request. Starting profile...
08-25 13:18:54.511  7579  7579 D A2dpService: start()
08-25 13:18:54.511  7579  7579 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 13:18:54.511  7579  7579 I bluedroid: get_profile_interface avrcp
,08-25 13:18:54.521  7579  7579 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 13:18:54.521  7579  7579 D Avrcp   : Initialize Media Controller
08-25 13:18:54.521  7579  7579 D Avrcp   : Get the Context Package Name: com.android.bluetooth,
,08-25 13:18:54.521  7579  7579 E Avrcp   : getActiveSessions
08-25 13:18:54.521  7579  7579 D Avrcp   : pick active media Controller
08-25 13:18:54.521  7579  7579 D Avrcp   : Get the active Media Controller ,
,08-25 13:18:54.531  7579  7579 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-25 13:18:54.541  7579  7614 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-25 13:18:54.541  7579  7579 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 13:18:54.541  7579  7579 D A2dpStateMachine: make
,08-25 13:18:54.541  7579  7579 I bluedroid: get_profile_interface a2dp
,08-25 13:18:54.541  7579  7616 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 13:18:54.541  7579  7579 E bt-btif : warning : media task started media_task_refcnt 1 
,08-25 13:18:54.541  7579  7579 D A2dpService: mStartError = false
08-25 13:18:54.541  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:54.541  7579  7579 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 13:18:54.551  7579  7615 D A2dpStateMachine: Enter Disconnected: -2
,08-25 13:18:54.551  7579  7579 D HidService: Received start request. Starting profile...
,08-25 13:18:54.551  7579  7579 D HidService: start()
08-25 13:18:54.551  7579  7579 I bluedroid: get_profile_interface hidhost
08-25 13:18:54.551  7579  7579 D HidService: setHidService(): set to: null
08-25 13:18:54.551  7579  7579 D HidService: mStartError = false
08-25 13:18:54.551  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:54.551  7579  7579 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 13:18:54.551  7579  7579 D HealthService: Received start request. Starting profile...
08-25 13:18:54.551  7579  7579 D HealthService: start()
,08-25 13:18:54.551  7579  7614 D BluetoothMediaBrowser: no now playing list
,08-25 13:18:54.551  7579  7579 I bluedroid: get_profile_interface health
08-25 13:18:54.551  7579  7579 D HealthService: mStartError = false
08-25 13:18:54.551  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:54.551  7579  7579 D HeadsetStateMachine: Try to query the phonestate on bind
,08-25 13:18:54.551  7579  7614 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-25 13:18:54.551  1442  1465 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 13:18:54.551  1442  1442 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-25 13:18:54.551  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 13:18:54.561  1442  1465 I Telecom : BluetoothPhoneService: Result of Message : true
,08-25 13:18:54.561  7579  7579 D HeadsetStateMachine: Proxy object connected
,08-25 13:18:54.561  7579  7579 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 13:18:54.561  7579  7579 D PanService: Received start request. Starting profile...
,08-25 13:18:54.561  7579  7579 D PanService: start()
08-25 13:18:54.561  7579  7579 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 13:18:54.561  7579  7579 I bluedroid: get_profile_interface pan
,08-25 13:18:54.561  7579  7579 D PanService: mStartError = false
,08-25 13:18:54.561  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:54.561  7579  7579 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-25 13:18:54.561  7579  7579 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-25 13:18:54.561  7579  7610 D HeadsetStateMachine: Disconnected process message: 11
08-25 13:18:54.561  7579  7610 D HeadsetStateMachine: Disconnected process message: 18
08-25 13:18:54.561  7579  7579 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-25 13:18:54.571  7579  7579 D BluetoothMapService: Received start request. Starting profile...
,08-25 13:18:54.571  7579  7579 D BluetoothMapService: start()
,08-25 13:18:54.571  7579  7579 D BluetoothMapService: mStartError = false
,08-25 13:18:54.571  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:54.571  7579  7579 E BluetoothAdapterService(276107427): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-25 13:18:54.571  7579  7579 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 13:18:54.571  7579  7610 D HeadsetStateMachine: Disconnected process message: 10
,08-25 13:18:54.571  7579  7579 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-25 13:18:54.571  7579  7610 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 13:18:54.571  7579  7610 D HeadsetStateMachine: Disconnected process message: 11
,08-25 13:18:54.571  7579  7579 D SapService: Received start request. Starting profile...
,08-25 13:18:54.571  7579  7579 D SapService: start()
08-25 13:18:54.571  7579  7579 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-25 13:18:54.571  7579  7579 I bluedroid: get_profile_interface sap
,08-25 13:18:54.571  7579  7579 D SapService: mStartError = false
08-25 13:18:54.571  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:54.571  7579  7579 D BluetoothA2dp: Proxy object connected
08-25 13:18:54.571  7579  7579 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-25 13:18:54.571  7579  7579 E BluetoothAdapterService(276107427): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-25 13:18:54.571  7579  7579 E BluetoothAdapterService(276107427): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-25 13:18:54.581  7579  7579 E BluetoothAdapterService(276107427): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-25 13:18:54.581  7579  7579 E BluetoothAdapterService(276107427): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 13:18:54.601  7579  7579 E BluetoothAdapterService(276107427): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-25 13:18:54.601  7579  7579 E BluetoothAdapterService(276107427): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 13:18:54.601  7579  7601 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-25 13:18:54.601  7579  7601 I bluedroid: enable
,08-25 13:18:54.601  7579  7621 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 13:18:54.601  7579  7601 I bt_hci_bdroid: init
,08-25 13:18:54.601  7579  7601 I bt_vendor: bt-vendor : init
08-25 13:18:54.601  7579  7601 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 13:18:54.601  7579  7601 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 13:18:54.601  7579  7601 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-25 13:18:54.601  7579  7601 D bt_userial_mct: userial_init
08-25 13:18:54.601  7579  7601 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 13:18:54.601  7579  7601 I bt_vendor: Starting hciattach daemon
08-25 13:18:54.601  7579  7601 I bt_vendor: try to set false
,08-25 13:18:54.601  7579  7601 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-25 13:18:54.601  7579  7601 I bt_vendor: Starting hciattach daemon
08-25 13:18:54.601  7579  7601 I bt_vendor: try to set true
,08-25 13:18:54.621  7625  7625 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 13:18:54.661  7631  7631 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-25 13:18:54.671  7632  7632 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 13:18:54.691  7635  7635 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 13:18:54.701  7636  7636 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-25 13:18:54.711  7637  7637 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 13:18:54.721  7638  7638 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-25 13:18:54.941  7641  7641 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-25 13:18:54.951  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 13:18:54.961  7579  7601 I bt_vendor: bluetooth satus is on,
08-25 13:18:54.961  7579  7623 D bt_userial_mct: userial_open(port:0)
08-25 13:18:54.961  7579  7623 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 13:18:54.971  7579  7623 I bt_vendor: Done intiailizing UART,
08-25 13:18:54.971  7579  7623 I bt_vendor: Done intiailizing UART
08-25 13:18:54.971  7579  7623 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 13:18:54.971  7579  7623 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-25 13:18:54.981  7579  7644 D bt_userial_mct: Entering userial_read_thread()
,08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_SAP
08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_SDP
,08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_SMP
,08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 13:18:54.981  7579  7621 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-25 13:18:55.071  1014  1451 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 13:18:55.081  1014  1451 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 13:18:55.081  1014  1451 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 13:18:55.081  1014  1451 D BatteryService: stay LED for fully charged
,08-25 13:18:55.081  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 13:18:55.081  1014  1014 I MotionRecognitionService: Plugged
,08-25 13:18:55.081  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 13:18:55.081  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-25 13:18:55.081  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 13:18:55.091  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,08-25 13:18:55.091  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 13:18:55.101  7579  7579 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-25 13:18:55.101  7579  7610 D HeadsetStateMachine: Disconnected process message: 10
,08-25 13:18:55.111  7579  7621 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-25 13:18:55.111  7579  7621 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42beed1 
,08-25 13:18:55.111  7579  7621 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42beed1 
,08-25 13:18:55.111  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 13:18:55.111  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-25 13:18:55.121  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:55.121  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:55.121  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 13:18:55.131  7579  7604 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-25 13:18:55.131  7579  7604 E bt-btif : Calling BTA_HhEnable
,08-25 13:18:55.131  7579  7604 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 13:18:55.141  7579  7604 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 13:18:55.141  7579  7604 E BluetoothServiceJni: populateRssiValuesNative
08-25 13:18:55.141  7579  7604 I bluedroid: getModelRssiValues
,08-25 13:18:55.141  7579  7604 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-25 13:18:55.141  7579  7604 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 13:18:55.141  1014  1014 D SettingsProvider: name = bluetooth_name
,08-25 13:18:55.141  7579  7604 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 13:18:55.151  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:55.151  7579  7604 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 13:18:55.151  7579  7604 D BluetoothAdapterProperties: Scan Mode:20
,08-25 13:18:55.151  7579  7604 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 13:18:55.151  7579  7604 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-25 13:18:55.151  7579  7604 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-25 13:18:55.151  7579  7604 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-25 13:18:55.161  7579  7604 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-25 13:18:55.161  7579  7604 E bt-btif : btif_sock_init: !vhci_init
,08-25 13:18:55.161  7579  7604 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-25 13:18:55.161  7579  7604 D IOP_DB_BT: db_open: db_open : handle 2965594128l, read 13894 bytes onto local cache
08-25 13:18:55.161  7579  7604 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-25 13:18:55.161  7579  7604 D IOP_DB_BT: db_query: result 1
08-25 13:18:55.161  7579  7604 I         : iop_db_open: iop_db_open status 0
08-25 13:18:55.161  7579  7644 E bt_mct  : hci lib postload completed
08-25 13:18:55.161  7579  7604 D bte_conf: Device ID record 1 : primary
08-25 13:18:55.161  7579  7604 D bte_conf:   vendorId            = 0075
08-25 13:18:55.161  7579  7604 D bte_conf:   vendorIdSource      = 0001
08-25 13:18:55.161  7579  7604 D bte_conf:   product             = 0100
08-25 13:18:55.161  7579  7604 D bte_conf:   version             = 0200
08-25 13:18:55.161  7579  7604 D bte_conf:   clientExecutableURL = 
08-25 13:18:55.161  7579  7604 D bte_conf:   serviceDescription  = 
08-25 13:18:55.161  7579  7604 D bte_conf:   documentationURL    = 
08-25 13:18:55.161  7579  7604 D bte_conf: bte_load_did_conf no section named DID2.
08-25 13:18:55.161  7579  7604 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 13:18:55.161  7579  7601 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 13:18:55.161  7579  7601 D BluetoothAdapterProperties: ScanMode =  20
,08-25 13:18:55.161  7579  7601 D BluetoothAdapterProperties: State =  11
,08-25 13:18:55.161  1014  4344 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 13:18:55.161  7579  7601 D BluetoothAdapterProperties: Setting state to 12,
08-25 13:18:55.161  7579  7601 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 13:18:55.171  7579  7604 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 13:18:55.171  7579  7604 D BluetoothAdapterProperties: Scan Mode:21
08-25 13:18:55.171  7579  7604 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 13:18:55.171  1014  1244 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-25 13:18:55.171  1014  1244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:55.171  1014  1244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:55.171  1014  1244 D SettingsProvider: selectionArgs: false
08-25 13:18:55.171  1014  1244 D SettingsProvider: selectionArgs: 1002
08-25 13:18:55.171  1014  1244 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:55.171  1014  1244 D SettingsProvider: ret = -1
,08-25 13:18:55.171  7579  7601 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 13:18:55.171  7579  7601 D BluetoothAdapterService: updateAdapterState state is 12
,08-25 13:18:55.171  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 13:18:55.171  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.171  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.171  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.171  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.181  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 13:18:55.181  1014  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-25 13:18:55.181  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 13:18:55.181  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.181  7579  7601 D BluetoothAdapterService: Autoconnection is available 
,08-25 13:18:55.181  7579  7601 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 13:18:55.181  7579  7601 D BluetoothAdapterService: starting service from this receiver
08-25 13:18:55.181  1014  1244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:55.181  1014  1014 D BluetoothA2dp: Proxy object connected
08-25 13:18:55.181  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.181  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:55.181  1014  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.181  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 13:18:55.181  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:55.181  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:55.181  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:55.181  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:55.181  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:55.181  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:55.181  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:55.181  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:55.181  1442  7552 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:55.181  7579  7601 I BluetoothAdapterState: Entering On State from state = 11
,08-25 13:18:55.181  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 13:18:55.191  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 13:18:55.191  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.191  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.191  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.191  1442  7552 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:55.191  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:55.191  7493  7507 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:55.191  7493  7507 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 13:18:55.191  1296  6964 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 13:18:55.191  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-25 13:18:55.191  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.191  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.191  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:55.191  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.201  7579  7579 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-25 13:18:55.201  1442  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:55.201  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 13:18:55.201  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 13:18:55.201  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.201  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 13:18:55.201  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.201  1442  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:55.211  1296  1317 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:55.211  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 13:18:55.211  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 13:18:55.211  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.211  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.211  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.211  1296  1317 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:55.211  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:55.211  1014  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:55.211  1994  2155 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:55.211  1994  2155 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 13:18:55.211  1296  1296 D HeadsetProfile: Bluetooth service connected
,08-25 13:18:55.211  7579  7593 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 13:18:55.211  7579  7579 I BluetoothPbapService: Handler(): got msg=1
08-25 13:18:55.211  1296  1311 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 13:18:55.211  1296  1311 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:55.221  7579  7593 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:55.221  7579  7593 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 13:18:55.221  1014  1133 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-25 13:18:55.221  1296  6964 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 13:18:55.221  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-25 13:18:55.221  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.221  1296  1296 D BluetoothMap: Proxy object connected
08-25 13:18:55.221  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.221  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.221  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.221  1296  1296 D MapProfile: Bluetooth service connected
08-25 13:18:55.221  1296  1296 D BluetoothMap: getConnectedDevices()
08-25 13:18:55.221  6760  6768 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:55.221  6760  6768 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:55.221  7579  7649 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-25 13:18:55.221  1296  1317 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 13:18:55.221  1296  1317 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:55.221  1296  1296 D BluetoothPbap: Proxy object connected
08-25 13:18:55.221  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 13:18:55.221  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.221  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.221  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.221  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.221  1296  1296 D PbapServerProfile: Bluetooth service connected
08-25 13:18:55.221  1296  1296 D BluetoothA2dp: Proxy object connected
08-25 13:18:55.221  1296  1296 D A2dpProfile: Bluetooth service connected
,08-25 13:18:55.221  1442  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:55.221  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 13:18:55.231  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 13:18:55.231  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.231  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.231  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.231  1442  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:55.231  1296  6964 D BluetoothPan: Binding service...
08-25 13:18:55.231  7579  7649 D BluetoothSocket: bindListen(): myUserId = 0
08-25 13:18:55.231  7579  7649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:18:55.231  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 13:18:55.231  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.231  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.231  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.231  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.231  7579  7649 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]},
08-25 13:18:55.231  7579  7649 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 13:18:55.231  7579  7649 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 13:18:55.231  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 13:18:55.231  7579  7649 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a45ed65,
08-25 13:18:55.231  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-25 13:18:55.231  7579  7649 D BluetoothSocket: channel: 19
08-25 13:18:55.231  7579  7649 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-25 13:18:55.231  1296  1296 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 13:18:55.231  1296  1296 D PanProfile: Bluetooth service connected
,08-25 13:18:55.231  1456  1800 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:55.231  1456  1800 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 13:18:55.231  1014  1045 D BluetoothPan: Binding service...
08-25 13:18:55.231  1014  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 13:18:55.231  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 13:18:55.231  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 13:18:55.241  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 13:18:55.241  1014  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 13:18:55.241  1475  1488 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 13:18:55.241  1014  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 13:18:55.241  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 13:18:55.241  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.241  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.241  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.241  1475  1488 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 13:18:55.241  1475  1671 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 13:18:55.241  1475  1671 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 13:18:55.241  1296  6964 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 13:18:55.241  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-25 13:18:55.241  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.241  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:55.241  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.241  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.251  1296  1296 D BluetoothInputDevice: Proxy object connected
,08-25 13:18:55.251  1442  1465 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:55.251  1442  1465 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 13:18:55.251  1296  1296 D HidProfile: Bluetooth service connected
08-25 13:18:55.251  1176  3371 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 13:18:55.251  1176  3371 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 13:18:55.251  1296  1311 D Bluetoothsap: onBluetoothStateChange: up=true
08-25 13:18:55.251  1296  1311 D Bluetoothsap: Binding service...
,08-25 13:18:55.251  1296  1311 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-25 13:18:55.251  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-25 13:18:55.251  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.251  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:55.251  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.251  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.251  1296  1311 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-25 13:18:55.251  1296  1296 D Bluetoothsap: BluetoothSAP Proxy object connected
08-25 13:18:55.251  1296  1296 D SapProfile: Bluetooth service connected
08-25 13:18:55.251  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-25 13:18:55.251  1296  1296 D Bluetoothsap: getConnectedDevices()
08-25 13:18:55.251  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 13:18:55.261  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:55.261  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
,08-25 13:18:55.261  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 13:18:55.261  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-25 13:18:55.261  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 13:18:55.261  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 13:18:55.271  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:55.271  1176  1176 D BluetoothTile:  getBluetoothState : 12
08-25 13:18:55.271  1442  1442 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@222f4d18, true
,08-25 13:18:55.271  1442  1442 D BluetoothHeadset: registerMessageListener
,08-25 13:18:55.271  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 13:18:55.271  1014  1495 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 13:18:55.271  1885  1885 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 13:18:55.271  1296  1296 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:55.271  1014  4344 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-25 13:18:55.271  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 13:18:55.281  1176  1775 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 13:18:55.281  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:55.281  1014  1460 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 13:18:55.281  7579  7605 D HeadsetService: registerMessageListener
08-25 13:18:55.281  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.281  7579  7605 D HeadsetService: registerMessageListener
,08-25 13:18:55.281  7579  7610 D HeadsetStateMachine: Disconnected process message: 70
,08-25 13:18:55.281  7579  7610 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2f390a3a
08-25 13:18:55.281  1442  1442 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-25 13:18:55.281  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 13:18:55.281  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:55.291  1014  1460 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:55.291  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:55.291  7579  7651 D BluetoothMapMasInstance: set MAP SDP message type : 1,
,08-25 13:18:55.291  1296  1296 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-25 13:18:55.291  1296  1296 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-25 13:18:55.291  1296  1296 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-25 13:18:55.291  1296  1296 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-25 13:18:55.291  1442  1442 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-25 13:18:55.291  1442  1442 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-25 13:18:55.291  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-25 13:18:55.301  7579  7610 D HeadsetStateMachine: Disconnected process message: 9
,08-25 13:18:55.301  7579  7610 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 13:18:55.301  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:55.301  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:55.301  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:55.301  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:55.301  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:55.301  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:55.301  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:55.301  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:55.301  7579  7651 D BluetoothSocket: bindListen(): myUserId = 0
08-25 13:18:55.301  7579  7651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:18:55.301  7579  7651 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-25 13:18:55.301  7579  7651 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 13:18:55.301  7579  7651 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 13:18:55.301  7579  7651 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f4336eb
,08-25 13:18:55.301  7579  7651 D BluetoothSocket: channel: 5,
,08-25 13:18:55.301  1296  1296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 13:18:55.301  1014  4344 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 13:18:55.301  1014  4344 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.311  1014  4344 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.311  1014  4344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.311  1014  4344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 13:18:55.311   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-25 13:18:55.311   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-25 13:18:55.311   282   282 V voice   : voice_set_parameters: exit with code(-2)
08-25 13:18:55.311   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-25 13:18:55.311   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-25 13:18:55.311   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-25 13:18:55.311   282   282 V audio_hw_primary: adev_set_parameters: exit
,08-25 13:18:55.311  7579  7610 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-25 13:18:55.311  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:55.311  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:55.311  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25fada5c added. We now have 8 listener(s)
08-25 13:18:55.311  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:55.311  1014  1514 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 13:18:55.311  1014  1514 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 13:18:55.311  1014  1514 D SecContentProvider2: mCursor = null
,08-25 13:18:55.321  1014  1514 D WifiService: setWifiEnabled: false pid=6760, uid=10171
,08-25 13:18:55.321  1014  1514 D SettingsProvider: name = wifi_on
,08-25 13:18:55.321  1296  1296 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:55.321  1296  1296 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 13:18:55.321  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:55.331  1014  1495 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-25 13:18:55.331  1014  1495 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 13:18:55.331  1014  1495 D SecContentProvider2: mCursor = null
,08-25 13:18:55.331  1014  1495 D WifiService: setWifiEnabled: true pid=6760, uid=10171
08-25 13:18:55.331  1014  1495 W ActivityManager: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 13:18:55.331  1014  1495 W WifiService: Failed getting userId using ActivityManagerNative
08-25 13:18:55.331  1014  1495 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6760, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 13:18:55.331  1014  1495 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 13:18:55.331  1014  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 13:18:55.331  1014  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 13:18:55.331  1014  1495 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 13:18:55.331  1014  1495 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 13:18:55.331  1014  1495 D SettingsProvider: name = wifi_on
,08-25 13:18:55.331  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:55.331  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 13:18:55.331  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-25 13:18:55.341  7579  7579 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:55.341  7579  7579 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 13:18:55.341  1014  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 13:18:55.341  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.351  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.351  1014  1460 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.351  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 13:18:55.361  1994  1994 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:55.361  1014  1460 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 13:18:55.361  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 13:18:55.361  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:55.361  1014  1460 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:55.361  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:55.371  1014  1460 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 13:18:55.381  1994  7660 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 13:18:55.381  1994  1994 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 13:18:55.381  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:55.391  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.391  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:18:55.391  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:55.391  7579  7664 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 13:18:55.391  7579  7664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:18:55.401  7579  7664 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-25 13:18:55.401  7579  7664 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 13:18:55.401  7579  7664 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 13:18:55.401  7579  7664 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@59c56c7
,08-25 13:18:55.401  7579  7664 D BluetoothSocket: channel: 12
,08-25 13:18:55.401  7579  7664 I BtOppRfcommListener: Accept thread started.
,08-25 13:18:55.401  1014  1244 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 13:18:55.411  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
,08-25 13:18:55.411  1014  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 13:18:55.411  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 13:18:55.411  1994  7660 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-25 13:18:55.671  1014  1043 D Tethering: interfaceAdded wlan0
,08-25 13:18:55.681  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 13:18:55.681  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 13:18:55.681  1014  1128 E Tethering: No numeric data
08-25 13:18:55.681  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-25 13:18:55.681  1014  1128 D Tethering: clearTetheredNotification()
08-25 13:18:55.681  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
08-25 13:18:55.681  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:55.681  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 13:18:55.681  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 13:18:55.691  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:55.691  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:55.691  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 13:18:55.691  1014  1128 D Tethering: InitialState.processMessage what=4
,08-25 13:18:55.691  1014  1043 D Tethering: interfaceAdded p2p0
,08-25 13:18:55.691  1014  1128 E Tethering: No numeric data
,08-25 13:18:55.691  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 13:18:55.691  1014  1128 D Tethering: clearTetheredNotification()
,08-25 13:18:55.691  1014  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-25 13:18:55.701  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-25 13:18:55.701  1014  1122 V NetworkStats: performPollLocked() took 15ms
08-25 13:18:55.701  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:55.701  1176  1176 D HotspotTile: updateTetherState():false, false
,08-25 13:18:55.701  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-25 13:18:55.701  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:55.701  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 13:18:55.701  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 13:18:55.711  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 13:18:55.711  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:55.711  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:55.711  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:55.711  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 13:18:55.711  1014  1122 V NetworkStats: performPollLocked() took 12ms
,08-25 13:18:55.721   277  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-25 13:18:55.721  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:55.721   277  1013 D SoftapController: Softap fwReload - Ok
08-25 13:18:55.721  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:55.721  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:55.721   277  1013 D CommandListener: Setting iface cfg
08-25 13:18:55.721   277  1013 D CommandListener: Trying to bring down wlan0
,08-25 13:18:55.721   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,08-25 13:18:55.731  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-25 13:18:55.771  7674  7674 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-25 13:18:55.771  7674  7674 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 13:18:55.771  7674  7674 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-25 13:18:55.791  7674  7674 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-25 13:18:55.791   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7674,
08-25 13:18:55.791   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 13:18:55.791  7674  7674 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 13:18:55.791  7674  7674 I wpa_supplicant: ssSupport state is = 1
08-25 13:18:55.791  7674  7674 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-25 13:18:55.791  7674  7674 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-25 13:18:55.791   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7674
08-25 13:18:55.791   350   350 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106,
,08-25 13:18:55.831  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-25 13:18:55.841  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 13:18:55.841  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:55.841  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 13:18:55.841  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 13:18:55.841  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:55.841  1176  1176 D HotspotTile: onReceive : 2, 0
08-25 13:18:55.841  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:55.841  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:55.841  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:55.841  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:55.841  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-25 13:18:55.841  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-25 13:18:55.851  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:55.861  1014  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-25 13:18:55.861  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:55.861  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:55.861  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:55.861  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 13:18:55.861  1616  1616 I Hs20UtilService: Starting #19
,08-25 13:18:55.861  1616  1645 I Hs20UtilService: Message received 5011
,08-25 13:18:55.861  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 13:18:55.861  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 13:18:55.861  6614  6614 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 13:18:55.861  6614  6614 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 13:18:55.981   350   350 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-25 13:18:55.981  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-25 13:18:56.021  7674  7674 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-25 13:18:56.021  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-25 13:18:56.031  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 13:18:56.031   350   350 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7674
,08-25 13:18:56.041   350   350 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-25 13:18:56.041  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-25 13:18:56.041  7674  7674 I wpa_supplicant: ssSupport state is = 1
08-25 13:18:56.041  7674  7674 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 13:18:56.041  7674  7674 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 13:18:56.041  7674  7674 E wpa_supplicant: SIM READ ERROR
08-25 13:18:56.041  7674  7674 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-25 13:18:56.041  7674  7674 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 13:18:56.041  7674  7674 E wpa_supplicant: SIM READ ERROR
08-25 13:18:56.041  7674  7674 I wpa_supplicant: Blacklist: Clear (all) 
08-25 13:18:56.041  7674  7674 I wpa_supplicant: wpa_default_ap_write_once
08-25 13:18:56.041  7674  7674 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-25 13:18:56.041  7674  7674 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 13:18:56.041  7674  7674 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-25 13:18:56.041  7674  7674 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 13:18:56.041  7674  7674 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 13:18:56.041  7674  7674 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-25 13:18:56.041  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 13:18:56.041  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-25 13:18:56.041  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 13:18:56.131  7674  7674 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-25 13:18:56.441  7674  7674 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-25 13:18:56.441  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-25 13:18:56.451  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-25 13:18:56.451   350   350 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7674
08-25 13:18:56.451   350   350 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-25 13:18:56.461  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-25 13:18:56.461  7674  7674 I wpa_supplicant: ssSupport state is = 1
08-25 13:18:56.461  7674  7674 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 13:18:56.461  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-25 13:18:56.471  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-25 13:18:56.471   350   350 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7674,
,08-25 13:18:56.471   350   350 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-25 13:18:56.471  7674  7674 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 13:18:56.471  7674  7674 I wpa_supplicant: ssSupport state is = 1
08-25 13:18:56.471  7674  7674 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-25 13:18:56.471  7674  7674 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 13:18:56.471  7674  7674 E wpa_supplicant: SIM READ ERROR
08-25 13:18:56.471  7674  7674 I wpa_supplicant: wpa_default_ap_write_once
08-25 13:18:56.471  7674  7674 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 13:18:56.471  7674  7674 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 13:18:56.471  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 13:18:56.471  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
08-25 13:18:56.481  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 13:18:56.481  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 13:18:56.481  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 13:18:56.481  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 13:18:56.531  7674  7674 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-25 13:18:56.531  7674  7674 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 13:18:56.611  7674  7674 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-25 13:18:56.611  7674  7674 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-25 13:18:56.611  7674  7674 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 13:18:56.621  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-25 13:18:56.621  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 13:18:56.621  7674  7674 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-25 13:18:56.621  7674  7674 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 13:18:56.621  7674  7674 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 13:18:56.621  7674  7674 E wpa_supplicant: SIM READ ERROR
08-25 13:18:56.621  7674  7674 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 13:18:56.641  7674  7674 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-25 13:18:56.651  7674  7674 I wpa_supplicant: Skip scan - bUseNetwork false,
08-25 13:18:56.651  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
08-25 13:18:56.651  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:56.651  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:56.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:56.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:56.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:56.651  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:56.651  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 13:18:56.651  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-25 13:18:56.651  1176  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-25 13:18:56.661  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:56.661  1176  1176 D HotspotTile: onReceive : 3, 0,
08-25 13:18:56.661  1296  1296 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 13:18:56.671  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-25 13:18:56.671  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:56.671  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:56.671  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:56.671  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:56.671  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-25 13:18:56.671  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:56.671  6760  6760 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:56.671  6760  6760 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:56.671  1014  1125 E WifiConfigStore: Not a HS20
,08-25 13:18:56.671  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 13:18:56.681  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 13:18:56.681  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
08-25 13:18:56.681  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 13:18:56.681  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 13:18:56.681  1014  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 13:18:56.681  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:56.681  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:56.681  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:56.681  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 13:18:56.681  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-25 13:18:56.681  7674  7674 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,08-25 13:18:56.681  7674  7674 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-25 13:18:56.681  7674  7674 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-25 13:18:56.681  7674  7674 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 13:18:56.681  7674  7674 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 13:18:56.681  7674  7674 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,08-25 13:18:56.681  7674  7674 I wpa_supplicant: First Scan Start
08-25 13:18:56.681  7674  7674 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-25 13:18:56.681  1616  1616 I Hs20UtilService: Starting #20
08-25 13:18:56.681  1616  1645 I Hs20UtilService: Message received 5011
,08-25 13:18:56.691  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-25 13:18:56.691  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 13:18:56.691  1014  1125 I WifiNative-HAL: startHal
08-25 13:18:56.691  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d40688c
,08-25 13:18:56.691  1014  1125 I WifiNative-HAL: Could not start hal
08-25 13:18:56.691  6966  6966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:18:56.691  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 13:18:56.691  6614  6614 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 13:18:56.691  6614  6614 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 13:18:56.691  6614  6614 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 13:18:56.701  1014  1125 E WifiNative-wlan0: do suspend true
,08-25 13:18:56.701  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-25 13:18:56.701   277  1013 D CommandListener: Setting iface cfg
08-25 13:18:56.701   277  1013 D CommandListener: Trying to bring up p2p0
,08-25 13:18:56.701  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 13:18:56.701  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-25 13:18:56.701  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,08-25 13:18:56.701  1014  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:56.701  1014  1148 I WifiNative-HAL: startHal
08-25 13:18:56.701  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e3b09bc
08-25 13:18:56.701  1014  1148 I WifiNative-HAL: Could not start hal
08-25 13:18:56.701  1014  1148 E WifiScanningService: could not start HAL
,08-25 13:18:56.701  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-25 13:18:56.701  1014  1124 D WifiP2pService: P2pEnablingState
08-25 13:18:56.701  1014  1149 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 13:18:56.711  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 13:18:56.711  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 13:18:56.711  1014  1125 E WifiNative-wlan0: invaild command id : 215
,08-25 13:18:56.711  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-25 13:18:56.711  1014  1124 D WifiP2pService: P2p socket connection successful
08-25 13:18:56.711  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 13:18:56.711  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 13:18:56.711  1014  1125 E WifiNative-wlan0: invaild command id : 215
,08-25 13:18:56.711  7674  7674 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 13:18:56.711  1014  1124 D WifiP2pService: P2pEnabledState
,08-25 13:18:56.711  7674  7674 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 13:18:56.711  7674  7674 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-25 13:18:56.711  1014  1125 E WifiStateMachine: Failed to set frequency band 0
,08-25 13:18:56.711  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:56.711  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:56.711  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 13:18:56.721  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:56.721  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 13:18:56.721  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-25 13:18:56.721  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-25 13:18:56.721  1014  1046 D WifiDisplayController: disconnect
08-25 13:18:56.721  1014  1046 D WifiDisplayController: updateConnection
08-25 13:18:56.721  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 13:18:56.721  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 13:18:56.721  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:56.721  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:56.721  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 13:18:56.721  1014  1495 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 13:18:56.721  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 13:18:56.721  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 13:18:56.721  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
08-25 13:18:56.721  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer,
08-25 13:18:56.721  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 13:18:56.731  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-25 13:18:56.731  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-25 13:18:56.731  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 13:18:56.731  1014  1124 D WifiP2pService: DeviceAddress: 0a:76:28
08-25 13:18:56.731  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 13:18:56.731   287   287 E SMD     : DCD OFF
08-25 13:18:56.731  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 13:18:56.731  1014  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  secondary type: null
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  wps: 0
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  grpcapab: 0
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  devcapab: 0
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  status: 3
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  wfdInfo: null
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  groupownerAddress: null
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  GOdeviceName: null
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  interfaceAddress: 
08-25 13:18:56.731  1014  1046 D WifiDisplayController:  SConnectInfo : null
,08-25 13:18:56.731  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 13:18:56.731  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:56.731  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 13:18:56.731  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 13:18:56.741  7364  7364 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 13:18:56.741  7364  7364 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 13:18:56.741  7364  7364 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 13:18:56.751  7379  7379 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 13:18:56.761  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-25 13:18:56.761  1014  1124 D WifiP2pService: InactiveState
,08-25 13:18:56.761  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-25 13:18:56.761  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 13:18:56.761  7674  7674 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-25 13:18:56.761  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-25 13:18:56.761  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 13:18:57.341  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:57.341  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:57.341  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:57.341  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:57.341  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:57.341  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:57.341  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:57.341  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:57.341  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-25 13:18:57.351  6760  6815 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 13:18:57.351  6760  6815 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 13:18:57.351  6760  6815 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c1b6893 Bundle[{}]
,08-25 13:18:57.361  6760  6815 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 13:18:57.361  6760  6815 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-25 13:18:57.361  6760  6815 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 13:18:57.361  6760  6815 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 13:18:57.361  6760  6815 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-25 13:18:57.361  6760  6815 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 13:18:57.371  6760  6815 I System.out: Running OutgoingSocketThread
,08-25 13:18:57.371  6760  7682 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1334)
,08-25 13:18:57.381  6760  7682 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46881
,08-25 13:18:57.381  6760  7682 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 13:18:57.741   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:57.881  7674  7674 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
08-25 13:18:57.881  7674  7674 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-25 13:18:57.881  7674  7674 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-25 13:18:57.881  7674  7674 I wpa_supplicant: Trying to associate with  'G700'
08-25 13:18:57.881  7674  7674 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-25 13:18:57.881  7674  7674 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-25 13:18:57.891  1014  7680 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 13:18:57.901  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-25 13:18:57.901  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:58.001  7674  7674 E wpa_supplicant: Cmd 35605 not handled
08-25 13:18:58.001  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:58.001  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 13:18:58.001  7674  7674 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-25 13:18:58.001  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 13:18:58.001  7674  7674 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-25 13:18:58.001  7674  7674 I wpa_supplicant: Associated with F4.99.3E
08-25 13:18:58.001  7674  7674 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 13:18:58.001  7674  7674 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-25 13:18:58.001  7674  7674 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-25 13:18:58.001  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 13:18:58.001  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 13:18:58.001  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 13:18:58.001  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, true,
08-25 13:18:58.001  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 13:18:58.001  1014  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-25 13:18:58.011  1014  1128 E Tethering: No numeric data
08-25 13:18:58.011  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 13:18:58.011  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
08-25 13:18:58.011  1014  1128 D Tethering: clearTetheredNotification()
08-25 13:18:58.011  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 13:18:58.011  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 13:18:58.011  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 13:18:58.011  7674  7674 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 13:18:58.011  7674  7674 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-25 13:18:58.011  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:58.011  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:58.011  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:58.011  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-25 13:18:58.011  7674  7674 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
,08-25 13:18:58.011  7674  7674 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-25 13:18:58.021  1014  1122 V NetworkStats: performPollLocked() took 9ms
08-25 13:18:58.011  7674  7674 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 13:18:58.011  7674  7674 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-25 13:18:58.021  7674  7674 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-25 13:18:58.021  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:58.021  7674  7674 I wpa_supplicant: Blacklist: Clear (temp) 
08-25 13:18:58.021  7674  7674 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-25 13:18:58.021  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 13:18:58.021  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:58.021  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:58.021  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 13:18:58.021  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 13:18:58.021  1014  1043 D Tethering: interfaceStatusChanged wlan0, true
08-25 13:18:58.021  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:58.031  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 13:18:58.031  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-25 13:18:58.041  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-25 13:18:58.041  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-25 13:18:58.041  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:58.041  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 13:18:58.041  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:58.041  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:58.041  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.041  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.041  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:58.041  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.041  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:18:58.041  1014  1452 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-25 13:18:58.041  1014  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 13:18:58.051  1014  1452 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:58.051  1014  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:58.051  1014  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 13:18:58.051  1616  1616 I Hs20UtilService: Starting #21
08-25 13:18:58.051  1616  1645 I Hs20UtilService: Message received 5007
,08-25 13:18:58.051  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
08-25 13:18:58.051  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 13:18:58.051  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 13:18:58.051  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 13:18:58.061  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 13:18:58.061  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 13:18:58.061  1296  1296 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 13:18:58.061  1296  2228 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 13:18:58.071   277  1013 D CommandListener: Setting iface cfg
,08-25 13:18:58.071  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,08-25 13:18:58.071  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 13:18:58.071  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:58.081  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 13:18:58.081  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:58.081  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.081  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:58.081  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.081  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:58.091  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 13:18:58.091  1014  1125 D SecContentProvider2: mCursor = null
,08-25 13:18:58.091  1014  1125 E WifiNative-wlan0: do suspend false
,08-25 13:18:58.091  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-25 13:18:58.091  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-25 13:18:58.311  7685  7685 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-25 13:18:58.311  7685  7685 I dhcpcd  : version 5.5.6 starting
,08-25 13:18:58.311  7685  7685 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 13:18:58.371  7685  7685 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-25 13:18:58.371  7685  7685 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-25 13:18:58.371  7685  7685 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-25 13:18:58.371  7685  7685 I dhcpcd  : bssid match
08-25 13:18:58.371  7685  7685 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
08-25 13:18:58.371  6760  6815 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1335)
08-25 13:18:58.371  6760  6815 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1335)
,08-25 13:18:58.371  6760  6815 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1340)
,08-25 13:18:58.371  6760  6815 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 13:18:58.371  6760  6815 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1341)
,08-25 13:18:58.381  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 13:18:58.381  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@197f3165 added. We now have 2 listener(s)
,08-25 13:18:58.381  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 13:18:58.381  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 13:18:58.381  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:18:58.381  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:18:58.381  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3552fe3a added. We now have 9 listener(s)
08-25 13:18:58.381  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:58.391  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:18:58.391  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:58.391  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:58.391  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:58.391  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:58.391  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:58.391  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:58.391  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:58.391  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:58.391  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:58.401  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:58.401  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:18:58.401  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:18:58.401  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34894048 added. We now have 3 listener(s)
,08-25 13:18:58.401  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:58.401  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:58.401  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-25 13:18:58.401  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:18:58.401  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:18:58.401  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:58.401  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fb67ee1 added. We now have 10 listener(s)
08-25 13:18:58.401  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:58.401  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:58.401  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:58.401  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:58.401  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:18:58.401  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.401  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:18:58.401  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.401  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@197f3165 removed from the list
08-25 13:18:58.401  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:58.401  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3552fe3a removed from the list
08-25 13:18:58.401  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:58.401  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 13:18:58.401  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.401  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:58.401  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:58.401  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:18:58.401  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.401  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3552fe3a not in the list
08-25 13:18:58.401  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.401  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.411  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:18:58.411  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:58.411  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.411  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fb67ee1 removed from the list
08-25 13:18:58.411  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:58.411  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.411  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.411  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.411  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34894048 removed from the list
08-25 13:18:58.411  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:18:58.411  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e62c406 added. We now have 2 listener(s)
,08-25 13:18:58.411  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 13:18:58.411  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:18:58.411  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 13:18:58.411  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:58.411  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6b7ac7 added. We now have 9 listener(s)
,08-25 13:18:58.411  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:58.411  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:18:58.421  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:58.421  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:58.421  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:58.421  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:58.421  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:58.421  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:58.421  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:58.421  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:58.421  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:58.421  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:58.421  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:18:58.421  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:18:58.421  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31bb281d added. We now have 3 listener(s)
,08-25 13:18:58.421  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:58.431  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 13:18:58.431  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:18:58.431  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:18:58.431  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:58.431  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16571a92 added. We now have 10 listener(s)
08-25 13:18:58.431  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:58.431  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:18:58.431  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:18:58.431  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:18:58.431  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:58.431  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 13:18:58.431  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:58.431  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 13:18:58.441  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:18:58.441  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:18:58.441  7685  7685 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-25 13:18:58.441  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 13:18:58.441  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 13:18:58.441  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 13:18:58.451  7579  7605 D BtGatt.GattService: registerClient() - UUID=da39178c-691a-456e-b860-3efccfa0191c
,08-25 13:18:58.491  7579  7604 D BtGatt.GattService: onClientRegistered() - UUID=da39178c-691a-456e-b860-3efccfa0191c, clientIf=6
,08-25 13:18:58.491  6760  6768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 13:18:58.491  7579  7593 D BtGatt.GattService: start scan with filters,
,08-25 13:18:58.491  7579  7609 D BtGatt.ScanManager: handling starting scan
,08-25 13:18:58.501  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 13:18:58.501  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:18:58.501  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 13:18:58.501  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:18:58.501  7579  7609 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@107510a3
,08-25 13:18:58.501  7579  7604 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 13:18:58.501  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.501  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:18:58.501  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 13:18:58.501  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:18:58.501  7579  7609 D BtGatt.ScanManager: allow scan with filters
08-25 13:18:58.501  7579  7609 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 13:18:58.501  7579  7609 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-25 13:18:58.501  7579  7604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 13:18:58.511  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.511  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 13:18:58.511  7579  7609 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 13:18:58.511  7579  7609 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 13:18:58.511  7579  7604 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 13:18:58.511  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.511  6760  6815 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 13:18:58.511  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:58.511  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 13:18:58.511  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.511  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 13:18:58.511  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 13:18:58.511  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:58.511  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:58.511  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:18:58.511  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:18:58.511  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 13:18:58.521  7579  7604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 13:18:58.521  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.521  7579  7589 D BtGatt.GattService: stopScan() - queue size =1
,08-25 13:18:58.521  7579  7647 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 13:18:58.521  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 13:18:58.521  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 13:18:58.521  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:18:58.521  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 13:18:58.521  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 13:18:58.531  7579  7609 D BtGatt.ScanManager: filter size is 1
08-25 13:18:58.531  7579  7609 D BtGatt.ScanManager: delete FilterIndex - 3
,08-25 13:18:58.531  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 13:18:58.531  7579  7604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 13:18:58.531  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.531  7579  7609 D BtGatt.ScanManager: stopping BLe Batch
,08-25 13:18:58.531  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 13:18:58.531  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 13:18:58.531  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 13:18:58.531  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:58.531  7579  7604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 13:18:58.531  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.531  7579  7609 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 13:18:58.541  7579  7604 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 13:18:58.541  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.541  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:18:58.541  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:18:58.541  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 13:18:58.541  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:58.541  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:18:58.541  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:18:58.551  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:18:58.551  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.551  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:58.551  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.551  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e62c406 removed from the list
,08-25 13:18:58.551  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.551  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6b7ac7 removed from the list
,08-25 13:18:58.551  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:58.551  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.551  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:58.551  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.551  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:58.551  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:58.551  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:58.551  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a6b7ac7 not in the list
08-25 13:18:58.551  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:58.551  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.561  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:18:58.561  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:58.561  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:58.561  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16571a92 removed from the list
,08-25 13:18:58.561  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:58.561  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.561  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.561  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.561  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31bb281d removed from the list
,08-25 13:18:58.561  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 13:18:58.561  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c84dde added. We now have 2 listener(s)
,08-25 13:18:58.561  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 13:18:58.561  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 13:18:58.561  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:18:58.561  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:18:58.561  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bb6fbbf added. We now have 9 listener(s)
08-25 13:18:58.561  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:58.571  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:18:58.571  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:58.571  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:58.571  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:58.571  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:58.571  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:58.571  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:58.571  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:58.571  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:58.571  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:58.581  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-25 13:18:58.581  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:18:58.581  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:18:58.581  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12383dd5 added. We now have 3 listener(s)
,08-25 13:18:58.581  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:58.581  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:58.581  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 13:18:58.581  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 13:18:58.581  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:18:58.581  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:18:58.581  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8769ea added. We now have 10 listener(s)
08-25 13:18:58.581  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:58.581  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 13:18:58.581  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:18:58.581  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 13:18:58.591  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:18:58.591  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:58.591  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 13:18:58.591  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 13:18:58.591  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:18:58.601  7685  7685 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
08-25 13:18:58.601  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:18:58.601  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 13:18:58.601  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 13:18:58.601  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 13:18:58.611  7579  7593 D BtGatt.GattService: registerClient() - UUID=a6a2e5f3-c33d-41d6-989a-4f94e6fd0d6b,
,08-25 13:18:58.651  7579  7604 D BtGatt.GattService: onClientRegistered() - UUID=a6a2e5f3-c33d-41d6-989a-4f94e6fd0d6b, clientIf=6,
08-25 13:18:58.651  6760  6771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 13:18:58.651  7579  7650 D BtGatt.GattService: start scan with filters
,08-25 13:18:58.651  7579  7609 D BtGatt.ScanManager: handling starting scan
08-25 13:18:58.651  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 13:18:58.651  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:18:58.651  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 13:18:58.651  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:18:58.661  7579  7604 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-25 13:18:58.661  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.661  7579  7609 D BtGatt.ScanManager: allow scan with filters,
08-25 13:18:58.661  7579  7609 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 13:18:58.661  7579  7609 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-25 13:18:58.671  7579  7604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 13:18:58.671  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.671  7579  7609 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 13:18:58.671  7579  7609 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-25 13:18:58.671  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:18:58.671  7579  7604 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 13:18:58.671  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.671  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 13:18:58.671  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:18:58.671  7579  7604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 13:18:58.671  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.671  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 13:18:58.681  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-25 13:18:58.681  6760  6815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 13:18:58.681  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:58.681  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:58.681  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:58.681  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:58.681  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 13:18:58.681  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 13:18:58.681  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.681  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c84dde removed from the list
08-25 13:18:58.681  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.681  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bb6fbbf removed from the list
08-25 13:18:58.681  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 13:18:58.681  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:58.691  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.691  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 13:18:58.691  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.691  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:58.691  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:58.691  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:58.691  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.691  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bb6fbbf not in the list,
08-25 13:18:58.691  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:58.691  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:58.691  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:18:58.691  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:18:58.691  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 13:18:58.691  7579  7589 D BtGatt.GattService: stopScan() - queue size =1
08-25 13:18:58.691  7579  7609 D BtGatt.ScanManager: filter size is 1
08-25 13:18:58.691  7579  7609 D BtGatt.ScanManager: delete FilterIndex - 4
,08-25 13:18:58.701  7579  7604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 13:18:58.701  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.701  7579  7593 D BtGatt.GattService: unregisterClient() - clientIf=6,
,08-25 13:18:58.701  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:18:58.701  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-25 13:18:58.701  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:18:58.701  7579  7609 D BtGatt.ScanManager: stopping BLe Batch
,08-25 13:18:58.701  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 13:18:58.701  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 13:18:58.701  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-25 13:18:58.701  7579  7604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 13:18:58.701  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.701  7579  7609 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 13:18:58.711  7579  7604 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 13:18:58.711  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.711  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:18:58.711  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 13:18:58.711  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 13:18:58.711  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.711  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:18:58.711  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:58.711  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:58.711  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:58.711  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:58.711  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.711  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8769ea removed from the list
08-25 13:18:58.711  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:58.711  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.711  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.711  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.711  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12383dd5 removed from the list
,08-25 13:18:58.711  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:18:58.711  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@206a3ab6 added. We now have 2 listener(s)
,08-25 13:18:58.721  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 13:18:58.721  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:18:58.721  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:18:58.721  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:18:58.721  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e2a3b7 added. We now have 9 listener(s)
08-25 13:18:58.721  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:58.721  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:18:58.721  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-25 13:18:58.731  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:58.731  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-25 13:18:58.731  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:58.731  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:58.731  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:58.731  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:58.731  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:58.731  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:58.741  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:58.741  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:18:58.741  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:18:58.741  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b528d added. We now have 3 listener(s)
08-25 13:18:58.741  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 13:18:58.741  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:18:58.741  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:18:58.741  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:18:58.741  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d74c42 added. We now have 10 listener(s)
08-25 13:18:58.741  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:58.741  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-25 13:18:58.741  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:18:58.741  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:18:58.741  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:58.741  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:18:58.751   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:58.751  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-25 13:18:58.751  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-25 13:18:58.751  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:58.761  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:18:58.761  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:18:58.761  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-25 13:18:58.761  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 13:18:58.761  6760  6815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-25 13:18:58.771  7579  7650 D BtGatt.GattService: registerClient() - UUID=85fb7f02-950c-49ca-b57e-241f7ca9e600,
,08-25 13:18:58.811  7579  7604 D BtGatt.GattService: onClientRegistered() - UUID=85fb7f02-950c-49ca-b57e-241f7ca9e600, clientIf=6,
08-25 13:18:58.811  6760  6768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 13:18:58.811  7579  7647 D BtGatt.GattService: start scan with filters
,08-25 13:18:58.821  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-25 13:18:58.821  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:18:58.821  7579  7609 D BtGatt.ScanManager: handling starting scan
08-25 13:18:58.821  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 13:18:58.821  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:18:58.821  7579  7604 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 13:18:58.821  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.821  7579  7609 D BtGatt.ScanManager: allow scan with filters
08-25 13:18:58.821  7579  7609 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 13:18:58.821  7579  7609 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-25 13:18:58.821  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:18:58.821  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 13:18:58.821  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:18:58.821  7579  7604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 13:18:58.821  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.821  7579  7609 D BtGatt.ScanManager: Starting BLE batch scan
08-25 13:18:58.821  7579  7609 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 13:18:58.821  7579  7604 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-25 13:18:58.821  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.821  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 13:18:58.831  7579  7604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 13:18:58.831  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-25 13:18:58.841  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:58.841  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:18:58.841  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:18:58.841  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:18:58.841  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.841  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 13:18:58.841  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.841  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@206a3ab6 removed from the list
,08-25 13:18:58.841  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.841  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e2a3b7 removed from the list
,08-25 13:18:58.841  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:58.841  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:58.841  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:58.841  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 13:18:58.841  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:58.841  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:58.841  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:58.841  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:58.841  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:58.841  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e2a3b7 not in the list
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 13:18:58.851  7579  7605 D BtGatt.GattService: stopScan() - queue size =1
,08-25 13:18:58.851  7579  7589 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 13:18:58.851  7579  7609 D BtGatt.ScanManager: filter size is 1
08-25 13:18:58.851  7579  7609 D BtGatt.ScanManager: delete FilterIndex - 5
,08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 13:18:58.851  7579  7604 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 13:18:58.851  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.851  7579  7609 D BtGatt.ScanManager: stopping BLe Batch
,08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.851  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:18:58.851  6760  6760 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:58.851  6760  6760 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.851  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d74c42 removed from the list
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:58.851  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:58.851  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:58.851  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.861  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b528d removed from the list
08-25 13:18:58.861  7579  7604 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 13:18:58.861  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 13:18:58.861  7579  7609 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 13:18:58.861  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:18:58.861  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d11ea8e added. We now have 2 listener(s)
08-25 13:18:58.861  7579  7604 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 13:18:58.861  7579  7604 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 13:18:58.861  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 13:18:58.861  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 13:18:58.861  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 13:18:58.861  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:58.861  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec52af added. We now have 9 listener(s)
,08-25 13:18:58.861  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:58.861  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:18:58.871  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:58.871  6760  6815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:58.871  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:58.871  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:58.871  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:58.871  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:58.871  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:58.871  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:58.871  6760  6815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:58.871  6760  6815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:58.871  6760  6815 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:18:58.871  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:18:58.871  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24454645 added. We now have 3 listener(s)
,08-25 13:18:58.881  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:58.881  6760  6760 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:58.881  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 13:18:58.881  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:18:58.881  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:18:58.881  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:58.881  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b46219a added. We now have 10 listener(s)
08-25 13:18:58.881  6760  6815 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:58.881  6760  6815 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:58.881  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:58.881  6760  6815 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:58.881  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:58.881  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.881  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:18:58.881  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.881  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d11ea8e removed from the list
08-25 13:18:58.881  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.881  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec52af removed from the list
08-25 13:18:58.881  6760  6815 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:58.881  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:58.881  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.881  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.881  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:58.881  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:58.881  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:58.881  6760  6815 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dec52af not in the list
,08-25 13:18:58.881  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.881  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:58.891  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:18:58.891  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:58.891  6760  6815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:58.891  6760  6815 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b46219a removed from the list
08-25 13:18:58.891  6760  6815 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:58.891  6760  6815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:58.891  6760  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:58.891  6760  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:18:58.891  6760  6815 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24454645 removed from the list
,08-25 13:18:58.891  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 13:18:58.891  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-25 13:18:58.891  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 13:18:58.891  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 13:18:58.891  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 13:18:58.891  6760  6815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:18:58.891  6760  7716 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1348, name: My test thread name)
,08-25 13:18:58.891  6760  7716 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1348, thread name: My test thread name)
08-25 13:18:58.901  6760  7716 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1348, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 13:18:58.901  6760  7717 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1350, name: My test thread name),
08-25 13:18:58.901  6760  7717 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1350, thread name: My test thread name)
,08-25 13:18:58.901  6760  7717 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1350, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 13:18:58.901  6760  6815 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-25 13:18:58.901  6760  6815 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 13:18:58.901  6760  6815 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-25 13:18:58.901  6760  6815 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 13:18:58.901  6760  6815 D com.test.thalitest.ThaliTestRunner: Total duration: 23445 ms
,08-25 13:18:58.901  6760  6815 I jxcore-log: Total number of executed tests:  80
08-25 13:18:58.901  6760  6815 I jxcore-log: 
,08-25 13:18:58.901  6760  6815 I jxcore-log: Number of passed tests:  80
08-25 13:18:58.901  6760  6815 I jxcore-log: 
,08-25 13:18:58.911  6760  6815 I jxcore-log: Number of failed tests:  0
08-25 13:18:58.911  6760  6815 I jxcore-log: 
,08-25 13:18:58.911  6760  6815 I jxcore-log: Number of ignored tests:  0
08-25 13:18:58.911  6760  6815 I jxcore-log: 
,08-25 13:18:58.911  6760  6815 I jxcore-log: Total duration:  23445
08-25 13:18:58.911  6760  6815 I jxcore-log: 
,08-25 13:18:58.911  6760  6815 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 13:18:58.911  6760  6815 I jxcore-log: 
,08-25 13:18:58.911  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:18:58.911  6760  6815 I jxcore-log: 
08-25 13:18:58.911  1014  1125 E WifiNative-wlan0: do suspend true
08-25 13:18:58.911  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:18:58.911  6760  6815 I jxcore-log: 
08-25 13:18:58.921  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:18:58.921  6760  6815 I jxcore-log: 
08-25 13:18:58.921  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:18:58.921  6760  6815 I jxcore-log: 
08-25 13:18:58.921  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:18:58.921  6760  6815 I jxcore-log: 
08-25 13:18:58.921  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:18:58.921  6760  6815 I jxcore-log: 
08-25 13:18:58.921  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:18:58.921  6760  6815 I jxcore-log: 
08-25 13:18:58.931  6760  6760 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 13:18:58.931  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 13:18:58.931  6760  6815 I jxcore-log: 
08-25 13:18:58.931  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.931  6760  6815 I jxcore-log: 
08-25 13:18:58.931  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.931  6760  6815 I jxcore-log: 
08-25 13:18:58.931  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:18:58.931  6760  6815 I jxcore-log: 
08-25 13:18:58.931  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:18:58.931  6760  6815 I jxcore-log: 
,08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
,08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
,08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
,08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
,08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
08-25 13:18:58.941  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
,08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
08-25 13:18:58.941  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 13:18:58.941  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:18:58.941  6760  6815 I jxcore-log: 
,08-25 13:18:58.951  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:18:58.951  6760  6815 I jxcore-log: 
,08-25 13:18:58.951  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:18:58.951  6760  6815 I jxcore-log: 
,08-25 13:18:58.951  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:18:58.951  6760  6815 I jxcore-log: 
,08-25 13:18:58.951  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:58.951  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:18:58.951  6760  6815 I jxcore-log: 
,08-25 13:18:58.951  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:58.951  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.951  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:18:58.951  6760  6815 I jxcore-log: 
,08-25 13:18:58.951  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:58.951  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.951  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:58.951  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-25 13:18:58.951  1014  1125 E WifiStateMachine: VerifyingLinkState enter
,08-25 13:18:58.951  1014  1127 E ConnectivityService: updateNetworkInfo()
,08-25 13:18:58.961  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-25 13:18:58.961  1014  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-25 13:18:58.971  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-25 13:18:58.971  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 13:18:58.971  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 13:18:58.971  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 13:18:58.971  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-25 13:18:58.981  1014  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504,
,08-25 13:18:58.981  1014  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-25 13:18:58.981  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:58.981  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:58.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:58.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:58.981  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-25 13:18:58.981  1014  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 13:18:58.981  1014  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-25 13:18:58.981  1014  1127 D ConnectivityService: LTETest block dns file not exists
,08-25 13:18:58.991  1014  1127 V NetworkStats: updateIfacesLocked()
08-25 13:18:58.991  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:58.991  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-25 13:18:58.991  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-25 13:18:58.991  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:58.991  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 13:18:58.991  1014  1244 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 13:18:58.991  1014  1127 V NetworkStats: performPollLocked() took 6ms
08-25 13:18:58.991  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:58.991  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 13:18:59.001  1014  1244 W ActivityManager: userId = 0, bbcId = -10000,
08-25 13:18:59.001  1014  1244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:59.001  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 13:18:59.001  1616  1616 I Hs20UtilService: Starting #22
08-25 13:18:59.001  1616  1645 I Hs20UtilService: Message received 5007
,08-25 13:18:59.001  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 13:18:59.001  1296  1296 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-25 13:18:59.011  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.011  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.011  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-25 13:18:59.011  1014  1127 E ConnectivityService: updateNetworkInfo()
,08-25 13:18:59.011  1014  1127 E ConnectivityService: updateNetworkInfo()
08-25 13:18:59.011  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 13:18:59.011  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 13:18:59.011  1014  1127 V NetworkStats: updateIfacesLocked()
08-25 13:18:59.011  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.011  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-25 13:18:59.021  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:59.021  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 13:18:59.021  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:59.021  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 13:18:59.021  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 13:18:59.021  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.021  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.021  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.021  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.021  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 13:18:59.021  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 13:18:59.021  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
08-25 13:18:59.021  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,08-25 13:18:59.031  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:59.031  1014  1127 V NetworkStats: performPollLocked() took 12ms
08-25 13:18:59.031  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:59.031  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 13:18:59.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:59.031  1014  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-25 13:18:59.031  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-25 13:18:59.031  1014  7683 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:59.031  1014  7683 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-25 13:18:59.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.031  1014  7683 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 13:18:59.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.031  1014  7683 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-25 13:18:59.031  1014  7683 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 13:18:59.031   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 13:18:59.031   277  1009 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-25 13:18:59.031  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 13:18:59.031  1014  1127 D ConnectivityService:    accepting network in place of null
,08-25 13:18:59.031  1014  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 13:18:59.031  1014  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-25 13:18:59.031  1475  1475 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 13:18:59.031  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 13:18:59.031  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 13:18:59.041  1475  1475 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 13:18:59.041  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.041  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:59.041  6760  6760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 13:18:59.041  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 13:18:59.041  6760  6815 I jxcore-log: 
,08-25 13:18:59.041  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-25 13:18:59.041  1014  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-25 13:18:59.041  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,08-25 13:18:59.041  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-25 13:18:59.051  1014  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-25 13:18:59.051  1014  1122 V NetworkStats: updateIfacesLocked()
08-25 13:18:59.051  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.051  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-25 13:18:59.051  1176  1747 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 13:18:59.051  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 13:18:59.051  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 13:18:59.051  4815  6824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 13:18:59.051  1014  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-25 13:18:59.051  1014  1495 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:59.051  1014  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 13:18:59.051  1014  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:59.051  1014  1122 V NetworkStats: performPollLocked() took 5ms
08-25 13:18:59.051  1014  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 13:18:59.051  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.051  1616  1616 I Hs20UtilService: Starting #23
,08-25 13:18:59.051  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-25 13:18:59.051  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 13:18:59.051  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-25 13:18:59.051  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-25 13:18:59.051  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 13:18:59.051  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-25 13:18:59.051  1616  1645 I Hs20UtilService: Message received 5007
,08-25 13:18:59.051  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.061  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-25 13:18:59.051  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.061  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.061  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.061  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.061  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.061  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 13:18:59.061  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-25 13:18:59.061  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 13:18:59.061  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 13:18:59.061  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:59.061  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 13:18:59.061  1296  1296 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 13:18:59.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.061  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-25 13:18:59.061  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 13:18:59.061  1296  1296 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-25 13:18:59.061  1296  1296 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-25 13:18:59.071  1014  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 13:18:59.071  1014  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 13:18:59.081  1014  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:18:59.081  1014  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:18:59.081  1014  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 13:18:59.081  1616  1616 I Hs20UtilService: Starting #24
,08-25 13:18:59.081  1296  1296 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 13:18:59.081  1296  1296 I NearbySettings: MountReceiver.onReceive - Keep current state
08-25 13:18:59.081  1616  1645 I Hs20UtilService: Message received 5007
,08-25 13:18:59.091  1014  1133 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-25 13:18:59.091  1014  1495 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-25 13:18:59.091  1014  1495 D SecContentProvider2: mCursor = null
,08-25 13:18:59.091  1014  1452 D SecContentProvider2: uri = 15 selection = getToastGravity
08-25 13:18:59.091  1014  1452 D SecContentProvider2: mCursor = null
,08-25 13:18:59.091  1014  1487 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-25 13:18:59.091  1014  1487 D SecContentProvider2: mCursor = null
,08-25 13:18:59.091  1014  1244 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-25 13:18:59.091  1014  1244 D SecContentProvider2: mCursor = null
,08-25 13:18:59.101  1014  1460 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-25 13:18:59.101  1014  1460 D SecContentProvider2: mCursor = null
,08-25 13:18:59.101  1014  4344 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-25 13:18:59.101  1014  4344 D SecContentProvider2: mCursor = null
,08-25 13:18:59.111  1014  7683 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-25 13:18:59.131   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-25 13:18:59.141  1014  1452 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,08-25 13:18:59.141  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-25 13:18:59.171  1014  7683 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 11:18:59 GMT], X-Android-Received-Millis=[1472123939177], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472123939146]}
,08-25 13:18:59.171  1014  7683 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-25 13:18:59.171  1014  7683 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-25 13:18:59.171  1014  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-25 13:18:59.171  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-25 13:18:59.171  1014  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-25 13:18:59.171  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-25 13:18:59.171  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 13:18:59.171  4815  6824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 13:18:59.171  1176  1747 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
,08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 13:18:59.181  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 13:18:59.181  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 13:18:59.181  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 13:18:59.211  7720  7720 D AndroidRuntime: 
08-25 13:18:59.211  7720  7720 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 13:18:59.211  7720  7720 D AndroidRuntime: CheckJNI is OFF
,08-25 13:18:59.211  7720  7720 D AndroidRuntime: readGMSProperty: start
08-25 13:18:59.211  7720  7720 D AndroidRuntime: readGMSProperty: already setted!!
08-25 13:18:59.211  7720  7720 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-25 13:18:59.211  7720  7720 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 13:18:59.211  7720  7720 D AndroidRuntime: readGMSProperty: end
08-25 13:18:59.211  7720  7720 D AndroidRuntime: addProductProperty: start
,08-25 13:18:59.211  6760  6760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 13:18:59.211  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 13:18:59.211  6760  6815 I jxcore-log: 
,08-25 13:18:59.331  7720  7720 E AffinityControl: AffinityControl: registerfunction enter,
,08-25 13:18:59.351  7720  7720 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-25 13:18:59.351  6760  6760 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 13:18:59.361  6760  6815 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 13:18:59.361  6760  6815 I jxcore-log: 
,08-25 13:18:59.371  1014  1133 D PackageManager: START PACKAGE DELETE: observer{404475298}
08-25 13:18:59.371  1014  1133 D PackageManager: pkg{<packageName>}
08-25 13:18:59.371  1014  1133 D PackageManager: user{0}
08-25 13:18:59.371  1014  1133 D PackageManager: caller{2000}
08-25 13:18:59.371  1014  1133 D PackageManager: flags{2}
08-25 13:18:59.371  1014  1133 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-25 13:18:59.371  1014  1133 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-25 13:18:59.371  1014  1133 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-25 13:18:59.371  1014  1133 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-25 13:18:59.371  1014  1133 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-25 13:18:59.371  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-25 13:18:59.371  1014  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-25 13:18:59.371  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-25 13:18:59.371  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-25 13:18:59.371  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-25 13:18:59.371  1014  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
08-25 13:18:59.381  1014  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-25 13:18:59.401  1014  1041 I ActivityManager: Killing 6760:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-25 13:18:59.491  1014  1055 W PackageSettings: Skipping PackageSetting{33623ba2 com.example.hello/10168} due to missing metadata
,08-25 13:18:59.511  1014  1026 I WindowState: WIN DEATH: Window{2d93dc43 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 13:18:59.521   257   447 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-25 13:18:59.521   257  1036 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-25 13:18:59.521  1014  1026 D InputDispatcher: Focus left window: 6760
,08-25 13:18:59.521  1014  1041 I ActivityManager:   Force finishing activity ActivityRecord{269e7063 u0 com.test.thalitest/.MainActivity t2}
,08-25 13:18:59.531  1014  1496 W ActivityManager: Spurious death for ProcessRecord{29ca1a33 6760:com.test.thalitest/u0a171}, curProc for 6760: null
,08-25 13:18:59.531  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-25 13:18:59.531  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 13:18:59.541  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:59.551  1014  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-25 13:18:59.551  1014  1055 I ActivityManager:   Force finishing activity ActivityRecord{269e7063 u0 com.test.thalitest/.MainActivity t2 f}
,08-25 13:18:59.551  1014  1055 W ActivityManager: Duplicate finish request for ActivityRecord{269e7063 u0 com.test.thalitest/.MainActivity t2 f}
,08-25 13:18:59.561  1014  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-25 13:18:59.611  1014  1041 D InputDispatcher: Focused application released
08-25 13:18:59.611  1014  1041 D FocusedStackFrame: Set to : 0
,08-25 13:18:59.621  1014  1041 W ActivityManager: mDVFSHelper.acquire()
,08-25 13:18:59.621  1014  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-25 13:18:59.641  1014  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:59.641  4815  4815 I art     : Explicit concurrent mark sweep GC freed 23188(1405KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 2.303ms total 89.036ms
,08-25 13:18:59.661  2638  2638 I art     : Explicit concurrent mark sweep GC freed 19555(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 803us total 57.980ms
,08-25 13:18:59.661  1497  1497 D Launcher: onRestart, Launcher: 218625881
,08-25 13:18:59.681  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 13:18:59.691  1885  1885 E SamsungIME: mOCRHelper is null
,08-25 13:18:59.711  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-25 13:18:59.711  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:18:59.711  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-25 13:18:59.711  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-25 13:18:59.711  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 13:18:59.711  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-25 13:18:59.721  1014  1122 V NetworkStats: performPollLocked() took 8ms
08-25 13:18:59.721  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:59.721  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:59.721  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:59.721  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:18:59.721  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:18:59.731   287   287 E SMD     : DCD OFF,
,08-25 13:18:59.741  7735  7735 E Zygote  : MountEmulatedStorage()
08-25 13:18:59.741  7735  7735 E Zygote  : v2
08-25 13:18:59.741  7735  7735 I libpersona: KNOX_SDCARD checking this for 1000
08-25 13:18:59.741  7735  7735 I libpersona: KNOX_SDCARD not a persona
,08-25 13:18:59.741  7735  7735 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:18:59.741  7735  7735 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:18:59.741  7735  7735 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:18:59.751   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 13:18:59.751  1014  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7735 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 13:18:59.761  1497  1497 D Launcher: onStart, Launcher: 218625881
08-25 13:18:59.761  1497  1497 D Launcher.HomeView: onStart
08-25 13:18:59.761  1497  1497 D Launcher: onResume, Launcher: 218625881
08-25 13:18:59.761  1014  1495 D SettingsProvider: name = kids_home_mode
08-25 13:18:59.761  1014  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 13:18:59.761  1014  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 13:18:59.761  1014  1495 D SettingsProvider: selectionArgs: false
08-25 13:18:59.761  1014  1495 D SettingsProvider: selectionArgs: 10006
08-25 13:18:59.761  1014  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 13:18:59.761  1014  1495 D SettingsProvider: ret = -1
08-25 13:18:59.761  1497  1497 D Launcher.HomeView: onResume
,08-25 13:18:59.801  7735  7735 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:18:59.801  7735  7735 D ActivityThread: Added TimaKeyStore provider
,08-25 13:18:59.801  1456  1456 D PersonaManager: isKioskContainerExistOnDevice,
,08-25 13:18:59.811  1456  1456 D RegisteredServicesCache: empty dynamic service
,08-25 13:18:59.821  1014  1014 I art     : Explicit concurrent mark sweep GC freed 76576(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 24MB/37MB, paused 21.253ms total 261.182ms
08-25 13:18:59.821  1014  1055 I art     : WaitForGcToComplete blocked for 241.733ms for cause Explicit
,08-25 13:18:59.841  1456  1456 D RegisteredComponentCache: Collect Tech packages for Knox
,08-25 13:18:59.841  1456  1456 D PersonaManager: isKioskContainerExistOnDevice
,08-25 13:18:59.861  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:59.861  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:59.901  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,08-25 13:18:59.901  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-25 13:18:59.901  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-25 13:18:59.901  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-25 13:18:59.901  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-25 13:18:59.911  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,08-25 13:18:59.911  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-25 13:18:59.971  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-25 13:18:59.971  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 13:18:59.971  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-25 13:18:59.971  1014  1014 V EnterpriseBillingPolicy: uID is 10171
08-25 13:18:59.971  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-25 13:18:59.971  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-25 13:18:59.971  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 13:18:59.971  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-25 13:18:59.971  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-25 13:18:59.971  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-25 13:18:59.971  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-25 13:18:59.981  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-25 13:18:59.981  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-25 13:18:59.981  1014  1014 V EnterpriseBillingPolicy: uID is 10171
08-25 13:18:59.981  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-25 13:18:59.981  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-25 13:18:59.981  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 13:18:59.981  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-25 13:18:59.981  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-25 13:18:59.981  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-25 13:18:59.981  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-25 13:18:59.981  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-25 13:18:59.981  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-25 13:18:59.981  1014  1014 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
08-25 13:18:59.981  1014  3341 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-25 13:18:59.991  1014  1094 V AlarmManager: waitForAlarm result :8
,08-25 13:18:59.991  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-25 13:18:59.991  1014  1127 V NetworkStats: updateIfacesLocked()
,08-25 13:18:59.991  1014  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-25 13:18:59.991  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:18:59.991  1014  1055 I art     : Explicit concurrent mark sweep GC freed 14583(1265KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 5.396ms total 172.338ms
08-25 13:18:59.991  1014  1487 I art     : WaitForGcToComplete blocked for 308.683ms for cause Explicit
,08-25 13:19:00.001  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-25 13:19:00.001  1014  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 13:19:00.011  1014  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:19:00.011  1014  1127 V NetworkStats: performPollLocked() took 13ms
,08-25 13:19:00.011  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 13:19:00.011  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 13:19:00.011  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-25 13:19:00.011  1176  1747 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-25 13:19:00.011  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-25 13:19:00.011  4815  6824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-25 13:19:00.011  1176  1747 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-25 13:19:00.011  4815  6824 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-25 13:19:00.051  1014  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-25 13:19:00.051  1014  1055 D PackageManager: delete codoeFile: 
,08-25 13:19:00.061  1014  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest,
08-25 13:19:00.061  1014  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-25 13:19:00.061  1014  1055 D PackageManager: result of delete: 1{404475298}
,08-25 13:19:00.061  7720  7720 D AndroidRuntime: Shutting down VM
,08-25 13:19:00.111  1014  1041 W ActivityManager: mDVFSHelper.release()
,08-25 13:19:00.151  1014  1487 I art     : Explicit concurrent mark sweep GC freed 7415(483KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.596ms total 156.557ms
,08-25 13:19:00.161  1994  2151 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 13:19:00.161  1014  1452 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-25 13:19:00.161  1014  1452 D SecContentProvider2: mCursor = null
,08-25 13:19:00.161  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-25 13:19:00.161  1014  1041 W ActivityManager: Activity pause timeout for ActivityRecord{1e46acb9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1}
,08-25 13:19:00.171  1014  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-25 13:19:00.171  1014  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-25 13:19:00.171  1014  1040 W TextServicesManagerService: no available spell checker services found
,08-25 13:19:00.181  1497  1497 D MenuAppsGridFragment: onResume
,08-25 13:19:00.191  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-25 13:19:00.191  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-25 13:19:00.201  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.211  7735  7735 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-25 13:19:00.211  7735  7735 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-25 13:19:00.211  7735  7735 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 13:19:00.211  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.221  1014  1133 D ActivityManager: handle home activity for 0
,08-25 13:19:00.221  1014  1133 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-25 13:19:00.221  1014  1014 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,08-25 13:19:00.221  1014  1133 D KnoxTimeoutHandler: post home show event for user 0
,08-25 13:19:00.221  1014  1133 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-25 13:19:00.221  1014  1014 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,08-25 13:19:00.221  1014  1133 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 13:19:00.221  1014  1133 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-25 13:19:00.221  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 13:19:00.221  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-25 13:19:00.221  1497  1497 D Launcher.HomeView: onPause
,08-25 13:19:00.221  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-25 13:19:00.231  1497  1497 I Choreographer: Skipped 32 frames!  The application may be doing too much work on its main thread.
,08-25 13:19:00.231  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.231  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.251  7735  7735 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-25 13:19:00.251  7735  7735 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-25 13:19:00.251  7735  7735 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-25 13:19:00.251  7735  7735 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:00.251   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-25 13:19:00.251  1014  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-25 13:19:00.251  1014  1244 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 6 r.nextReceiver= 1 receivers.size=28
08-25 13:19:00.251  1014  1244 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
08-25 13:19:00.251  1014  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-25 13:19:00.261  1014  1514 D InputDispatcher: Focus entered window: 1497
,08-25 13:19:00.261  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 13:19:00.261  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 13:19:00.261  1497  1497 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-25 13:19:00.261  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-25 13:19:00.271  7720  7720 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-25 13:19:00.271  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.271  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:19:00.271  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.271  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:19:00.281  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{33eeef7e token=android.os.BinderProxy@22cd6c36 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-25 13:19:00.281  1497  1497 D Launcher.HomeView: onStop
,08-25 13:19:00.291  7754  7754 E Zygote  : MountEmulatedStorage()
08-25 13:19:00.291  7754  7754 E Zygote  : v2
08-25 13:19:00.291  7754  7754 I libpersona: KNOX_SDCARD checking this for 10001
08-25 13:19:00.291  7754  7754 I libpersona: KNOX_SDCARD not a persona
,08-25 13:19:00.291  1014  1495 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-25 13:19:00.291  7754  7754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:19:00.291  1014  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-25 13:19:00.291  1014  1055 D PackageManager: userId{-1}
08-25 13:19:00.291  1014  1055 D PackageManager: andCode{true}
,08-25 13:19:00.291  1014  7758 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-25 13:19:00.291  7754  7754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:19:00.301  7754  7754 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:19:00.301  1014  1495 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6760 uid 10171
,08-25 13:19:00.301  1176  1176 I StatusBar: Icon Only
08-25 13:19:00.301  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7754 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 13:19:00.301  1176  1176 D PanelView: There is/are notification(s) 
,08-25 13:19:00.311  1014  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-25 13:19:00.321  1885  1885 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-25 13:19:00.321  1014  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:19:00.321  1014  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.321  1014  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.321  1014  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:19:00.321  1014  1452 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-25 13:19:00.321  1014  1452 D SecContentProvider2: mCursor = null
,08-25 13:19:00.331  1014  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-25 13:19:00.331  7754  7754 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 13:19:00.331  7754  7754 D ActivityThread: Added TimaKeyStore provider
,08-25 13:19:00.331  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.331  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 13:19:00.331  7772  7772 E Zygote  : MountEmulatedStorage()
08-25 13:19:00.331  7772  7772 E Zygote  : v2
08-25 13:19:00.331  7772  7772 I libpersona: KNOX_SDCARD checking this for 10003
08-25 13:19:00.331  7772  7772 I libpersona: KNOX_SDCARD not a persona
,08-25 13:19:00.341  7772  7772 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:19:00.341  1014  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7772 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-25 13:19:00.341  7772  7772 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:19:00.351  7772  7772 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:19:00.351  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-25 13:19:00.351  1690  1690 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-25 13:19:00.351  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.351  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.351  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.351  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:19:00.371  7772  7772 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 13:19:00.371  7772  7772 D ActivityThread: Added TimaKeyStore provider
,08-25 13:19:00.371  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.381  7787  7787 E Zygote  : MountEmulatedStorage()
,08-25 13:19:00.381  7787  7787 E Zygote  : v2
08-25 13:19:00.381  7787  7787 I libpersona: KNOX_SDCARD checking this for 10121
08-25 13:19:00.381  7787  7787 I libpersona: KNOX_SDCARD not a persona
08-25 13:19:00.381  1014  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-25 13:19:00.381  1014  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:19:00.381  1014  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 13:19:00.381  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-25 13:19:00.381  1014  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7787 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-25 13:19:00.391  7787  7787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 13:19:00.391  7787  7787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 13:19:00.391  7787  7787 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:19:00.391  1014  1460 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-25 13:19:00.391  1014  1460 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
08-25 13:19:00.391  1014  1460 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:19:00.391  1014  1460 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 13:19:00.391  1014  1460 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-25 13:19:00.401  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.411  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.411  1014  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-25 13:19:00.421  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.421  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 13:19:00.421  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.421  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-25 13:19:00.421  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 13:19:00.421  1014  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 13:19:00.421  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.431  2466  2752 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 13
,08-25 13:19:00.431  7802  7802 E Zygote  : MountEmulatedStorage(),
08-25 13:19:00.431  7802  7802 E Zygote  : v2
08-25 13:19:00.431  7802  7802 I libpersona: KNOX_SDCARD checking this for 10031
08-25 13:19:00.431  7802  7802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 13:19:00.431  7802  7802 I libpersona: KNOX_SDCARD not a persona
,08-25 13:19:00.431  7802  7802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 13:19:00.431  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 13:19:00.431  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-25 13:19:00.431  7787  7787 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 13:19:00.441  7787  7787 D ActivityThread: Added TimaKeyStore provider
08-25 13:19:00.441  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 13:19:00.441  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-25 13:19:00.441  7802  7802 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 13:19:00.441  1014  1495 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7802 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-25 13:19:00.441  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 13:19:00.451  1690  1690 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-25 13:19:00.451  1690  1690 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-25 13:19:00.451  1690  1690 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-25 13:19:00.451  1690  1690 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-25 13:19:00.461  1014  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e46acb9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:161843
,08-25 13:19:00.471  1014  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-25 13:19:00.471  1690  1690 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-25 13:19:00.471   306   306 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 31.340ms
,08-25 13:19:00.481  1690  1690 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-25 13:19:00.481  1014  4344 I ActivityManager: Killing 7139:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-25 13:19:00.481  1014  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-25 13:19:00.491  7802  7802 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 13:19:00.491  7802  7802 D ActivityThread: Added TimaKeyStore provider
,08-25 13:19:00.491   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 20.666ms
,08-25 13:19:00.501  7787  7787 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 13:19:00.501  7787  7787 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-25 13:19:00.501  7787  7787 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 13:19:00.511  1014  1244 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-25 13:19:00.511  1014  1244 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:19:00.511  1014  1244 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
08-25 13:19:00.511  1014  1244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 13:19:00.511  1014  1244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-25 13:19:00.511   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 664us total 17.586ms
,08-25 13:19:00.531  1014  1451 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-25 13:19:00.531  1014  1451 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 13:19:00.531  1014  1451 W ActivityManager: userId = 0, bbcId = -10000
08-25 13:19:00.531  7787  7787 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:00.531  1014  1451 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 13:19:00.531  1014  1451 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 13:19:00.531  7787  7787 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service

```
