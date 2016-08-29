#### Test 82914073a7b15c1_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-29 18:39:35.306  1015  1748 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1172 (0x0)
,08-29 18:39:35.486  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-29 18:39:35.486  1015  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 18:39:35.486  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 18:39:35.486  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 18:39:35.496  1015  1015 I MotionRecognitionService: Plugged
08-29 18:39:35.496  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 18:39:35.496  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 18:39:35.496  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
--------- beginning of main
08-29 18:39:35.496  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 18:39:35.496  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 18:39:35.506  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 18:39:35.506  3178  3283 D HeadsetStateMachine: Disconnected process message: 10
08-29 18:39:35.516  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 18:39:35.516  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 18:39:35.516  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 18:39:35.636  6888  6888 D AndroidRuntime: 
08-29 18:39:35.636  6888  6888 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 18:39:35.646  6888  6888 D AndroidRuntime: CheckJNI is OFF
08-29 18:39:35.646  6888  6888 D AndroidRuntime: readGMSProperty: start
08-29 18:39:35.646  6888  6888 D AndroidRuntime: readGMSProperty: already setted!!
08-29 18:39:35.646  6888  6888 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 18:39:35.646  6888  6888 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 18:39:35.646  6888  6888 D AndroidRuntime: readGMSProperty: end
08-29 18:39:35.646  6888  6888 D AndroidRuntime: addProductProperty: start
08-29 18:39:35.786  6888  6888 E AffinityControl: AffinityControl: registerfunction enter
08-29 18:39:35.806  1015  3354 D SSRM:n  : SIOP:: AP = 350
08-29 18:39:35.806  6888  6888 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 18:39:35.826  1015  1495 E PersonaManagerService: inState():  stateMachine is null !!
08-29 18:39:35.836  1015  1495 I PersonaManagerService: PersonaId don't exist
08-29 18:39:35.836  1015  1495 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-29 18:39:35.836  1015  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 18:39:35.856  1015  1495 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
08-29 18:39:35.856  1015  1495 W ActivityManager: mDVFSHelper.acquire()
08-29 18:39:35.856   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-29 18:39:35.856   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-29 18:39:35.876  1015  1495 D FocusedStackFrame: Set to : 0
08-29 18:39:35.886  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 18:39:35.886  1480  1480 D Launcher.HomeView: onPause
08-29 18:39:35.886  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-29 18:39:35.886  1015  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-29 18:39:35.886  1015  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 18:39:35.886  1015  1495 D InputDispatcher: Focused application set to: xxxx
08-29 18:39:35.886  1015  1495 D InputDispatcher: Focus left window: 1480
08-29 18:39:35.886  6888  6888 D AndroidRuntime: Shutting down VM
08-29 18:39:35.886  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-29 18:39:35.886  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 18:39:35.886  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 18:39:35.886   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-29 18:39:35.886  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:35.886  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:35.886  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
08-29 18:39:35.896  6807  6807 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
08-29 18:39:35.906  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:35.906  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 18:39:35.906  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 18:39:35.906  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:35.906  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:35.906  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:35.926  6901  6901 E Zygote  : MountEmulatedStorage()
08-29 18:39:35.926  6901  6901 I libpersona: KNOX_SDCARD checking this for 10171
08-29 18:39:35.926  6901  6901 E Zygote  : v2
08-29 18:39:35.926  6901  6901 I libpersona: KNOX_SDCARD not a persona
08-29 18:39:35.926  1015  1215 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6901 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 18:39:35.926  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:35.936  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:35.936  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 18:39:35.936  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{27a85d5e token=android.os.BinderProxy@1c495b97 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-29 18:39:35.966  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 18:39:35.966  6901  6901 D ActivityThread: Added TimaKeyStore provider
08-29 18:39:35.966  1015  1476 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
08-29 18:39:35.966  1015  1476 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
08-29 18:39:35.966  1015  1476 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-29 18:39:35.966  1015  1015 V ActivityManager: Display changed displayId=0
08-29 18:39:35.976  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-29 18:39:35.976  1480  1480 D Launcher.HomeView: onStop
08-29 18:39:35.976  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{27a85d5e token=android.os.BinderProxy@1c495b97 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-29 18:39:35.986  1015  1476 D PersonaManager: isKioskContainerExistOnDevice
08-29 18:39:36.006  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-29 18:39:36.006  1015  1015 D SensorService: [SO] activate (ident=0xb8a48678, enabled=0)
08-29 18:39:36.006  1015  1015 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
08-29 18:39:36.016  1015  1015 D SensorManager: unregisterListener ::   
08-29 18:39:36.016  1015  1015 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
08-29 18:39:36.016  1015  1015 D SensorService: [SO] changed settle time [1]
08-29 18:39:36.016  1015  1015 D SensorService: [SO] setDelay [66000000]
08-29 18:39:36.016  1015  1015 D SensorService: [SO] activate (ident=0xb8ce0690, enabled=1)
08-29 18:39:36.016  1015  1015 D SensorService: [SO] AR_init
08-29 18:39:36.016  1015  1015 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
08-29 18:39:36.026  1480  1480 D Launcher: onTrimMemory. Level: 20
08-29 18:39:36.026  1015  1015 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
08-29 18:39:36.096  1015  1038 D SensorService: [SO] Reset Rotation Old [100], Init [1]
08-29 18:39:36.096  6888  6888 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 18:39:36.106  6901  6901 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-29 18:39:36.126  6901  6901 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6740-6742)
,08-29 18:39:36.126  6901  6901 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 18:39:36.156  6901  6901 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {237e6914}
,08-29 18:39:36.156  6901  6901 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 18:39:36.166  1015  1038 D SensorService: [SO] -0.345 0.172 9.864
08-29 18:39:36.166  1015  1038 D SensorService: [SO] [100 -> 255]
,08-29 18:39:36.166  6901  6901 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 18:39:36.206  6901  6901 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 18:39:36.216  6901  6901 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 18:39:36.226  6901  6901 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 18:39:36.266  6901  6901 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 18:39:36.266  6901  6901 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 18:39:36.266  6901  6901 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 18:39:36.266  6901  6901 I Adreno-EGL: Local Branch: 
08-29 18:39:36.266  6901  6901 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 18:39:36.266  6901  6901 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 18:39:36.266  6901  6901 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 18:39:36.366  6901  6901 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 18:39:36.386  6901  6901 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 18:39:36.386  6901  6901 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 18:39:36.396  6901  6901 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 18:39:36.396  6901  6901 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 18:39:36.406   288   288 E SMD     : DCD OFF
,08-29 18:39:36.426   258  1888 I SurfaceFlinger: id=6 Removed Mauncher (5/8)
,08-29 18:39:36.426   258   446 I SurfaceFlinger: id=6 Removed Mauncher (-2/8)
,08-29 18:39:36.516  6901  6901 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-29 18:39:36.526  6901  6901 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 18:39:36.536  6901  6901 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-29 18:39:36.536  6901  6901 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-29 18:39:36.546  6901  6901 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-29 18:39:36.546  6901  6901 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 18:39:36.546  6901  6901 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 18:39:36.676  6901  6941 D OpenGLRenderer: Render dirty regions requested: true
,08-29 18:39:36.676  1015  1476 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 18:39:36.676  1015  1476 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 18:39:36.676  1015  1476 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-29 18:39:36.676  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-29 18:39:36.686  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 18:39:36.686  6901  6928 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-29 18:39:36.686  6901  6901 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-29 18:39:36.686  6901  6901 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-29 18:39:36.706   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-29 18:39:36.726  1015  1477 D InputDispatcher: Focus entered window: 6901
,08-29 18:39:36.726  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 18:39:36.726  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 18:39:36.726  6901  6901 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-29 18:39:36.726  6901  6941 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 18:39:36.736  6901  6941 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-29 18:39:36.736  6901  6941 D OpenGLRenderer: Enabling debug mode 0
,08-29 18:39:36.796  1015  1478 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
08-29 18:39:36.796  1172  1172 I StatusBar: Icon Only
08-29 18:39:36.796  1172  1172 D PanelView: There is/are notification(s) 
,08-29 18:39:36.806  1015  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 18:39:36.806  1015  1046 I ActivityManager: Displayed Component not be shown by security: +903ms,
,08-29 18:39:36.816  1015  1046 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
08-29 18:39:36.816  1015  1046 W ActivityManager: mDVFSHelper.release()
08-29 18:39:36.816  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3aa1e72 u0 com.test.thalitest/.MainActivity t2} time:107433
08-29 18:39:36.816  1015  1041 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@11
,08-29 18:39:36.816  1872  1872 I SamsungIME: getCurrentCandidateView
,08-29 18:39:36.826  6901  6901 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d369561 time:107445
,08-29 18:39:36.866  6901  6901 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6901
,08-29 18:39:36.926  1872  1872 D SamsungIME: Dismiss ExpandCandiate
,08-29 18:39:37.006  1015  1038 D SensorService: [SO] -0.364 0.172 9.826
,08-29 18:39:37.026   258   446 I SurfaceFlinger: id=12 Removed uhalitest (7/8)
,08-29 18:39:37.026   258  1037 I SurfaceFlinger: id=12 Removed uhalitest (-2/8)
,08-29 18:39:37.116  1015  1015 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@11
,08-29 18:39:37.136  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c,
,08-29 18:39:37.206  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 18:39:37.216  1872  1872 I SamsungIME: KeybaordView init() : load resources
,08-29 18:39:37.246  1872  1872 I SamsungIME: getCurrentKeyboard
,08-29 18:39:37.246  1872  1872 I SamsungIME: getTextKeyboard
,08-29 18:39:37.266  1872  1872 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619,
,08-29 18:39:37.316  1015  1307 E Watchdog: !@Sync 3
,08-29 18:39:37.376  6901  6901 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 18:39:37.466  6901  6945 D jxcore_app_log: JniHelper::setJavaVM(0xb84722b0), pthread_self() = -1197445792
,08-29 18:39:37.476  6901  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 18:39:37.476  6901  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 18:39:37.476  6901  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 18:39:37.476  6901  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 18:39:37.476  6901  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 18:39:37.476  6901  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e1fd66a added. We now have 1 listener(s)
,08-29 18:39:37.486  6901  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27,
08-29 18:39:37.486  6901  6945 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 18:39:37.486  6901  6945 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:39:37.486  6901  6945 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500,
08-29 18:39:37.496  6901  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6be98d1 added. We now have 1 listener(s)
08-29 18:39:37.496  6901  6945 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:39:37.496  6901  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:39:37.496  6901  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-29 18:39:37.496  6901  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 18:39:37.496  6901  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 18:39:37.496  6901  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 18:39:37.506  6901  6945 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:39:37.506  6901  6945 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-29 18:39:37.506  6901  6945 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 18:39:37.506  6901  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:39:37.506  6901  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:37.506  6901  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:37.506  6901  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:37.506  6901  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:39:37.506  6901  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:37.506  6901  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:37.506  6901  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:39:37.506  6901  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 18:39:37.506  6901  6945 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:39:37.516  6901  6945 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 18:39:37.516  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:37.516  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:37.546  6901  6901 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 18:39:38.146  6901  6955 W jxcore-log: Initializing JXcore engine
08-29 18:39:38.146  6901  6955 W jxcore-log: JXcore engine is ready
,08-29 18:39:38.206  2001  2001 E audit   : type=1400 msg=audit(1472488778.206:205): avc:  denied  { ioctl } for  pid=6955 comm="Thread-1286" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 18:39:38.206  2001  2001 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:38.206  2001  2001 E audit   : type=1300 msg=audit(1472488778.206:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9b9008f8 items=0 ppid=304 ppcomm=main pid=6955 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1286" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-29 18:39:38.206  2001  2001 E audit   : type=1320 msg=audit(1472488778.206:205): 
,08-29 18:39:38.216  6901  6955 W jxcore-log: Starting JXcore engine
,08-29 18:39:38.326  6901  6955 W jxcore-log: Platform android
08-29 18:39:38.326  6901  6955 W jxcore-log: 
08-29 18:39:38.326  6901  6955 W jxcore-log: Process ARCH arm
08-29 18:39:38.326  6901  6955 W jxcore-log: 
,08-29 18:39:38.426   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-29 18:39:38.426   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 18:39:38.526  6901  6955 I jxcore-log: JXcore Cordova bridge is ready!
08-29 18:39:38.526  6901  6955 I jxcore-log: 
,08-29 18:39:38.526  6901  6955 W jxcore-log: JXcore engine is started
,08-29 18:39:38.536  6901  6945 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 18:39:38.536  6901  6901 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 18:39:39.296  1015  1048 D PowerManagerService: [s] UserActivityState : 1 -> 2,
08-29 18:39:39.296  1015  1048 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
08-29 18:39:39.296  1015  1048 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
08-29 18:39:39.296  1015  1048 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,08-29 18:39:39.306  1015  1156 D lights  : lcd : 15 +,
08-29 18:39:39.306  1015  1048 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
08-29 18:39:39.306  1015  1048 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,08-29 18:39:39.326  1015  1156 D lights  : lcd : 15 -,
08-29 18:39:39.326  1015  1048 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
08-29 18:39:39.326  1015  1048 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,08-29 18:39:39.406   288   288 E SMD     : DCD OFF
,08-29 18:39:42.406   288   288 E SMD     : DCD OFF,
,08-29 18:39:43.436   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 18:39:43.766  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 18:39:43.766  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 18:39:43.766  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:43.766  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:43.766  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:43.766  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-29 18:39:44.206  5646  5646 D FactoryTest: Not factory mode
,08-29 18:39:44.206  5646  5646 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-29 18:39:44.206  5646  5646 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-29 18:39:44.206  5646  5646 D MTPRx   : still no open session command from host, so toast
,08-29 18:39:44.216  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-29 18:39:44.216  5646  5646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-29 18:39:44.216  5646  5646 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114832
,08-29 18:39:44.216  1015  1477 E PersonaManagerService: inState():  stateMachine is null !!
,08-29 18:39:44.216  1015  1477 I PersonaManagerService: PersonaId don't exist
,08-29 18:39:44.216  1015  1477 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-29 18:39:44.216  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 18:39:44.226  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:44.226  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:44.226  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-29 18:39:44.226  1015  1477 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
,08-29 18:39:44.226  1015  1477 W ActivityManager: mDVFSHelper.acquire()
,08-29 18:39:44.266  6901  6901 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 18:39:44.266  6901  6901 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 18:39:44.266  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 18:39:44.266  1015  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-29 18:39:44.266  1015  1477 D InputDispatcher: Focused application set to: xxxx
,08-29 18:39:44.266  1015  1477 D InputDispatcher: Focus left window: 6901
,08-29 18:39:44.266  5646  5646 E MTPRx   : started activity for popup
,08-29 18:39:44.276  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 18:39:44.276  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 18:39:44.316  5646  5646 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-29 18:39:44.316  5646  5646 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 18:39:44.316  5646  5646 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 18:39:44.316  5646  5646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 18:39:44.316  5646  5646 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 18:39:44.316  5646  5646 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 18:39:44.346  5646  5646 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-29 18:39:44.356  1015  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 18:39:44.356  1015  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 18:39:44.356  1015  1479 D InputDispatcher: Focused application set to: xxxx
,08-29 18:39:44.356  1015  1479 D InputDispatcher: Focus entered window: 6901
,08-29 18:39:44.356  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 18:39:44.356  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 18:39:44.366  1015  1495 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-29 18:39:44.366  1015  1495 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@362548ef attribute=null, token = android.os.BinderProxy@fef9559
,08-29 18:39:44.366  1015  1479 E ActivityManager: Invalid thumbnail dimensions: 488x488
,08-29 18:39:44.406  5646  5646 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-29 18:39:44.416  5646  5646 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-29 18:39:44.416  5646  5646 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-29 18:39:44.436   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 18:39:44.436  6901  6901 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 18:39:44.436  6901  6901 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-29 18:39:44.436  1015  1478 D PersonaManager: isKioskContainerExistOnDevice
,08-29 18:39:44.446  1015  1215 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 18:39:44.446  1015  1215 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-29 18:39:44.446  1015  1215 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 18:39:44.446  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 18:39:44.446  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 18:39:44.466  6901  6901 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d369561 time:115080
,08-29 18:39:44.766  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:39:44.766  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-29 18:39:44.766  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:44.766  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:44.776  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:44.776  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:45.286  1015  1048 D PowerManagerService: [s] UserActivityState : 2 -> 4
,08-29 18:39:45.286  1015  1048 I PowerManagerService: Nap time (uid 1000)...
08-29 18:39:45.296  1015  1048 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,08-29 18:39:45.296  1015  1048 I PowerManagerService: !@[ps] Screen__Off - 1 :  dream(timeout) (2)
08-29 18:39:45.296  1015  1048 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-29 18:39:45.296  1015  1048 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
08-29 18:39:45.296  1015  1048 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
,08-29 18:39:45.296  1015  1152 V WindowOrientationListener: WindowOrientationListener disabled
08-29 18:39:45.296  1015  1048 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
08-29 18:39:45.296  1015  1048 D PowerManagerService: handleSandman : startDream(true)
08-29 18:39:45.296  1015  1152 D SensorService: [SO] activate (ident=0xb8ce0690, enabled=0)
08-29 18:39:45.296  1015  1152 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,08-29 18:39:45.296  1015  1048 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
08-29 18:39:45.296  1015  1048 I PowerManagerService: Sleeping (uid 1000)...
,08-29 18:39:45.296  1015  1048 D PowerManagerService: [s] UserActivityState : 4 -> 0
,08-29 18:39:45.296   258   258 I SurfaceFlinger: id=14 createSurf (540x960),-1 flag=20004, DolorFade
,08-29 18:39:45.296  1015  1152 D SensorManager: unregisterListener ::   
,08-29 18:39:45.306  1172  1983 D KeyguardViewMediator: onScreenTurnedOff(3)
,08-29 18:39:45.306  1172  1983 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
08-29 18:39:45.306  1172  1983 D KeyguardEffectViewController: changeWallpaperByScreenOff()
,08-29 18:39:45.306  1172  1983 D KeyguardViewMediator: notifyScreenOffLocked
,08-29 18:39:45.306  6901  6901 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 18:39:45.306  6901  6901 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 18:39:45.306  1015  1048 D PowerManagerService: Excessive delay in ColorFade : createSurface: 17ms
,08-29 18:39:45.316  1172  1983 D KeyguardViewMediator: timeout : 5000
,08-29 18:39:45.316  6901  6901 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@10b1d82d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3232ff0a, 16908290=android.view.AbsSavedState$1@3232ff0a}, android:focusedViewId=100}]}]
,08-29 18:39:45.316  6901  6901 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE,
08-29 18:39:45.316  6901  6901 V ActivityThread: updateVisibility : ActivityRecord{3527d37b token=android.os.BinderProxy@2d369561 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-29 18:39:45.316  6901  6901 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 18:39:45.316  1015  1048 D PowerManagerService: Excessive delay in ColorFade : createEglSurface: 10ms,
,08-29 18:39:45.316  6901  6901 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 18:39:45.326  1172  1983 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,08-29 18:39:45.326  1172  1172 D KeyguardViewMediator: handleNotifyScreenOff
08-29 18:39:45.326  1172  1172 D VolumePanel: onScreenTurnedOff()
08-29 18:39:45.326  1172  1172 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,08-29 18:39:45.336  1172  1172 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
,08-29 18:39:45.336  1172  1172 D SecKeyguardClockSingleView: onScreenTurnedOff
,08-29 18:39:45.346  1015  1015 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1015) 
,08-29 18:39:45.346  1015  1015 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
08-29 18:39:45.346  1015  1015 D BatteryService: turn on LED for fully charged
,08-29 18:39:45.346  1015  1076 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
08-29 18:39:45.346  1015  1076 E lights  : write_int failed to open -1
08-29 18:39:45.346  1015  1076 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,08-29 18:39:45.346  1015  1090 E SmartFaceService: onReceive: android.intent.action.SCREEN_OFF
,08-29 18:39:45.346  1015  1090 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
08-29 18:39:45.346  1015  1090 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 18:39:45.346  1015  1090 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 18:39:45.346  1015  1090 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 18:39:45.346  1015  1090 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
08-29 18:39:45.346  1015  1090 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
08-29 18:39:45.346  1015  1090 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
08-29 18:39:45.346  1015  1090 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
08-29 18:39:45.346  1015  1090 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 18:39:45.346  1015  1090 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 18:39:45.346  1015  1090 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:39:45.346  1015  1090 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 18:39:45.346  1015  1090 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
08-29 18:39:45.346  1015  1090 E SmartFaceService: fail to set sysfs 0
08-29 18:39:45.346  1015  1090 W System.err: 	at libcore.io.Posix.open(Native Method)
08-29 18:39:45.346  1015  1090 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 18:39:45.346  1015  1090 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 18:39:45.346  1015  1090 W System.err: 	... 10 more
,08-29 18:39:45.356  1015  1048 D PowerManagerService: Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 31ms
,08-29 18:39:45.366  1172  1172 I StatusBar: Icon Only
08-29 18:39:45.366  1172  1172 D PanelView: There is/are notification(s) 
,08-29 18:39:45.366  1015  1015 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,08-29 18:39:45.366  1015  1048 D PowerManagerService: Excessive delay in ColorFade : initGLShaders: 11ms
,08-29 18:39:45.366  1015  1048 D DisplayPowerController: ColorFade: onAnimationStart
08-29 18:39:45.366  1015  1048 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
08-29 18:39:45.366  1015  1048 D DisplayPowerController: performScreenOffTransition : no brightness animation
,08-29 18:39:45.366  1015  1101 E MotionRecognitionService:  handler : SCREEN_OFF end 
,08-29 18:39:45.376  1015  1124 E WifiNative-wlan0: do suspend true
,08-29 18:39:45.386  1015  1015 D NotificationService: ACTION_SCREEN_OFF
,08-29 18:39:45.386  1015  1015 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
,08-29 18:39:45.386  1015  1015 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
08-29 18:39:45.386  1015  1076 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
08-29 18:39:45.386  1015  1076 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,08-29 18:39:45.386   281  1371 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 18:39:45.386   281  1371 V voice   : voice_set_parameters: enter: screen_state=off
08-29 18:39:45.386   281  1371 V voice   : voice_set_parameters: exit with code(-2)
08-29 18:39:45.386   281  1371 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-29 18:39:45.386   281  1371 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 18:39:45.386   281  1371 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 18:39:45.386   281  1371 V audio_hw_primary: adev_set_parameters: exit
,08-29 18:39:45.396  1015  1094 V AlarmManager: waitForAlarm result :4
,08-29 18:39:45.396  1015  1015 I BackgroundCompactionService: Schedule Type1 BGCompaction
,08-29 18:39:45.406  1172  1172 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-29 18:39:45.406   288   288 E SMD     : DCD OFF,
,08-29 18:39:45.426  2003  2003 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-29 18:39:45.436  1015  1046 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,08-29 18:39:45.436  1015  1046 D IpRemoteDisplayController: Bridge Server is not available
08-29 18:39:45.436   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 18:39:45.436  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,08-29 18:39:45.446  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,08-29 18:39:45.446  1407  1407 V EmergencyMode: [EmergencyStateReceiver] binteractive [false] why[3]
,08-29 18:39:45.446  1015  1015 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
,08-29 18:39:45.446  1015  1060 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,08-29 18:39:45.466  1015  1215 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:39:45.466  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-29 18:39:45.466  1015  1215 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:45.466  1015  1215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:45.466  1015  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:45.466  1433  3204 D NfcService: call the applyRouting
,08-29 18:39:45.486  1768  1768 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,08-29 18:39:45.486  1768  1768 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,08-29 18:39:45.496  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:45.496  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:45.496  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,08-29 18:39:45.496  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,08-29 18:39:45.496  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:45.496  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:45.496  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,08-29 18:39:45.506  1768  1768 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,08-29 18:39:45.516  2471  2485 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-29 18:39:45.516  1768  1768 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 18:39:45.516  1768  1768 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-29 18:39:45.516  1768  1768 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-29 18:39:45.516  1768  1768 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,08-29 18:39:45.516  2471  4735 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-29 18:39:45.546  2471  2485 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-29 18:39:45.556  1015  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 18:39:45.556  1015  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 18:39:45.556  1015  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 18:39:45.556  1015  1479 D BatteryService: stay LED for fully charged
,08-29 18:39:45.556  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 18:39:45.566  1015  1015 I MotionRecognitionService: Plugged
08-29 18:39:45.566  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 18:39:45.566  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 18:39:45.566  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 18:39:45.566  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 18:39:45.566  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 18:39:45.576  1015  1048 D DisplayPowerState: !@ ColorFade entry
08-29 18:39:45.576  1015  1048 D DisplayPowerController: ColorFade: onAnimationEnd
,08-29 18:39:45.576  1015  1048 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
08-29 18:39:45.576  1015  1048 D DisplayPowerController: performScreenOffTransition : no brightness animation
,08-29 18:39:45.576  1015  1156 D lights  : lcd : 0 +
,08-29 18:39:45.576  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 18:39:45.576  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:39:45.576  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:39:45.586  3178  3178 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 18:39:45.586  3178  3283 D HeadsetStateMachine: Disconnected process message: 10
08-29 18:39:45.586  1768  1768 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
08-29 18:39:45.586  1768  1768 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
08-29 18:39:45.586  1768  1768 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,08-29 18:39:45.586  1768  1768 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,08-29 18:39:45.596  1015  1156 D lights  : lcd : 0 -
,08-29 18:39:45.596  1015  1048 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
08-29 18:39:45.596  1015  6966 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 0
08-29 18:39:45.596  1015  1048 D DisplayPowerController: performScreenOffTransition : no brightness animation
08-29 18:39:45.596  1015  1048 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
08-29 18:39:45.596  1015  1048 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-29 18:39:45.596  1015  6965 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
08-29 18:39:45.596  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:45.596  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:45.596  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
08-29 18:39:45.596  1015  6965 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
,08-29 18:39:45.626  1768  1768 D accuweather: [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,08-29 18:39:45.636  2003  2003 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
08-29 18:39:45.636  1768  1768 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
08-29 18:39:45.636  1768  1768 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
08-29 18:39:45.646  1015  6966 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 0
08-29 18:39:45.646  1015  1053 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
08-29 18:39:45.646  1015  1053 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
08-29 18:39:45.646  1015  1053 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(false) while turning screen off: 58ms
08-29 18:39:45.646  1015  1053 I QCOM PowerHAL: Got set_interactive hint
08-29 18:39:45.656  1015  1053 D PowerManagerService: Excessive delay in nativeSetInteractive(false): 60ms
08-29 18:39:45.656  1015  1053 D DisplayManagerService: !@display_state: ON -> OFF
08-29 18:39:45.656   258   258 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb84dd690
08-29 18:39:45.656  1015  1046 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-29 18:39:45.656   258   258 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-29 18:39:45.656   258   258 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
08-29 18:39:45.656   258   258 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
08-29 18:39:45.656  1015  1015 V ActivityManager: Display changed displayId=0
,08-29 18:39:45.676  1172  1172 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,08-29 18:39:45.676  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 18:39:45.676  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-29 18:39:45.686  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:45.686  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 18:39:45.686  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:45.686  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:45.686  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:45.686  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:45.706  1015  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 18:39:45.706  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-29 18:39:45.706  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:45.706  1015  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:45.716  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-29 18:39:45.726  1015  1215 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-29 18:39:45.726  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-29 18:39:45.736   268   268 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7be77c8
08-29 18:39:45.736   268   268 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-29 18:39:45.736   268   268 I rmt_storage: wakelock acquired: 1, error no: 42
08-29 18:39:45.736   268   380 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1212254920)
,08-29 18:39:45.766  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-29 18:39:45.766  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0,
08-29 18:39:45.766  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:45.766  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:45.766  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:45.776   268   380 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-29 18:39:45.776   268   380 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-29 18:39:45.776   268   380 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1212254920) wakelock released: 1, error no: 0
08-29 18:39:45.776   268   380 I rmt_storage: 
,08-29 18:39:45.776   268   268 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7be77c8
,08-29 18:39:45.806  4737  6968 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-29 18:39:45.806  4737  6968 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-29 18:39:45.826  1015  3354 D SSRM:n  : SIOP:: AP = 390,
,08-29 18:39:45.846  1015  3354 D SSRM:n  : SIOP:: AP = 390,
08-29 18:39:45.846  2043  2043 E LibSecureUISvc: svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,08-29 18:39:45.856  2003  2003 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 18:39:45.866  1015  1152 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,08-29 18:39:45.886  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:45.886  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:45.886  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:45.896   258   258 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 18:39:45.896   258   537 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-29 18:39:45.896   258   537 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
,08-29 18:39:45.896   258   537 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,08-29 18:39:45.896  1015  1053 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
08-29 18:39:45.896  1015  1053 D PowerManagerService: Excessive delay in !@display_state: OFF: 243ms
08-29 18:39:45.896  1015  1053 I libsuspend: !@autosuspend_wakeup_count_enable
08-29 18:39:45.896  1015  1053 I libsuspend: !@autosuspend_wakeup_count_enable done
08-29 18:39:45.896  1015  1053 D PowerManagerService: Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 304ms
,08-29 18:39:45.896  1015  1048 I PowerManagerService: [PWL] Off : 0s ago
08-29 18:39:45.896  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-29 18:39:45.896  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 18:39:45.896  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10011, pid=2003, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=199)
08-29 18:39:45.896  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Message' (uid=1000, pid=1015, ws=null) (elapsedTime=55)
08-29 18:39:45.896  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10011, pid=2003, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=26)
,08-29 18:39:45.946  1015  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-29 18:39:45.946  1015  6971 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,08-29 18:39:45.956  1015  6971 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 18:39:45.976  1015  6971 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 18:39:45.996  1015  1218 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 18:39:45.996  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-29 18:39:46.006  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:46.006  1015  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:46.006  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.016  1015  6971 I BatteryStatsDumper: Screen bin #0: time=63118 power=0.30507033333333333
08-29 18:39:46.016  1015  6971 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
08-29 18:39:46.016  1015  6971 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
08-29 18:39:46.016  1015  6971 I BatteryStatsDumper: Screen bin #3: time=0 power=0.0
08-29 18:39:46.016  1015  6971 I BatteryStatsDumper: Screen bin #4: time=0 power=0.0
08-29 18:39:46.016  1015  6971 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,08-29 18:39:46.056  1015  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:39:46.056  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-29 18:39:46.056  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:46.056  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:39:46.056  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.126  1015  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:46.126  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:46.126  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:46.126  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.206  1015  6971 I BatteryStatsDumper: Writing to database completed
,08-29 18:39:46.226  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:46.226  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:46.226  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:46.226  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.286  1015  1748 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:46.286  1015  1748 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:46.286  1015  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:46.286  1015  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.286  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 18:39:46.286  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:46.286  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:46.286  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-29 18:39:46.306  6976  6976 E Zygote  : MountEmulatedStorage(),
08-29 18:39:46.306  6976  6976 E Zygote  : v2
08-29 18:39:46.306  6976  6976 I libpersona: KNOX_SDCARD checking this for 10011
08-29 18:39:46.306  6976  6976 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:46.306  1015  1748 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6976 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-29 18:39:46.316  6976  6976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 18:39:46.316  6976  6976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:46.316  6976  6976 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-29 18:39:46.356  6976  6976 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:46.356  6976  6976 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:46.376  6976  6976 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-29 18:39:46.376  6976  6976 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 18:39:46.426  6976  6976 I MultiDex: VM with version 2.1.0 has multidex support
08-29 18:39:46.426  6976  6976 I MultiDex: install
08-29 18:39:46.426  6976  6976 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 18:39:46.436   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 18:39:46.456  6976  6976 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-29 18:39:46.526  6976  6976 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 18:39:46.526  6976  6976 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a372210: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-29 18:39:46.526  6976  6976 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 18:39:46.546  6976  6976 D ChimeraCfgMgr: Reading stored module config
,08-29 18:39:46.546  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-29 18:39:46.556  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:46.556  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:46.556  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:46.556  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.576  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:46.576  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:46.576  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:46.576  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.616  6976  6989 W art     : Suspending all threads took: 8.261ms,
,08-29 18:39:46.636  6976  6989 I art     : Background sticky concurrent mark sweep GC freed 27730(1295KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 7MB/7MB, paused 12.406ms total 77.999ms
,08-29 18:39:46.646  2003  2003 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=55a2646a-2873-4ff5-83f5-304d6991fd1c
,08-29 18:39:46.676  6976  6989 I art     : Background partial concurrent mark sweep GC freed 739(150KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 15.058ms total 36.765ms
,08-29 18:39:46.676  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-29 18:39:46.676  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-29 18:39:46.676  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:46.676  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:46.676  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.686  2003  2003 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 18:39:46.686  2003  2003 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 18:39:46.686  6976  6994 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-29 18:39:46.696  6976  6976 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-29 18:39:46.696  6976  6976 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-29 18:39:46.706  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:46.706  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:46.706  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:39:46.706  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.786   281  1371 D WVCdm   : Instantiating CDM.
,08-29 18:39:46.786   281   709 I WVCdm   : CdmEngine::OpenSession
08-29 18:39:46.786   281   709 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-29 18:39:46.806   281   709 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-29 18:39:46.836   281   709 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-29 18:39:46.876  6976  6990 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-29 18:39:46.876  6976  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 18:39:46.876  6976  6990 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 18:39:46.876  6976  6990 I System.out: (HTTPLog)-Thread-1265-450836349: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 18:39:46.876  6976  6990 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:39:46.876   276   950 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 18:39:46.876   276   950 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 18:39:46.886   281   709 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-29 18:39:46.886   281   719 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-29 18:39:46.886   281   719 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-29 18:39:46.886   281   719 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-29 18:39:46.896   281   719 D WVCdm   : PrepareKeyRequest: nonce=1477483404
,08-29 18:39:46.906  2003  2153 W GCoreFlp: No location to return for getLastLocation()
,08-29 18:39:46.936  6976  6990 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 18:39:46.936  6976  6990 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6976, getuid(): 10011
,08-29 18:39:46.936  1015  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:46.936  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:46.936  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:46.936  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.946  1015  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:46.956  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:46.956  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:39:46.956  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.956  1015  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:46.956  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:46.956  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:46.956  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:46.966  4737  6972 D UdcContextInitService: registered all accounts: true
,08-29 18:39:47.006  2003  2156 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 18:39:47.026  2003  2175 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-29 18:39:47.226  1015  1041 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
,08-29 18:39:47.236  1015  1041 W ActivityManager: mDVFSHelper.release()
,08-29 18:39:47.256  1015  1335 I art     : Explicit concurrent mark sweep GC freed 59814(3MB) AllocSpace objects, 16(1566KB) LOS objects, 33% free, 25MB/37MB, paused 2.746ms total 160.787ms
,08-29 18:39:47.266  6976  6990 I qtaguid : Untagging socket 30
,08-29 18:39:47.276  1015  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 18:39:47.276  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-29 18:39:47.286  6976  6989 I art     : Background sticky concurrent mark sweep GC freed 7945(456KB) AllocSpace objects, 69(4MB) LOS objects, 32% free, 8MB/12MB, paused 7.883ms total 46.176ms
08-29 18:39:47.286  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:47.286  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:47.286  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:47.446   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 18:39:47.546  1015  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:47.546  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:47.546  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:47.546  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:47.626  2003  2175 I art     : Explicit concurrent mark sweep GC freed 59369(3MB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 11MB/18MB, paused 1.406ms total 74.334ms
,08-29 18:39:47.686  4358  4436 I art     : Explicit concurrent mark sweep GC freed 1379(47KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 833us total 22.720ms
,08-29 18:39:47.686  7004  7004 I dex2oat : ----------------------------------------------------
08-29 18:39:47.686  7004  7004 I dex2oat : <SS>: S T A R T I N G . . .
08-29 18:39:47.686  7004  7004 I dex2oat : <SS>: Zip is absent. Canceled.
,08-29 18:39:47.686  7004  7004 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 18:39:47.736  1015  1335 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:47.736  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:47.736  1015  1335 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:47.736  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:47.746  7004  7004 I dex2oat : dex2oat took 59.225ms (threads: 4)
,08-29 18:39:47.746  1015  1476 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 18:39:47.746  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-29 18:39:47.746  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:47.746  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:39:47.746  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:47.756  6976  6990 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 18:39:47.756  6976  6990 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 18:39:47.756  6976  6990 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 18:39:47.756  6976  6990 I Adreno-EGL: Local Branch: 
08-29 18:39:47.756  6976  6990 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 18:39:47.756  6976  6990 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 18:39:47.756  6976  6990 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 18:39:47.796  1015  1748 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:47.796  1015  1748 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:47.796  1015  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:47.796  1015  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:47.796  2003  7011 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-29 18:39:47.796  2003  7003 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-29 18:39:47.796  1015  1218 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:47.806  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:47.806  1015  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:47.806  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:47.836  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-29 18:39:47.846  1015  1028 W ActivityManager: userId = 0, bbcId = -10000,
08-29 18:39:47.846  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:47.846  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:47.876  2003  7011 E CommitToConfigurationOperation: Malformed snapshot token (size): ,
,08-29 18:39:47.886  2003  7003 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-29 18:39:47.886  1015  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:47.886  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:47.886  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:47.886  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:47.926  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:47.926  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:47.926  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:47.926  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:47.926  2003  7011 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-29 18:39:47.926  2003  7003 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-29 18:39:47.926  2003  7003 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-29 18:39:47.956  2003  7003 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 18:39:48.016  6976  6990 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-29 18:39:48.016  6976  6990 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 18:39:48.016  6976  6990 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 18:39:48.016  6976  6990 I Adreno-EGL: Local Branch: 
08-29 18:39:48.016  6976  6990 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 18:39:48.016  6976  6990 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 18:39:48.016  6976  6990 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 18:39:48.046  1015  1335 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-29 18:39:48.066  6976  6990 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 18:39:48.066  6976  6990 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 18:39:48.066  6976  6990 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 18:39:48.066  6976  6990 I Adreno-EGL: Local Branch: 
08-29 18:39:48.066  6976  6990 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 18:39:48.066  6976  6990 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 18:39:48.066  6976  6990 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 18:39:48.096  1015  1538 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 18:39:48.096  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-29 18:39:48.096  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:48.096  1015  1538 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:48.096  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:48.106  2003  7003 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:39:48.126   276   950 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 18:39:48.126   276   950 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 18:39:48.126  2003  7003 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 18:39:48.126  2003  7003 I qtaguid : Tagging socket 73 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2003, getuid(): 10011
,08-29 18:39:48.186  2003  7003 I qtaguid : Tagging socket 76 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2003, getuid(): 10011
,08-29 18:39:48.386  2003  6975 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:39:48.396   276   950 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 18:39:48.396   276   950 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 18:39:48.396  2003  6975 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 18:39:48.396  2003  6975 I qtaguid : Tagging socket 77 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2003, getuid(): 10011
,08-29 18:39:48.406   288   288 E SMD     : DCD OFF
,08-29 18:39:48.436  2003  6975 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2003, getuid(): 10011
,08-29 18:39:48.446   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 18:39:48.466  1015  1335 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-29 18:39:48.476  2003  7003 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:39:48.476  2003  7003 I qtaguid : Tagging socket 73 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2003, getuid(): 10011
,08-29 18:39:48.546   281  1371 I WVCdm   : CdmEngine::CloseSession
,08-29 18:39:48.546   281  1371 I WVCdm   : L3 Terminate.
,08-29 18:39:48.586  2003  2175 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 18:39:48.586  2003  2175 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-29 18:39:48.596  2003  2175 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-29 18:39:47.469+0200, stopTime=2016-08-29 18:39:48.599+0200, duration=1130ms,
,08-29 18:39:48.606  2003  7020 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:39:48.606   276   950 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 18:39:48.606   276   950 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 18:39:48.616  2003  7020 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 18:39:48.616  2003  7020 I qtaguid : Tagging socket 80 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2003, getuid(): 10011
,08-29 18:39:48.626  1015  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-29 18:39:48.646  2003  7003 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:39:48.646  2003  7003 I qtaguid : Tagging socket 73 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 2003, getuid(): 10011
,08-29 18:39:48.656  2003  7020 I qtaguid : Tagging socket 83 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2003, getuid(): 10011
,08-29 18:39:48.666  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-29 18:39:48.916  2003  7020 I qtaguid : Untagging socket 80
,08-29 18:39:48.926  2003  2175 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-29 18:39:49.386  1015  1094 V AlarmManager: waitForAlarm result :4
08-29 18:39:49.386  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-29 18:39:49.486  4737  4737 D ConnectivityManager: CallingUid : 10011, CallingPid : 4737
,08-29 18:39:49.486  1015  1479 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 18:39:49.486  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-29 18:39:49.486  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-29 18:39:49.486  1015  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,08-29 18:39:49.486  4737  7027 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 18:39:49.546  4737  7028 W DriveInitializer: Background init thread started
,08-29 18:39:49.576   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-29 18:39:49.576   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 18:39:49.586  4737  7028 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-29 18:39:49.646  4737  7028 W DriveInitializer: Background init thread ended
,08-29 18:39:50.316  1015  1094 V AlarmManager: waitForAlarm result :4
,08-29 18:39:50.316  1172  1172 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,08-29 18:39:50.316  1172  1172 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,08-29 18:39:50.316  1172  1172 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,08-29 18:39:50.716  2003  7022 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:39:50.726  2003  7022 I qtaguid : Tagging socket 80 with tag 1000310200000000{268448002,0} for uid 10011, pid: 2003, getuid(): 10011
,08-29 18:39:50.896  1015  1048 I PowerManagerService: [PWL] Off : 5s ago,
,08-29 18:39:50.926  2003  7022 I qtaguid : Untagging socket 80
,08-29 18:39:50.926  2003  2175 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-29 18:39:50.956  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-29 18:39:51.196  1015  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 18:39:51.416   288   288 E SMD     : DCD OFF
,08-29 18:39:51.696  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 18:39:51.696  6901  6955 I jxcore-log: 
,08-29 18:39:51.706  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-29 18:39:51.706  6901  6955 I jxcore-log: 
,08-29 18:39:51.706  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:39:51.706  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:51.706  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:51.706  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:51.706  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:39:51.706  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:51.706  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:51.706  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:39:51.716  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:39:51.716  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 18:39:51.716  6901  6955 I jxcore-log: 
,08-29 18:39:51.716  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 18:39:51.716  6901  6955 I jxcore-log: 
,08-29 18:39:52.386  6901  6955 D executeNativeTests: Running unit tests
,08-29 18:39:52.486  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 18:39:52.486  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 added. We now have 2 listener(s)
,08-29 18:39:52.486  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 18:39:52.486  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:39:52.486  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:39:52.486  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:39:52.486  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 added. We now have 2 listener(s)
08-29 18:39:52.486  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:39:52.486  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 18:39:52.496  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:39:52.496  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:39:52.496  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:52.496  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:52.496  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:52.496  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:39:52.496  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:52.496  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:52.496  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:39:52.496  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:39:52.496  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:39:52.496  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:52.506  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:52.506  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 18:39:52.506  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 18:39:52.506  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 18:39:52.506  6901  6955 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 18:39:52.506  6901  6955 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 18:39:52.506  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 18:39:52.506  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:39:52.506  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 18:39:52.516  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:39:52.516  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:52.516  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:39:52.516  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:52.516  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.516  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:39:52.516  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:39:52.516  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 removed from the list
08-29 18:39:52.516  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.516  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 removed from the list
08-29 18:39:52.516  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:52.516  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:52.516  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.516  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:52.516  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:52.516  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:52.516  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.516  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:52.516  6901  6955 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 18:39:52.516  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:39:52.516  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:39:52.516  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:52.526  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:39:52.526  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.526  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.526  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.526  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.526  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:52.526  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.526  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.526  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.526  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.526  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:52.526  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 18:39:52.526  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.526  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510],
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 18:39:52.526  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 18:39:52.536  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 18:39:52.536  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:52.536  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:52.536  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:52.536  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:52.536  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.536  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.536  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.536  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.536  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.536  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:52.536  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.536  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.536  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.536  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.536  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:52.536  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:52.536  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.536  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.536  6901  6955 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 18:39:52.536  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:39:52.546  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:39:52.546  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:52.546  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:52.546  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:52.546  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:39:52.546  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:52.546  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:52.546  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:39:52.546  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:52.546  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:39:52.546  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:39:52.546  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:39:52.546  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:39:52.546  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:39:52.546  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:39:52.546  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 18:39:52.546  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:39:52.556  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 18:39:52.566  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 18:39:52.566  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 18:39:52.566  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 18:39:52.576  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 18:39:52.576  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 18:39:52.576  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 18:39:52.576  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 18:39:52.596  3178  3194 D BtGatt.GattService: registerClient() - UUID=379916a9-9908-48bc-bcd8-2a511900abc2
,08-29 18:39:52.646  3178  3276 D BtGatt.GattService: onClientRegistered() - UUID=379916a9-9908-48bc-bcd8-2a511900abc2, clientIf=6
,08-29 18:39:52.646  6901  6948 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 18:39:52.646  3178  3191 D BtGatt.GattService: start scan with filters
,08-29 18:39:52.646  3178  3282 D BtGatt.ScanManager: handling starting scan
,08-29 18:39:52.656  3178  3282 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767,
,08-29 18:39:52.656  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 18:39:52.656  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 18:39:52.656  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 18:39:52.656  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 18:39:52.656  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 18:39:52.666  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 18:39:52.666  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:39:52.666  3178  3276 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 18:39:52.666  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.666  3178  3282 D BtGatt.ScanManager: allow scan with filters
,08-29 18:39:52.666  3178  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 18:39:52.666  3178  3282 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-29 18:39:52.676  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:39:52.676  3178  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 18:39:52.676  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.676  3178  3282 D BtGatt.ScanManager: Starting BLE batch scan
08-29 18:39:52.676  3178  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 18:39:52.676  6901  6955 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 18:39:52.686  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:39:52.686  6901  6955 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 18:39:52.686  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:39:52.686  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 18:39:52.686  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:39:52.686  3178  3276 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 18:39:52.686  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.686  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 18:39:52.696  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 18:39:52.696  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 18:39:52.696  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:39:52.696  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 18:39:52.696  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 18:39:52.696  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 18:39:52.696  3178  3194 D BtGatt.GattService: stopScan() - queue size =1
,08-29 18:39:52.696  3178  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 18:39:52.696  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-29 18:39:52.696  3178  3191 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 18:39:52.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:39:52.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:39:52.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 18:39:52.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:39:52.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 18:39:52.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:39:52.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 18:39:52.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:39:52.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:39:52.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:39:52.706  3178  3282 D BtGatt.ScanManager: filter size is 1
,08-29 18:39:52.706  3178  3282 D BtGatt.ScanManager: delete FilterIndex - 3
,08-29 18:39:52.706  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:39:52.706  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:39:52.706  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:39:52.716  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:52.716  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.716  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:39:52.716  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.716  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.716  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.716  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:52.716  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.716  6901  6955 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 18:39:52.716  3178  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 18:39:52.716  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:39:52.716  3178  3282 D BtGatt.ScanManager: stopping BLe Batch
,08-29 18:39:52.716  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:39:52.716  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:39:52.716  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:52.716  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:52.716  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:52.716  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:39:52.716  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:52.716  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:52.716  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:39:52.716  3178  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-29 18:39:52.726  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:39:52.726  3178  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 18:39:52.726  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:39:52.726  3178  3276 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 18:39:52.726  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.726  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:39:52.726  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:52.736  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:39:52.736  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:39:52.736  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:39:52.736  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:39:52.736  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 18:39:52.736  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:52.736  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 18:39:52.746  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:39:52.746  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 18:39:52.746  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 18:39:52.746  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 18:39:52.746  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 18:39:52.746  3178  3365 D BtGatt.GattService: registerClient() - UUID=1cdd1685-a42b-4a33-9d57-6aee8e990d21
,08-29 18:39:52.786  3178  3276 D BtGatt.GattService: onClientRegistered() - UUID=1cdd1685-a42b-4a33-9d57-6aee8e990d21, clientIf=6
,08-29 18:39:52.796  6901  6915 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 18:39:52.796  3178  3194 D BtGatt.GattService: start scan with filters
,08-29 18:39:52.796  3178  3282 D BtGatt.ScanManager: handling starting scan
,08-29 18:39:52.796  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 18:39:52.796  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 18:39:52.796  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 18:39:52.796  3178  3276 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 18:39:52.796  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.796  3178  3282 D BtGatt.ScanManager: allow scan with filters
,08-29 18:39:52.796  3178  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 18:39:52.796  3178  3282 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-29 18:39:52.806  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:39:52.806  3178  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 18:39:52.806  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.806  3178  3282 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 18:39:52.806  3178  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 18:39:52.806  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:39:52.806  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:39:52.816  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 18:39:52.816  3178  3276 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 18:39:52.816  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-29 18:39:52.816  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:39:52.816  3178  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 18:39:52.816  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.826  6901  6955 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 18:39:52.826  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:39:52.826  6901  6955 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 18:39:52.826  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:39:52.826  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 18:39:52.826  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:39:52.826  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 18:39:52.836  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 18:39:52.836  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 18:39:52.836  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 18:39:52.836  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 18:39:52.836  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 18:39:52.836  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 18:39:52.836  3178  3191 D BtGatt.GattService: stopScan() - queue size =1
,08-29 18:39:52.836  3178  3282 D BtGatt.ScanManager: filter size is 1
,08-29 18:39:52.836  3178  3282 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 18:39:52.836  3178  3365 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 18:39:52.846  3178  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-29 18:39:52.846  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:39:52.846  3178  3282 D BtGatt.ScanManager: stopping BLe Batch
08-29 18:39:52.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 18:39:52.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:39:52.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 18:39:52.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:39:52.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 18:39:52.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:39:52.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-29 18:39:52.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:39:52.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 18:39:52.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:39:52.846  3178  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-29 18:39:52.846  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:39:52.846  3178  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 18:39:52.856  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:39:52.856  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:39:52.856  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:39:52.856  3178  3276 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 18:39:52.856  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:52.856  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.856  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:39:52.856  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.856  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.856  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:52.856  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:52.856  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.856  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:52.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:39:52.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:52.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.856  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:52.856  6901  6955 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 18:39:52.866  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:39:52.866  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:39:52.866  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:52.866  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:52.866  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:52.866  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:39:52.866  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:52.866  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:52.866  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:39:52.866  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 18:39:52.866  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:39:52.876  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:39:52.876  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:39:52.876  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:39:52.876  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:39:52.876  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 18:39:52.876  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:52.876  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:52.876  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 18:39:52.886  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:39:52.886  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 18:39:52.886  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 18:39:52.886  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 18:39:52.886  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 18:39:52.896  3178  3365 D BtGatt.GattService: registerClient() - UUID=33b08a56-6c8d-4fe8-8dfa-ddf923ac216f
,08-29 18:39:52.936  3178  3276 D BtGatt.GattService: onClientRegistered() - UUID=33b08a56-6c8d-4fe8-8dfa-ddf923ac216f, clientIf=6
,08-29 18:39:52.936  6901  6914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 18:39:52.936  3178  3194 D BtGatt.GattService: start scan with filters
08-29 18:39:52.936  3178  3282 D BtGatt.ScanManager: handling starting scan
08-29 18:39:52.936  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 18:39:52.936  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 18:39:52.936  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 18:39:52.936  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:39:52.946  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:39:52.946  3178  3276 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 18:39:52.946  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.946  3178  3282 D BtGatt.ScanManager: allow scan with filters
08-29 18:39:52.946  3178  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 18:39:52.946  3178  3282 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-29 18:39:52.946  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:39:52.946  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 18:39:52.946  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:39:52.956  3178  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 18:39:52.956  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.956  3178  3282 D BtGatt.ScanManager: Starting BLE batch scan
08-29 18:39:52.956  3178  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 18:39:52.956  6901  6955 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 18:39:52.956  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:39:52.956  6901  6955 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 18:39:52.966  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:52.966  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 18:39:52.966  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:39:52.966  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 18:39:52.966  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 18:39:52.966  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 18:39:52.966  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:39:52.966  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:39:52.966  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 18:39:52.966  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 18:39:52.966  3178  3191 D BtGatt.GattService: stopScan() - queue size =1
,08-29 18:39:52.966  3178  3365 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 18:39:52.966  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:39:52.966  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:39:52.966  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 18:39:52.966  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:39:52.966  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 18:39:52.966  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:39:52.966  3178  3276 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 18:39:52.966  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.966  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 18:39:52.966  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:39:52.976  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 18:39:52.976  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:39:52.976  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:39:52.976  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:39:52.976  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:39:52.976  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:39:52.976  6901  6955 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 18:39:52.976  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:52.976  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:52.976  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:52.976  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.976  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:39:52.976  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.976  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.976  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.976  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:52.976  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:52.976  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.976  3178  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 18:39:52.976  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:52.976  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.976  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:52.976  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:52.976  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.976  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:52.976  6901  6955 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 18:39:52.976  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:52.976  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:52.976  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:52.976  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:52.976  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.976  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.976  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.976  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.976  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.976  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:52.976  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.976  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.976  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.976  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:52.986  3178  3282 D BtGatt.ScanManager: filter size is 1
,08-29 18:39:52.986  3178  3282 D BtGatt.ScanManager: delete FilterIndex - 5
,08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.986  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:52.986  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 18:39:52.986  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:52.986  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:52.986  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:52.986  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.986  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.986  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.986  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.986  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:52.986  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.986  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.986  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.986  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.986  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:52.986  6901  6955 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 18:39:52.986  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:52.986  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:52.986  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:39:52.986  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.986  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.986  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.986  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.986  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 18:39:52.986  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.986  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.986  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.986  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 18:39:52.986  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.986  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.996  3178  3276 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 18:39:52.996  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-29 18:39:52.996  3178  3282 D BtGatt.ScanManager: stopping BLe Batch
08-29 18:39:52.996  6901  6955 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 18:39:52.996  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:52.996  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:39:52.996  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:52.996  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.996  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 18:39:52.996  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.996  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.996  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 18:39:52.996  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.996  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.996  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:39:52.996  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.996  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:52.996  3178  3276 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 18:39:52.996  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:52.996  3178  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 18:39:52.996  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 18:39:52.996  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 18:39:52.996  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 18:39:52.996  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:52.996  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:52.996  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:52.996  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.996  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:52.996  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:52.996  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:52.996  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:52.996  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:52.996  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:52.996  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.006  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.006  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:53.006  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:39:53.006  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:53.006  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.006  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:53.006  6901  6955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:39:53.006  6901  6955 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 18:39:53.006  3178  3276 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 18:39:53.006  6901  6955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:39:53.006  6901  6955 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 18:39:53.006  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 18:39:53.006  6901  6955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 18:39:53.006  6901  6955 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 18:39:53.006  6901  6955 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 18:39:53.006  6901  6955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:39:53.006  6901  6955 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 18:39:53.006  6901  6955 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 18:39:53.006  6901  6955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:39:53.006  6901  6955 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 18:39:53.006  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 18:39:53.006  3178  3276 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:39:53.006  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 18:39:53.016  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 18:39:53.016  6901  6955 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 18:39:53.016  6901  6955 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 18:39:53.016  6901  7039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1350)
08-29 18:39:53.016  6901  6955 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-29 18:39:53.016  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:53.016  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:53.016  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.016  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.016  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.016  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 18:39:53.016  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.016  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.016  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:53.016  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.016  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.016  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.016  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.016  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:53.016  6901  7040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1350
,08-29 18:39:53.016  6901  6955 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 18:39:53.016  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:53.016  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:53.016  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.016  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.016  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.016  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.016  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.016  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.016  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:53.016  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.016  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.016  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.016  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:53.026  6901  6955 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-29 18:39:53.026  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:53.026  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:53.026  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.026  6901  7039 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 18:39:53.026  6901  6955 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 18:39:53.026  6901  6955 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-29 18:39:53.026  6901  6955 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 18:39:53.026  6901  6955 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 18:39:53.026  6901  6955 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 18:39:53.026  6901  6955 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 18:39:53.026  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:39:53.026  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:53.026  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list,
,08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.026  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:53.026  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:53.026  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.026  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.026  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.026  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.026  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:39:53.026  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.036  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.036  6901  6955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:39:53.036  6901  7039 D BluetoothSocket: connect(): myUserId = 0
08-29 18:39:53.036  6901  7039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 18:39:53.036  6901  6955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 18:39:53.036  6901  6955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 18:39:53.036  6901  6901 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 18:39:53.036  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 18:39:53.036  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.036  6901  6955 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 18:39:53.036  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.036  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 18:39:53.036  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:39:53.036  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:39:53.036  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.036  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.036  6901  7041 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 18:39:53.036  6901  7041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 18:39:53.036  6901  6901 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 18:39:53.036  3178  3365 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:39:53.046  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:39:53.046  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.046  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:39:53.046  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:53.046  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:39:53.046  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:53.046  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:53.046  6901  6901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 18:39:53.046  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.046  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.046  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_ST,ARTED, is discovering: false, is advertising: false
08-29 18:39:53.046  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.046  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.046  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.046  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.046  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:53.046  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.046  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.046  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.046  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.046  6901  7039 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[121]}
,08-29 18:39:53.046  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:39:53.046  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:53.046  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.046  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:53.046  6901  6955 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-29 18:39:53.046  6901  6955 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 18:39:53.046  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 18:39:53.046  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 18:39:53.046  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:39:53.046  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:39:53.046  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:53.046  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.046  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.046  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.046  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
,08-29 18:39:53.046  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.046  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.046  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:53.046  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.046  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.046  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.046  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:53.056  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:39:53.056  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:53.056  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.056  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:53.056  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:39:53.056  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:53.056  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:39:53.056  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.056  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.056  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:53.056  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.056  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.056  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.056  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 18:39:53.056  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.056  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.056  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.056  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.056  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:53.056  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:53.056  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:39:53.056  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:53.066  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:39:53.066  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:39:53.066  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:39:53.066  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:39:53.066  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:39:53.066  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.066  6901  6955 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@305eb4c8 not in the list
08-29 18:39:53.066  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.066  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
08-29 18:39:53.066  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:39:53.066  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:39:53.066  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:39:53.066  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:39:53.066  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:39:53.066  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:39:53.066  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:39:53.066  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:39:53.066  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e181961 not in the list
,08-29 18:39:53.066  6901  6955 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
08-29 18:39:53.066  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 18:39:53.066  6901  6955 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 18:39:53.066  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 18:39:53.066  6901  6955 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 18:39:53.066  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
,08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-29 18:39:53.076  6901  6955 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 18:39:53.076  6901  6955 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 18:39:53.076  6901  6955 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id,
08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 18:39:53.076  6901  6955 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-29 18:39:53.076  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 18:39:53.076  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12dcab5b added. We now have 2 listener(s)
08-29 18:39:53.076  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:39:53.076  6901  6955 D BluetoothAdapter: enable(),
,08-29 18:39:53.086  6901  6955 D BluetoothAdapter: enable(): BT is already enabled..!,
,08-29 18:39:53.086  1015  1538 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-29 18:39:53.086  1015  1538 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 18:39:53.086  1015  1538 D SecContentProvider2: mCursor = null
,08-29 18:39:53.086  1015  1538 D WifiService: setWifiEnabled: true pid=6901, uid=10171,
,08-29 18:39:53.086  1015  1538 W ActivityManager: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 18:39:53.096  1015  1538 W WifiService: Failed getting userId using ActivityManagerNative,
08-29 18:39:53.096  1015  1538 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 18:39:53.096  1015  1538 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 18:39:53.096  1015  1538 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 18:39:53.096  1015  1538 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 18:39:53.096  1015  1538 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 18:39:53.096  1015  1538 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 18:39:53.096  1015  1538 D SettingsProvider: name = wifi_on
08-29 18:39:53.096  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:39:53.096  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@278cdff8 added. We now have 3 listener(s)
08-29 18:39:53.096  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:39:53.106  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:39:53.106  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35091cd1 added. We now have 4 listener(s)
08-29 18:39:53.106  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:39:53.116  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:39:53.116  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@364f2336 added. We now have 5 listener(s)
08-29 18:39:53.116  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:39:53.126  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 18:39:53.126  1015  1028 D WifiService: setWifiEnabled: false pid=6901, uid=10171
08-29 18:39:53.126  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 18:39:53.126  1015  1028 D SecContentProvider2: mCursor = null,
08-29 18:39:53.126  1015  1028 D SettingsProvider: name = wifi_on
,08-29 18:39:53.136  6901  6955 D BluetoothAdapter: disable()
,08-29 18:39:53.136  1015  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 18:39:53.136  1372  1372 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-29 18:39:53.136  1372  1372 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-29 18:39:53.136  1372  1372 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 18:39:53.136  1372  1372 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
08-29 18:39:53.136  1015  1748 D SettingsProvider: name = bluetooth_on,
,08-29 18:39:53.146  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-29 18:39:53.166  3178  3273 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-29 18:39:53.166  3178  3273 D BluetoothAdapterProperties: Setting state to 13
08-29 18:39:53.166  3178  3273 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
08-29 18:39:53.166  3178  3273 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 18:39:53.166  1015  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:39:53.166  3178  3273 D BluetoothAdapterService: updateAdapterState state is 13
08-29 18:39:53.166  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
08-29 18:39:53.176  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.176  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.176  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:39:53.176  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:39:53.176  3178  3178 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-29 18:39:53.176  3178  3178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@109d91e6, channel: 19, state: LISTENING
08-29 18:39:53.176  3178  3178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@109d91e6, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d16af0e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@136f6327mSocket: android.net.LocalSocket@dcd49d4 impl:android.net.LocalSocketImpl@1adf377d fd:FileDescriptor[74]
08-29 18:39:53.176  3178  3178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@dcd49d4 impl:android.net.LocalSocketImpl@1adf377d fd:FileDescriptor[74]
,08-29 18:39:53.176  3178  3273 D BluetoothAdapterService: Autoconnection is available ,
08-29 18:39:53.176  3178  3273 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 18:39:53.176  3178  3273 D BluetoothAdapterService: terminating service from this receiver
08-29 18:39:53.176  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 18:39:53.176  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
08-29 18:39:53.176  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:53.176  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:39:53.176  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-29 18:39:53.176  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:53.176  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:53.176  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:39:53.176  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:53.176  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:53.176  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:39:53.176  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:53.176  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:53.186  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:39:53.186  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:53.186  1372  1372 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-29 18:39:53.186  1372  1372 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-29 18:39:53.186  1372  1372 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,08-29 18:39:53.186  1015  1124 E WifiNative-wlan0: do suspend true
,08-29 18:39:53.186  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-29 18:39:53.196  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
08-29 18:39:53.196  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:39:53.196  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 18:39:53.196  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:39:53.196  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
08-29 18:39:53.196  1172  1172 D BluetoothTile:  getBluetoothState : 13
,08-29 18:39:53.196  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-29 18:39:53.196  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 18:39:53.206  1015  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 18:39:53.206  1015  1477 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-29 18:39:53.206  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:53.206  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 18:39:53.206  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:39:53.206  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:53.206  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:53.206  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:53.206  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:39:53.206  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:53.206  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 18:39:53.206  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 18:39:53.206  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:53.206  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 18:39:53.206  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 18:39:53.206  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.206  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.206  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:39:53.206  3901  3901 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:39:53.216  3178  3273 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 18:39:53.216  3178  3273 D BluetoothAdapterProperties: mDiscovering is false
,08-29 18:39:53.216  1015  1475 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 18:39:53.216  3178  3273 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 18:39:53.216  1015  1748 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:39:53.216  1015  1748 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 18:39:53.216  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:53.216  1015  1748 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.216  1015  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:53.216  1015  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:53.226  3178  3276 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 18:39:53.226  3178  3178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ba0e672, channel: 5, state: LISTENING
,08-29 18:39:53.226  3178  3178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ba0e672, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ed2fd2f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37e50ac3mSocket: android.net.LocalSocket@2b9f2f40 impl:android.net.LocalSocketImpl@1eacce79 fd:FileDescriptor[76]
08-29 18:39:53.226  3178  3178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2b9f2f40 impl:android.net.LocalSocketImpl@1eacce79 fd:FileDescriptor[76]
,08-29 18:39:53.236  3178  3178 I BtOppRfcommListener: stopping Accept Thread
08-29 18:39:53.236  3178  3276 D BluetoothAdapterProperties: Scan Mode:20
,08-29 18:39:53.236  3178  3178 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2112f7be, channel: 12, state: LISTENING
08-29 18:39:53.236  3178  3178 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2112f7be, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32c65841, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3783901fmSocket: android.net.LocalSocket@fe7ff6c impl:android.net.LocalSocketImpl@2f22d935 fd:FileDescriptor[81]
08-29 18:39:53.236  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:39:53.236  3178  3178 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@fe7ff6c impl:android.net.LocalSocketImpl@2f22d935 fd:FileDescriptor[81]
,08-29 18:39:53.236  3178  5143 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 18:39:53.236  3178  5143 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 18:39:53.236  3178  3273 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 18:39:53.236  3178  3273 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-29 18:39:53.236  3178  3273 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-29 18:39:53.236  3178  3273 E bt-btif : cmd socket is not created
,08-29 18:39:53.236  3178  3294 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-29 18:39:53.236  3178  3294 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 18:39:53.236  6901  7039 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@29ac03a4, channel: -1, state: INIT
08-29 18:39:53.236  6901  7039 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@29ac03a4, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c31b50d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b623cc2mSocket: android.net.LocalSocket@37632ad3 impl:android.net.LocalSocketImpl@3e77b610 fd:FileDescriptor[121]
08-29 18:39:53.236  6901  7039 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37632ad3 impl:android.net.LocalSocketImpl@3e77b610 fd:FileDescriptor[121]
,08-29 18:39:53.236  6901  7039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1350)
,08-29 18:39:53.236  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:53.236  3178  3273 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 18:39:53.236  3178  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:39:53.246  3178  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:39:53.246  3178  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:39:53.246  3178  3178 V BluetoothOppManager: cleanUp...
,08-29 18:39:53.246  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 18:39:53.246  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 18:39:53.246  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-29 18:39:53.246  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.246  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.246  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 18:39:53.246  3901  3901 D BluetoothPbap: Proxy object disconnected
08-29 18:39:53.246  3901  3901 D PbapServerProfile: Bluetooth service disconnected
,08-29 18:39:53.256  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:39:53.256  3901  3901 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 18:39:53.266  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:39:53.266  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 18:39:53.266  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 18:39:53.266  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:53.266  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:53.266  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:53.266  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:53.286  7047  7047 E Zygote  : MountEmulatedStorage(),
08-29 18:39:53.286  7047  7047 E Zygote  : v2
,08-29 18:39:53.286  1015  1495 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7047 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,08-29 18:39:53.286  7047  7047 I libpersona: KNOX_SDCARD checking this for 10055
08-29 18:39:53.286  7047  7047 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:53.286  7047  7047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 18:39:53.286  7047  7047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:53.296  7047  7047 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:53.316   304   304 I art     : Explicit concurrent mark sweep GC freed 8684(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 22.513ms
,08-29 18:39:53.326   276   954 D CommandListener: Clearing all IP addresses on wlan0,
08-29 18:39:53.326  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
08-29 18:39:53.326  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 18:39:53.326  2003  3019 V NativeCrypto: Read error: ssl=0xb89688f0: I/O error during system call, Connection timed out
,08-29 18:39:53.326  2003  3019 V NativeCrypto: SSL shutdown failed: ssl=0xb89688f0: I/O error during system call, Broken pipe
08-29 18:39:53.326  2003  3019 E GCM     : Wifi connection closed with errorCode 20
08-29 18:39:53.336  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:53.336  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 18:39:53.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.336  1015  1478 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-29 18:39:53.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:53.336  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:39:53.336   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 18.252ms
08-29 18:39:53.336  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 18:39:53.346  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:53.346  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
08-29 18:39:53.346  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:39:53.346  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 18:39:53.346  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.346  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:39:53.346  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.346  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-29 18:39:53.346  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 18:39:53.346  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.346  7047  7047 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 18:39:53.346  7047  7047 D ActivityThread: Added TimaKeyStore provider
08-29 18:39:53.346  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:39:53.346  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 18:39:53.346  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:39:53.346  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-29 18:39:53.346  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:39:53.346  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 18:39:53.356  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-29 18:39:53.356  1015  1740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-11ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:39:53.356  1015  1740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-11ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:39:53.356  1015  1740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-29 18:39:53.356  1015  1740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:39:53.356  1015  1740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-29 18:39:53.356   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 16.970ms
08-29 18:39:53.356  1015  1740 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:39:53.356  1015  1740 I qtaguid : Tagging socket 319 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,08-29 18:39:53.356  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:39:53.356  1015  1740 I qtaguid : Untagging socket 319
08-29 18:39:53.356  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-29 18:39:53.356  1015  1740 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:39:53.376  1015  1028 I ActivityManager: Killing 6647:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-29 18:39:53.376  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 18:39:53.376  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 18:39:53.376  1015  1123 D WifiP2pService: P2pDisablingState
,08-29 18:39:53.376  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
08-29 18:39:53.376  1015  1123 D WifiP2pService: p2p socket connection lost
08-29 18:39:53.386  1015  1124 E WifiNative-wlan0: do suspend true
08-29 18:39:53.386  1015  1123 D WifiP2pService: P2pDisabledState
,08-29 18:39:53.386  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 18:39:53.386  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 18:39:53.386  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 18:39:53.386  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 18:39:53.386  1015  1046 D WifiDisplayController: disconnect
08-29 18:39:53.386  1015  1046 D WifiDisplayController: updateConnection
,08-29 18:39:53.386  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 18:39:53.386  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 18:39:53.386  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 18:39:53.386  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 18:39:53.386  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 18:39:53.386  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 18:39:53.396  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 18:39:53.406  1015  1495 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 18:39:53.406  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 18:39:53.416  7047  7047 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 18:39:53.436  3178  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 18:39:53.436  3178  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:39:53.436  3178  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:39:53.436  3178  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:39:53.436  3178  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:39:53.436  3178  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:39:53.436  3178  3294 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:39:53.436  3178  3294 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:39:53.436  3178  3294 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:39:53.436  3178  3294 W bt-btif : ag scb idx 1 not allocated
08-29 18:39:53.436  3178  3294 W bt-btif : ag scb idx 2 not allocated
08-29 18:39:53.436  3178  3294 E bt-btif : BTA AG is already disabled, ignoring ...
,08-29 18:39:53.436  3178  3345 I bt_userial_mct: exiting userial_read_thread
08-29 18:39:53.436  3178  3345 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-29 18:39:53.436  3178  3276 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 18:39:53.436  3178  3296 I bt_vendor: hw_epilog_process
08-29 18:39:53.436  3178  3276 D bt_userial_mct: userial_close
,08-29 18:39:53.436  3178  3276 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 18:39:53.446   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 18:39:53.456  7047  7047 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
08-29 18:39:53.456  7047  7047 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 18:39:53.456  7047  7047 D UserAnalysis: Create SecureDbHelper
,08-29 18:39:53.466  7047  7047 D IntelligenceServiceApplication: onCreate()
,08-29 18:39:53.466  1015  1478 I ActivityManager: Killing 6659:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-29 18:39:53.476  1015  1478 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 18:39:53.476  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:53.476  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:53.476  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:53.476  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:53.476  7047  7047 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 18:39:53.496  7069  7069 E Zygote  : MountEmulatedStorage()
,08-29 18:39:53.496  7069  7069 E Zygote  : v2
08-29 18:39:53.496  7069  7069 I libpersona: KNOX_SDCARD checking this for 10105
08-29 18:39:53.496  7069  7069 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:53.496  7069  7069 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:53.496  1015  1478 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7069 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-29 18:39:53.496  1015  1748 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 18:39:53.496  7069  7069 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:53.496  7047  7047 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 18:39:53.496  7069  7069 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 18:39:53.506  7047  7047 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 18:39:53.516  7069  7069 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:53.516  7069  7069 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:53.526  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 },
08-29 18:39:53.526  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-29 18:39:53.536  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:39:53.536  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:39:53.536  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.536  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.536  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.536  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:53.546  6901  6901 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 18:39:53.566   276   950 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-29 18:39:53.566   276   950 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-29 18:39:53.566  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.566  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 18:39:53.566  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:39:53.566  1015  1126 V NetworkStats: updateIfacesLocked()
,08-29 18:39:53.566  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 18:39:53.566  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-29 18:39:53.566   276   954 D CommandListener: Clearing all IP addresses on wlan0,
,08-29 18:39:53.566  1015  1740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-29 18:39:53.576  1015  1740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-29 18:39:53.576  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 18:39:53.576  1372  1372 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
,08-29 18:39:53.576  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.576  1015  1126 V NetworkStats: performPollLocked() took 13ms
08-29 18:39:53.576  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:53.576  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:39:53.576  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.576  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.576  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:53.576  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:53.576  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502],
,08-29 18:39:53.586  1172  1749 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 18:39:53.586  1015  1740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:39:53.586  1015  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:39:53.586  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:39:53.586  1015  1124 D SecContentProvider2: mCursor = null
08-29 18:39:53.586  1451  1451 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 18:39:53.586  1451  1451 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:39:53.586  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 18:39:53.586  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 18:39:53.586  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,08-29 18:39:53.586  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:53.586  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 18:39:53.586  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.586  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.586  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.586  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:53.596  4737  7027 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 18:39:53.596  1015  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-29 18:39:53.596  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 18:39:53.596  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-29 18:39:53.596  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 18:39:53.596  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 18:39:53.596  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:53.596  1172  1172 D HotspotTile: onReceive : 0, 0
08-29 18:39:53.596  3901  3901 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:53.596  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.596  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:53.596  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 18:39:53.606  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-29 18:39:53.606  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,08-29 18:39:53.606  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 18:39:53.606  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 18:39:53.606  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:39:53.606  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:39:53.606  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-29 18:39:53.606  1015  1121 V NetworkStats: updateIfacesLocked()
,08-29 18:39:53.606  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 18:39:53.606  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 18:39:53.606  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:53.606  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.606  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:39:53.606  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:53.606  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:53.606  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:39:53.606  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:39:53.606  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:39:53.606  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:39:53.606  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 18:39:53.606  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:39:53.606  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 18:39:53.616  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:39:53.616  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:39:53.616  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
08-29 18:39:53.616  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 18:39:53.616  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 18:39:53.616  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-29 18:39:53.616  1172  1172 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 18:39:53.616  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 18:39:53.616  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.616  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.616  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.616  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.616  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 18:39:53.616  1015  1121 V NetworkStats: performPollLocked() took 6ms
08-29 18:39:53.616  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.616  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:53.616  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:39:53.616  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:53.616  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:53.616  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:39:53.616  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:39:53.616  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:39:53.616  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:39:53.616  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:39:53.616  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:53.616  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:39:53.616  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-29 18:39:53.616  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-29 18:39:53.626  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 18:39:53.626  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.626  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.626  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:53.626  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 18:39:53.626  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.626  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.626  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:53.626  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:53.656   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 18:39:53.656   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 18:39:53.656  7069  7091 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 18:39:53.666   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 18:39:53.666   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 18:39:53.666  7069  7091 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 18:39:53.676  3178  3276 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 18:39:53.676  3178  3276 I bt_vendor: bluetooth satus is on
08-29 18:39:53.676  3178  3276 I bt_vendor: bt-vendor : resetting BT status
08-29 18:39:53.676  3178  3276 I bt_vendor: Starting hciattach daemon
08-29 18:39:53.676  3178  3276 I bt_vendor: try to set false
,08-29 18:39:53.676  3178  3276 I bt_vendor: Starting hciattach daemon
08-29 18:39:53.676  3178  3276 I bt_vendor: try to set false
,08-29 18:39:53.676  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.676  3178  3276 I bt_vendor: cleanup
,08-29 18:39:53.686  3178  3294 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-29 18:39:53.686  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 18:39:53.686  1372  1372 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 18:39:53.686  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.686  3178  3276 I GKI_LINUX: GKI_exit_task 0 done
08-29 18:39:53.686  3178  3276 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-29 18:39:53.686  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 18:39:53.686  3178  3273 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 18:39:53.686  3178  3273 D BtConfig.SecureMode: isSecureModeOn:false
08-29 18:39:53.686  3178  3273 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 18:39:53.686  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 18:39:53.686  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 18:39:53.686  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.686  3178  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 18:39:53.686  1015  1538 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:39:53.686  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 18:39:53.696  1015  1538 W ActivityManager: userId = 0, bbcId = -10000,
08-29 18:39:53.696  1015  1538 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.696  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:39:53.696  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-29 18:39:53.696  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:39:53.696  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 18:39:53.696  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-29 18:39:53.696  3178  3178 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 18:39:53.696  3178  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 18:39:53.696  3178  3178 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 18:39:53.696  3178  3178 D BtGatt.GattService: stop()
,08-29 18:39:53.696  3178  3178 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 18:39:53.696  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.696  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.696  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:39:53.696  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:39:53.696  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.696  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.696  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 18:39:53.696  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.696  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 18:39:53.696  3178  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 18:39:53.696  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:39:53.696  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:39:53.706  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.706  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.706  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:39:53.706  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.706  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 18:39:53.706  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 18:39:53.706  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 18:39:53.706  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 18:39:53.706  3178  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 18:39:53.706  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:39:53.706  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 18:39:53.706  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.706  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.706  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:39:53.706  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.706  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 18:39:53.706  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 18:39:53.706  3178  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-29 18:39:53.706  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:39:53.706  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 18:39:53.706  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:53.706  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.706  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:39:53.716  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-29 18:39:53.716  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 18:39:53.716  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 18:39:53.716  3178  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 18:39:53.716  1015  1335 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:39:53.716  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-29 18:39:53.716  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.716  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 18:39:53.716  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.716  1015  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.716  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:39:53.716  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 18:39:53.716  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 18:39:53.716  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.716  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:39:53.716  3178  3273 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-29 18:39:53.716  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 18:39:53.716  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.716  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.716  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.716  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:39:53.716  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.726  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.726  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-29 18:39:53.726  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 18:39:53.726  3178  3273 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService,
08-29 18:39:53.726  1015  1215 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:39:53.726  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-29 18:39:53.726  1015  1215 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.726  1015  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.726  1015  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:39:53.726  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 18:39:53.726  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:39:53.726  3178  3273 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 18:39:53.726  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:39:53.726  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:39:53.726  3178  3273 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:39:53.726  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.726  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 18:39:53.726  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 18:39:53.726  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 18:39:53.736  3178  3273 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 18:39:53.736  3178  3273 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 18:39:53.736  3178  3273 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 18:39:53.736  3178  3273 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 18:39:53.736  3178  3273 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 18:39:53.736  3178  3178 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-29 18:39:53.736  3178  3178 D HeadsetService: Received stop request...Stopping profile...,
08-29 18:39:53.736  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:39:53.736  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.736  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 18:39:53.736  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 18:39:53.736  3178  3178 D A2dpService: Received stop request...Stopping profile...
,08-29 18:39:53.736  3901  3901 D HeadsetProfile: Bluetooth service disconnected
,08-29 18:39:53.736  3178  3287 D A2dpStateMachine: Exit Disconnected: -1
,08-29 18:39:53.736  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.746  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.746  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.746  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:39:53.746  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-29 18:39:53.746  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 18:39:53.746  3901  3901 D BluetoothA2dp: Proxy object disconnected
08-29 18:39:53.746  3901  3901 D A2dpProfile: Bluetooth service disconnected
08-29 18:39:53.746  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.746  3178  3178 D HidService: Received stop request...Stopping profile...
08-29 18:39:53.746  3178  3178 D HidService: Stopping Bluetooth HidService
08-29 18:39:53.746  3178  3178 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 18:39:53.746  3178  3178 W bt-btif : cleanup: HH disabling or disabled already, status = 0,
08-29 18:39:53.746  3178  3178 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 18:39:53.746  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:39:53.746  3901  3901 D BluetoothInputDevice: Proxy object disconnected
08-29 18:39:53.746  3901  3901 D HidProfile: Bluetooth service disconnected
08-29 18:39:53.746  3178  3178 D HealthService: Received stop request...Stopping profile...
08-29 18:39:53.746  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 18:39:53.746  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:39:53.746  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 18:39:53.746  3178  3178 D PanService: Received stop request...Stopping profile...
08-29 18:39:53.756  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:39:53.756  1372  1372 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 18:39:53.756  3178  3178 D BluetoothMapService: Received stop request...Stopping profile...
08-29 18:39:53.756  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 18:39:53.756  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 18:39:53.756  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 18:39:53.756  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 18:39:53.756  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 18:39:53.756  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:39:53.756  3178  3178 D SapService: Received stop request...Stopping profile...
08-29 18:39:53.756  3178  3178 D SapService: Stopping Bluetooth SapService
08-29 18:39:53.756  3178  3178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:39:53.766  3901  3901 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 18:39:53.766  3901  3901 D PanProfile: Bluetooth service disconnected
,08-29 18:39:53.766  3178  3178 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 18:39:53.766  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 18:39:53.766  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 18:39:53.766  3178  3178 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 18:39:53.766  3178  3178 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 18:39:53.766  3178  3178 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-29 18:39:53.766  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 18:39:53.766  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 18:39:53.766  3178  3178 D BluetoothA2dp: Proxy object disconnected
08-29 18:39:53.766  3178  3178 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-29 18:39:53.766  3178  3288 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-29 18:39:53.766  3178  3178 I GKI_LINUX: GKI_exit_task 2 done
08-29 18:39:53.766  3178  3178 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-29 18:39:53.766  3178  3178 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 18:39:53.766  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 18:39:53.766  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 18:39:53.776  3901  3901 D BluetoothMap: Proxy object disconnected
08-29 18:39:53.776  3901  3901 D MapProfile: Bluetooth service disconnected
08-29 18:39:53.776  3901  3901 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 18:39:53.776  3901  3901 D SapProfile: Bluetooth service disconnected
,08-29 18:39:53.776  3178  3178 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 18:39:53.776  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 18:39:53.776  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 18:39:53.776  3178  3178 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 18:39:53.776  3178  3178 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 18:39:53.776  3178  3178 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 18:39:53.776  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 18:39:53.776  3178  3178 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 18:39:53.776  3178  3178 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 18:39:53.776  3178  3178 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 18:39:53.776  3178  3178 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-29 18:39:53.776  3178  3178 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 18:39:53.776  3178  3178 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-29 18:39:53.776  3178  3178 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-29 18:39:53.776  3178  3178 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 18:39:53.776  3178  3178 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 18:39:53.776  1372  1372 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-29 18:39:53.776  1372  1372 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 18:39:53.776  1372  1372 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-29 18:39:53.786  1372  1372 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 18:39:53.786  1372  1372 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 18:39:53.786  3178  3273 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-29 18:39:53.786  3178  3273 D BluetoothAdapterProperties: Setting state to 10
08-29 18:39:53.786  3178  3273 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 18:39:53.786  3178  3273 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 18:39:53.786  3178  3273 D BluetoothAdapterService: updateAdapterState state is 10
08-29 18:39:53.786  3178  3273 D BluetoothAdapterService: Autoconnection is available 
08-29 18:39:53.786  3178  3273 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 18:39:53.786  3178  3273 I BluetoothAdapterState: Entering OffState
,08-29 18:39:53.786  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:53.786  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:39:53.786  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 18:39:53.786  1015  1129 D Tethering: InitialState.processMessage what=4
,08-29 18:39:53.786  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:53.786  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:39:53.786  1015  1129 E Tethering: No numeric data
08-29 18:39:53.786  2003  2011 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:39:53.786  2003  2011 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:39:53.786  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 18:39:53.786  1015  1129 D Tethering: clearTetheredNotification()
,08-29 18:39:53.786  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 18:39:53.786  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:53.786  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.786  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 18:39:53.796  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 18:39:53.796  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 18:39:53.796  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 18:39:53.796  1172  1172 D HotspotTile: updateTetherState():false, false
08-29 18:39:53.796  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:53.796  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:39:53.796  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 18:39:53.796  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:39:53.796  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:39:53.796  3901  3909 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 18:39:53.796  3901  3918 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:39:53.796  3901  3918 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:39:53.796  6901  6915 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:39:53.796  6901  6915 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:39:53.796  6901  6915 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 18:39:53.796  6901  6915 D BluetoothLeAdvertiser: Exit stop advertising
08-29 18:39:53.796  6901  6915 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 18:39:53.796  6901  6915 D BluetoothLeScanner: Exiting stopAllScan
08-29 18:39:53.796  1015  1121 V NetworkStats: performPollLocked() took 6ms
08-29 18:39:53.796  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:53.796  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:53.796  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:53.796  1433  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 18:39:53.796  1433  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 18:39:53.796  3901  3917 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 18:39:53.806  3178  3191 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:39:53.806  3178  3191 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 18:39:53.806  1451  1690 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 18:39:53.806  1451  1690 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:39:53.806  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:39:53.806  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:39:53.806  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 18:39:53.806  1422  1440 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:39:53.806  1422  1440 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:39:53.806  1172  3272 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:39:53.806  1172  3272 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 18:39:53.806  3178  3365 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 18:39:53.806  3901  3909 D Bluetoothsap: onBluetoothStateChange: up=false
08-29 18:39:53.806  3901  3909 D Bluetoothsap: Unbinding service...
08-29 18:39:53.806  3901  3917 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 18:39:53.806  3901  3909 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 18:39:53.816  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 18:39:53.816  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 18:39:53.816  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 18:39:53.816  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-29 18:39:53.816  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 18:39:53.826  3178  3276 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 18:39:53.826  3178  3178 I GKI_LINUX: GKI_exit_task 1 done
08-29 18:39:53.826  3178  3178 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-29 18:39:53.826  3178  3178 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 18:39:53.826  1172  1172 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
,08-29 18:39:53.826  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 18:39:53.826  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:39:53.826  1172  1172 D BluetoothTile:  getBluetoothState : 10
,08-29 18:39:53.826  1172  1763 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
08-29 18:39:53.826  1172  1763 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
08-29 18:39:53.826  1172  1172 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
08-29 18:39:53.826  1172  1172 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
,08-29 18:39:53.826  1015  1477 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 18:39:53.826  3178  3178 I art     : System.exit called, status: 0
08-29 18:39:53.826  3178  3178 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 18:39:53.836  1015  1538 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-29 18:39:53.836  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 18:39:53.836  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 18:39:53.836  3901  3901 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:39:53.836  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:39:53.836  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 18:39:53.836  2003  2161 D BluetoothAdapter: 412910426: getState() :  mService = null. Returning STATE_OFF
,08-29 18:39:53.836  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:53.836  2003  2161 D BluetoothAdapter: 412910426: getState() :  mService = null. Returning STATE_OFF
08-29 18:39:53.836  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:39:53.836  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:53.836  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:53.836  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:39:53.836  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:39:53.836  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:39:53.836  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:39:53.836  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:39:53.836  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:39:53.836  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.836  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:53.836  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:53.896  1015  1335 I ActivityManager: Process com.android.bluetooth (pid 3178)(adj 0) has died(24,703)
,08-29 18:39:53.916  7069  7069 D StrictMode: StrictMode policy violation; ~duration=239 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 18:39:53.916  7069  7069 D StrictMode: StrictMode policy violation; ~duration=238 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:39:53.916  7069  7069 D StrictMode: StrictMode policy violation; ~duration=237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:39:53.916  7069  7069 D StrictMode: StrictMode policy violation; ~duration=235 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:39:53.916  7069  7069 D StrictMode: StrictMode policy violation; ~duration=231 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:39:53.916  7069  7069 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:39:53.916  7069  7069 D StrictMode: StrictMode policy violation; ~duration=190 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:39:53.916  7069  7069 D StrictMode: StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:39:53.916  7069  7069 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:39:53.926  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 18:39:53.926  1015  1477 I ActivityManager: Killing 6678:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
08-29 18:39:53.936  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-29 18:39:53.936  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:39:53.936  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 18:39:53.936  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:53.936  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:53.936  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 18:39:53.946  1631  1631 I Hs20UtilService: Starting #8
08-29 18:39:53.946  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 18:39:53.946  1631  1727 I Hs20UtilService: Message received 5007
08-29 18:39:53.946  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 18:39:53.946  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 18:39:53.956  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 18:39:53.956  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 18:39:53.956  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 18:39:53.956  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 18:39:53.956  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 18:39:53.956  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 18:39:53.966  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 18:39:53.966  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 18:39:53.966  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 18:39:53.966  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 18:39:53.966  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 18:39:53.966  1015  1218 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-29 18:39:53.966  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:53.966  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:53.966  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:53.966  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:53.986  7122  7122 E Zygote  : MountEmulatedStorage()
08-29 18:39:53.986  7122  7122 E Zygote  : v2
08-29 18:39:53.986  7122  7122 I libpersona: KNOX_SDCARD checking this for 10064
08-29 18:39:53.986  7122  7122 I libpersona: KNOX_SDCARD not a persona
08-29 18:39:53.986  7122  7122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:53.986  7069  7118 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-29 18:39:53.986  7122  7122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:53.986  1015  1218 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7122 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 18:39:53.986  7122  7122 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:53.996  1372  1372 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 18:39:54.006  1015  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:54.006  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.006  7122  7122 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 18:39:54.006  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:39:54.016  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-29 18:39:54.016  7122  7122 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:54.026  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:54.026  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:39:54.026  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 18:39:54.026  7122  7122 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 18:39:54.026  1372  1372 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 18:39:54.046  7122  7122 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 18:39:54.046  7122  7122 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 18:39:54.076  7122  7122 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 18:39:54.076  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-29 18:39:54.076  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:54.076  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.076  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.076  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:54.086  7139  7139 E Zygote  : MountEmulatedStorage()
08-29 18:39:54.086  1015  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7139 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 18:39:54.086  7139  7139 E Zygote  : v2
08-29 18:39:54.086  1015  1027 I ActivityManager: Killing 6699:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-29 18:39:54.086  7139  7139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:54.086  7139  7139 I libpersona: KNOX_SDCARD checking this for 10065
08-29 18:39:54.086  7139  7139 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:54.096  7139  7139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:54.096  7139  7139 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:54.106  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:39:54.106  7139  7139 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:54.106  7139  7139 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:54.106  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-29 18:39:54.116  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:54.126  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:54.136  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-29 18:39:54.136  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 18:39:54.136  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:39:54.136  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 18:39:54.136  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:54.136  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:54.136  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:54.136  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:54.146  2003  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:39:54.146  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 18:39:54.146  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-29 18:39:54.146  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:54.146  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 18:39:54.146  3901  3901 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:54.146  1172  1172 D HotspotTile: onReceive : 1, 0
,08-29 18:39:54.146  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:54.146  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:54.146  7139  7139 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 18:39:54.156  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.156  1015  1538 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:54.156  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-29 18:39:54.156  1015  1538 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-29 18:39:54.156  1015  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:54.156  1015  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.156  1015  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.156  1015  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:54.176  1015  1538 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7154 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
08-29 18:39:54.176  7154  7154 E Zygote  : MountEmulatedStorage()
08-29 18:39:54.176  7154  7154 E Zygote  : v2
08-29 18:39:54.176  7154  7154 I libpersona: KNOX_SDCARD checking this for 10102
08-29 18:39:54.176  7154  7154 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:54.176  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:54.176  1015  1538 I ActivityManager: Killing 6628:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-29 18:39:54.176  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:54.176  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 18:39:54.196  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:54.196  7154  7154 D ActivityThread: Added TimaKeyStore provider,
,08-29 18:39:54.206  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:39:54.206  7154  7154 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 18:39:54.416   288   288 E SMD     : DCD OFF
,08-29 18:39:54.446  7154  7174 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-29 18:39:54.446  7154  7174 I Babel_SMS: MmsConfig.loadMmsSettings
08-29 18:39:54.446  7154  7174 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-29 18:39:54.446  7154  7174 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 18:39:54.446   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 18:39:54.476  7154  7174 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-29 18:39:54.476  7154  7174 I Babel_SMS: MmsConfig.loadFromResources
,08-29 18:39:54.486  7154  7174 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 18:39:54.486  7154  7174 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 18:39:54.496  1015  1475 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-29 18:39:54.496  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-29 18:39:54.496  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.496  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:54.496  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 18:39:54.516  7154  7154 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:39:54.526  7154  7154 I Babel_Crash: startup - clean
,08-29 18:39:54.556  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 18:39:54.556  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:39:54.556  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.556  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:39:54.556  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:39:54.556  1631  1631 I Hs20UtilService: Starting #9
,08-29 18:39:54.556  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 18:39:54.556  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 18:39:54.556  1631  1727 I Hs20UtilService: Message received 5007
08-29 18:39:54.556  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 18:39:54.566  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 18:39:54.566  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 18:39:54.566  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 18:39:54.566  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 18:39:54.566  7154  7154 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 18:39:54.576  1015  1538 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:39:54.576  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:39:54.576  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.576  1015  1538 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.576  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:39:54.576  1015  1335 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-29 18:39:54.576  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:54.576  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.576  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.576  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:54.576  1631  1631 I Hs20UtilService: Starting #10
,08-29 18:39:54.586  1631  1727 I Hs20UtilService: Message received 5011
,08-29 18:39:54.586  1015  1335 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7177 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 18:39:54.596  7177  7177 E Zygote  : MountEmulatedStorage()
08-29 18:39:54.596  7177  7177 I libpersona: KNOX_SDCARD checking this for 1000
08-29 18:39:54.596  7177  7177 E Zygote  : v2
08-29 18:39:54.596  7177  7177 I libpersona: KNOX_SDCARD not a persona
08-29 18:39:54.596  7177  7177 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:54.596  7177  7177 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:54.596  7177  7177 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:54.606  7154  7154 W AudioCapabilities: Unsupported mime audio/evrc
08-29 18:39:54.606  7154  7154 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 18:39:54.616  7154  7154 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-29 18:39:54.616  7154  7154 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-29 18:39:54.616  7154  7154 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-29 18:39:54.616  7154  7154 W AudioCapabilities: Unsupported mime audio/x-ima
,08-29 18:39:54.626  7154  7154 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 18:39:54.626  7177  7177 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:54.626  7154  7154 W AudioCapabilities: Unsupported mime audio/evrc
08-29 18:39:54.626  7177  7177 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:54.636  7154  7154 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 18:39:54.636  7154  7154 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 18:39:54.646  7154  7154 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-29 18:39:54.646  7154  7154 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 18:39:54.656  1015  1043 D Tethering: interfaceRemoved wlan0
08-29 18:39:54.656  7154  7154 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 18:39:54.656  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 18:39:54.656  7154  7154 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-29 18:39:54.656  7154  7154 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-29 18:39:54.656  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 18:39:54.656  7154  7154 W VideoCapabilities: Unsupported mime video/mp43
,08-29 18:39:54.666  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 18:39:54.666  7177  7177 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 18:39:54.666  7154  7154 W VideoCapabilities: Unsupported mime video/sorenson
,08-29 18:39:54.666  7177  7177 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 18:39:54.666  1015  1215 I ActivityManager: Killing 6719:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-29 18:39:54.666  7154  7154 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 18:39:54.676  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.676  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.676  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.676  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.676  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.676  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.686  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.686  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.686  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.686  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.686  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.686  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.686  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.686  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.686  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.696  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.696  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.696  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.696  7154  7154 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 18:39:54.696  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.696  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.696  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.696  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.706  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.706  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.706  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.706  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.706  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.706  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.706  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.706  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.716  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.716  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.716  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.716  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.716  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.716  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.716  7154  7154 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 18:39:54.716  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.716  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.716  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.726  7154  7154 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 18:39:54.726  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.726  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.726  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.726  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.726  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.726  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 18:39:54.726  7154  7154 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 18:39:54.736  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 18:39:54.736  7154  7154 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-29 18:39:54.736  1015  1538 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 18:39:54.736  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 18:39:54.736  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.736  1015  1538 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:54.736  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 18:39:54.736  1015  1478 I ActivityManager: Killing 6738:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-29 18:39:54.736  7154  7154 I vclib   : onServiceConnected
,08-29 18:39:54.746  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:39:54.746  3901  3901 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 18:39:54.746  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:39:54.746  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 18:39:54.756  1015  1335 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-29 18:39:54.756  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.756  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.756  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.756  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:54.766  7194  7194 E Zygote  : MountEmulatedStorage()
,08-29 18:39:54.766  7194  7194 E Zygote  : v2
08-29 18:39:54.766  7194  7194 I libpersona: KNOX_SDCARD checking this for 1002
08-29 18:39:54.766  7194  7194 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:54.766  7194  7194 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:54.766  7194  7194 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:54.766  1015  1335 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7194 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-29 18:39:54.776  7194  7194 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:54.796  7194  7194 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:54.796  7194  7194 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:54.806  7194  7194 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 18:39:54.806  7194  7194 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 18:39:54.836  7194  7194 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 18:39:54.846  1015  1043 D Tethering: interfaceRemoved p2p0
,08-29 18:39:54.846  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 18:39:54.866  7194  7194 D BtSettings.ProfileConfig: Adding GattService
,08-29 18:39:54.866  7194  7194 D BtSettings.ProfileConfig: Adding HeadsetService
08-29 18:39:54.866  7194  7194 D BtSettings.ProfileConfig: Adding A2dpService
,08-29 18:39:54.866  7194  7194 D BtSettings.ProfileConfig: Adding HidService
08-29 18:39:54.866  7194  7194 D BtSettings.ProfileConfig: Adding HealthService
08-29 18:39:54.866  7194  7194 D BtSettings.ProfileConfig: Adding PanService
,08-29 18:39:54.866  7194  7194 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-29 18:39:54.866  7194  7194 D BtSettings.ProfileConfig: Adding SapService
08-29 18:39:54.866  7194  7194 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-29 18:39:54.876  7194  7194 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-29 18:39:54.876  7194  7194 D BtSettings.ProfileConfig: Adding SapClientService
,08-29 18:39:54.876  7194  7194 D BtSettings.ProfileConfig: Adding HidDevService
08-29 18:39:54.876  7194  7194 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 18:39:54.876  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-29 18:39:54.876  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:39:54.876  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.876  1015  1476 D SettingsProvider: selectionArgs: false
08-29 18:39:54.876  1015  1476 D SettingsProvider: selectionArgs: 1002
08-29 18:39:54.876  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:39:54.876  1015  1476 D SettingsProvider: ret = -1
,08-29 18:39:54.876  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-29 18:39:54.876  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:39:54.876  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.876  1015  1475 D SettingsProvider: selectionArgs: false
08-29 18:39:54.876  1015  1475 D SettingsProvider: selectionArgs: 1002
08-29 18:39:54.876  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:39:54.876  1015  1475 D SettingsProvider: ret = -1
,08-29 18:39:54.876  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-29 18:39:54.876  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 18:39:54.876  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.876  1015  1495 D SettingsProvider: selectionArgs: false
08-29 18:39:54.876  1015  1495 D SettingsProvider: selectionArgs: 1002
08-29 18:39:54.876  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 18:39:54.876  1015  1495 D SettingsProvider: ret = -1
08-29 18:39:54.876  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-29 18:39:54.876  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:39:54.876  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.876  1015  1478 D SettingsProvider: selectionArgs: false
08-29 18:39:54.876  1015  1478 D SettingsProvider: selectionArgs: 1002
08-29 18:39:54.876  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 18:39:54.876  1015  1478 D SettingsProvider: ret = -1
08-29 18:39:54.876  1015  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-29 18:39:54.876  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:39:54.876  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.876  1015  1477 D SettingsProvider: selectionArgs: false
08-29 18:39:54.876  1015  1477 D SettingsProvider: selectionArgs: 1002
08-29 18:39:54.876  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:39:54.876  1015  1477 D SettingsProvider: ret = -1
,08-29 18:39:54.876  1015  1538 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-29 18:39:54.876  1015  1538 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:39:54.876  1015  1538 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.876  1015  1538 D SettingsProvider: selectionArgs: false,
08-29 18:39:54.876  1015  1538 D SettingsProvider: selectionArgs: 1002,
08-29 18:39:54.876  1015  1538 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:39:54.876  1015  1538 D SettingsProvider: ret = -1
08-29 18:39:54.886  1015  1215 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-29 18:39:54.886  1015  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:39:54.886  1015  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.886  1015  1215 D SettingsProvider: selectionArgs: false
08-29 18:39:54.886  1015  1215 D SettingsProvider: selectionArgs: 1002
08-29 18:39:54.886  1015  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 18:39:54.886  1015  1215 D SettingsProvider: ret = -1
08-29 18:39:54.886  1015  1218 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-29 18:39:54.886  1015  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:39:54.886  1015  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:39:54.886  1015  1218 D SettingsProvider: selectionArgs: false
08-29 18:39:54.886  1015  1218 D SettingsProvider: selectionArgs: 1002
08-29 18:39:54.886  1015  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:39:54.886  1015  1218 D SettingsProvider: ret = -1
08-29 18:39:54.886  1015  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:39:54.886  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:39:54.886  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.886  1015  1479 D SettingsProvider: selectionArgs: false
08-29 18:39:54.886  1015  1479 D SettingsProvider: selectionArgs: 1002,
08-29 18:39:54.886  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:39:54.886  1015  1479 D SettingsProvider: ret = -1
,08-29 18:39:54.886  1015  1748 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:39:54.886  1015  1748 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 18:39:54.886  1015  1748 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.886  1015  1748 D SettingsProvider: selectionArgs: false
,08-29 18:39:54.886  1015  1748 D SettingsProvider: selectionArgs: 1002
,08-29 18:39:54.886  1015  1748 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:39:54.886  1015  1748 D SettingsProvider: ret = -1
08-29 18:39:54.886  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-29 18:39:54.886  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 18:39:54.886  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.886  1015  1027 D SettingsProvider: selectionArgs: false
,08-29 18:39:54.886  1015  1027 D SettingsProvider: selectionArgs: 1002
08-29 18:39:54.886  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:39:54.906  1015  1476 I ActivityManager: Killing 6575:com.android.calendar/u0a131 (adj 15): empty #21
08-29 18:39:54.886  1015  1027 D SettingsProvider: ret = -1
08-29 18:39:54.886  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-29 18:39:54.886  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:39:54.886  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:39:54.886  1015  1028 D SettingsProvider: selectionArgs: false
08-29 18:39:54.886  1015  1028 D SettingsProvider: selectionArgs: 1002
08-29 18:39:54.886  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 18:39:54.886  1015  1028 D SettingsProvider: ret = -1
08-29 18:39:54.906  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 18:39:54.906  1015  1538 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:39:54.906  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 18:39:54.916  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.916  1015  1538 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:54.916  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:54.926  2003  7210 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 18:39:54.926  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 18:39:54.926  1015  1538 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 18:39:54.926  1015  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.926  1015  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.926  1015  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:54.926  1015  1538 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:54.946  7211  7211 E Zygote  : MountEmulatedStorage()
,08-29 18:39:54.946  7211  7211 I libpersona: KNOX_SDCARD checking this for 1000
08-29 18:39:54.946  7211  7211 E Zygote  : v2
08-29 18:39:54.946  7211  7211 I libpersona: KNOX_SDCARD not a persona
08-29 18:39:54.946  7211  7211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:54.946  1015  1538 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7211 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 18:39:54.946  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:54.956  7211  7211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:54.956  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:54.956  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:54.956  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:54.956  7211  7211 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:54.966  1015  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:54.976  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:54.976  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:54.976  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:54.986  2003  7210 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-29 18:39:54.986  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 18:39:54.986  7211  7211 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.016  7211  7211 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-29 18:39:55.016  7211  7211 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-29 18:39:55.016  7211  7211 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 18:39:55.026  7211  7211 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-29 18:39:55.026  7211  7211 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-29 18:39:55.026  7211  7211 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 18:39:55.026  7211  7211 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:39:55.026  1015  1495 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-29 18:39:55.026  7211  7226 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-29 18:39:55.036  1015  1495 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-29 18:39:55.036  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 18:39:55.046  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.046  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.046  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.046  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.056  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7228 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:39:55.056  7228  7228 E Zygote  : MountEmulatedStorage()
08-29 18:39:55.056  7228  7228 E Zygote  : v2
08-29 18:39:55.056  7228  7228 I libpersona: KNOX_SDCARD checking this for 10001
08-29 18:39:55.056  7228  7228 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:55.056  7228  7228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:55.066  7228  7228 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:55.066  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 18:39:55.066  1768  1768 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-29 18:39:55.066  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.066  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.066  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.066  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.066  7228  7228 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:55.076  7238  7238 E Zygote  : MountEmulatedStorage()
08-29 18:39:55.076  7238  7238 I libpersona: KNOX_SDCARD checking this for 10121
08-29 18:39:55.076  7238  7238 E Zygote  : v2
08-29 18:39:55.076  7238  7238 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:55.086  7238  7238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:55.086  7238  7238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 18:39:55.086  7238  7238 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:55.086  1015  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7238 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,08-29 18:39:55.086  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 18:39:55.096  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.096  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.096  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.096  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.096  2471  2485 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-29 18:39:55.106  7228  7228 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:55.106  7228  7228 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.106  7257  7257 E Zygote  : MountEmulatedStorage()
,08-29 18:39:55.106  7257  7257 E Zygote  : v2
08-29 18:39:55.106  7257  7257 I libpersona: KNOX_SDCARD checking this for 10031
08-29 18:39:55.106  7257  7257 I libpersona: KNOX_SDCARD not a persona
08-29 18:39:55.106  7238  7238 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:55.106  7257  7257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:55.106  7238  7238 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.116  7257  7257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:55.116  7257  7257 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 18:39:55.116  1015  1495 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7257 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-29 18:39:55.116  1768  1768 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 18:39:55.126  1768  1768 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-29 18:39:55.126  1768  1768 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-29 18:39:55.126  1768  1768 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 18:39:55.136  7257  7257 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:55.136  7257  7257 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.136  1768  1768 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 18:39:55.136  7238  7238 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
08-29 18:39:55.136  1768  1768 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
08-29 18:39:55.136  7238  7238 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 18:39:55.136  7238  7238 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 18:39:55.136  1015  1748 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-29 18:39:55.136  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.136  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.136  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.146  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.156  7238  7238 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:39:55.156  7273  7273 E Zygote  : MountEmulatedStorage()
08-29 18:39:55.156  7273  7273 E Zygote  : v2
08-29 18:39:55.156  7273  7273 I libpersona: KNOX_SDCARD checking this for 10077
08-29 18:39:55.156  7273  7273 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:55.156  7273  7273 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:55.156  1015  1748 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7273 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:39:55.166  7273  7273 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:55.166  7273  7273 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
08-29 18:39:55.166  7238  7238 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 18:39:55.176  7238  7238 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-29 18:39:55.176  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-29 18:39:55.176  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.176  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.176  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.176  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.186  7273  7273 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:55.186  7273  7273 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.186   304   304 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 28.239ms
,08-29 18:39:55.206   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.173ms
,08-29 18:39:55.226   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.122ms
,08-29 18:39:55.236  7290  7290 E Zygote  : MountEmulatedStorage(),
08-29 18:39:55.236  7290  7290 E Zygote  : v2
08-29 18:39:55.236  7290  7290 I libpersona: KNOX_SDCARD checking this for 10141,
08-29 18:39:55.236  1015  1495 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7290 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-29 18:39:55.236  7290  7290 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:55.236  1015  1495 I ActivityManager: Killing 6754:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-29 18:39:55.236  7290  7290 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:55.236  7290  7290 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:55.246  7290  7290 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:55.246  7257  7257 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-29 18:39:55.246  1015  1495 I ActivityManager: Killing 6795:com.sec.android.widgetapp.dualclockdigital/u0a89 (adj 15): empty #21
,08-29 18:39:55.266  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
08-29 18:39:55.266  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.266  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.266  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.266  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.266  7290  7290 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:55.266  7290  7290 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.276  7305  7305 E Zygote  : MountEmulatedStorage(),
,08-29 18:39:55.286  7305  7305 E Zygote  : v2
08-29 18:39:55.286  7305  7305 I libpersona: KNOX_SDCARD checking this for 1000
08-29 18:39:55.286  7305  7305 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:55.286  1015  1495 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7305 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 18:39:55.286  1015  1495 I ActivityManager: Killing 6824:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-29 18:39:55.286  7305  7305 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:55.286  7305  7305 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:55.286  7305  7305 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:55.296  1015  1748 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 18:39:55.296  2757  7311 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-29 18:39:55.296  2757  7311 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-29 18:39:55.296  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.296  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.296  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.296  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.296  2757  7311 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-29 18:39:55.296  2757  7311 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-29 18:39:55.306  2757  7311 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 18:39:55.306  7305  7305 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:55.306  7305  7305 D ActivityThread: Added TimaKeyStore provider
08-29 18:39:55.306  7290  7290 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-29 18:39:55.316  7290  7290 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 18:39:55.316  7290  7290 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 18:39:55.316  7290  7290 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 18:39:55.316  7321  7321 E Zygote  : MountEmulatedStorage()
08-29 18:39:55.316  7321  7321 I libpersona: KNOX_SDCARD checking this for 10032
08-29 18:39:55.316  7321  7321 E Zygote  : v2
08-29 18:39:55.316  7321  7321 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:55.316  7321  7321 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:55.316  7321  7321 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:55.316  7321  7321 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 18:39:55.316  1015  1748 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7321 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:39:55.346  7321  7321 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 18:39:55.346  7321  7321 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.356  7305  7305 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-29 18:39:55.396  1015  1094 V AlarmManager: waitForAlarm result :8
,08-29 18:39:55.406  7321  7337 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-29 18:39:55.406  7321  7337 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 18:39:55.406  7321  7337 D SPPClientService: PushLog.txt file is not deleted.
,08-29 18:39:55.406  7321  7337 D SPPClientService: PushLog.txt file is not deleted.
,08-29 18:39:55.406  7321  7337 D SPPClientService: ============PushLog. stop!
,08-29 18:39:55.446   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 18:39:55.466  7321  7321 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-29 18:39:55.466  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-29 18:39:55.466  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.466  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.466  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.466  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.486  7339  7339 E Zygote  : MountEmulatedStorage(),
08-29 18:39:55.486  7339  7339 E Zygote  : v2
08-29 18:39:55.486  7339  7339 I libpersona: KNOX_SDCARD checking this for 10036
08-29 18:39:55.486  7339  7339 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:55.486  7339  7339 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:55.486  7339  7339 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 18:39:55.486  1015  1475 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7339 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 18:39:55.486  7339  7339 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 18:39:55.486  1015  1475 I ActivityManager: Killing 6842:com.sec.android.widgetapp.digitalclock/u0a84 (adj 15): empty #21
08-29 18:39:55.486  1015  1748 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:55.486  1015  1748 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-29 18:39:55.486  1015  1748 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 18:39:55.486  1015  1748 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-29 18:39:55.486  1015  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-29 18:39:55.506  7305  7305 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-29 18:39:55.516  7339  7339 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:55.516  7339  7339 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.526  7305  7305 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-29 18:39:55.536  7305  7305 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:39:55.536  7305  7305 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 18:39:55.536  7305  7305 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-29 18:39:55.536  7305  7305 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-29 18:39:55.536  1015  1215 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-29 18:39:55.536  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.536  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.536  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.536  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.556  7339  7339 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@ab5c67c
,08-29 18:39:55.566  1015  1215 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7356 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:39:55.566  7356  7356 E Zygote  : MountEmulatedStorage()
08-29 18:39:55.566  7356  7356 I libpersona: KNOX_SDCARD checking this for 10008
08-29 18:39:55.566  7356  7356 E Zygote  : v2
08-29 18:39:55.566  7356  7356 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:55.566  7356  7356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:55.576  7339  7339 I SA      : [SSP] onCreated
08-29 18:39:55.576  7356  7356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:55.576  7356  7356 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 18:39:55.586  7339  7339 I SA      : [TPM] There is no property file
,08-29 18:39:55.596  7339  7339 I SA      : [SCU] isHaveSA() - false
,08-29 18:39:55.596  7339  7339 I SA      : [TPM] getModelProperty : null
08-29 18:39:55.596  7339  7339 I SA      : [TPM] getCSCProperty : null
,08-29 18:39:55.596  7339  7339 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-29 18:39:55.596  7339  7339 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-29 18:39:55.596  7339  7339 I SA      : [DM] TFT FEATURE: false
,08-29 18:39:55.596  7339  7339 I SA      : [DM] init START
,08-29 18:39:55.606  7356  7356 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:55.606  7356  7356 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.616  7339  7339 I SA      : [DM] This device is not a Vodafone
,08-29 18:39:55.616  1015  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-29 18:39:55.616  1015  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 18:39:55.616  1015  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 18:39:55.616  1015  1495 D BatteryService: stay LED for fully charged
08-29 18:39:55.616  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 18:39:55.616  7339  7339 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-29 18:39:55.616  7339  7339 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-29 18:39:55.616  7339  7339 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-29 18:39:55.616  7339  7339 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-29 18:39:55.626  1015  1015 I MotionRecognitionService: Plugged
08-29 18:39:55.626  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 18:39:55.626  7339  7339 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-29 18:39:55.626  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-29 18:39:55.626  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-29 18:39:55.626  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 18:39:55.626  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-29 18:39:55.626  7339  7339 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-29 18:39:55.636  7339  7339 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-29 18:39:55.636  7339  7339 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-29 18:39:55.636  7339  7339 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 18:39:55.636  7339  7339 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-29 18:39:55.636  7339  7339 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-29 18:39:55.636  7339  7339 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
08-29 18:39:55.636  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 18:39:55.636  7339  7339 I SA      : [SCU] isHaveSA() - false
08-29 18:39:55.636  7339  7339 I SA      : support phone number id : false
08-29 18:39:55.636  7339  7339 I SA      : [DM] Supports Ref Jpn : true
08-29 18:39:55.636  7339  7339 I SA      : [DM] init END
08-29 18:39:55.636  7339  7339 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 18:39:55.646  7339  7339 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-29 18:39:55.646  7339  7339 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 18:39:55.656  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 18:39:55.656  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:39:55.656  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:39:55.666  7321  7348 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-29 18:39:55.686  1015  1028 I ActivityManager: Killing 6859:com.sec.android.app.camera/u0a135 (adj 15): empty #21
,08-29 18:39:55.686  2856  2856 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 18:39:55 GMT+02:00 2016
,08-29 18:39:55.686  1015  1495 I ActivityManager: Killing 6126:com.android.mms/u0a41 (adj 15): empty #21
,08-29 18:39:55.686  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-29 18:39:55.696  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:55.696  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-29 18:39:55.696  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:55.696  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 18:39:55.696  2856  2856 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 18:39:55.706  2856  2856 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 18:39:55.706  2856  2856 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 18:39:55.706  2856  2856 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 18:39:55.706  2856  7377 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 18:39:55.706  1015  1218 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:39:55.706  2856  7377 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 18:39:55.726  2856  7377 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-29 18:39:55.726  1015  1218 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 18:39:55.726  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 18:39:55.726  2856  7377 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
08-29 18:39:55.726  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:55.726  1015  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:55.726  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 18:39:55.726  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-29 18:39:55.726  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.726  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.726  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:55.726  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:55.736  7339  7339 I SA      : [SLFUCHKMGR] constructor called
,08-29 18:39:55.736  7339  7339 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 18:39:55.736  7339  7339 I SA      : [OR] == isSIMCardReady false ==
,08-29 18:39:55.746  7380  7380 E Zygote  : MountEmulatedStorage()
08-29 18:39:55.746  7380  7380 E Zygote  : v2
08-29 18:39:55.746  7380  7380 I libpersona: KNOX_SDCARD checking this for 10110
08-29 18:39:55.746  7380  7380 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:55.746  7380  7380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:55.746  1015  1028 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7380 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:39:55.746  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 18:39:55.746  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 18:39:55.746  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:55.746  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:55.746  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-29 18:39:55.746  7380  7380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:55.746  7380  7380 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 18:39:55.756  2856  2856 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 18:39:55.756  7339  7339 I SA      : [SCU] == networkStateCheck == false
08-29 18:39:55.756  7339  7339 I SA      : [OR] onReceive END
,08-29 18:39:55.756  7154  7378 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 18:39:55.756  1015  1478 I ActivityManager: Killing 6073:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-29 18:39:55.766  1015  1478 I ActivityManager: Killing 5891:com.android.vending/u0a26 (adj 15): empty #21
,08-29 18:39:55.766  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
08-29 18:39:55.766  7380  7380 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:55.766  7380  7380 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:55.776  1015  1476 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:39:55.856  1015  1028 D CountryDetector: No listener is left
,08-29 18:39:55.866  1015  1495 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:39:55.866  1015  3354 D SSRM:n  : SIOP:: AP = 400
,08-29 18:39:55.946  1015  1218 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:39:55.976  1015  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 18:39:56.006  1015  1476 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-29 18:39:56.006  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:56.006  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:56.006  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:56.006  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:56.026  7404  7404 E Zygote  : MountEmulatedStorage()
08-29 18:39:56.026  7404  7404 E Zygote  : v2,
08-29 18:39:56.026  1015  1476 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7404 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-29 18:39:56.026  7404  7404 I libpersona: KNOX_SDCARD checking this for 10068
,08-29 18:39:56.026  7404  7404 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:56.036  7404  7404 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 18:39:56.036  7404  7404 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:56.036  7404  7404 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 18:39:56.056  1015  1477 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:39:56.056  7404  7404 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:56.056  7404  7404 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:56.076  7404  7404 D BadgeProvider: onCreate
,08-29 18:39:56.086  7404  7404 D BadgeProvider: DatabaseHelper
,08-29 18:39:56.096  7404  7414 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-29 18:39:56.106  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:39:56.116  7404  7414 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-29 18:39:56.116  7404  7414 D BadgeProvider: sendNotify, [notify] : null
08-29 18:39:56.116  7404  7414 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-29 18:39:56.116  7404  7414 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-29 18:39:56.116  7404  7414 D BadgeProvider: update, [UpdateCount] : 1
,08-29 18:39:56.116  1480  1480 D Launcher.Model: reloadBadges entered.
,08-29 18:39:56.126  1015  1478 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:39:56.136  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:39:56.136  1015  1218 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-29 18:39:56.136  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:56.136  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:56.136  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:56.136  1015  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:56.146  7422  7422 E Zygote  : MountEmulatedStorage(),
08-29 18:39:56.146  7422  7422 I libpersona: KNOX_SDCARD checking this for 10009
08-29 18:39:56.146  7422  7422 E Zygote  : v2
08-29 18:39:56.146  7422  7422 I libpersona: KNOX_SDCARD not a persona,
08-29 18:39:56.156  7422  7422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:56.156  7422  7422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:39:56.156  1015  1218 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7422 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-29 18:39:56.156  7422  7422 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-29 18:39:56.156  1015  1218 I ActivityManager: Killing 6807:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
,08-29 18:39:56.176  7422  7422 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:56.176  7422  7422 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:56.186  1015  1748 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 18:39:56.186  1015  1748 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 18:39:56.186  1015  1748 D SecContentProvider2: mCursor = null
,08-29 18:39:56.196  1015  1748 D WifiService: setWifiEnabled: true pid=6901, uid=10171
,08-29 18:39:56.196  1015  1748 W ActivityManager: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 18:39:56.196  1015  1748 W WifiService: Failed getting userId using ActivityManagerNative
08-29 18:39:56.196  1015  1748 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 18:39:56.196  1015  1748 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 18:39:56.196  1015  1748 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 18:39:56.196  1015  1748 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 18:39:56.196  1015  1748 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 18:39:56.196  1015  1748 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 18:39:56.196  1015  1748 D SettingsProvider: name = wifi_on
,08-29 18:39:56.206   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 18:39:56.206   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 18:39:56.216  7380  7438 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 18:39:56.216  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 18:39:56.226   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 18:39:56.226   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 18:39:56.226  7380  7438 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 18:39:56.246  7380  7380 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 18:39:56.246  7380  7380 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 18:39:56.246  7380  7380 I GAv4    :   adb logcat -s GAv4
,08-29 18:39:56.246   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 18:39:56.246   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 18:39:56.256  7380  7440 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 18:39:56.286   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/,
08-29 18:39:56.286   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 18:39:56.296  1015  1495 I art     : Explicit concurrent mark sweep GC freed 58993(3MB) AllocSpace objects, 6(144KB) LOS objects, 33% free, 25MB/37MB, paused 2.809ms total 181.745ms
,08-29 18:39:56.296  7380  7440 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 18:39:56.306  7380  7380 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 18:39:56.306  1015  1476 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 18:39:56.316  1015  1215 I ActivityManager: Killing 6597:com.samsung.android.sm/1000 (adj 15): empty #21
,08-29 18:39:56.316  7380  7380 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 18:39:56.336  1015  1028 I ActivityManager: Killing 6976:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-29 18:39:56.336  1015  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:39:56.336  7380  7444 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 18:39:56.336  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 18:39:56.346  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:56.346  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:56.346  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:39:56.366  4737  7446 I iu.SyncManager: SYNC; picasa accounts
,08-29 18:39:56.376  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-29 18:39:56.376  1015  1538 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-29 18:39:56.376  1015  1748 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-29 18:39:56.376  4737  4737 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-29 18:39:56.376  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-29 18:39:56.446   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 18:39:56.566  1015  1218 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:39:56.576  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:56.576  1015  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:39:56.576  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-29 18:39:56.616  7380  7380 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-29 18:39:56.616  1015  1043 D Tethering: interfaceAdded wlan0
,08-29 18:39:56.626  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:56.626  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:39:56.626  1015  1129 E Tethering: No numeric data,
08-29 18:39:56.626  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:39:56.626  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 18:39:56.626  1015  1129 D Tethering: clearTetheredNotification(),
08-29 18:39:56.626  1015  1129 D Tethering: InitialState.processMessage what=4
08-29 18:39:56.636  1015  1129 E Tethering: No numeric data
08-29 18:39:56.636  1015  1043 D Tethering: interfaceAdded p2p0
08-29 18:39:56.636  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 18:39:56.636  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:56.636  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 18:39:56.636  1172  1172 D HotspotTile: updateTetherState():false, false
08-29 18:39:56.636  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:39:56.636  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 18:39:56.636  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 18:39:56.636  1015  1129 D Tethering: clearTetheredNotification()
,08-29 18:39:56.636  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-29 18:39:56.636  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 18:39:56.636  1172  1172 D HotspotTile: updateTetherState():false, false
,08-29 18:39:56.636  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 18:39:56.636  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 18:39:56.636  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 18:39:56.636   276   954 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-29 18:39:56.636   276   954 D SoftapController: Softap fwReload - Ok
,08-29 18:39:56.646  1015  1121 V NetworkStats: performPollLocked() took 9ms
,08-29 18:39:56.646  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:56.646   276   954 D CommandListener: Setting iface cfg
08-29 18:39:56.646   276   954 D CommandListener: Trying to bring down wlan0
,08-29 18:39:56.646   276   954 D CommandListener: Clearing all IP addresses on wlan0
,08-29 18:39:56.646  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:56.646  1015  1121 V NetworkStats: performPollLocked(flags=0x1),
,08-29 18:39:56.646  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:39:56.646  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:56.646  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:56.646  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 18:39:56.646  1015  1121 V NetworkStats: performPollLocked() took 4ms
08-29 18:39:56.646  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 18:39:56.646  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:56.656  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:56.656  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:56.656  7380  7380 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 7267-7271)
08-29 18:39:56.656  7380  7380 I cr.library_loader: Expected native library version number "", actual native library version number "",
,08-29 18:39:56.666  7380  7380 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {136f6327}
,08-29 18:39:56.666  7380  7380 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 18:39:56.666  7380  7380 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 18:39:56.686  7380  7380 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 18:39:56.686  7380  7380 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-29 18:39:56.686  7380  7380 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-29 18:39:56.706  7380  7380 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-29 18:39:56.706  7380  7380 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 18:39:56.706  7380  7380 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 18:39:56.706  7380  7380 I Adreno-EGL: Local Branch: 
08-29 18:39:56.706  7380  7380 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 18:39:56.706  7380  7380 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 18:39:56.706  7380  7380 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 18:39:56.716  7468  7468 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-29 18:39:56.716  7468  7468 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 18:39:56.716  7468  7468 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 18:39:56.736  7468  7468 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-29 18:39:56.736   327   327 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7468
08-29 18:39:56.736   327   327 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-29 18:39:56.736  7468  7468 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 18:39:56.736  7468  7468 I wpa_supplicant: ssSupport state is = 1
08-29 18:39:56.736  7468  7468 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 18:39:56.736  7468  7468 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-29 18:39:56.736   327   327 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7468
08-29 18:39:56.736   327   327 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-29 18:39:56.756  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 18:39:56.756  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:56.756  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
08-29 18:39:56.756  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:56.756  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:56.756  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:56.756  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:56.756  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 18:39:56.756  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-29 18:39:56.756  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 18:39:56.756  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:56.756  1172  1172 D HotspotTile: onReceive : 2, 0
,08-29 18:39:56.756  3901  3901 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:56.766  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:56.766  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:39:56.776  7380  7482 W cr.media: Requires BLUETOOTH permission
,08-29 18:39:56.776  7380  7380 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 18:39:56.796  7380  7380 I NSApplication: Starting up...
08-29 18:39:56.796  1015  1748 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
08-29 18:39:56.796  1015  1477 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 18:39:56.806  1015  1335 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-29 18:39:56.806  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:56.806  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:56.806  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:56.806  1015  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:56.816  7487  7487 E Zygote  : MountEmulatedStorage()
,08-29 18:39:56.816  7487  7487 E Zygote  : v2
08-29 18:39:56.816  7487  7487 I libpersona: KNOX_SDCARD checking this for 10117
08-29 18:39:56.816  7487  7487 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:56.816  7487  7487 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:39:56.816  1015  1335 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7487 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
08-29 18:39:56.826  1015  1335 I ActivityManager: Killing 7122:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-29 18:39:56.826  7487  7487 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:56.826  7487  7487 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 18:39:56.846  7487  7487 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 18:39:56.846  7487  7487 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:56.866  7487  7487 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 18:39:56.926   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-29 18:39:56.926  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-29 18:39:56.976  7468  7468 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-29 18:39:56.976  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 18:39:56.986  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-29 18:39:56.986   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7468
,08-29 18:39:56.986   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 18:39:56.986  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 18:39:56.986  7468  7468 I wpa_supplicant: ssSupport state is = 1
08-29 18:39:56.986  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,08-29 18:39:56.996  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 18:39:56.996  7468  7468 E wpa_supplicant: SIM READ ERROR
08-29 18:39:56.996  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 18:39:56.996  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 18:39:56.996  7468  7468 E wpa_supplicant: SIM READ ERROR
,08-29 18:39:56.996  7468  7468 I wpa_supplicant: Blacklist: Clear (all) 
08-29 18:39:56.996  7468  7468 I wpa_supplicant: wpa_default_ap_write_once
08-29 18:39:56.996  7468  7468 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 18:39:56.996  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 18:39:56.996  7468  7468 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-29 18:39:56.996  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 18:39:56.996  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 18:39:56.996  7468  7468 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 18:39:56.996  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:56.996  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:39:56.996  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:39:57.086  7468  7468 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-29 18:39:57.206  1015  1748 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-29 18:39:57.206  1015  1748 I ActivityManager: Killing 7139:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-29 18:39:57.216  1015  1218 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:39:57.216  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:39:57.216  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:57.216  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:57.216  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:39:57.226  1631  1631 I Hs20UtilService: Starting #11
,08-29 18:39:57.226  1631  1727 I Hs20UtilService: Message received 5011
08-29 18:39:57.226  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 18:39:57.226  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 18:39:57.226  7177  7177 D SecurityLogAgent: StateMachine : Current State = 1
08-29 18:39:57.226  7177  7177 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-29 18:39:57.226  7468  7468 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 18:39:57.226  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 18:39:57.236  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-29 18:39:57.236   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7468
08-29 18:39:57.236   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 18:39:57.236  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 18:39:57.236  7468  7468 I wpa_supplicant: ssSupport state is = 1
,08-29 18:39:57.236  1015  1335 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 18:39:57.236  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:39:57.236  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:57.236  1015  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:57.236  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:39:57.246  1631  1631 I Hs20UtilService: Starting #12
,08-29 18:39:57.246  1631  1727 I Hs20UtilService: Message received 5011
,08-29 18:39:57.246  7468  7468 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 18:39:57.246  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 18:39:57.246  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 18:39:57.246  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 18:39:57.246  7177  7177 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 18:39:57.246  7177  7177 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 18:39:57.256  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-29 18:39:57.256   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7468
08-29 18:39:57.256   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 18:39:57.256  7468  7468 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 18:39:57.256  7468  7468 I wpa_supplicant: ssSupport state is = 1
08-29 18:39:57.256  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 18:39:57.256  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 18:39:57.256  7468  7468 E wpa_supplicant: SIM READ ERROR
08-29 18:39:57.256  7468  7468 I wpa_supplicant: wpa_default_ap_write_once
08-29 18:39:57.256  7468  7468 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 18:39:57.256  7468  7468 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 18:39:57.256  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 18:39:57.256  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 18:39:57.256  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 18:39:57.266  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 18:39:57.266  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 18:39:57.266  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 18:39:57.376  7468  7468 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-29 18:39:57.376  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 18:39:57.416   288   288 E SMD     : DCD OFF,
,08-29 18:39:57.446   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 18:39:57.456  7468  7468 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
,08-29 18:39:57.456  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-29 18:39:57.456  7468  7468 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 18:39:57.466  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-29 18:39:57.466  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-29 18:39:57.466  7468  7468 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-29 18:39:57.466  7468  7468 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 18:39:57.466  7468  7468 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 18:39:57.466  7468  7468 E wpa_supplicant: SIM READ ERROR,
08-29 18:39:57.466  7468  7468 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 18:39:57.486  7468  7468 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-29 18:39:57.496  7468  7468 I wpa_supplicant: Skip scan - bUseNetwork false,
08-29 18:39:57.496  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
08-29 18:39:57.496  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:57.496  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 18:39:57.496  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:57.496  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:57.496  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:57.496  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:57.506  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 18:39:57.506  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-29 18:39:57.506  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 18:39:57.506  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:57.506  1172  1172 D HotspotTile: onReceive : 3, 0
,08-29 18:39:57.506  3901  3901 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:57.516  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:39:57.516  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:57.516  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:39:57.516  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:39:57.516  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:39:57.516  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:57.516  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:39:57.516  1015  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 18:39:57.516  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:39:57.516  1015  1124 E WifiConfigStore: Not a HS20
,08-29 18:39:57.516  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:57.516  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:39:57.516  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 18:39:57.516  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 18:39:57.516  1631  1631 I Hs20UtilService: Starting #13
,08-29 18:39:57.516  1631  1727 I Hs20UtilService: Message received 5011
,08-29 18:39:57.526  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 18:39:57.526  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-29 18:39:57.526  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 18:39:57.526  7177  7177 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 18:39:57.526  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 18:39:57.526  7468  7468 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 18:39:57.526  7468  7468 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 18:39:57.526  7468  7468 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 18:39:57.526  7468  7468 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 18:39:57.526  7468  7468 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 18:39:57.526  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=,
08-29 18:39:57.526  7468  7468 I wpa_supplicant: First Scan Start
08-29 18:39:57.526  7468  7468 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 18:39:57.526  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
,08-29 18:39:57.526  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 18:39:57.526  1015  1124 I WifiNative-HAL: startHal
08-29 18:39:57.526  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d53d88c
08-29 18:39:57.526  1015  1124 I WifiNative-HAL: Could not start hal
,08-29 18:39:57.536  7154  7154 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:39:57.536  7177  7177 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 18:39:57.536  1015  1124 E WifiNative-wlan0: do suspend true
,08-29 18:39:57.536  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 18:39:57.536   276   954 D CommandListener: Setting iface cfg
08-29 18:39:57.536   276   954 D CommandListener: Trying to bring up p2p0
,08-29 18:39:57.536  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 18:39:57.536  1015  1123 D WifiP2pService: P2pEnablingState
,08-29 18:39:57.536  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-29 18:39:57.536  1015  1123 D WifiP2pService: P2p socket connection successful
08-29 18:39:57.536  1015  1123 D WifiP2pService: P2pEnabledState
,08-29 18:39:57.546  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-29 18:39:57.546  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 18:39:57.546  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:39:57.546  1015  1147 I WifiNative-HAL: startHal
08-29 18:39:57.546  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e1d59bc
08-29 18:39:57.546  1015  1147 I WifiNative-HAL: Could not start hal
08-29 18:39:57.546  1015  1147 E WifiScanningService: could not start HAL
08-29 18:39:57.546  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-29 18:39:57.546  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 18:39:57.546  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:39:57.546  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:39:57.546  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 18:39:57.546  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 18:39:57.546  1015  1124 E WifiNative-wlan0: invaild command id : 215
,08-29 18:39:57.546  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 18:39:57.546  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-29 18:39:57.546  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 18:39:57.556  1015  1046 D WifiDisplayController: disconnect
08-29 18:39:57.556  1015  1046 D WifiDisplayController: updateConnection
08-29 18:39:57.556  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-29 18:39:57.556  7468  7468 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-29 18:39:57.556  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,08-29 18:39:57.556  7468  7468 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 18:39:57.556  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:39:57.556  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 18:39:57.556  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 18:39:57.556  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-29 18:39:57.556  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
08-29 18:39:57.556  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
08-29 18:39:57.556  7468  7468 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 18:39:57.556  1015  1477 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 18:39:57.556  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,08-29 18:39:57.556  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 18:39:57.556  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 18:39:57.556  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 18:39:57.556  1015  1124 E WifiNative-wlan0: invaild command id : 215
,08-29 18:39:57.566  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-29 18:39:57.566  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 18:39:57.566  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:39:57.566  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,08-29 18:39:57.566  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  secondary type: null
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  wps: 0
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  grpcapab: 0
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  devcapab: 0
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  status: 3
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  wfdInfo: null
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-29 18:39:57.566  1015  1046 D WifiDisplayController:  SConnectInfo : null
08-29 18:39:57.566  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 18:39:57.566  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 18:39:57.566  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:39:57.566  1015  1124 D SecContentProvider2: mCursor = null
08-29 18:39:57.566  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 18:39:57.566  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 18:39:57.566  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 18:39:57.566  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 18:39:57.566  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 18:39:57.576  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-29 18:39:57.576  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:57.576  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:57.576  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:57.576  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:57.586  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 18:39:57.586  7517  7517 E Zygote  : MountEmulatedStorage(),
,08-29 18:39:57.586  7517  7517 E Zygote  : v2
08-29 18:39:57.586  7517  7517 I libpersona: KNOX_SDCARD checking this for 10064
08-29 18:39:57.586  7517  7517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:57.586  7517  7517 I libpersona: KNOX_SDCARD not a persona
08-29 18:39:57.586  1015  1475 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7517 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:39:57.586  1015  1123 D WifiP2pService: InactiveState
08-29 18:39:57.596  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
08-29 18:39:57.596  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 18:39:57.596  7468  7468 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 18:39:57.596  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
08-29 18:39:57.596  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 18:39:57.596  7517  7517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:57.596  7517  7517 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:57.616  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 18:39:57.616  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 18:39:57.616  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 18:39:57.616  7517  7517 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:57.616  7517  7517 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:57.636  7517  7517 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 18:39:57.646  7517  7517 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 18:39:57.656  7517  7517 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 18:39:57.686  7517  7517 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 18:39:57.696  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-29 18:39:57.696  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:57.696  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:57.696  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:39:57.696  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:39:57.716  7532  7532 E Zygote  : MountEmulatedStorage(),
08-29 18:39:57.716  7532  7532 E Zygote  : v2
08-29 18:39:57.716  7532  7532 I libpersona: KNOX_SDCARD checking this for 10065
,08-29 18:39:57.716  7532  7532 I libpersona: KNOX_SDCARD not a persona
,08-29 18:39:57.716  1015  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7532 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:39:57.716  7532  7532 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:39:57.716  1015  1028 I ActivityManager: Killing 7047:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-29 18:39:57.716  7532  7532 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:39:57.736  7532  7532 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:39:57.746   304   304 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 717us total 26.628ms
,08-29 18:39:57.746  7532  7532 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:39:57.746  7532  7532 D ActivityThread: Added TimaKeyStore provider
,08-29 18:39:57.766   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 699us total 19.952ms,
,08-29 18:39:57.776  7532  7532 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 18:39:57.776  1015  1477 I ActivityManager: Killing 7194:com.android.bluetooth/1002 (adj 15): empty #21
,08-29 18:39:57.786   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 671us total 19.571ms
,08-29 18:39:58.396  1015  1094 V AlarmManager: waitForAlarm result :8,
,08-29 18:39:58.446   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 18:39:58.726  7468  7468 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-29 18:39:58.726  7468  7468 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-29 18:39:58.726  7468  7468 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-29 18:39:58.726  7468  7468 I wpa_supplicant: Trying to associate with  'G700'
08-29 18:39:58.726  7468  7468 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-29 18:39:58.726  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-29 18:39:58.726  1015  7513 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 18:39:58.746  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:39:58.746  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:39:58.846  7468  7468 E wpa_supplicant: Cmd 35605 not handled
,08-29 18:39:58.846  7468  7468 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
08-29 18:39:58.846  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:58.846  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:39:58.846  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 18:39:58.846  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:39:58.846  7468  7468 I wpa_supplicant: Associated with F4.99.3E
,08-29 18:39:58.846  7468  7468 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 18:39:58.846  7468  7468 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 18:39:58.846  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-29 18:39:58.846  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-29 18:39:58.846  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 18:39:58.846  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-29 18:39:58.846  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-29 18:39:58.846  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 18:39:58.846  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 18:39:58.856  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 18:39:58.846  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 18:39:58.866  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 18:39:58.846  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-29 18:39:58.856  7468  7468 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 18:39:58.856  7468  7468 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-29 18:39:58.856  7468  7468 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 18:39:58.856  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 18:39:58.856  7468  7468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 18:39:58.856  7468  7468 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 18:39:58.856  7468  7468 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-29 18:39:58.856  7468  7468 I wpa_supplicant: Blacklist: Clear (temp) 
08-29 18:39:58.856  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 18:39:58.866  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:39:58.866  1015  1124 D SecContentProvider2: mCursor = null
08-29 18:39:58.866  1015  1129 E Tethering: No numeric data
,08-29 18:39:58.866  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 18:39:58.866  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-29 18:39:58.866  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-29 18:39:58.866  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 18:39:58.866  1015  1129 D Tethering: clearTetheredNotification()
,08-29 18:39:58.866  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 18:39:58.876  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 18:39:58.876  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:58.876  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 18:39:58.876  1172  1172 D HotspotTile: updateTetherState():false, false
08-29 18:39:58.876  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:39:58.876  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 18:39:58.876  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 18:39:58.876  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 18:39:58.876  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:39:58.876  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 18:39:58.876  1015  1121 V NetworkStats: performPollLocked() took 5ms
08-29 18:39:58.876  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:58.886  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:39:58.886  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:39:58.886  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:58.886  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:58.886  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:58.886  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:58.886  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 18:39:58.886  1015  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:39:58.886  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:39:58.896  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:58.896  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:58.896  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:39:58.896  1631  1631 I Hs20UtilService: Starting #14
,08-29 18:39:58.896  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:58.896  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:58.896  1631  1727 I Hs20UtilService: Message received 5007
,08-29 18:39:58.896  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 18:39:58.896  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 18:39:58.896  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 18:39:58.896  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 18:39:58.906  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 18:39:58.906  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 18:39:58.906  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 18:39:58.906  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 18:39:58.916   276   954 D CommandListener: Setting iface cfg,
,08-29 18:39:58.916  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,08-29 18:39:58.916  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 18:39:58.916  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:39:58.926  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 18:39:58.926  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:39:58.936  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:39:58.936  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 18:39:58.936  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:58.936  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:58.936  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:58.936  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:58.946  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 18:39:58.946  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:39:58.946  1015  1124 E WifiNative-wlan0: do suspend false
,08-29 18:39:58.956  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-29 18:39:58.956  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 18:39:59.166  7549  7549 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 18:39:59.176  7549  7549 I dhcpcd  : version 5.5.6 starting,
,08-29 18:39:59.176  7549  7549 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 18:39:59.216  1015  1477 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 18:39:59.216  1015  1477 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 18:39:59.216  1015  1477 D SecContentProvider2: mCursor = null
,08-29 18:39:59.216  1015  1477 D SettingsProvider: name = wifi_on,
08-29 18:39:59.216  1015  1477 D WifiService: setWifiEnabled: false pid=6901, uid=10171
,08-29 18:39:59.226  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-29 18:39:59.246  1015  1124 E WifiNative-wlan0: do suspend true,
,08-29 18:39:59.246  7549  7549 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-29 18:39:59.246  7549  7549 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,08-29 18:39:59.266  1015  1123 D WifiP2pService: InactiveState{ what=143375 },
08-29 18:39:59.266  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 18:39:59.266  7549  7549 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,08-29 18:39:59.266  7549  7549 I dhcpcd  : bssid match,
08-29 18:39:59.266  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:59.266  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:39:59.266  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.266  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.266  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.266  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.276   276   954 D CommandListener: Clearing all IP addresses on wlan0
,08-29 18:39:59.276  7549  7549 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127,
08-29 18:39:59.276  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:39:59.276  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:39:59.276  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:39:59.276  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-29 18:39:59.276   276   954 E Netd    : no such netId 503
08-29 18:39:59.276  1015  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-29 18:39:59.276  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 18:39:59.276  1015  1126 V NetworkStats: updateIfacesLocked()
08-29 18:39:59.276  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:59.276  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-29 18:39:59.276  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
08-29 18:39:59.276  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:39:59.276  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 18:39:59.286  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 18:39:59.286  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 18:39:59.286  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 18:39:59.286  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-29 18:39:59.286  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,08-29 18:39:59.286  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:39:59.286  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:39:59.286  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.286  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.286  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.286  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.286  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 18:39:59.296  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-29 18:39:59.296  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 18:39:59.296  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:59.296  1015  1126 V NetworkStats: performPollLocked() took 15ms
,08-29 18:39:59.296  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-29 18:39:59.296  1015  7547 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:39:59.296  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 18:39:59.296  1015  7547 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting,
08-29 18:39:59.296  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 18:39:59.296  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 18:39:59.296  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 18:39:59.296  1015  1123 D WifiP2pService: P2pDisablingState
08-29 18:39:59.296  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:39:59.296  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-29 18:39:59.296  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:39:59.296  1015  1123 D WifiP2pService: p2p socket connection lost
08-29 18:39:59.296  1015  1124 E WifiNative-wlan0: do suspend true,
08-29 18:39:59.296  1015  1123 D WifiP2pService: P2pDisabledState,
,08-29 18:39:59.296  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-29 18:39:59.296  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 18:39:59.296  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 18:39:59.296  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 18:39:59.306  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 18:39:59.306  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 18:39:59.306  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:59.306  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-29 18:39:59.306  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:59.306  1015  1046 D WifiDisplayController: disconnect
08-29 18:39:59.306  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:59.306  1015  1046 D WifiDisplayController: updateConnection
08-29 18:39:59.306  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:59.306  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 18:39:59.306  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:39:59.306  1015  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:39:59.306  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 18:39:59.306  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 18:39:59.306  1631  1631 I Hs20UtilService: Starting #15
,08-29 18:39:59.306  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 18:39:59.306  1015  1215 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 18:39:59.306  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 18:39:59.316  1631  1727 I Hs20UtilService: Message received 5007
,08-29 18:39:59.316  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 18:39:59.316  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 18:39:59.316  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 18:39:59.316  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 18:39:59.316  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 18:39:59.316  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 18:39:59.316  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 18:39:59.326  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 18:39:59.326  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 18:39:59.326  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 18:39:59.326  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 18:39:59.326  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 18:39:59.326  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 18:39:59.326  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 18:39:59.326  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-29 18:39:59.326  7517  7517 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 18:39:59.326  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
08-29 18:39:59.326  7517  7517 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 18:39:59.326  7517  7517 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 18:39:59.336   276   954 D CommandListener: Clearing all IP addresses on wlan0
,08-29 18:39:59.336  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:39:59.336  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:39:59.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.336  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:59.336  7532  7532 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 18:39:59.336  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 18:39:59.346  7468  7468 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 18:39:59.346  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:39:59.346  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:39:59.346  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.346  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 18:39:59.346  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.346  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:59.346  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:39:59.346  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:39:59.356  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:39:59.356  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-29 18:39:59.356  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:59.356  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.356  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:39:59.356  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:39:59.356  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 18:39:59.356  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-29 18:39:59.356  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 18:39:59.356  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:59.366  1172  1172 D HotspotTile: onReceive : 0, 0
08-29 18:39:59.366  3901  3901 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:39:59.366  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:39:59.366  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:59.366  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:39:59.366  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:39:59.366  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:39:59.366  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:39:59.366  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:39:59.366  1015  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:39:59.366  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:39:59.366  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:39:59.366  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:39:59.366  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:39:59.376  1631  1631 I Hs20UtilService: Starting #16
,08-29 18:39:59.376  1631  1727 I Hs20UtilService: Message received 5007
,08-29 18:39:59.376  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 18:39:59.376  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 18:39:59.376  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 18:39:59.376  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 18:39:59.376  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 18:39:59.376  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 18:39:59.376  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 18:39:59.386  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:39:59.386  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:39:59.386  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:39:59.386  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:39:59.386  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:39:59.386  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 18:39:59.386  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 18:39:59.396  7177  7177 D SecurityLogAgent: StateMachine : Current State = 1
08-29 18:39:59.396  7177  7177 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 18:39:59.396  1631  1631 I Hs20UtilService: Starting #17
08-29 18:39:59.396  1631  1727 I Hs20UtilService: Message received 5011
,08-29 18:39:59.406  7549  7549 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-29 18:39:59.486  7549  7549 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-29 18:39:59.566  7468  7468 I wpa_supplicant: Blacklist: Clear (all) ,
,08-29 18:39:59.606  7468  7468 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 18:39:59.606  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 18:39:59.606  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 18:39:59.606  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 18:39:59.626  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 18:39:59.626  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 18:39:59.636  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-29 18:39:59.636  1015  1129 D Tethering: InitialState.processMessage what=4
,08-29 18:39:59.636  7468  7468 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-29 18:39:59.636  7468  7468 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 18:39:59.636  7468  7468 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 18:39:59.636  7468  7468 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 18:39:59.636  7468  7468 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 18:39:59.636  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:59.636  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:39:59.646  1015  1129 E Tethering: No numeric data
,08-29 18:39:59.646  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:39:59.646  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 18:39:59.646  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:39:59.646  1015  1129 D Tethering: clearTetheredNotification()
08-29 18:39:59.646  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:39:59.646  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:39:59.646  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:59.646  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 18:39:59.656  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 18:39:59.656  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 18:39:59.656  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 18:39:59.656  1172  1172 D HotspotTile: updateTetherState():false, false
,08-29 18:39:59.656  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:59.656  1015  1121 V NetworkStats: performPollLocked() took 5ms
,08-29 18:39:59.656  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:39:59.656  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:39:59.806  1015  1041 W ProcessCpuTracker: Skipping unknown process pid 7549,
,08-29 18:39:59.836  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 18:39:59.836  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:39:59.836  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:39:59.936  7468  7468 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 18:39:59.986  1015  1094 V AlarmManager: waitForAlarm result :8
,08-29 18:39:59.996  1015  1476 I ActivityManager: Killing 7069:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-29 18:40:00.006  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:40:00.006  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:40:00.006  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 18:40:00.006  7468  7468 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 18:40:00.116  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-29 18:40:00.116  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 18:40:00.116  7154  7154 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:00.126  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:40:00.126  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 18:40:00.126  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:00.126  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:00.126  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:00.126  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:00.126  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 18:40:00.126  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-29 18:40:00.136  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 18:40:00.136  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:00.136  2003  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:00.146  3901  3901 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:00.146  1172  1172 D HotspotTile: onReceive : 1, 0
,08-29 18:40:00.156  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:00.156  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:00.156  1015  1215 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 18:40:00.156  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:40:00.156  1015  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:00.156  1015  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:00.156  1015  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:40:00.166  1631  1631 I Hs20UtilService: Starting #18
,08-29 18:40:00.166  1631  1727 I Hs20UtilService: Message received 5011
,08-29 18:40:00.176  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 18:40:00.176  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 18:40:00.176  7177  7177 D SecurityLogAgent: StateMachine : Current State = 1
08-29 18:40:00.176  7177  7177 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 18:40:00.416   288   288 E SMD     : DCD OFF,
,08-29 18:40:00.816   276   948 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-29 18:40:00.816  1015  1043 D Tethering: interfaceRemoved wlan0
,08-29 18:40:00.816  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 18:40:00.906  1015  1048 I PowerManagerService: [PWL] Off : 15s ago
,08-29 18:40:00.906  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-29 18:40:00.906  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 18:40:00.906  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=7296)
,08-29 18:40:00.946  1015  1043 D Tethering: interfaceRemoved p2p0
,08-29 18:40:00.946  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 18:40:01.796  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-29 18:40:02.226  6901  6955 D BluetoothAdapter: enable()
,08-29 18:40:02.236  1015  1748 W ActivityManager: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 18:40:02.236  1015  1748 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 18:40:02.236  1015  1748 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 18:40:02.236  1015  1748 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 18:40:02.236  1015  1748 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 18:40:02.236  1015  1748 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 18:40:02.236  1015  1748 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 18:40:02.236  1015  1748 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 18:40:02.236  1015  1748 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 18:40:02.236  1015  1748 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:02.236  1015  1748 D SettingsProvider: name = bluetooth_on
,08-29 18:40:02.246  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:02.246  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:02.246  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-29 18:40:02.246  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-29 18:40:02.256  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.256  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.256  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.256  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.266  7581  7581 E Zygote  : MountEmulatedStorage(),
08-29 18:40:02.276  7581  7581 E Zygote  : v2
,08-29 18:40:02.276  7581  7581 I libpersona: KNOX_SDCARD checking this for 1002
08-29 18:40:02.276  7581  7581 I libpersona: KNOX_SDCARD not a persona
,08-29 18:40:02.276  7581  7581 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:40:02.276  1015  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7581 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-29 18:40:02.276  7581  7581 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 18:40:02.286  7581  7581 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:40:02.306  7581  7581 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:40:02.306  7581  7581 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:02.326  7581  7581 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 18:40:02.326  7581  7581 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 18:40:02.346  7581  7581 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding GattService
,08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding HeadsetService
08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding A2dpService
,08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding HidService
08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding HealthService
08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding PanService
,08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding SapService
,08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding SapClientService
,08-29 18:40:02.386  7581  7581 D BtSettings.ProfileConfig: Adding HidDevService
08-29 18:40:02.386  7581  7581 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 18:40:02.386  1015  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
08-29 18:40:02.386  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 18:40:02.386  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:02.386  1015  1477 D SettingsProvider: selectionArgs: false
,08-29 18:40:02.386  1015  1477 D SettingsProvider: selectionArgs: 1002
,08-29 18:40:02.386  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 18:40:02.386  1015  1477 D SettingsProvider: ret = -1
,08-29 18:40:02.396  1015  1218 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-29 18:40:02.396  1015  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 18:40:02.396  1015  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:02.396  1015  1218 D SettingsProvider: selectionArgs: false
08-29 18:40:02.396  1015  1218 D SettingsProvider: selectionArgs: 1002
08-29 18:40:02.396  1015  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-29 18:40:02.396  1015  1218 D SettingsProvider: ret = -1
08-29 18:40:02.396  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-29 18:40:02.396  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.396  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:02.396  1015  1475 D SettingsProvider: selectionArgs: false
,08-29 18:40:02.396  1015  1475 D SettingsProvider: selectionArgs: 1002
08-29 18:40:02.396  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:02.396  1015  1475 D SettingsProvider: ret = -1
08-29 18:40:02.396  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-29 18:40:02.396  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.396  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:02.396  1015  1495 D SettingsProvider: selectionArgs: false
08-29 18:40:02.396  1015  1495 D SettingsProvider: selectionArgs: 1002
08-29 18:40:02.396  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-29 18:40:02.396  1015  1495 D SettingsProvider: ret = -1
08-29 18:40:02.396  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-29 18:40:02.396  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.396  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:02.396  1015  1478 D SettingsProvider: selectionArgs: false
08-29 18:40:02.396  1015  1478 D SettingsProvider: selectionArgs: 1002
08-29 18:40:02.396  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:02.396  1015  1478 D SettingsProvider: ret = -1
,08-29 18:40:02.396  1015  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-29 18:40:02.396  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.396  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:02.396  1015  1479 D SettingsProvider: selectionArgs: false
08-29 18:40:02.396  1015  1479 D SettingsProvider: selectionArgs: 1002,
08-29 18:40:02.396  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:02.396  1015  1479 D SettingsProvider: ret = -1
08-29 18:40:02.396  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-29 18:40:02.396  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.396  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:02.396  1015  1476 D SettingsProvider: selectionArgs: false
08-29 18:40:02.396  1015  1476 D SettingsProvider: selectionArgs: 1002
,08-29 18:40:02.396  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:02.396  1015  1476 D SettingsProvider: ret = -1
08-29 18:40:02.396  1015  1215 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-29 18:40:02.396  1015  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.396  1015  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:02.396  1015  1215 D SettingsProvider: selectionArgs: false
08-29 18:40:02.396  1015  1215 D SettingsProvider: selectionArgs: 1002
08-29 18:40:02.396  1015  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-29 18:40:02.396  1015  1215 D SettingsProvider: ret = -1
08-29 18:40:02.396  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService,
08-29 18:40:02.396  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.396  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:02.396  1015  1027 D SettingsProvider: selectionArgs: false
08-29 18:40:02.396  1015  1027 D SettingsProvider: selectionArgs: 1002
08-29 18:40:02.396  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-29 18:40:02.396  1015  1027 D SettingsProvider: ret = -1
08-29 18:40:02.396  1015  1748 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-29 18:40:02.396  1015  1748 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.396  1015  1748 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:02.396  1015  1748 D SettingsProvider: selectionArgs: false,
08-29 18:40:02.396  1015  1748 D SettingsProvider: selectionArgs: 1002
,08-29 18:40:02.396  1015  1748 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:02.396  1015  1748 D SettingsProvider: ret = -1
08-29 18:40:02.396  1015  1538 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-29 18:40:02.396  1015  1538 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 18:40:02.396  1015  1538 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:02.396  1015  1538 D SettingsProvider: selectionArgs: false
08-29 18:40:02.396  1015  1538 D SettingsProvider: selectionArgs: 1002
08-29 18:40:02.396  1015  1538 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 18:40:02.396  1015  1538 D SettingsProvider: ret = -1
08-29 18:40:02.396  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-29 18:40:02.396  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.396  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:02.396  1015  1028 D SettingsProvider: selectionArgs: false
08-29 18:40:02.396  1015  1028 D SettingsProvider: selectionArgs: 1002
08-29 18:40:02.406  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:02.406  1015  1028 D SettingsProvider: ret = -1
,08-29 18:40:02.416  7581  7581 D BluetoothAdapterState: make
,08-29 18:40:02.426  7581  7596 I BluetoothAdapterState: Entering OffState
08-29 18:40:02.426  7581  7581 I bluedroid: init
,08-29 18:40:02.426  7581  7581 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 18:40:02.426  7581  7581 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 18:40:02.426  7581  7581 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 18:40:02.426  7581  7581 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 18:40:02.436  7581  7581 E bt-btif : btif_fetch_local_ble_random_bdaddr,
08-29 18:40:02.436  7581  7581 I bluedroid: get_profile_interface socket
08-29 18:40:02.436  7581  7581 I bluedroid: get_profile_interface map_client
,08-29 18:40:02.436  7581  7599 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 18:40:02.436  7581  7581 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-29 18:40:02.436  7581  7599 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-29 18:40:02.436  7581  7599 E BluetoothServiceJni: populateRssiValuesNative
,08-29 18:40:02.436  7581  7599 I bluedroid: getModelRssiValues
08-29 18:40:02.436  7581  7599 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-29 18:40:02.436  7581  7599 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 18:40:02.436  7581  7599 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3),
,08-29 18:40:02.436  1015  1015 D SettingsProvider: name = bluetooth_name
,08-29 18:40:02.446  7581  7581 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:02.446  1015  1538 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-29 18:40:02.446  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:40:02.446  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:02.446  1015  1538 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.446  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:02.456  7581  7589 I bluedroid: config_hci_snoop_log
,08-29 18:40:02.456  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-29 18:40:02.456  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-29 18:40:02.456  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-29 18:40:02.456  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 18:40:02.456  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 18:40:02.466  7581  7581 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-29 18:40:02.466  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 18:40:02.466  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:02.476  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 18:40:02.476  7581  7596 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 18:40:02.476  7581  7596 D BluetoothAdapterProperties: Setting state to 11
,08-29 18:40:02.476  7581  7596 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 18:40:02.476  7581  7596 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 18:40:02.476  7581  7596 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 18:40:02.476  7581  7596 D BluetoothAdapterService: Autoconnection is available 
,08-29 18:40:02.476  7581  7596 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-29 18:40:02.486  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 18:40:02.486  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:02.486  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-29 18:40:02.486  7581  7596 D BluetoothSecureManager: getInstant: null
08-29 18:40:02.496  7581  7596 D BluetoothSecureManager: calling getMethod for getService
08-29 18:40:02.496  7581  7596 D BluetoothSecureManager: calling getService
08-29 18:40:02.496  7581  7596 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2e762f75
,08-29 18:40:02.496  1015  1479 D BluetoothSecureManagerService: isSecureModeEnabled
08-29 18:40:02.496  1015  1479 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-29 18:40:02.496  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 18:40:02.496  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 18:40:02.496  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:02.496  1172  1172 D BluetoothTile:  getBluetoothState : 11
,08-29 18:40:02.496  7581  7596 D BtConfig.SecureMode: isSecureModeOn:false
08-29 18:40:02.496  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 18:40:02.496  7581  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-29 18:40:02.496  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-29 18:40:02.496  7581  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-29 18:40:02.496  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 18:40:02.496  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:02.496  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 18:40:02.506  3901  3901 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:02.506  7581  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-29 18:40:02.506  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:40:02.506  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 18:40:02.506  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-29 18:40:02.506  7581  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-29 18:40:02.506  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 18:40:02.506  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 18:40:02.506  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.506  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:02.506  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:02.506  1015  1477 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 18:40:02.506  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 18:40:02.506  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.506  7581  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-29 18:40:02.506  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 18:40:02.516  7581  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-29 18:40:02.516  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 18:40:02.516  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:02.516  7581  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-29 18:40:02.516  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 18:40:02.516  7581  7596 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-29 18:40:02.516  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:40:02.516  7581  7596 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 18:40:02.516  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 18:40:02.516  7581  7596 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:02.516  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 18:40:02.516  7581  7596 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 18:40:02.516  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 18:40:02.516  7581  7596 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-29 18:40:02.526  3901  3901 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 18:40:02.526  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:02.526  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-29 18:40:02.526  7581  7596 D BluetoothBondStateMachine: make
,08-29 18:40:02.526  1015  1215 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 18:40:02.536  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 18:40:02.536  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 18:40:02.536  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-29 18:40:02.536  7581  7602 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 18:40:02.536  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.536  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:02.536  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.536  1015  1215 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.546  7603  7603 E Zygote  : MountEmulatedStorage()
08-29 18:40:02.546  1015  1215 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7603 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-29 18:40:02.546  7603  7603 E Zygote  : v2
08-29 18:40:02.546  7603  7603 I libpersona: KNOX_SDCARD checking this for 10055
08-29 18:40:02.546  7603  7603 I libpersona: KNOX_SDCARD not a persona
,08-29 18:40:02.546  7603  7603 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:40:02.546  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:02.546  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 18:40:02.546  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.546  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.546  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:02.546  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 18:40:02.546  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 18:40:02.546  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 18:40:02.546  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:40:02.546  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-29 18:40:02.546  7581  7581 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 18:40:02.546  7581  7581 D BtGatt.GattService: Received start request. Starting profile...
08-29 18:40:02.546  7581  7581 D BtGatt.GattService: start()
08-29 18:40:02.546  7581  7581 D BtGatt.GattService: start()
08-29 18:40:02.546  7581  7581 I bluedroid: get_profile_interface gatt
,08-29 18:40:02.556  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:40:02.556  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.556  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.556  7581  7581 D BtGatt.AdvertiseManager: advertise manager created
08-29 18:40:02.556  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:02.556  7603  7603 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:40:02.556  7603  7603 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 18:40:02.556  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 18:40:02.556  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 18:40:02.556  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 18:40:02.556  1015  1335 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:02.556  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:40:02.556  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.556  1015  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.556  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:40:02.556  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 18:40:02.556  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 18:40:02.556  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-29 18:40:02.556  1015  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:02.556  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 18:40:02.556  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.556  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.556  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:02.566  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 18:40:02.566  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 18:40:02.566  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 18:40:02.566  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:02.566  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 18:40:02.566  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.566  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.566  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:02.566  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 18:40:02.566  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 18:40:02.566  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 18:40:02.566  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:40:02.566  7581  7581 D BtGatt.GattService: mStartError = false
08-29 18:40:02.566  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:02.566  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
,08-29 18:40:02.576  7581  7581 D HeadsetService: Received start request. Starting profile...
08-29 18:40:02.576  7581  7581 D HeadsetService: start()
08-29 18:40:02.576  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.576  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.576  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:40:02.576  7581  7581 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 18:40:02.576  7581  7581 D HeadsetStateMachine: make
,08-29 18:40:02.576  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 18:40:02.576  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 18:40:02.576  7603  7603 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 18:40:02.576  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-29 18:40:02.576  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:02.576  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 18:40:02.576  7603  7603 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:02.576  7581  7581 E HeadsetStateMachine: # of Max HF connection is 2
08-29 18:40:02.576  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.576  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.576  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:02.576  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-29 18:40:02.576  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 18:40:02.576  7581  7596 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 18:40:02.576  1015  1335 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:02.576  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 18:40:02.586  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.586  1015  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.586  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:02.586  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 18:40:02.586  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 18:40:02.586  7581  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 18:40:02.586  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:02.586  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:02.586  7581  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:02.586  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 18:40:02.586  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 18:40:02.586  7581  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 18:40:02.586  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 18:40:02.586  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 18:40:02.586  7581  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-29 18:40:02.586  7581  7596 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-29 18:40:02.586  1015  1335 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-29 18:40:02.586  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 18:40:02.586  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:02.586  1015  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:02.586  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 18:40:02.596  1015  1478 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-29 18:40:02.596  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 18:40:02.596  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:02.596  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:02.596  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 18:40:02.596  7581  7581 I bluedroid: get_profile_interface handsfree
,08-29 18:40:02.616  7581  7581 I DualScoManager: Instantiating Dual Sco Manager
,08-29 18:40:02.616  7603  7603 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-29 18:40:02.616  7581  7581 I DualScoManager: Set HeadsetServiceHelper
,08-29 18:40:02.616  7581  7581 D BluetoothAtMessage: createCMTIContentObservers
,08-29 18:40:02.616  1015  1479 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-29 18:40:02.616  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:02.616  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:02.616  1015  1479 D SettingsProvider: selectionArgs: false
08-29 18:40:02.616  1015  1479 D SettingsProvider: selectionArgs: 1002
,08-29 18:40:02.616  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:02.616  1015  1479 D SettingsProvider: ret = -1
,08-29 18:40:02.616  7581  7622 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 18:40:02.626  7581  7581 D HeadsetService: mStartError = false
08-29 18:40:02.626  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:02.626  7581  7581 D A2dpService: Received start request. Starting profile...
08-29 18:40:02.626  7581  7581 D A2dpService: start()
,08-29 18:40:02.626  7581  7622 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-29 18:40:02.626  7581  7622 D HeadsetStateMachine: map size, before remove : 0
08-29 18:40:02.626  7581  7622 D HeadsetStateMachine: map size, after remove: 0
08-29 18:40:02.626  7581  7581 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 18:40:02.626  7581  7581 I bluedroid: get_profile_interface avrcp
,08-29 18:40:02.636  7581  7581 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 18:40:02.636  7581  7581 D Avrcp   : Initialize Media Controller
08-29 18:40:02.636  7581  7581 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 18:40:02.636  7581  7581 E Avrcp   : getActiveSessions
08-29 18:40:02.636  7581  7581 D Avrcp   : pick active media Controller
08-29 18:40:02.636  7581  7581 D Avrcp   : Get the active Media Controller 
,08-29 18:40:02.646  7603  7603 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-29 18:40:02.656  7603  7603 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 18:40:02.656  7603  7603 D UserAnalysis: Create SecureDbHelper
,08-29 18:40:02.656  7581  7581 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 18:40:02.656  7581  7624 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 18:40:02.656  7581  7581 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 18:40:02.656  7581  7581 D A2dpStateMachine: make
,08-29 18:40:02.666  7581  7581 I bluedroid: get_profile_interface a2dp
08-29 18:40:02.666  7603  7603 D IntelligenceServiceApplication: onCreate()
08-29 18:40:02.666  7581  7626 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 18:40:02.666  7581  7581 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 18:40:02.666  7581  7581 D A2dpService: mStartError = false,
08-29 18:40:02.666  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:40:02.666  7581  7625 D A2dpStateMachine: Enter Disconnected: -2
08-29 18:40:02.666  7581  7581 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 18:40:02.666  7581  7581 D HidService: Received start request. Starting profile...
08-29 18:40:02.666  7581  7581 D HidService: start()
08-29 18:40:02.666  7581  7581 I bluedroid: get_profile_interface hidhost
08-29 18:40:02.666  7581  7581 D HidService: setHidService(): set to: null
08-29 18:40:02.666  7581  7581 D HidService: mStartError = false
08-29 18:40:02.666  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:02.666  7581  7581 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 18:40:02.666  1015  1479 I ActivityManager: Killing 7211:com.sec.pcw.device/1000 (adj 15): empty #21
,08-29 18:40:02.666  7581  7581 D HealthService: Received start request. Starting profile...
08-29 18:40:02.666  7581  7581 D HealthService: start()
,08-29 18:40:02.676  7581  7581 I bluedroid: get_profile_interface health
,08-29 18:40:02.676  7581  7581 D HealthService: mStartError = false
08-29 18:40:02.676  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:40:02.676  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-29 18:40:02.676  7581  7581 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 18:40:02.676  7603  7603 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 18:40:02.676  7581  7581 D PanService: Received start request. Starting profile...
08-29 18:40:02.676  7581  7624 D BluetoothMediaBrowser: no now playing list
08-29 18:40:02.676  7581  7581 D PanService: start()
08-29 18:40:02.676  7581  7581 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 18:40:02.676  7581  7581 I bluedroid: get_profile_interface pan
,08-29 18:40:02.676  7581  7581 D PanService: mStartError = false
08-29 18:40:02.676  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-29 18:40:02.676  7581  7624 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-29 18:40:02.676  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:02.676  7603  7603 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 18:40:02.676  7581  7581 D BluetoothMapService: Received start request. Starting profile...
08-29 18:40:02.676  7581  7581 D BluetoothMapService: start()
,08-29 18:40:02.686  7581  7581 D BluetoothMapService: mStartError = false
08-29 18:40:02.686  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:02.686  7581  7581 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-29 18:40:02.686  7581  7581 D SapService: Received start request. Starting profile...
08-29 18:40:02.686  7581  7581 D SapService: start()
08-29 18:40:02.686  7581  7581 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 18:40:02.686  7581  7581 I bluedroid: get_profile_interface sap
08-29 18:40:02.686  7581  7581 D SapService: mStartError = false
08-29 18:40:02.686  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:02.686  7581  7581 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 18:40:02.686  1422  1440 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 18:40:02.686  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-29 18:40:02.686  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 18:40:02.686  1422  1440 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 18:40:02.686  7581  7581 D HeadsetStateMachine: Proxy object connected
08-29 18:40:02.686  7581  7581 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 18:40:02.686  7581  7581 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 18:40:02.686  7581  7622 D HeadsetStateMachine: Disconnected process message: 11
08-29 18:40:02.686  7581  7581 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-29 18:40:02.686  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 18:40:02.686  7581  7581 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 18:40:02.686  7581  7581 D BluetoothA2dp: Proxy object connected
08-29 18:40:02.686  7581  7581 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-29 18:40:02.686  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-29 18:40:02.686  7581  7622 D HeadsetStateMachine: Disconnected process message: 18
08-29 18:40:02.686  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-29 18:40:02.696  7581  7622 D HeadsetStateMachine: Disconnected process message: 10
,08-29 18:40:02.696  7581  7622 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 18:40:02.696  7581  7622 D HeadsetStateMachine: Disconnected process message: 11
08-29 18:40:02.696  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-29 18:40:02.696  1015  1748 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-29 18:40:02.696  7603  7603 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 18:40:02.696  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.696  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:02.696  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.696  1015  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:02.716  1015  1748 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7631 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-29 18:40:02.716  7631  7631 E Zygote  : MountEmulatedStorage()
08-29 18:40:02.716  7631  7631 E Zygote  : v2
08-29 18:40:02.716  7631  7631 I libpersona: KNOX_SDCARD checking this for 10105
08-29 18:40:02.716  7631  7631 I libpersona: KNOX_SDCARD not a persona
,08-29 18:40:02.716  7631  7631 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 18:40:02.716  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 18:40:02.716  7631  7631 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:40:02.716  7631  7631 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 18:40:02.736  7631  7631 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:40:02.736  7631  7631 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:02.746  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-29 18:40:02.746  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 18:40:02.756  7581  7596 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-29 18:40:02.756  7581  7596 I bluedroid: enable
,08-29 18:40:02.756  7581  7596 I bt_hci_bdroid: init
,08-29 18:40:02.756  7581  7646 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-29 18:40:02.756  7581  7596 I bt_vendor: bt-vendor : init
08-29 18:40:02.756  7581  7596 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 18:40:02.756  7581  7596 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 18:40:02.756  7581  7596 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-29 18:40:02.756  7581  7596 D bt_userial_mct: userial_init
08-29 18:40:02.756  7581  7596 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 18:40:02.756  7581  7596 I bt_vendor: Starting hciattach daemon
08-29 18:40:02.756  7581  7596 I bt_vendor: try to set false
,08-29 18:40:02.756  7581  7596 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 18:40:02.756  7581  7596 I bt_vendor: Starting hciattach daemon
08-29 18:40:02.756  7581  7596 I bt_vendor: try to set true
,08-29 18:40:02.776  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 18:40:02.826  7658  7658 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-29 18:40:02.836  7659  7659 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-29 18:40:02.856  7661  7661 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 18:40:02.866  7663  7663 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 18:40:02.876  7665  7665 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 18:40:02.876  7667  7667 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-29 18:40:02.896   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 18:40:02.896   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 18:40:02.896  7631  7666 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 18:40:02.906   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 18:40:02.906   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 18:40:02.906  7631  7666 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 18:40:03.056  7631  7631 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:40:03.056  7631  7631 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:40:03.056  7631  7631 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:40:03.056  7631  7631 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:40:03.056  7631  7631 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:40:03.056  7631  7631 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:40:03.056  7631  7631 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:40:03.056  7631  7631 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:40:03.056  7631  7631 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 18:40:03.056  1015  1477 I ActivityManager: Killing 7228:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
08-29 18:40:03.066  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 18:40:03.066  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 18:40:03.116  7631  7662 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 18:40:03.166  7679  7679 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-29 18:40:03.166  1015  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:40:03.166  7681  7681 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 18:40:03.176  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:03.176  1015  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:40:03.176  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 18:40:03.216  7581  7596 I bt_vendor: bluetooth satus is on
,08-29 18:40:03.216  7581  7648 D bt_userial_mct: userial_open(port:0)
,08-29 18:40:03.216  7581  7648 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 18:40:03.226  7581  7648 I bt_vendor: Done intiailizing UART
,08-29 18:40:03.226  7581  7648 I bt_vendor: Done intiailizing UART
,08-29 18:40:03.226  7581  7648 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,08-29 18:40:03.226  7581  7648 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-29 18:40:03.236  7581  7684 D bt_userial_mct: Entering userial_read_thread()
,08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_SAP
08-29 18:40:03.236  7581  7646 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 18:40:03.246  7581  7646 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 18:40:03.246  7581  7646 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 18:40:03.246  7581  7646 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 18:40:03.246  7581  7646 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 18:40:03.246  7581  7646 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-29 18:40:03.336  7581  7646 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-29 18:40:03.346  7581  7646 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4317ed1 
,08-29 18:40:03.346  7581  7646 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4317ed1 
,08-29 18:40:03.356  7581  7599 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-29 18:40:03.356  7581  7599 E bt-btif : Calling BTA_HhEnable
,08-29 18:40:03.366  7581  7599 E bt-btif :                : sec: 0x80_orig 1, psm 0x0013, proto_id 
,08-29 18:40:03.366  7581  7599 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-29 18:40:03.366  7581  7599 E BluetoothServiceJni: populateRssiValuesNative
08-29 18:40:03.366  7581  7599 I bluedroid: getModelRssiValues
08-29 18:40:03.366  7581  7599 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 18:40:03.366  7581  7599 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 18:40:03.366  7581  7599 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 18:40:03.366  1015  1015 D SettingsProvider: name = bluetooth_name
,08-29 18:40:03.366  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:03.376  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:03.376  7581  7599 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 18:40:03.376  7581  7599 D BluetoothAdapterProperties: Scan Mode:20
,08-29 18:40:03.376  7581  7599 D BluetoothAdapterProperties: Discoverable Timeout:120,
08-29 18:40:03.376  7581  7599 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-29 18:40:03.376  7581  7599 E bt-btif : HC lpm_result_cb ooth_enable_evt: btif_core_radio_ref_count:1
,08-29 18:40:03.376  7581  7599 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0,
08-29 18:40:03.376  7581  7599 E bt-btif : btif_sock_init: !radio_req && !rfc_init,
08-29 18:40:03.376  7581  7599 E bt-btif : btif_sock_init: !vhci_init,
08-29 18:40:03.376  7581  7599 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-29 18:40:03.386  7581  7684 E bt_mct  : hci lib postload completed
,08-29 18:40:03.386  7581  7599 D IOP_DB_BT: db_open: db_open : handle 3024252944l, read 13894 bytes onto local cache
,08-29 18:40:03.386  7581  7599 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-29 18:40:03.386  7581  7599 D IOP_DB_BT: db_query: result 1
,08-29 18:40:03.386  7581  7599 I         : iop_db_open: iop_db_open status 0
,08-29 18:40:03.386  7581  7599 D bte_conf: Device ID record 1 : primary
,08-29 18:40:03.386  7581  7599 D bte_conf:   vendorId            = 0075
,08-29 18:40:03.386  7581  7599 D bte_conf:   vendorIdSource      = 0001
08-29 18:40:03.386  7581  7599 D bte_conf:   product             = 0100
08-29 18:40:03.386  7581  7599 D bte_conf:   version             = 0200
08-29 18:40:03.386  7581  7599 D bte_conf:   clientExecutableURL = 
08-29 18:40:03.386  7581  7599 D bte_conf:   serviceDescription  = 
08-29 18:40:03.386  7581  7599 D bte_conf:   documentationURL    = 
08-29 18:40:03.386  7581  7599 D bte_conf: bte_load_did_conf no section named DID2.
08-29 18:40:03.386  7581  7599 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 18:40:03.396  7581  7596 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 18:40:03.396  7581  7596 D BluetoothAdapterProperties: ScanMode =  20
,08-29 18:40:03.396  7581  7596 D BluetoothAdapterProperties: State =  11
,08-29 18:40:03.396  1015  1478 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 18:40:03.396  7581  7596 D BluetoothAdapterProperties: Setting state to 12
08-29 18:40:03.396  7581  7596 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 18:40:03.406  7581  7599 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 18:40:03.406  7581  7599 D BluetoothAdapterProperties: Scan Mode:21
08-29 18:40:03.406  7581  7599 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 18:40:03.406  1015  1538 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-29 18:40:03.406  1015  1538 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:03.406  1015  1538 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:03.406  1015  1538 D SettingsProvider: selectionArgs: false
08-29 18:40:03.406  1015  1538 D SettingsProvider: selectionArgs: 1002
08-29 18:40:03.406  1015  1538 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:03.406  1015  1538 D SettingsProvider: ret = -1
,08-29 18:40:03.406  7581  7596 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 18:40:03.406  7581  7596 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 18:40:03.406  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:40:03.406  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.406  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:03.406  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:03.406  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:03.406  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:03.406  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:03.406  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:03.406  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:03.406  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 18:40:03.406  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.406  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.406  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.416   288   288 E SMD     : DCD OFF
,08-29 18:40:03.426  7581  7596 D BluetoothAdapterService: Autoconnection is available 
,08-29 18:40:03.426  7581  7596 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 18:40:03.426  7581  7596 D BluetoothAdapterService: starting service from this receiver
,08-29 18:40:03.426  1015  1538 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:03.426  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.426  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:03.426  1015  1538 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.426  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.426  7581  7596 I BluetoothAdapterState: Entering On State from state = 11
,08-29 18:40:03.426  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:03.426  7581  7600 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 18:40:03.436  3901  3918 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:03.436  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 18:40:03.436  7581  7581 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 18:40:03.436  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:03.436  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:03.436  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:03.436  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:03.436  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:03.436  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:03.436  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:03.436  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:03.436  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:03.436  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.436  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.436  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.436  3901  3918 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 18:40:03.436  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:03.446  2003  3916 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:03.446  2003  3916 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:03.446  3901  3917 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 18:40:03.446  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-29 18:40:03.446  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.446  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.446  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.446  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.446  7581  7581 I BluetoothPbapService: Handler(): got msg=1
,08-29 18:40:03.446  1015  1538 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 18:40:03.456  1422  1430 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:03.456  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 18:40:03.456  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:03.456  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:03.456  7581  7688 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 18:40:03.456  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:03.466  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-29 18:40:03.466  1422  1430 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 18:40:03.466  3901  3901 D HeadsetProfile: Bluetooth service connected
,08-29 18:40:03.466  3901  3917 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:03.466  3901  3917 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:03.466  1015  1045 D BluetoothPan: Binding service...
08-29 18:40:03.466  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 18:40:03.466  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.466  6901  6915 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:03.466  6901  6915 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:03.466  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 18:40:03.466  7581  7688 D BluetoothSocket: bindListen(): myUserId = 0
08-29 18:40:03.466  7581  7688 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:03.466  3901  3901 D BluetoothMap: Proxy object connected
08-29 18:40:03.466  3901  3901 D MapProfile: Bluetooth service connected
08-29 18:40:03.466  3901  3901 D BluetoothMap: getConnectedDevices()
08-29 18:40:03.466  1422  1430 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:03.476  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 18:40:03.476  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:03.476  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.476  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.476  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.476  1422  1430 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 18:40:03.476  7581  7688 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-29 18:40:03.476  7581  7688 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 18:40:03.476  7581  7688 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 18:40:03.476  7581  7688 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e3a9109
08-29 18:40:03.476  7581  7688 D BluetoothSocket: channel: 19
08-29 18:40:03.476  7581  7688 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-29 18:40:03.476  1451  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:03.476  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 18:40:03.476  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:03.476  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.476  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.476  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.476  1451  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 18:40:03.476  7581  7600 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:03.476  7581  7600 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:03.476  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:03.476  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 18:40:03.476  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 18:40:03.476  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:03.486  1433  1458 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:03.486  1433  1458 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:03.486  7631  7639 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:03.486  7631  7639 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:03.486  3901  3909 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 18:40:03.486  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-29 18:40:03.486  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.486  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:03.486  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.486  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.486  3901  3901 D BluetoothPbap: Proxy object connected
,08-29 18:40:03.486  1451  1690 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:03.486  1451  1690 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:03.486  3901  3901 D PbapServerProfile: Bluetooth service connected
,08-29 18:40:03.496  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:03.496  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:03.496  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 18:40:03.496  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 18:40:03.496  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 18:40:03.496  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.496  1422  7689 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:03.496  1015  1015 D BluetoothA2dp: Proxy object connected
08-29 18:40:03.496  1422  7689 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:03.496  1172  1202 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:03.496  1172  1202 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:03.496  3901  3917 D Bluetoothsap: onBluetoothStateChange: up=true
08-29 18:40:03.496  3901  3917 D Bluetoothsap: Binding service...
,08-29 18:40:03.496  3901  3917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 18:40:03.496  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-29 18:40:03.496  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.506  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:03.506  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:03.506  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.506  3901  3901 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-29 18:40:03.506  3901  3917 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 18:40:03.506  3901  3901 D SapProfile: Bluetooth service connected
,08-29 18:40:03.506  3901  3901 D Bluetoothsap: getConnectedDevices()
08-29 18:40:03.506  1422  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:03.506  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 18:40:03.506  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:03.506  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.506  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.506  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.506  1422  1440 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 18:40:03.506  3901  3909 D BluetoothPan: Binding service...
,08-29 18:40:03.516  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 18:40:03.516  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.516  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:03.516  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.516  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.516  3901  3901 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 18:40:03.516  3901  3901 D PanProfile: Bluetooth service connected
08-29 18:40:03.516  3901  3917 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 18:40:03.516  3901  3917 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:03.516  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 18:40:03.516  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.516  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.516  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.516  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.516  3901  3909 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 18:40:03.526  3901  3901 D BluetoothA2dp: Proxy object connected
08-29 18:40:03.526  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 18:40:03.526  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.526  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.526  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.526  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.526  3901  3901 D A2dpProfile: Bluetooth service connected
08-29 18:40:03.526  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 18:40:03.526  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 18:40:03.526  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:03.526  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-29 18:40:03.526  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 18:40:03.526  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-29 18:40:03.526  1422  1422 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@17748c55, true
,08-29 18:40:03.536  1422  1422 D BluetoothHeadset: registerMessageListener
,08-29 18:40:03.536  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0,
08-29 18:40:03.536  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 18:40:03.536  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:03.536  1172  1172 D BluetoothTile:  getBluetoothState : 12
,08-29 18:40:03.536  1015  1477 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 18:40:03.536  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:03.536  1015  1479 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 18:40:03.546  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 18:40:03.546  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:03.546  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:03.546  1015  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:40:03.546  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.546  7581  7589 D HeadsetService: registerMessageListener
,08-29 18:40:03.546  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.546  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:03.546  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:03.546  7581  7589 D HeadsetService: registerMessageListener
08-29 18:40:03.546  7581  7622 D HeadsetStateMachine: Disconnected process message: 70
08-29 18:40:03.546  7581  7622 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2d16af0e
,08-29 18:40:03.546  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param null,
08-29 18:40:03.546  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-29 18:40:03.556  3901  3901 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:03.556  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:03.556  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 18:40:03.556  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-29 18:40:03.556  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 18:40:03.556  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:03.556  3901  3901 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-29 18:40:03.566  3901  3901 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 18:40:03.566  3901  3901 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 18:40:03.566  3901  3901 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-29 18:40:03.566  7581  7622 D HeadsetStateMachine: Disconnected process message: 9
,08-29 18:40:03.566  7581  7622 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 18:40:03.566  7581  7692 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-29 18:40:03.576   281   281 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-29 18:40:03.576   281   281 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 18:40:03.576   281   281 V voice   : voice_set_parameters: exit with code(-2)
08-29 18:40:03.576   281   281 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 18:40:03.576   281   281 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 18:40:03.576   281   281 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 18:40:03.576   281   281 V audio_hw_primary: adev_set_parameters: exit
,08-29 18:40:03.576  7581  7622 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 18:40:03.576  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 18:40:03.576  7581  7692 D BluetoothSocket: bindListen(): myUserId = 0
08-29 18:40:03.576  7581  7692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:03.576  1015  1475 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 18:40:03.576  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-29 18:40:03.576  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.576  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.576  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 18:40:03.576  3901  3901 D BluetoothInputDevice: Proxy object connected
08-29 18:40:03.576  3901  3901 D HidProfile: Bluetooth service connected
08-29 18:40:03.576  7581  7692 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-29 18:40:03.576  7581  7692 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 18:40:03.576  7581  7692 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 18:40:03.576  7581  7692 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ed2fd2f
,08-29 18:40:03.576  7581  7692 D BluetoothSocket: channel: 5
,08-29 18:40:03.586  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:03.586  3901  3901 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 18:40:03.596  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:03.596  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 18:40:03.606  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:40:03.606  7581  7581 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 18:40:03.606  1015  1538 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:40:03.606  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.606  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:03.606  1015  1538 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:03.606  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:03.616  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:03.616  1015  1748 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 18:40:03.626  1015  1748 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 18:40:03.626  1015  1748 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:03.626  1015  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:03.626  1015  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:03.636  2003  7698 D EasyUnlockInitService: Handling intent for initializer IntentService.,
08-29 18:40:03.636  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 18:40:03.636  1015  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:40:03.636  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:03.636  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:40:03.646  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:03.646  1015  1479 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 18:40:03.656  1015  1335 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:40:03.666  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:03.666  1015  1335 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:40:03.666  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:03.666  7581  7702 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 18:40:03.666  7581  7702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:03.676  7581  7702 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-29 18:40:03.676  7581  7702 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 18:40:03.676  7581  7702 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 18:40:03.676  7581  7702 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32c65841
08-29 18:40:03.676  7581  7702 D BluetoothSocket: channel: 12
08-29 18:40:03.676  7581  7702 I BtOppRfcommListener: Accept thread started.
,08-29 18:40:03.676  2003  7698 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-29 18:40:05.266  6901  6955 D BluetoothAdapter: disable()
,08-29 18:40:05.266  1015  1538 D SettingsProvider: name = bluetooth_on
,08-29 18:40:05.276  7581  7596 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-29 18:40:05.276  7581  7596 D BluetoothAdapterProperties: Setting state to 13
08-29 18:40:05.276  7581  7596 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 18:40:05.276  7581  7596 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 18:40:05.276  7581  7596 D BluetoothAdapterService: updateAdapterState state is 13
,08-29 18:40:05.276  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:05.276  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 18:40:05.276  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:05.276  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:05.276  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:05.286  7581  7596 D BluetoothAdapterService: Autoconnection is available 
,08-29 18:40:05.286  7581  7596 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-29 18:40:05.286  7581  7596 D BluetoothAdapterService: terminating service from this receiver
,08-29 18:40:05.286  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 18:40:05.286  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:05.286  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:05.286  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:05.286  7581  7596 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 18:40:05.286  7581  7596 D BluetoothAdapterProperties: mDiscovering is false
,08-29 18:40:05.286  1015  1477 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 18:40:05.296  7581  7596 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 18:40:05.296  7581  7581 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-29 18:40:05.296  7581  7581 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@109d91e6, channel: 19, state: LISTENING
08-29 18:40:05.296  7581  7581 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@109d91e6, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e3a9109, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@136f6327mSocket: android.net.LocalSocket@dcd49d4 impl:android.net.LocalSocketImpl@1adf377d fd:FileDescriptor[74]
08-29 18:40:05.296  7581  7581 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@dcd49d4 impl:android.net.LocalSocketImpl@1adf377d fd:FileDescriptor[74]
,08-29 18:40:05.296  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:05.296  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-29 18:40:05.306  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-29 18:40:05.306  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 18:40:05.306  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:05.306  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:05.306  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:05.316  1172  1172 D BluetoothTile:  getBluetoothState : 13,
08-29 18:40:05.316  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 18:40:05.316  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 18:40:05.316  3901  3901 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:05.316  1015  1335 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 18:40:05.326  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 18:40:05.326  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 18:40:05.326  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 18:40:05.326  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:05.326  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:05.326  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:05.326  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:05.326  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:05.326  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:05.326  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:05.326  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:05.326  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:05.326  1015  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:40:05.326  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 18:40:05.326  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:05.326  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:05.336  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:05.336  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:05.336  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:05.336  7581  7599 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 18:40:05.336  7581  7599 D BluetoothAdapterProperties: Scan Mode:20
,08-29 18:40:05.336  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 18:40:05.336  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:05.336  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:05.336  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:05.336  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:05.336  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 18:40:05.336  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:05.336  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:05.336  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:05.336  6901  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 18:40:05.336  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:05.346  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 18:40:05.346  7581  7596 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-29 18:40:05.346  7581  7596 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-29 18:40:05.346  7581  7596 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-29 18:40:05.346  7581  7596 E bt-btif : cmd socket is not created
,08-29 18:40:05.346  7581  7702 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 18:40:05.346  7581  7596 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 18:40:05.346  1015  1478 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 18:40:05.346  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 18:40:05.346  7581  7646 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-29 18:40:05.346  7581  7646 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 18:40:05.346  7581  7646 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 18:40:05.346  7581  7646 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:05.346  7581  7646 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 18:40:05.346  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:05.356  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:05.356  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:05.356  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 18:40:05.356  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:05.356  3901  3901 D BluetoothPbap: Proxy object disconnected
08-29 18:40:05.356  3901  3901 D PbapServerProfile: Bluetooth service disconnected
,08-29 18:40:05.366  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:05.376  7581  7581 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ba0e672, channel: 5, state: LISTENING
,08-29 18:40:05.376  7581  7581 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ba0e672, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ed2fd2f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37e50ac3mSocket: android.net.LocalSocket@2b9f2f40 impl:android.net.LocalSocketImpl@1eacce79 fd:FileDescriptor[76]
,08-29 18:40:05.376  7581  7581 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2b9f2f40 impl:android.net.LocalSocketImpl@1eacce79 fd:FileDescriptor[76]
,08-29 18:40:05.376  7581  7581 I BtOppRfcommListener: stopping Accept Thread
,08-29 18:40:05.376  7581  7581 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2112f7be, channel: 12, state: LISTENING
,08-29 18:40:05.376  7581  7581 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2112f7be, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32c65841, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3783901fmSocket: android.net.LocalSocket@fe7ff6c impl:android.net.LocalSocketImpl@2f22d935 fd:FileDescriptor[80]
08-29 18:40:05.376  7581  7581 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@fe7ff6c impl:android.net.LocalSocketImpl@2f22d935 fd:FileDescriptor[80]
,08-29 18:40:05.376  7581  7702 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 18:40:05.386  3901  3901 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 18:40:05.386  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:05.386  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 18:40:05.396  7581  7581 V BluetoothOppManager: cleanUp...
,08-29 18:40:05.406  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:05.406  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 18:40:05.546  7581  7646 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 18:40:05.546  7581  7646 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 18:40:05.546  7581  7646 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:05.546  7581  7646 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 18:40:05.546  7581  7646 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 18:40:05.546  7581  7646 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:05.546  7581  7646 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-29 18:40:05.546  7581  7646 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 18:40:05.546  7581  7646 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 18:40:05.546  7581  7646 W bt-btif : ag scb idx 1 not allocated
,08-29 18:40:05.546  7581  7646 W bt-btif : ag scb idx 2 not allocated
08-29 18:40:05.546  7581  7646 E bt-btif : BTA AG is already disabled, ignoring ...
,08-29 18:40:05.546  7581  7684 I bt_userial_mct: exiting userial_read_thread
08-29 18:40:05.546  7581  7684 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-29 18:40:05.546  7581  7599 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 18:40:05.546  7581  7648 I bt_vendor: hw_epilog_process
,08-29 18:40:05.546  7581  7599 D bt_userial_mct: userial_close
08-29 18:40:05.546  7581  7599 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 18:40:05.686  1015  1477 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 18:40:05.686  1015  1477 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 18:40:05.686  1015  1477 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 18:40:05.686  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 18:40:05.686  1015  1477 D BatteryService: stay LED for fully charged
,08-29 18:40:05.686  1015  1015 I MotionRecognitionService: Plugged
,08-29 18:40:05.686  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 18:40:05.686  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,08-29 18:40:05.686  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
,08-29 18:40:05.696  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 18:40:05.696  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 18:40:05.716  7581  7581 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 18:40:05.716  7581  7622 D HeadsetStateMachine: Disconnected process message: 10
,08-29 18:40:05.716  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:40:05.716  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:40:05.716  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:40:05.876  1015  1475 I art     : Explicit concurrent mark sweep GC freed 65644(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 25MB/37MB, paused 2.337ms total 170.945ms
,08-29 18:40:05.896  1015  3354 D SSRM:n  : SIOP:: AP = 370
,08-29 18:40:05.976  7581  7599 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
08-29 18:40:05.976  7581  7599 I bt_vendor: bluetooth satus is on
08-29 18:40:05.976  7581  7599 I bt_vendor: bt-vendor : resetting BT status
08-29 18:40:05.976  7581  7599 I bt_vendor: Starting hciattach daemon
08-29 18:40:05.976  7581  7599 I bt_vendor: try to set false
08-29 18:40:05.976  7581  7599 I bt_vendor: Starting hciattach daemon
08-29 18:40:05.976  7581  7599 I bt_vendor: try to set false
,08-29 18:40:05.976  7581  7599 I bt_vendor: cleanup
08-29 18:40:05.976  1015  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:05.976  7581  7646 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 18:40:05.976  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-29 18:40:05.976  7581  7599 I GKI_LINUX: GKI_exit_task 0 done
08-29 18:40:05.976  7581  7599 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-29 18:40:05.976  7581  7596 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 18:40:05.976  7581  7596 D BtConfig.SecureMode: isSecureModeOn:false
08-29 18:40:05.976  7581  7596 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 18:40:05.976  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 18:40:05.976  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 18:40:05.976  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-29 18:40:05.976  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:05.976  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:05.976  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:40:05.976  1015  1538 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:05.976  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 18:40:05.976  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-29 18:40:05.976  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 18:40:05.976  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 18:40:05.986  7581  7581 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 18:40:05.986  7581  7581 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 18:40:05.986  7581  7581 D BtGatt.GattService: stop()
08-29 18:40:05.986  7581  7581 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 18:40:05.986  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:05.986  1015  1538 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:05.986  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:40:05.986  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 18:40:05.986  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 18:40:05.986  1015  1335 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:05.986  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-29 18:40:05.986  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:40:05.986  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:05.986  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:05.986  1015  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:05.986  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:05.986  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 18:40:05.986  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 18:40:05.986  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 18:40:05.986  7581  7581 D HeadsetService: Received stop request...Stopping profile...
,08-29 18:40:05.986  1015  1215 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:05.986  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 18:40:05.996  1015  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:05.996  1015  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:05.996  1015  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:05.996  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-29 18:40:05.996  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 18:40:05.996  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-29 18:40:05.996  1015  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:05.996  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:40:05.996  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 18:40:05.996  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:05.996  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:05.996  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:05.996  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 18:40:05.996  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 18:40:05.996  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 18:40:05.996  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:05.996  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 18:40:06.006  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 18:40:06.006  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:06.006  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:06.006  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:40:06.006  3901  3901 D HeadsetProfile: Bluetooth service disconnected
,08-29 18:40:06.006  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 18:40:06.006  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 18:40:06.006  7581  7596 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 18:40:06.006  1015  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:40:06.006  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 18:40:06.006  1015  1477 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:06.006  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:06.006  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:06.006  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-29 18:40:06.006  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 18:40:06.006  7581  7596 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 18:40:06.016  1015  1215 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:06.016  1015  1215 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 18:40:06.016  1015  1215 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:06.016  1015  1215 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:06.016  1015  1215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:06.016  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:40:06.016  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 18:40:06.016  7581  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:40:06.016  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:06.016  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 18:40:06.016  7581  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-29 18:40:06.016  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 18:40:06.016  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 18:40:06.016  7581  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService,
08-29 18:40:06.016  7581  7596 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 18:40:06.016  7581  7596 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 18:40:06.016  7581  7596 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
,08-29 18:40:06.016  7581  7596 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 18:40:06.016  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-29 18:40:06.016  7581  7581 D A2dpService: Received stop request...Stopping profile...
08-29 18:40:06.016  7581  7625 D A2dpStateMachine: Exit Disconnected: -1
,08-29 18:40:06.026  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:06.026  1015  1015 D BluetoothA2dp: Proxy object disconnected
,08-29 18:40:06.026  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 18:40:06.026  7581  7581 D HidService: Received stop request...Stopping profile...
,08-29 18:40:06.026  7581  7581 D HidService: Stopping Bluetooth HidService
,08-29 18:40:06.026  7581  7581 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 18:40:06.026  7581  7581 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 18:40:06.026  7581  7581 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 18:40:06.026  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:06.026  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 18:40:06.026  7581  7581 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 18:40:06.026  7581  7581 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 18:40:06.026  7581  7581 D HealthService: Received stop request...Stopping profile...
,08-29 18:40:06.026  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:06.036  3901  3901 D BluetoothA2dp: Proxy object disconnected
08-29 18:40:06.036  3901  3901 D A2dpProfile: Bluetooth service disconnected
08-29 18:40:06.036  3901  3901 D BluetoothInputDevice: Proxy object disconnected
,08-29 18:40:06.036  3901  3901 D HidProfile: Bluetooth service disconnected
,08-29 18:40:06.036  7581  7581 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 18:40:06.036  7581  7581 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 18:40:06.036  7581  7581 D PanService: Received stop request...Stopping profile...
,08-29 18:40:06.036  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:06.036  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 18:40:06.036  7581  7581 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 18:40:06.036  3901  3901 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 18:40:06.036  3901  3901 D PanProfile: Bluetooth service disconnected
,08-29 18:40:06.036  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:06.046  7581  7581 D SapService: Received stop request...Stopping profile...
08-29 18:40:06.046  7581  7581 D SapService: Stopping Bluetooth SapService
08-29 18:40:06.046  7581  7581 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:06.046  3901  3901 D BluetoothMap: Proxy object disconnected
08-29 18:40:06.046  3901  3901 D MapProfile: Bluetooth service disconnected
,08-29 18:40:06.046  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-29 18:40:06.046  7581  7581 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 18:40:06.046  7581  7581 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 18:40:06.046  7581  7581 D BluetoothA2dp: Proxy object disconnected
08-29 18:40:06.046  7581  7581 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-29 18:40:06.046  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 18:40:06.046  7581  7581 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 18:40:06.046  7581  7581 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 18:40:06.046  3901  3901 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 18:40:06.046  7581  7626 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 18:40:06.046  3901  3901 D SapProfile: Bluetooth service disconnected
08-29 18:40:06.046  7581  7581 I GKI_LINUX: GKI_exit_task 2 done
08-29 18:40:06.046  7581  7581 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-29 18:40:06.046  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 18:40:06.046  7581  7581 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 18:40:06.046  7581  7581 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 18:40:06.046  7581  7581 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 18:40:06.046  7581  7581 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 18:40:06.046  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 18:40:06.046  7581  7581 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 18:40:06.046  7581  7581 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 18:40:06.046  7581  7581 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 18:40:06.046  7581  7581 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 18:40:06.046  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-29 18:40:06.046  7581  7581 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 18:40:06.046  7581  7581 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-29 18:40:06.046  7581  7581 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-29 18:40:06.046  7581  7581 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 18:40:06.046  7581  7581 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 18:40:06.046  7581  7596 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-29 18:40:06.046  7581  7596 D BluetoothAdapterProperties: Setting state to 10
08-29 18:40:06.046  7581  7596 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 18:40:06.046  7581  7596 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 18:40:06.046  7581  7596 D BluetoothAdapterService: updateAdapterState state is 10
,08-29 18:40:06.056  7581  7596 D BluetoothAdapterService: Autoconnection is available 
08-29 18:40:06.056  7581  7596 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 18:40:06.056  7581  7596 I BluetoothAdapterState: Entering OffState
08-29 18:40:06.056  7581  7590 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 18:40:06.056  2003  2011 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 18:40:06.056  2003  2011 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 18:40:06.056  3901  3909 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 18:40:06.056  3901  3918 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 18:40:06.056  3901  3918 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 18:40:06.056  6901  6914 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 18:40:06.056  6901  6914 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:40:06.056  6901  6914 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-29 18:40:06.056  6901  6914 D BluetoothLeAdvertiser: Exit stop advertising
,08-29 18:40:06.056  6901  6914 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 18:40:06.056  6901  6914 D BluetoothLeScanner: Exiting stopAllScan
,08-29 18:40:06.056  7581  7691 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:40:06.056  7581  7691 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 18:40:06.066  1433  1458 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:40:06.066  1433  1458 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:40:06.066  7631  7640 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:40:06.066  7631  7640 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 18:40:06.066  3901  3917 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 18:40:06.066  1451  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 18:40:06.066  1451  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:40:06.066  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 18:40:06.066  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 18:40:06.066  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 18:40:06.066  1422  7689 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 18:40:06.066  1422  7689 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 18:40:06.066  1172  1193 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 18:40:06.066  1172  1193 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 18:40:06.066  3901  3909 D Bluetoothsap: onBluetoothStateChange: up=false
08-29 18:40:06.066  3901  3909 D Bluetoothsap: Unbinding service...
,08-29 18:40:06.066  3901  3917 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 18:40:06.066  3901  3909 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 18:40:06.066  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 18:40:06.076  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 18:40:06.076  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:06.076  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
,08-29 18:40:06.076  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 18:40:06.086  1172  1172 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
,08-29 18:40:06.086  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 18:40:06.086  1172  1763 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
,08-29 18:40:06.086  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:06.086  1172  1172 D BluetoothTile:  getBluetoothState : 10
,08-29 18:40:06.086  1172  1763 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
,08-29 18:40:06.086  1172  1172 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
,08-29 18:40:06.086  1172  1172 D BluetoothAdapter: 228657031: getState() :  mService = null. Returning STATE_OFF
,08-29 18:40:06.086  1015  1477 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 18:40:06.086  1015  1215 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 18:40:06.096  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 18:40:06.096  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 18:40:06.096  2003  2161 D BluetoothAdapter: 412910426: getState() :  mService = null. Returning STATE_OFF
,08-29 18:40:06.096  2003  2161 D BluetoothAdapter: 412910426: getState() :  mService = null. Returning STATE_OFF
,08-29 18:40:06.096  3901  3901 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:06.096  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:06.096  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:06.106  1015  1218 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 18:40:06.106  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 18:40:06.106  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:06.106  1015  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:06.106  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:06.106  7581  7599 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 18:40:06.106  7581  7581 I GKI_LINUX: GKI_exit_task 1 done
,08-29 18:40:06.106  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 18:40:06.106  7581  7581 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-29 18:40:06.106  7581  7581 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 18:40:06.106  1015  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 18:40:06.106  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 18:40:06.106  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:06.106  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:06.106  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 18:40:06.116  7581  7581 I art     : System.exit called, status: 0
08-29 18:40:06.116  7581  7581 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 18:40:06.116  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:06.116  3901  3901 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 18:40:06.126  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:06.126  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 18:40:06.186  1015  1475 I ActivityManager: Process com.android.bluetooth (pid 7581)(adj 0) has died(43,703)
,08-29 18:40:06.196  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:06.196  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 18:40:06.196  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 18:40:06.196  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:06.196  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:40:06.196  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:06.206  2003  7719 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 18:40:06.206  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 18:40:06.216  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:40:06.216  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:06.216  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:06.216  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:06.216  2003  7719 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false,
,08-29 18:40:06.416   288   288 E SMD     : DCD OFF
,08-29 18:40:07.326  1015  1307 E Watchdog: !@Sync 4
,08-29 18:40:08.276  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 18:40:08.276  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:08.446   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 18:40:09.426   288   288 E SMD     : DCD OFF,
,08-29 18:40:09.456   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 18:40:10.456   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 18:40:11.206  1015  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 18:40:11.276  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:11.276  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32d19509 added. We now have 6 listener(s)
,08-29 18:40:11.276  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:11.276  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:11.276  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c9b630e added. We now have 7 listener(s)
08-29 18:40:11.276  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:11.286  6901  6955 I System.out: IsBluetoothEnabled,
08-29 18:40:11.286  6901  6955 D BluetoothAdapter: disable()
,08-29 18:40:11.286  1015  1218 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,08-29 18:40:11.286  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:11.286  6901  6955 D BluetoothAdapter: enable()
,08-29 18:40:11.296  1015  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 18:40:11.296  1015  1028 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 18:40:11.296  1015  1028 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 18:40:11.296  1015  1028 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 18:40:11.296  1015  1028 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 18:40:11.296  1015  1028 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 18:40:11.296  1015  1028 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 18:40:11.296  1015  1028 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 18:40:11.296  1015  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:11.296  1015  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:11.296  1015  1028 D SettingsProvider: name = bluetooth_on,
,08-29 18:40:11.306  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:11.306  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:11.316  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-29 18:40:11.316  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-29 18:40:11.316  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 18:40:11.316  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:11.316  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:11.316  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:11.326  7725  7725 E Zygote  : MountEmulatedStorage()
08-29 18:40:11.326  7725  7725 I libpersona: KNOX_SDCARD checking this for 1002
08-29 18:40:11.326  7725  7725 E Zygote  : v2
08-29 18:40:11.326  7725  7725 I libpersona: KNOX_SDCARD not a persona
08-29 18:40:11.326  7725  7725 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:40:11.336  1015  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7725 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-29 18:40:11.336  7725  7725 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:40:11.336  7725  7725 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:40:11.356  7725  7725 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:40:11.356  7725  7725 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:11.376  7725  7725 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 18:40:11.376  7725  7725 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 18:40:11.396  7725  7725 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding GattService
,08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding HeadsetService
08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding A2dpService
,08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding HidService
08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding HealthService
08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding PanService
08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding SapService
08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding SapClientService
,08-29 18:40:11.426  7725  7725 D BtSettings.ProfileConfig: Adding HidDevService
08-29 18:40:11.426  7725  7725 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 18:40:11.426  1015  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
08-29 18:40:11.426  1015  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.426  1015  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:11.426  1015  1479 D SettingsProvider: selectionArgs: false
08-29 18:40:11.426  1015  1479 D SettingsProvider: selectionArgs: 1002
08-29 18:40:11.426  1015  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.426  1015  1479 D SettingsProvider: ret = -1
,08-29 18:40:11.426  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-29 18:40:11.426  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.426  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:11.426  1015  1478 D SettingsProvider: selectionArgs: false
08-29 18:40:11.426  1015  1478 D SettingsProvider: selectionArgs: 1002
,08-29 18:40:11.426  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.426  1015  1478 D SettingsProvider: ret = -1
,08-29 18:40:11.426  1015  1538 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-29 18:40:11.426  1015  1538 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.426  1015  1538 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:11.426  1015  1538 D SettingsProvider: selectionArgs: false,
08-29 18:40:11.426  1015  1538 D SettingsProvider: selectionArgs: 1002
08-29 18:40:11.426  1015  1538 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-29 18:40:11.426  1015  1538 D SettingsProvider: ret = -1
,08-29 18:40:11.426  1015  1335 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-29 18:40:11.426  1015  1335 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.426  1015  1335 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:11.426  1015  1335 D SettingsProvider: selectionArgs: false
,08-29 18:40:11.436  1015  1335 D SettingsProvider: selectionArgs: 1002,
08-29 18:40:11.436  1015  1335 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.436  1015  1335 D SettingsProvider: ret = -1
,08-29 18:40:11.436  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-29 18:40:11.436  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.436  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:11.436  1015  1027 D SettingsProvider: selectionArgs: false
,08-29 18:40:11.436  1015  1027 D SettingsProvider: selectionArgs: 1002
08-29 18:40:11.436  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.436  1015  1027 D SettingsProvider: ret = -1
08-29 18:40:11.436  1015  1218 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-29 18:40:11.436  1015  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.436  1015  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:11.436  1015  1218 D SettingsProvider: selectionArgs: false
,08-29 18:40:11.436  1015  1218 D SettingsProvider: selectionArgs: 1002
08-29 18:40:11.436  1015  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.436  1015  1218 D SettingsProvider: ret = -1
08-29 18:40:11.436  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-29 18:40:11.436  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.436  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:11.436  1015  1475 D SettingsProvider: selectionArgs: false
08-29 18:40:11.436  1015  1475 D SettingsProvider: selectionArgs: 1002
,08-29 18:40:11.436  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.436  1015  1475 D SettingsProvider: ret = -1
08-29 18:40:11.436  1015  1495 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
08-29 18:40:11.436  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.436  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:11.436  1015  1495 D SettingsProvider: selectionArgs: false
08-29 18:40:11.436  1015  1495 D SettingsProvider: selectionArgs: 1002,
08-29 18:40:11.436  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.436  1015  1495 D SettingsProvider: ret = -1
08-29 18:40:11.436  1015  1748 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:40:11.436  1015  1748 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.436  1015  1748 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-29 18:40:11.436  1015  1748 D SettingsProvider: selectionArgs: false,
08-29 18:40:11.436  1015  1748 D SettingsProvider: selectionArgs: 1002
08-29 18:40:11.436  1015  1748 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 18:40:11.436  1015  1748 D SettingsProvider: ret = -1
08-29 18:40:11.436  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:11.436  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.436  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:11.436  1015  1028 D SettingsProvider: selectionArgs: false
08-29 18:40:11.436  1015  1028 D SettingsProvider: selectionArgs: 1002
08-29 18:40:11.436  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.436  1015  1028 D SettingsProvider: ret = -1,
08-29 18:40:11.436  1015  1215 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-29 18:40:11.436  1015  1215 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.436  1015  1215 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:11.436  1015  1215 D SettingsProvider: selectionArgs: false,
08-29 18:40:11.436  1015  1215 D SettingsProvider: selectionArgs: 1002
08-29 18:40:11.436  1015  1215 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.436  1015  1215 D SettingsProvider: ret = -1
08-29 18:40:11.436  1015  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
08-29 18:40:11.436  1015  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.436  1015  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:11.436  1015  1477 D SettingsProvider: selectionArgs: false
08-29 18:40:11.436  1015  1477 D SettingsProvider: selectionArgs: 1002
,08-29 18:40:11.436  1015  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.436  1015  1477 D SettingsProvider: ret = -1
,08-29 18:40:11.446  7725  7725 D BluetoothAdapterState: make,
08-29 18:40:11.456   315   315 I ServiceManager: Waiting for service AtCmdFwd...
08-29 18:40:11.456  7725  7725 I bluedroid: init
08-29 18:40:11.456  7725  7740 I BluetoothAdapterState: Entering OffState
,08-29 18:40:11.456  7725  7725 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 18:40:11.456  7725  7725 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 18:40:11.456  7725  7725 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 18:40:11.456  7725  7725 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 18:40:11.456  7725  7725 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-29 18:40:11.456  7725  7725 I bluedroid: get_profile_interface socket
08-29 18:40:11.456  7725  7725 I bluedroid: get_profile_interface map_client
08-29 18:40:11.456  7725  7743 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-29 18:40:11.456  7725  7725 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-29 18:40:11.466  7725  7743 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 18:40:11.466  7725  7743 E BluetoothServiceJni: populateRssiValuesNative
08-29 18:40:11.466  7725  7743 I bluedroid: getModelRssiValues
,08-29 18:40:11.466  7725  7743 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-29 18:40:11.466  7725  7743 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 18:40:11.466  1015  1015 D SettingsProvider: name = bluetooth_name
,08-29 18:40:11.466  7725  7743 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 18:40:11.476  7725  7725 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,08-29 18:40:11.476  1015  1477 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 18:40:11.476  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.476  1015  1477 W ActivityManager: userId = 0, bbcId = -10000,
08-29 18:40:11.476  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.476  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:11.476  7725  7733 I bluedroid: config_hci_snoop_log
,08-29 18:40:11.476  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 18:40:11.476  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-29 18:40:11.486  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-29 18:40:11.486  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 18:40:11.486  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 18:40:11.486  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:11.486  7725  7725 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-29 18:40:11.486  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 18:40:11.496  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 18:40:11.496  7725  7740 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 18:40:11.496  7725  7740 D BluetoothAdapterProperties: Setting state to 11
,08-29 18:40:11.496  7725  7740 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 18:40:11.496  7725  7740 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 18:40:11.496  7725  7740 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 18:40:11.496  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 18:40:11.496  7725  7740 D BluetoothAdapterService: Autoconnection is available 
,08-29 18:40:11.496  7725  7740 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-29 18:40:11.506  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:11.506  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-29 18:40:11.506  7725  7740 D BluetoothSecureManager: getInstant: null
,08-29 18:40:11.506  7725  7740 D BluetoothSecureManager: calling getMethod for getService
08-29 18:40:11.506  7725  7740 D BluetoothSecureManager: calling getService
,08-29 18:40:11.506  7725  7740 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2035c6ac
,08-29 18:40:11.506  1015  1218 D BluetoothSecureManagerService: isSecureModeEnabled
08-29 18:40:11.506  1015  1218 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-29 18:40:11.506  7725  7740 D BtConfig.SecureMode: isSecureModeOn:false
08-29 18:40:11.506  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 18:40:11.506  7725  7740 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-29 18:40:11.506  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-29 18:40:11.516  7725  7740 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-29 18:40:11.516  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 18:40:11.516  7725  7740 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-29 18:40:11.516  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 18:40:11.516  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 18:40:11.516  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:11.516  1172  1172 D BluetoothTile:  getBluetoothState : 11
,08-29 18:40:11.516  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:11.516  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 18:40:11.526  7725  7740 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-29 18:40:11.526  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 18:40:11.526  7725  7740 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-29 18:40:11.526  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 18:40:11.526  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 18:40:11.526  7725  7740 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-29 18:40:11.526  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 18:40:11.526  7725  7740 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-29 18:40:11.526  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 18:40:11.526  7725  7740 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-29 18:40:11.526  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:40:11.526  7725  7740 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 18:40:11.526  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 18:40:11.526  3901  3901 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:11.526  7725  7740 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:11.526  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 18:40:11.526  7725  7740 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 18:40:11.526  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 18:40:11.526  7725  7740 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-29 18:40:11.526  1015  1538 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 18:40:11.526  1015  1215 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 18:40:11.536  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 18:40:11.536  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:11.536  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 18:40:11.536  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.536  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:11.536  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:11.536  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:11.546  3901  3901 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 18:40:11.546  7725  7740 D BluetoothBondStateMachine: make
,08-29 18:40:11.546  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:11.546  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 18:40:11.546  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 18:40:11.546  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 18:40:11.546  7725  7740 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 18:40:11.556  7725  7746 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 18:40:11.556  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:40:11.556  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.556  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:11.556  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.556  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:11.556  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-29 18:40:11.556  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 18:40:11.556  7725  7740 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 18:40:11.556  7725  7725 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 18:40:11.556  7725  7725 D BtGatt.GattService: Received start request. Starting profile...
08-29 18:40:11.556  7725  7725 D BtGatt.GattService: start()
08-29 18:40:11.556  7725  7725 D BtGatt.GattService: start()
08-29 18:40:11.556  7725  7725 I bluedroid: get_profile_interface gatt
,08-29 18:40:11.556  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:40:11.556  7725  7725 D BtGatt.AdvertiseManager: advertise manager created
,08-29 18:40:11.566  1015  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:40:11.566  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.566  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:11.566  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:11.566  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:11.566  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 18:40:11.566  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 18:40:11.566  7725  7740 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 18:40:11.566  1015  1538 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:11.566  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.576  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:11.576  1015  1538 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.576  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:11.576  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-29 18:40:11.576  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 18:40:11.576  7725  7740 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 18:40:11.576  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:11.576  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.576  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:11.576  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.576  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:11.576  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 18:40:11.576  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 18:40:11.576  7725  7740 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 18:40:11.576  1015  1748 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:11.576  1015  1748 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.576  7725  7725 D BtGatt.GattService: mStartError = false
,08-29 18:40:11.576  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:11.586  1015  1748 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:11.586  1015  1748 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.586  1015  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:11.586  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 18:40:11.586  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 18:40:11.586  7725  7740 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 18:40:11.586  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:11.586  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-29 18:40:11.586  7725  7725 D HeadsetService: Received start request. Starting profile...
08-29 18:40:11.586  7725  7725 D HeadsetService: start()
08-29 18:40:11.586  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:11.586  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.586  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:40:11.586  7725  7725 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 18:40:11.586  7725  7725 D HeadsetStateMachine: make
,08-29 18:40:11.586  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 18:40:11.586  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 18:40:11.586  7725  7740 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 18:40:11.596  7725  7725 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 18:40:11.596  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:11.606  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:40:11.606  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.606  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:11.606  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.606  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:11.606  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-29 18:40:11.606  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.606  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:11.606  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.606  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 18:40:11.606  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-29 18:40:11.606  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 18:40:11.606  7725  7740 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 18:40:11.616  1015  1538 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:11.616  1015  1538 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.616  1015  1538 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:11.616  1015  1538 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.616  1015  1538 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:11.616  1015  1335 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-29 18:40:11.616  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 18:40:11.616  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:11.616  1015  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:11.616  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 18:40:11.616  7725  7725 I bluedroid: get_profile_interface handsfree
,08-29 18:40:11.626  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:40:11.626  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:40:11.626  7725  7740 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 18:40:11.626  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:11.626  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:11.626  7725  7740 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 18:40:11.626  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 18:40:11.626  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 18:40:11.626  7725  7740 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 18:40:11.626  7725  7740 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 18:40:11.626  7725  7740 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 18:40:11.626  7725  7740 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 18:40:11.626  7725  7740 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-29 18:40:11.626  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 18:40:11.636  7725  7725 I DualScoManager: Instantiating Dual Sco Manager
,08-29 18:40:11.636  7725  7725 I DualScoManager: Set HeadsetServiceHelper
,08-29 18:40:11.636  7725  7725 D BluetoothAtMessage: createCMTIContentObservers
,08-29 18:40:11.636  1015  1495 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-29 18:40:11.646  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:11.646  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 18:40:11.646  1015  1495 D SettingsProvider: selectionArgs: false
08-29 18:40:11.646  1015  1495 D SettingsProvider: selectionArgs: 1002
,08-29 18:40:11.646  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:11.646  1015  1495 D SettingsProvider: ret = -1
,08-29 18:40:11.646  7725  7750 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 18:40:11.646  7725  7725 D HeadsetService: mStartError = false
08-29 18:40:11.646  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:11.646  7725  7725 D A2dpService: Received start request. Starting profile...
08-29 18:40:11.646  7725  7725 D A2dpService: start()
,08-29 18:40:11.646  7725  7750 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-29 18:40:11.646  7725  7750 D HeadsetStateMachine: map size, before remove : 0
08-29 18:40:11.646  7725  7750 D HeadsetStateMachine: map size, after remove: 0
,08-29 18:40:11.646  7725  7725 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 18:40:11.656  7725  7725 I bluedroid: get_profile_interface avrcp
,08-29 18:40:11.656  7725  7725 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 18:40:11.656  7725  7725 D Avrcp   : Initialize Media Controller
,08-29 18:40:11.656  7725  7725 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 18:40:11.656  7725  7725 E Avrcp   : getActiveSessions
,08-29 18:40:11.656  7725  7725 D Avrcp   : pick active media Controller
08-29 18:40:11.656  7725  7725 D Avrcp   : Get the active Media Controller 
,08-29 18:40:11.676  7725  7725 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 18:40:11.676  7725  7753 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 18:40:11.676  7725  7725 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 18:40:11.676  7725  7725 D A2dpStateMachine: make
,08-29 18:40:11.676  7725  7725 I bluedroid: get_profile_interface a2dp
,08-29 18:40:11.676  7725  7755 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 18:40:11.676  7725  7725 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 18:40:11.686  7725  7725 D A2dpService: mStartError = false
08-29 18:40:11.686  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:11.686  7725  7725 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 18:40:11.686  7725  7754 D A2dpStateMachine: Enter Disconnected: -2
,08-29 18:40:11.686  7725  7725 D HidService: Received start request. Starting profile...
08-29 18:40:11.686  7725  7725 D HidService: start()
08-29 18:40:11.686  7725  7725 I bluedroid: get_profile_interface hidhost
08-29 18:40:11.686  7725  7725 D HidService: setHidService(): set to: null
08-29 18:40:11.686  7725  7725 D HidService: mStartError = false
08-29 18:40:11.686  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:11.686  7725  7725 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-29 18:40:11.686  7725  7725 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 18:40:11.686  7725  7725 D HealthService: Received start request. Starting profile...
08-29 18:40:11.686  7725  7725 D HealthService: start()
,08-29 18:40:11.686  7725  7753 D BluetoothMediaBrowser: no now playing list
08-29 18:40:11.686  7725  7753 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 18:40:11.686  7725  7725 I bluedroid: get_profile_interface health
,08-29 18:40:11.696  7725  7725 D HealthService: mStartError = false
08-29 18:40:11.696  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:11.696  7725  7725 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 18:40:11.696  7725  7725 D PanService: Received start request. Starting profile...
,08-29 18:40:11.696  7725  7725 D PanService: start()
,08-29 18:40:11.696  7725  7725 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 18:40:11.696  7725  7725 I bluedroid: get_profile_interface pan
,08-29 18:40:11.696  7725  7725 D PanService: mStartError = false
,08-29 18:40:11.696  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:11.696  7725  7725 D BluetoothMapService: Received start request. Starting profile...
,08-29 18:40:11.696  7725  7725 D BluetoothMapService: start()
,08-29 18:40:11.706  7725  7725 D BluetoothMapService: mStartError = false
,08-29 18:40:11.706  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:11.706  7725  7725 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 18:40:11.706  1422  7689 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 18:40:11.706  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-29 18:40:11.706  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 18:40:11.706  1422  7689 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 18:40:11.706  7725  7725 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-29 18:40:11.706  7725  7725 D SapService: Received start request. Starting profile...
08-29 18:40:11.706  7725  7725 D SapService: start()
08-29 18:40:11.706  7725  7725 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 18:40:11.706  7725  7725 I bluedroid: get_profile_interface sap
08-29 18:40:11.706  7725  7725 D SapService: mStartError = false
08-29 18:40:11.706  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
08-29 18:40:11.706  7725  7725 D HeadsetStateMachine: Proxy object connected
,08-29 18:40:11.706  7725  7725 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 18:40:11.716  7725  7725 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 18:40:11.716  7725  7750 D HeadsetStateMachine: Disconnected process message: 11
08-29 18:40:11.716  7725  7750 D HeadsetStateMachine: Disconnected process message: 18
08-29 18:40:11.716  7725  7725 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-29 18:40:11.716  7725  7725 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 18:40:11.716  7725  7725 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 18:40:11.716  7725  7725 D BluetoothA2dp: Proxy object connected
08-29 18:40:11.716  7725  7725 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-29 18:40:11.716  7725  7725 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 18:40:11.716  7725  7725 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-29 18:40:11.716  7725  7750 D HeadsetStateMachine: Disconnected process message: 10
08-29 18:40:11.716  7725  7750 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 18:40:11.716  7725  7750 D HeadsetStateMachine: Disconnected process message: 11
,08-29 18:40:11.716  7725  7725 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 18:40:11.716  7725  7725 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 18:40:11.726  1015  2058 V SAMP_SPCM_test: CSC File load.. 
,08-29 18:40:11.736  7725  7725 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-29 18:40:11.736  7725  7725 E BluetoothAdapterService(255883111): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-29 18:40:11.746  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-29 18:40:11.776  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi,
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn,
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-29 18:40:11.786  1015  2058 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,08-29 18:40:11.786  1015  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-29 18:40:11.796  1015  2058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:11.796  1015  2058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:11.796  1015  2058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:11.796  1015  2058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:11.806  7759  7759 E Zygote  : MountEmulatedStorage()
,08-29 18:40:11.806  7759  7759 E Zygote  : v2
08-29 18:40:11.806  7759  7759 I libpersona: KNOX_SDCARD checking this for 1000
08-29 18:40:11.806  7759  7759 I libpersona: KNOX_SDCARD not a persona
,08-29 18:40:11.806  7759  7759 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 18:40:11.806  1015  2058 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7759 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-29 18:40:11.806  7725  7740 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-29 18:40:11.806  7725  7740 I bluedroid: enable
08-29 18:40:11.806  7725  7765 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 18:40:11.806  7725  7740 I bt_hci_bdroid: init
,08-29 18:40:11.806  7759  7759 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:40:11.806  7725  7740 I bt_vendor: bt-vendor : init
08-29 18:40:11.806  7725  7740 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 18:40:11.806  7725  7740 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 18:40:11.806  7725  7740 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-29 18:40:11.806  7725  7740 D bt_userial_mct: userial_init
08-29 18:40:11.806  7725  7740 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 18:40:11.806  7759  7759 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 18:40:11.806  7725  7740 I bt_vendor: Starting hciattach daemon
08-29 18:40:11.806  7725  7740 I bt_vendor: try to set false
08-29 18:40:11.806  7725  7740 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 18:40:11.806  7725  7740 I bt_vendor: Starting hciattach daemon
08-29 18:40:11.806  7725  7740 I bt_vendor: try to set true
,08-29 18:40:11.826  7772  7772 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-29 18:40:11.836  7759  7759 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-29 18:40:11.846  7759  7759 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:11.856  7759  7759 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,08-29 18:40:11.876  7784  7784 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 18:40:11.886  7785  7785 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-29 18:40:11.906  7787  7787 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 18:40:11.916  1015  1015 I ActivityManager: Killing 7238:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-29 18:40:11.916  1015  2058 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-29 18:40:11.916  7789  7789 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 18:40:11.926  7790  7790 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 18:40:11.936  7791  7791 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-29 18:40:12.166  7794  7794 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-29 18:40:12.176  7795  7795 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-29 18:40:12.216  7725  7740 I bt_vendor: bluetooth satus is on
08-29 18:40:12.216  7725  7767 D bt_userial_mct: userial_open(port:0)
08-29 18:40:12.216  7725  7767 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 18:40:12.216  7725  7767 I bt_vendor: Done intiailizing UART
,08-29 18:40:12.216  7725  7767 I bt_vendor: Done intiailizing UART
08-29 18:40:12.216  7725  7767 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-29 18:40:12.216  7725  7767 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 18:40:12.226  7725  7797 D bt_userial_mct: Entering userial_read_thread()
,08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_SAP
,08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 18:40:12.226  7725  7765 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-29 18:40:12.326  7725  7765 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-29 18:40:12.326  7725  7765 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42f3ed1 
,08-29 18:40:12.326  7725  7765 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42f3ed1 
,08-29 18:40:12.346  7725  7743 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-29 18:40:12.346  7725  7743 E bt-btif : Calling BTA_HhEnable
,08-29 18:40:12.346  7725  7743 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 18:40:12.346  7725  7743 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 18:40:12.346  7725  7743 E BluetoothServiceJni: populateRssiValuesNative
08-29 18:40:12.346  7725  7743 I bluedroid: getModelRssiValues
,08-29 18:40:12.346  7725  7743 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 18:40:12.346  7725  7743 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 18:40:12.356  1015  1015 D SettingsProvider: name = bluetooth_name
,08-29 18:40:12.356  7725  7743 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 18:40:12.366  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:12.366  7725  7743 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 18:40:12.366  7725  7743 D BluetoothAdapterProperties: Scan Mode:20
08-29 18:40:12.366  7725  7743 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 18:40:12.366  7725  7743 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-29 18:40:12.366  7725  7743 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-29 18:40:12.366  7725  7743 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-29 18:40:12.366  7725  7743 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 18:40:12.366  7725  7743 E bt-btif : btif_sock_init: !vhci_init
08-29 18:40:12.366  7725  7743 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-29 18:40:12.366  7725  7743 D IOP_DB_BT: db_open: db_open : handle 3028701200l, read 13894 bytes onto local cache
08-29 18:40:12.366  7725  7743 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-29 18:40:12.366  7725  7743 D IOP_DB_BT: db_query: result 1
08-29 18:40:12.366  7725  7743 I         : iop_db_open: iop_db_open status 0
08-29 18:40:12.366  7725  7743 D bte_conf: Device ID record 1 : primary
08-29 18:40:12.366  7725  7743 D bte_conf:   vendorId            = 0075
08-29 18:40:12.366  7725  7743 D bte_conf:   vendorIdSource      = 0001
08-29 18:40:12.366  7725  7743 D bte_conf:   product             = 0100,
08-29 18:40:12.366  7725  7743 D bte_conf:   version             = 0200
08-29 18:40:12.366  7725  7743 D bte_conf:   clientExecutableURL = 
,08-29 18:40:12.366  7725  7743 D bte_conf:   serviceDescription  = 
08-29 18:40:12.366  7725  7743 D bte_conf:   documentationURL    = 
08-29 18:40:12.366  7725  7743 D bte_conf: bte_load_did_conf no section named DID2.
,08-29 18:40:12.366  7725  7743 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 18:40:12.376  7725  7740 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 18:40:12.376  7725  7740 D BluetoothAdapterProperties: ScanMode =  20
08-29 18:40:12.376  7725  7740 D BluetoothAdapterProperties: State =  11
,08-29 18:40:12.376  1015  1215 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 18:40:12.376  7725  7740 D BluetoothAdapterProperties: Setting state to 12,
,08-29 18:40:12.376  7725  7740 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 18:40:12.376  1015  1028 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-29 18:40:12.376  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 18:40:12.376  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:12.376  1015  1028 D SettingsProvider: selectionArgs: false
08-29 18:40:12.376  1015  1028 D SettingsProvider: selectionArgs: 1002
08-29 18:40:12.376  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 18:40:12.376  1015  1028 D SettingsProvider: ret = -1
08-29 18:40:12.376  7725  7743 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 18:40:12.376  7725  7743 D BluetoothAdapterProperties: Scan Mode:21
08-29 18:40:12.376  7725  7740 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 18:40:12.376  7725  7743 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 18:40:12.376  7725  7740 D BluetoothAdapterService: updateAdapterState state is 12
08-29 18:40:12.376  7725  7797 E bt_mct  : hci lib postload completed
,08-29 18:40:12.376  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:12.376  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.386  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.386  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.386  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.386  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:12.386  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:12.386  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:12.386  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:12.386  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:12.386  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:12.386  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:12.386  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:12.386  7725  7740 D BluetoothAdapterService: Autoconnection is available 
,08-29 18:40:12.386  7725  7740 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 18:40:12.386  7725  7740 D BluetoothAdapterService: starting service from this receiver
,08-29 18:40:12.396  3901  3909 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 18:40:12.396  1015  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 18:40:12.396  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.396  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.396  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.396  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 18:40:12.396  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:12.396  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 18:40:12.406  7725  7740 I BluetoothAdapterState: Entering On State from state = 11
08-29 18:40:12.406  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:12.406  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:12.406  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.406  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.406  3901  3909 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 18:40:12.406  2003  2011 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:12.406  2003  2011 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:12.406  7725  7739 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 18:40:12.416  3901  3917 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 18:40:12.416  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-29 18:40:12.416  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.416  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.416  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.416  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.416  7725  7725 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 18:40:12.426  1422  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:12.426   288   288 E SMD     : DCD OFF
,08-29 18:40:12.426  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 18:40:12.426  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:12.426  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.426  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.426  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.426  1422  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 18:40:12.426  3901  3918 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:12.426  3901  3918 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:12.426  1015  1045 D BluetoothPan: Binding service...
08-29 18:40:12.426  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 18:40:12.426  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.436  6901  6948 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:12.436  6901  6948 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:12.436  1422  1430 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:12.436  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 18:40:12.436  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:12.436  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:12.436  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.436  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.436  1422  1430 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 18:40:12.436  1451  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:12.436  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 18:40:12.446  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:12.446  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.446  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.446  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-29 18:40:12.446  1451  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 18:40:12.446  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:12.446  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 18:40:12.446  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 18:40:12.446  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 18:40:12.446  1433  1462 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:12.446  1433  1462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:12.446  7631  7639 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:12.446  7725  7725 I BluetoothPbapService: Handler(): got msg=1
08-29 18:40:12.446  7631  7639 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:12.446  3901  3901 D HeadsetProfile: Bluetooth service connected
,08-29 18:40:12.446  1015  1475 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 18:40:12.456  3901  3918 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 18:40:12.456   315   315 I ServiceManager: Waiting for service AtCmdFwd...
08-29 18:40:12.456  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 18:40:12.456  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.456  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:12.456  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:12.456  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.456  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 18:40:12.456  7725  7801 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 18:40:12.456  1451  1690 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:12.466  1451  1690 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:12.466  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:12.466  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:12.466  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 18:40:12.466  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 18:40:12.466  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 18:40:12.466  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.466  1422  7689 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 18:40:12.466  1422  7689 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:12.466  1015  1015 D BluetoothA2dp: Proxy object connected
,08-29 18:40:12.466  1172  1202 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:12.466  3901  3901 D BluetoothMap: Proxy object connected
08-29 18:40:12.466  3901  3901 D MapProfile: Bluetooth service connected
08-29 18:40:12.466  3901  3901 D BluetoothMap: getConnectedDevices()
,08-29 18:40:12.466  1172  1202 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 18:40:12.466  3901  3909 D Bluetoothsap: onBluetoothStateChange: up=true
08-29 18:40:12.466  3901  3909 D Bluetoothsap: Binding service...
,08-29 18:40:12.466  3901  3901 D BluetoothPbap: Proxy object connected
,08-29 18:40:12.466  3901  3909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-29 18:40:12.466  3901  3901 D PbapServerProfile: Bluetooth service connected
,08-29 18:40:12.466  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-29 18:40:12.466  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.466  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.466  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.466  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 18:40:12.466  7725  7801 D BluetoothSocket: bindListen(): myUserId = 0
08-29 18:40:12.466  7725  7801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:12.466  3901  3909 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 18:40:12.476  1422  1430 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:12.476  7725  7801 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-29 18:40:12.476  7725  7801 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 18:40:12.476  7725  7801 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 18:40:12.476  7725  7801 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e3a9109
,08-29 18:40:12.476  3901  3901 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 18:40:12.476  7725  7801 D BluetoothSocket: channel: 19
08-29 18:40:12.476  7725  7801 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-29 18:40:12.476  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 18:40:12.476  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 18:40:12.476  3901  3901 D SapProfile: Bluetooth service connected
,08-29 18:40:12.476  3901  3901 D Bluetoothsap: getConnectedDevices()
08-29 18:40:12.476  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:12.476  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.476  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.476  1422  1430 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 18:40:12.476  3901  3917 D BluetoothPan: Binding service...
,08-29 18:40:12.476  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 18:40:12.476  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.476  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.476  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.476  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.476  3901  3918 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 18:40:12.476  3901  3901 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 18:40:12.476  3901  3901 D PanProfile: Bluetooth service connected
08-29 18:40:12.476  3901  3918 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 18:40:12.476  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 18:40:12.476  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.486  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:12.486  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.486  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.486  3901  3917 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 18:40:12.486  3901  3901 D BluetoothA2dp: Proxy object connected
08-29 18:40:12.486  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 18:40:12.486  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.486  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.486  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.486  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 18:40:12.486  3901  3901 D A2dpProfile: Bluetooth service connected
,08-29 18:40:12.486  7725  7739 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 18:40:12.486  7725  7739 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 18:40:12.486  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 18:40:12.486  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 18:40:12.486  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 18:40:12.486  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-29 18:40:12.486  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 18:40:12.496  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-29 18:40:12.496  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 18:40:12.496  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:12.506  1422  1422 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1e1fd66a, true
,08-29 18:40:12.506  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:12.506  1172  1172 D BluetoothTile:  getBluetoothState : 12
,08-29 18:40:12.506  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:12.506  1422  1422 D BluetoothHeadset: registerMessageListener
,08-29 18:40:12.506  1172  1763 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 18:40:12.506  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 18:40:12.506  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 18:40:12.516  1015  1335 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 18:40:12.516  1015  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 18:40:12.516  7725  7733 D HeadsetService: registerMessageListener
,08-29 18:40:12.516  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:12.516  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.516  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 18:40:12.516  7725  7733 D HeadsetService: registerMessageListener
,08-29 18:40:12.516  7725  7750 D HeadsetStateMachine: Disconnected process message: 70
08-29 18:40:12.516  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-29 18:40:12.516  3901  3901 D BluetoothInputDevice: Proxy object connected
08-29 18:40:12.516  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 18:40:12.516  3901  3901 D HidProfile: Bluetooth service connected
08-29 18:40:12.516  7725  7750 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2d16af0e
,08-29 18:40:12.516  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.516  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:12.516  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:12.526  3901  3901 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:12.526  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 18:40:12.526  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-29 18:40:12.526  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 18:40:12.526  7725  7803 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-29 18:40:12.526  7725  7750 D HeadsetStateMachine: Disconnected process message: 9
,08-29 18:40:12.526  7725  7750 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 18:40:12.526  3901  3901 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-29 18:40:12.526  7725  7803 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 18:40:12.526  7725  7803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:12.526  3901  3901 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-29 18:40:12.526  7725  7803 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-29 18:40:12.526  7725  7803 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 18:40:12.526  3901  3901 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 18:40:12.526  3901  3901 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-29 18:40:12.526  7725  7803 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 18:40:12.526  7725  7803 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ed2fd2f
,08-29 18:40:12.526  7725  7803 D BluetoothSocket: channel: 5
,08-29 18:40:12.536   281   709 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-29 18:40:12.536   281   709 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 18:40:12.536   281   709 V voice   : voice_set_parameters: exit with code(-2)
08-29 18:40:12.536   281   709 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 18:40:12.536   281   709 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 18:40:12.536   281   709 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 18:40:12.536   281   709 V audio_hw_primary: adev_set_parameters: exit
08-29 18:40:12.536  7725  7750 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 18:40:12.546  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 18:40:12.546  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 18:40:12.546  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.546  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.546  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.546  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 18:40:12.546  3901  3901 D DockEventReceiver: finishStartingService: stopping service
,08-29 18:40:12.556  3901  3901 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 18:40:12.556  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 18:40:12.556  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 18:40:12.566  7725  7725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:12.566  7725  7725 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 18:40:12.566  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 18:40:12.566  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.566  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:12.566  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:12.566  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 18:40:12.596  2003  2003 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 18:40:12.596  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 18:40:12.596  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 18:40:12.596  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:12.596  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:12.596  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:12.596  1015  1215 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 18:40:12.606  2003  7813 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 18:40:12.606  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:40:12.606  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.606  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:12.606  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:12.606  2003  2003 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 18:40:12.616  7725  7814 D BluetoothSocket: bindListen(): myUserId = 0
08-29 18:40:12.616  7725  7814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 18:40:12.626  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 18:40:12.626  7725  7814 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-29 18:40:12.626  7725  7814 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 18:40:12.626  7725  7814 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 18:40:12.626  7725  7814 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32c65841
,08-29 18:40:12.626  7725  7814 D BluetoothSocket: channel: 12
08-29 18:40:12.626  7725  7814 I BtOppRfcommListener: Accept thread started.
,08-29 18:40:12.626  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:12.626  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:12.626  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:12.636  2003  7813 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-29 18:40:13.316  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:13.316  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:13.316  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:13.316  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 18:40:13.316  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:13.316  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:13.316  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:13.316  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:13.316  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:13.326  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:13.326  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@212ba12f added. We now have 8 listener(s)
08-29 18:40:13.326  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:13.326  1015  1495 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 18:40:13.326  1015  1495 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 18:40:13.326  1015  1495 D SecContentProvider2: mCursor = null
,08-29 18:40:13.326  1015  1495 D WifiService: setWifiEnabled: false pid=6901, uid=10171
,08-29 18:40:13.336  1015  1495 D SettingsProvider: name = wifi_on
,08-29 18:40:13.336  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:13.336  1015  1748 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 18:40:13.336  1015  1748 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 18:40:13.336  1015  1748 D SecContentProvider2: mCursor = null
,08-29 18:40:13.336  1015  1748 D WifiService: setWifiEnabled: true pid=6901, uid=10171
,08-29 18:40:13.336  1015  1748 W ActivityManager: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 18:40:13.346  1015  1748 W WifiService: Failed getting userId using ActivityManagerNative
08-29 18:40:13.346  1015  1748 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6901, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 18:40:13.346  1015  1748 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 18:40:13.346  1015  1748 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 18:40:13.346  1015  1748 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 18:40:13.346  1015  1748 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 18:40:13.346  1015  1748 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 18:40:13.346  1015  1748 D SettingsProvider: name = wifi_on
,08-29 18:40:13.356  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 18:40:13.456   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 18:40:13.676  1015  1043 D Tethering: interfaceAdded wlan0
,08-29 18:40:13.676  1015  1129 E Tethering: No numeric data
,08-29 18:40:13.686  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 18:40:13.686  1015  1129 D Tethering: clearTetheredNotification()
,08-29 18:40:13.686  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 18:40:13.686  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:13.686  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 18:40:13.686  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 18:40:13.696  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 18:40:13.696  1172  1172 D HotspotTile: updateTetherState():false, false
08-29 18:40:13.696  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 18:40:13.696  1015  1121 V NetworkStats: performPollLocked() took 9ms
,08-29 18:40:13.696  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:40:13.696  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:40:13.696  1015  1129 D Tethering: InitialState.processMessage what=4
08-29 18:40:13.696  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 18:40:13.696  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:13.696  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:13.706  1015  1129 E Tethering: No numeric data
,08-29 18:40:13.706  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 18:40:13.706  1015  1129 D Tethering: clearTetheredNotification()
,08-29 18:40:13.706  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 18:40:13.706  1015  1043 D Tethering: interfaceAdded p2p0
,08-29 18:40:13.706  1172  1172 D HotspotTile: updateTetherState():false, false
,08-29 18:40:13.706  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-29 18:40:13.716  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 18:40:13.716  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:13.716  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 18:40:13.716  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 18:40:13.716  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 18:40:13.716  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 18:40:13.726   276   954 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-29 18:40:13.726  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 18:40:13.726   276   954 D SoftapController: Softap fwReload - Ok
,08-29 18:40:13.726   276   954 D CommandListener: Setting iface cfg
08-29 18:40:13.726   276   954 D CommandListener: Trying to bring down wlan0
,08-29 18:40:13.726   276   954 D CommandListener: Clearing all IP addresses on wlan0
08-29 18:40:13.726  1015  1121 V NetworkStats: performPollLocked() took 14ms
08-29 18:40:13.726  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:13.726  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:13.726  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:13.736  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 18:40:13.746  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-29 18:40:13.746  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:40:13.756  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 18:40:13.756  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:13.756  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:13.756  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:13.756  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:13.756  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:13.756  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-29 18:40:13.756  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 18:40:13.766  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:13.766  1172  1172 D HotspotTile: onReceive : 2, 0
,08-29 18:40:13.766  3901  3901 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:13.766  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:13.776  1015  1477 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 18:40:13.776  1015  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:40:13.776  1015  1477 W ActivityManager: userId = 0, bbcId = -10000,
08-29 18:40:13.776  1015  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:13.776  1015  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:40:13.786  1631  1631 I Hs20UtilService: Starting #19
08-29 18:40:13.786  1631  1727 I Hs20UtilService: Message received 5011
,08-29 18:40:13.786  7826  7826 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-29 18:40:13.786  7826  7826 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 18:40:13.786  7826  7826 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 18:40:13.796  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 18:40:13.796  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 18:40:13.796  7177  7177 D SecurityLogAgent: StateMachine : Current State = 1
08-29 18:40:13.796  7177  7177 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 18:40:13.806  7826  7826 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-29 18:40:13.806   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7826
08-29 18:40:13.806   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 18:40:13.806  7826  7826 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 18:40:13.806  7826  7826 I wpa_supplicant: ssSupport state is = 1
08-29 18:40:13.806  7826  7826 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 18:40:13.806  7826  7826 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-29 18:40:13.806   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7826
08-29 18:40:13.806   327   327 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-29 18:40:13.946   327   327 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-29 18:40:13.946  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-29 18:40:13.996  7826  7826 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-29 18:40:13.996  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 18:40:14.006  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-29 18:40:14.006   327   327 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7826
08-29 18:40:14.006   327   327 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 18:40:14.006  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 18:40:14.006  7826  7826 I wpa_supplicant: ssSupport state is = 1
08-29 18:40:14.006  7826  7826 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 18:40:14.006  7826  7826 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 18:40:14.006  7826  7826 E wpa_supplicant: SIM READ ERROR
08-29 18:40:14.006  7826  7826 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 18:40:14.006  7826  7826 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 18:40:14.006  7826  7826 E wpa_supplicant: SIM READ ERROR
,08-29 18:40:14.006  7826  7826 I wpa_supplicant: Blacklist: Clear (all) 
08-29 18:40:14.006  7826  7826 I wpa_supplicant: wpa_default_ap_write_once
08-29 18:40:14.006  7826  7826 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 18:40:14.006  7826  7826 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 18:40:14.006  7826  7826 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,08-29 18:40:14.006  7826  7826 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 18:40:14.006  7826  7826 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-29 18:40:14.006  7826  7826 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-29 18:40:14.006  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 18:40:14.006  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:40:14.006  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 18:40:14.086  7826  7826 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-29 18:40:14.266  7826  7826 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-29 18:40:14.266  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-29 18:40:14.276  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-29 18:40:14.286   327   327 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7826
08-29 18:40:14.286   327   327 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-29 18:40:14.286  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 18:40:14.286  7826  7826 I wpa_supplicant: ssSupport state is = 1
08-29 18:40:14.286  7826  7826 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-29 18:40:14.286  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 18:40:14.296  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 18:40:14.296   327   327 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7826
08-29 18:40:14.296   327   327 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 18:40:14.296  7826  7826 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 18:40:14.296  7826  7826 I wpa_supplicant: ssSupport state is = 1
08-29 18:40:14.296  7826  7826 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 18:40:14.296  7826  7826 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 18:40:14.296  7826  7826 E wpa_supplicant: SIM READ ERROR
08-29 18:40:14.296  7826  7826 I wpa_supplicant: wpa_default_ap_write_once
08-29 18:40:14.296  7826  7826 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 18:40:14.296  7826  7826 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 18:40:14.306  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 18:40:14.306  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 18:40:14.306  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 18:40:14.306  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 18:40:14.306  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 18:40:14.306  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 18:40:14.416  7826  7826 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-29 18:40:14.416  7826  7826 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 18:40:14.496  7826  7826 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-29 18:40:14.496  7826  7826 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 18:40:14.496  7826  7826 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 18:40:14.506  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-29 18:40:14.506  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 18:40:14.506  7826  7826 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-29 18:40:14.506  7826  7826 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 18:40:14.506  7826  7826 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 18:40:14.506  7826  7826 E wpa_supplicant: SIM READ ERROR
08-29 18:40:14.506  7826  7826 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 18:40:14.526  7826  7826 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-29 18:40:14.536  7826  7826 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-29 18:40:14.536  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:40:14.546  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:40:14.546  1172  1763 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 18:40:14.546  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:14.546  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 18:40:14.546  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:14.546  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:14.546  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:14.546  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 18:40:14.546  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-29 18:40:14.546  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
,08-29 18:40:14.546  1172  1172 D HotspotTile: onReceive : 3, 0
,08-29 18:40:14.556  3901  3901 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 18:40:14.566  1015  1124 E WifiConfigStore: Not a HS20
,08-29 18:40:14.566  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 18:40:14.566  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:14.566  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:14.566  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:14.566  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:14.566  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:14.566  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:14.566  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:14.566  6901  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:14.566  1015  1218 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:40:14.566  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-29 18:40:14.566  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 18:40:14.566  6901  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:14.566  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:14.566  1015  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:14.566  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 18:40:14.566  1631  1631 I Hs20UtilService: Starting #20
08-29 18:40:14.566  1631  1727 I Hs20UtilService: Message received 5011
,08-29 18:40:14.576  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 18:40:14.576  7826  7826 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 18:40:14.576  7826  7826 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 18:40:14.576  7826  7826 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-29 18:40:14.576  7826  7826 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 18:40:14.576  7826  7826 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 18:40:14.576  7826  7826 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 18:40:14.576  7826  7826 I wpa_supplicant: First Scan Start
,08-29 18:40:14.576  7826  7826 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 18:40:14.576  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 18:40:14.576  7177  7177 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 18:40:14.576  7177  7177 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 18:40:14.576  7177  7177 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-29 18:40:14.576  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
,08-29 18:40:14.576  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 18:40:14.576  1015  1124 I WifiNative-HAL: startHal
08-29 18:40:14.576  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d53d88c
08-29 18:40:14.576  1015  1124 I WifiNative-HAL: Could not start hal
,08-29 18:40:14.576  7154  7154 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 18:40:14.586  1015  1124 E WifiNative-wlan0: do suspend true
,08-29 18:40:14.586  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 18:40:14.586   276   954 D CommandListener: Setting iface cfg
08-29 18:40:14.586   276   954 D CommandListener: Trying to bring up p2p0
,08-29 18:40:14.586  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 18:40:14.586  1015  1123 D WifiP2pService: P2pEnablingState
,08-29 18:40:14.586  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-29 18:40:14.586  1015  1123 D WifiP2pService: P2p socket connection successful
08-29 18:40:14.586  1015  1123 D WifiP2pService: P2pEnabledState
,08-29 18:40:14.596  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-29 18:40:14.596  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 18:40:14.596  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-29 18:40:14.596  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 18:40:14.596  1015  1046 D WifiDisplayController: disconnect
,08-29 18:40:14.596  1015  1046 D WifiDisplayController: updateConnection
08-29 18:40:14.596  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-29 18:40:14.596  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 18:40:14.596  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-29 18:40:14.596  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 18:40:14.596  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 18:40:14.596  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 18:40:14.596  1015  1124 E WifiNative-wlan0: invaild command id : 215
08-29 18:40:14.596  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-29 18:40:14.596  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-29 18:40:14.596  1015  1147 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:14.596  1015  1147 I WifiNative-HAL: startHal
08-29 18:40:14.596  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e1d59bc
08-29 18:40:14.596  1015  1147 I WifiNative-HAL: Could not start hal
08-29 18:40:14.596  1015  1147 E WifiScanningService: could not start HAL
08-29 18:40:14.596  1015  1148 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 18:40:14.596  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 18:40:14.596  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 18:40:14.596  1015  1124 E WifiNative-wlan0: invaild command id : 215
,08-29 18:40:14.606  7826  7826 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-29 18:40:14.606  7826  7826 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 18:40:14.606  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 18:40:14.606  7826  7826 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 18:40:14.606  1015  1477 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 18:40:14.606  1015  1124 E WifiStateMachine: Failed to set frequency band 0
08-29 18:40:14.606  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 18:40:14.606  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:40:14.606  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 18:40:14.606  1015  1124 D SecContentProvider2: mCursor = null
08-29 18:40:14.606  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 18:40:14.606  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 18:40:14.606  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 18:40:14.616  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 18:40:14.616  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 18:40:14.616  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 18:40:14.616  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:40:14.616  1015  1124 D SecContentProvider2: mCursor = null
08-29 18:40:14.616  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
08-29 18:40:14.616  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-29 18:40:14.616  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 18:40:14.616  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 18:40:14.616  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 18:40:14.616  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
08-29 18:40:14.616  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 18:40:14.616  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  secondary type: null
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  wps: 0
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  grpcapab: 0
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  devcapab: 0
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  status: 3
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  wfdInfo: null
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-29 18:40:14.616  1015  1046 D WifiDisplayController:  SConnectInfo : null
08-29 18:40:14.616  7517  7517 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 18:40:14.626  7517  7517 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 18:40:14.626  7517  7517 D FileShare-Client: Outbound.stopDelayTimer - 
08-29 18:40:14.626  7532  7532 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 18:40:14.636  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
08-29 18:40:14.636  1015  1123 D WifiP2pService: InactiveState
08-29 18:40:14.636  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
08-29 18:40:14.636  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
08-29 18:40:14.636  7826  7826 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 18:40:14.636  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
08-29 18:40:14.636  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 18:40:14.696  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 18:40:14.696  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 18:40:14.696  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 18:40:15.366  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 18:40:15.366  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:15.366  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:15.366  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:15.366  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:15.366  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:15.366  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:15.366  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:15.366  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:15.366  6901  6955 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 18:40:15.376  6901  6955 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 18:40:15.376  6901  6955 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@10b1d82d Bundle[{}]
08-29 18:40:15.376  6901  6955 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 18:40:15.376  6901  6955 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 18:40:15.376  6901  6955 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 18:40:15.376  6901  6955 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 18:40:15.376  6901  6955 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 18:40:15.376  6901  6955 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 18:40:15.376  6901  6955 I System.out: Running OutgoingSocketThread
,08-29 18:40:15.386  6901  7833 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1380)
,08-29 18:40:15.386  6901  7833 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57715
,08-29 18:40:15.386  6901  7833 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 18:40:15.426   288   288 E SMD     : DCD OFF
,08-29 18:40:15.746  1015  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 18:40:15.746  1015  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 18:40:15.746  1015  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 18:40:15.746  1015  1218 D BatteryService: stay LED for fully charged
08-29 18:40:15.746  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 18:40:15.746  1015  1015 I MotionRecognitionService: Plugged,
08-29 18:40:15.746  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-29 18:40:15.756  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 18:40:15.756  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 18:40:15.756  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 18:40:15.756  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 18:40:15.766  7725  7725 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 18:40:15.766  7725  7750 D HeadsetStateMachine: Disconnected process message: 10
,08-29 18:40:15.776  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:40:15.786  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:40:15.786  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 18:40:15.806  7826  7826 I wpa_supplicant: nl80211: Received scan results (31 BSSes)
08-29 18:40:15.806  7826  7826 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-29 18:40:15.806  7826  7826 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-29 18:40:15.806  7826  7826 I wpa_supplicant: Trying to associate with  'G700',
08-29 18:40:15.806  7826  7826 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-29 18:40:15.806  7826  7826 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-29 18:40:15.816  1015  7831 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 18:40:15.816  1015  1094 V AlarmManager: waitForAlarm result :4
,08-29 18:40:15.826  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:40:15.826  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:40:15.836  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-29 18:40:15.836  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-29 18:40:15.836  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-29 18:40:15.846  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-29 18:40:15.846  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 18:40:15.856  1015  1015 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-29 18:40:15.856  1015  1015 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,08-29 18:40:15.856  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-29 18:40:15.856  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
,08-29 18:40:15.866  1015  1015 I BackgroundCompactionService: onStart. jobID=801
,08-29 18:40:15.866  1015  1015 I BackgroundCompactionService: onStart done. jobID=801
,08-29 18:40:15.866  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 18:40:15.866  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-29 18:40:15.866  1172  1172 I KeyguardEffectViewController: *** don't update sliding image ***
,08-29 18:40:15.876  1015  7836 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
08-29 18:40:15.876  1015  7836 I BackgroundCompactionService: compact_memory command done
,08-29 18:40:15.906  1015  1048 I PowerManagerService: [PWL] Off : 30s ago
,08-29 18:40:15.906  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-29 18:40:15.906  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 18:40:15.906  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 18:40:15.906  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=22302)
08-29 18:40:15.906  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=7725, ws=null) (elapsedTime=3683)
08-29 18:40:15.906  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1015, ws=WorkSource{1000}) (elapsedTime=76)
,08-29 18:40:15.916  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 18:40:15.916  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 18:40:15.926  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 18:40:15.926  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 18:40:15.926  7826  7826 E wpa_supplicant: Cmd 35605 not handled
08-29 18:40:15.926  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 18:40:15.926  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 18:40:15.926  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 18:40:15.936  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 18:40:15.936  7826  7826 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-29 18:40:15.936  7826  7826 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 18:40:15.936  7826  7826 I wpa_supplicant: Associated with F4.99.3E
08-29 18:40:15.936  7826  7826 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 18:40:15.936  7826  7826 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-29 18:40:15.936  7826  7826 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-29 18:40:15.936  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 18:40:15.936  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 18:40:15.936  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 18:40:15.946  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 18:40:15.946  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-29 18:40:15.946  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-29 18:40:15.946  1015  3354 D SSRM:n  : SIOP:: AP = 350
08-29 18:40:15.946  1015  1129 E Tethering: No numeric data
,08-29 18:40:15.946  7826  7826 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 18:40:15.956  7826  7826 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-29 18:40:15.956  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:40:15.956  1015  1124 D SecContentProvider2: mCursor = null
08-29 18:40:15.956  7826  7826 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 18:40:15.956  7826  7826 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 18:40:15.956  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 18:40:15.956  1015  1129 D Tethering: clearTetheredNotification()
08-29 18:40:15.956  7826  7826 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-29 18:40:15.956  7826  7826 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 18:40:15.956  7826  7826 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 18:40:15.956  7826  7826 I wpa_supplicant: Blacklist: Clear (temp) 
08-29 18:40:15.956  7826  7826 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 18:40:15.956  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true,
08-29 18:40:15.956  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-29 18:40:15.956  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 18:40:15.956  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:15.956  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 18:40:15.956  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:40:15.956  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-29 18:40:15.956  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 18:40:15.956  1172  1172 D HotspotTile: updateTetherState():false, false
,08-29 18:40:15.956  1015  1121 V NetworkStats: performPollLocked() took 5ms
08-29 18:40:15.956  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:15.966  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 18:40:15.966  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:15.966  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:15.966  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 18:40:15.966  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:40:15.976  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-29 18:40:15.976  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 18:40:15.986  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:40:15.986  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:40:15.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:15.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:15.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:15.986  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:15.986  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 18:40:15.986  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 18:40:15.986  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:40:15.986  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:40:15.986  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 18:40:15.986  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 18:40:15.986  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:40:15.986  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:15.986  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:15.986  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:40:15.986  1631  1631 I Hs20UtilService: Starting #21
,08-29 18:40:15.986  1631  1727 I Hs20UtilService: Message received 5007
,08-29 18:40:15.986  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 18:40:15.996  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 18:40:15.996  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 18:40:15.996  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 18:40:15.996  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 18:40:15.996  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 18:40:15.996  3901  3901 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 18:40:15.996  3901  3976 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 18:40:16.006   276   954 D CommandListener: Setting iface cfg
,08-29 18:40:16.006  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,08-29 18:40:16.006  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 18:40:16.006  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:40:16.016  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 18:40:16.016  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-29 18:40:16.016  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:16.016  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.016  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:16.016  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:16.026  1015  1124 E WifiNative-wlan0: do suspend false
,08-29 18:40:16.026  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-29 18:40:16.026  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 18:40:16.026  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 18:40:16.026  1015  1124 D SecContentProvider2: mCursor = null
,08-29 18:40:16.236  7840  7840 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-29 18:40:16.246  7840  7840 I dhcpcd  : version 5.5.6 starting
,08-29 18:40:16.246  7840  7840 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-29 18:40:16.296  7840  7840 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-29 18:40:16.296  7840  7840 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 18:40:16.296  7840  7840 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-29 18:40:16.296  7840  7840 I dhcpcd  : bssid match
08-29 18:40:16.296  7840  7840 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-29 18:40:16.386  6901  6955 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1381)
08-29 18:40:16.386  6901  6955 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1381)
08-29 18:40:16.386  6901  6955 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1386)
08-29 18:40:16.386  6901  6955 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-29 18:40:16.386  6901  6955 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1387)
08-29 18:40:16.386  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.386  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40a233c added. We now have 2 listener(s)
,08-29 18:40:16.396  7840  7840 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-29 18:40:16.396  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 18:40:16.396  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 18:40:16.396  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:16.396  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:16.396  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7578c5 added. We now have 9 listener(s)
,08-29 18:40:16.396  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:16.396  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 18:40:16.396  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:16.406  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 18:40:16.406  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:16.406  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:16.406  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:16.406  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:16.406  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:16.406  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:16.406  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:16.406  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:16.406  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:40:16.406  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.406  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285b214b added. We now have 3 listener(s)
,08-29 18:40:16.406  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 18:40:16.406  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3df43728 added. We now have 10 listener(s),
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:16.416  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 18:40:16.416  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:16.416  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:16.416  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40a233c removed from the list
08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7578c5 removed from the list
08-29 18:40:16.416  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:16.416  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.416  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7578c5 not in the list
08-29 18:40:16.416  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3df43728 removed from the list
08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 18:40:16.416  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:16.416  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285b214b removed from the list
08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab9dc41 added. We now have 2 listener(s)
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-29 18:40:16.416  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d84c5e6 added. We now have 9 listener(s)
08-29 18:40:16.416  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:16.426  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 18:40:16.426  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:16.426  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:16.426  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:16.426  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:16.426  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-29 18:40:16.426  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:16.426  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:16.426  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:16.426  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:16.436  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:16.436  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:40:16.436  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 18:40:16.436  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.436  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15e99dd4 added. We now have 3 listener(s)
08-29 18:40:16.436  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 18:40:16.436  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 18:40:16.436  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:16.436  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:16.436  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:16.436  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2886fb7d added. We now have 10 listener(s)
08-29 18:40:16.436  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:16.436  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:16.436  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:16.436  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:16.436  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:16.436  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 18:40:16.446  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 18:40:16.446  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:40:16.446  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 18:40:16.456  7840  7840 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-29 18:40:16.466  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-29 18:40:16.466  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 18:40:16.466  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-29 18:40:16.476  7725  7804 D BtGatt.GattService: registerClient() - UUID=63752e72-b7b0-48fe-a054-4023f0267431,
,08-29 18:40:16.516  7725  7743 D BtGatt.GattService: onClientRegistered() - UUID=63752e72-b7b0-48fe-a054-4023f0267431, clientIf=6
,08-29 18:40:16.516  6901  6914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-29 18:40:16.516  7725  7802 D BtGatt.GattService: start scan with filters
08-29 18:40:16.526  7725  7748 D BtGatt.ScanManager: handling starting scan
08-29 18:40:16.526  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 18:40:16.526  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 18:40:16.526  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 18:40:16.526  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:40:16.526  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:16.526  7725  7748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f407767
,08-29 18:40:16.536  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 18:40:16.536  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:16.536  7725  7743 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 18:40:16.536  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:40:16.536  7725  7748 D BtGatt.ScanManager: allow scan with filters
,08-29 18:40:16.536  7725  7748 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 18:40:16.536  7725  7748 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-29 18:40:16.536  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:40:16.546  7725  7743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 18:40:16.546  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.546  7725  7748 D BtGatt.ScanManager: Starting BLE batch scan
08-29 18:40:16.546  7725  7748 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 18:40:16.546  7725  7743 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-29 18:40:16.546  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:40:16.546  6901  6955 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 18:40:16.546  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:16.546  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 18:40:16.546  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.546  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 18:40:16.546  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 18:40:16.546  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 18:40:16.546  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:40:16.546  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 18:40:16.546  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 18:40:16.546  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 18:40:16.546  7725  7743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 18:40:16.546  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.556  7725  7739 D BtGatt.GattService: stopScan() - queue size =1
,08-29 18:40:16.556  7725  7748 D BtGatt.ScanManager: filter size is 1
,08-29 18:40:16.556  7725  7748 D BtGatt.ScanManager: delete FilterIndex - 3
,08-29 18:40:16.556  7725  7743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 18:40:16.556  7725  7804 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 18:40:16.556  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 18:40:16.556  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:40:16.556  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 18:40:16.556  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:40:16.556  7725  7748 D BtGatt.ScanManager: stopping BLe Batch
08-29 18:40:16.566  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:40:16.566  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 18:40:16.566  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:40:16.566  7725  7743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-29 18:40:16.576  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:40:16.576  7725  7748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 18:40:16.576  7725  7743 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-29 18:40:16.576  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.586  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 18:40:16.586  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:16.586  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:16.586  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:16.586  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:16.586  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:16.586  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:16.586  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.586  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.586  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab9dc41 removed from the list
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.586  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d84c5e6 removed from the list
08-29 18:40:16.586  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:16.586  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:16.586  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.586  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:16.586  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:16.586  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.586  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d84c5e6 not in the list
08-29 18:40:16.586  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.586  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:16.586  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2886fb7d removed from the list
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:16.586  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.586  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:16.586  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.586  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15e99dd4 removed from the list
,08-29 18:40:16.586  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.586  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@190cd279 added. We now have 2 listener(s)
,08-29 18:40:16.596  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 18:40:16.596  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:16.596  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:16.596  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 18:40:16.596  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@152cabbe added. We now have 9 listener(s)
08-29 18:40:16.596  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:16.596  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 18:40:16.596  1015  1041 W ProcessCpuTracker: Skipping unknown process pid 7853
,08-29 18:40:16.606  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:16.606  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:16.606  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:16.606  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:16.606  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:16.606  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:16.606  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:16.606  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:16.606  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:16.616  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 18:40:16.616  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:40:16.616  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.616  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbad36c added. We now have 3 listener(s)
08-29 18:40:16.616  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 18:40:16.616  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:16.616  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 18:40:16.616  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:16.616  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97f1d35 added. We now have 10 listener(s)
08-29 18:40:16.616  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:16.616  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:16.616  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:16.616  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 18:40:16.616  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:16.616  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:16.616  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 18:40:16.616  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 18:40:16.616  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:16.626  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:16.626  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:40:16.626  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 18:40:16.636  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-29 18:40:16.636  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 18:40:16.636  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 18:40:16.636  7725  7802 D BtGatt.GattService: registerClient() - UUID=b06f6d14-36fe-493d-abab-3800a4616ea1,
,08-29 18:40:16.676  7725  7743 D BtGatt.GattService: onClientRegistered() - UUID=b06f6d14-36fe-493d-abab-3800a4616ea1, clientIf=6
08-29 18:40:16.676  6901  6948 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 18:40:16.676  7725  7733 D BtGatt.GattService: start scan with filters
,08-29 18:40:16.676  7725  7748 D BtGatt.ScanManager: handling starting scan
,08-29 18:40:16.676  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 18:40:16.686  7725  7743 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 18:40:16.686  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:40:16.686  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 18:40:16.686  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 18:40:16.686  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 18:40:16.686  7725  7748 D BtGatt.ScanManager: allow scan with filters
08-29 18:40:16.686  7725  7748 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 18:40:16.686  7725  7748 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-29 18:40:16.686  7725  7743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 18:40:16.686  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:40:16.686  7725  7748 D BtGatt.ScanManager: Starting BLE batch scan
08-29 18:40:16.686  7725  7748 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 18:40:16.686  7725  7743 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 18:40:16.686  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.686  7725  7743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 18:40:16.686  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.696  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 18:40:16.696  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 18:40:16.696  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 18:40:16.696  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:16.696  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 18:40:16.696  6901  6955 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 18:40:16.696  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:16.696  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:16.696  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 18:40:16.696  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:16.696  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.696  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 18:40:16.696  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.696  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@190cd279 removed from the list
08-29 18:40:16.696  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 18:40:16.696  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@152cabbe removed from the list
08-29 18:40:16.696  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:16.696  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:16.696  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.696  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 18:40:16.706  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:16.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:16.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:16.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.706  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@152cabbe not in the list
08-29 18:40:16.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 18:40:16.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:40:16.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 18:40:16.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 18:40:16.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 18:40:16.706  7725  7804 D BtGatt.GattService: stopScan() - queue size =1
,08-29 18:40:16.706  7725  7748 D BtGatt.ScanManager: filter size is 1
08-29 18:40:16.706  7725  7748 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 18:40:16.706  7725  7802 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 18:40:16.706  7725  7743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 18:40:16.706  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:40:16.706  7725  7748 D BtGatt.ScanManager: stopping BLe Batch
,08-29 18:40:16.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:16.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:40:16.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 18:40:16.706  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:40:16.706  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 18:40:16.716  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-29 18:40:16.716  7725  7743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 18:40:16.716  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.716  7725  7748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 18:40:16.716  7725  7743 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-29 18:40:16.716  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.716  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 18:40:16.716  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:40:16.716  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 18:40:16.716  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:16.726  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:16.726  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:16.726  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.736  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97f1d35 removed from the list
08-29 18:40:16.736  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:16.736  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.736  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:16.736  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.736  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbad36c removed from the list
,08-29 18:40:16.736  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.736  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c9157b1 added. We now have 2 listener(s)
,08-29 18:40:16.736  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 18:40:16.736  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:16.736  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:40:16.736  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 18:40:16.736  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:16.736  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 18:40:16.736  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:16.736  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16807496 added. We now have 9 listener(s)
08-29 18:40:16.736  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 18:40:16.736  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 18:40:16.736  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 18:40:16.746  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:16.746  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:16.746  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:16.746  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:16.746  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:16.746  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:16.746  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:16.746  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:16.746  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:16.746  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 18:40:16.746  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:16.746  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.746  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a2404 added. We now have 3 listener(s)
,08-29 18:40:16.746  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:16.746  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 18:40:16.746  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:16.746  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:16.746  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:16.746  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b2bded added. We now have 10 listener(s)
08-29 18:40:16.746  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:16.746  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:16.746  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 18:40:16.746  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 18:40:16.746  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 18:40:16.746  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 18:40:16.756  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 18:40:16.756  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 18:40:16.756  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 18:40:16.756  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 18:40:16.766  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 18:40:16.766  6901  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 18:40:16.766  7725  7804 D BtGatt.GattService: registerClient() - UUID=d73b48db-d213-4990-ac1f-bb04fd81473a
,08-29 18:40:16.806  7725  7743 D BtGatt.GattService: onClientRegistered() - UUID=d73b48db-d213-4990-ac1f-bb04fd81473a, clientIf=6
,08-29 18:40:16.806  6901  6914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 18:40:16.806  7725  7733 D BtGatt.GattService: start scan with filters
,08-29 18:40:16.806  7725  7748 D BtGatt.ScanManager: handling starting scan
,08-29 18:40:16.806  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 18:40:16.806  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 18:40:16.806  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 18:40:16.806  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 18:40:16.816  7725  7743 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 18:40:16.816  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.816  7725  7748 D BtGatt.ScanManager: allow scan with filters
08-29 18:40:16.816  7725  7748 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 18:40:16.816  7725  7748 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-29 18:40:16.816  7725  7743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 18:40:16.816  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.816  7725  7748 D BtGatt.ScanManager: Starting BLE batch scan
08-29 18:40:16.816  7725  7748 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 18:40:16.826  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:16.826  7725  7743 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 18:40:16.826  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.826  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 18:40:16.826  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 18:40:16.826  7725  7743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 18:40:16.826  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.826  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 18:40:16.836  1015  1124 E WifiNative-wlan0: do suspend true
,08-29 18:40:16.836  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 18:40:16.836  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 18:40:16.836  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:16.836  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:16.836  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.836  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 18:40:16.836  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.836  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c9157b1 removed from the list
08-29 18:40:16.836  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.836  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16807496 removed from the list
08-29 18:40:16.836  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:16.836  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:16.836  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.836  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 18:40:16.836  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.836  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 18:40:16.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:16.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:16.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.846  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16807496 not in the list
,08-29 18:40:16.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 18:40:16.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 18:40:16.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 18:40:16.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 18:40:16.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 18:40:16.846  7725  7804 D BtGatt.GattService: stopScan() - queue size =1
,08-29 18:40:16.846  7725  7748 D BtGatt.ScanManager: filter size is 1
,08-29 18:40:16.846  7725  7748 D BtGatt.ScanManager: delete FilterIndex - 5
,08-29 18:40:16.846  7725  7733 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 18:40:16.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 18:40:16.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 18:40:16.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 18:40:16.846  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 18:40:16.846  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 18:40:16.856  7725  7743 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 18:40:16.856  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:40:16.856  7725  7748 D BtGatt.ScanManager: stopping BLe Batch
,08-29 18:40:16.856  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 18:40:16.856  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 18:40:16.856  6901  6955 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 18:40:16.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 18:40:16.856  7725  7743 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 18:40:16.856  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 18:40:16.856  7725  7748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 18:40:16.856  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:16.856  7725  7743 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 18:40:16.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:16.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:16.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.856  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b2bded removed from the list
08-29 18:40:16.856  7725  7743 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 18:40:16.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:16.856  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.856  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:16.856  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.856  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a2404 removed from the list
08-29 18:40:16.856  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:16.856  6901  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 18:40:16.856  6901  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 18:40:16.856  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.856  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0a4be9 added. We now have 2 listener(s)
08-29 18:40:16.866  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
08-29 18:40:16.866  1015  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 18:40:16.866  1015  1124 E WifiStateMachine: VerifyingLinkState enter
08-29 18:40:16.866  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 18:40:16.866  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:40:16.866  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:40:16.866  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.866  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.866  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.866  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.866  1015  1126 E ConnectivityService: updateNetworkInfo()
,08-29 18:40:16.866  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-29 18:40:16.866  1015  1126 D ConnectivityService: Adding iface wlan0 to network 504
,08-29 18:40:16.866  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 18:40:16.866  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:16.866  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:16.866  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:16.866  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b9806e added. We now have 9 listener(s)
08-29 18:40:16.866  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:16.866  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 18:40:16.886  1015  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-29 18:40:16.886  1015  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 18:40:16.886  1015  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 18:40:16.886  1015  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-29 18:40:16.886  1015  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 18:40:16.886  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:40:16.886  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:40:16.886  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.886  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.886  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.886  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:16.896  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-29 18:40:16.896  1015  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-29 18:40:16.896  1015  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-29 18:40:16.896  1015  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-29 18:40:16.896  1015  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-29 18:40:16.896  1015  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 18:40:16.896  1015  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-29 18:40:16.896  1015  1126 D ConnectivityService: LTETest block dns file not exists
,08-29 18:40:16.906  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:40:16.906  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 18:40:16.906  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.906  1015  1126 V NetworkStats: updateIfacesLocked()
08-29 18:40:16.906  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-29 18:40:16.906  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:16.906  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:16.906  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 18:40:16.906  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:40:16.906  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 18:40:16.906  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 18:40:16.906  1015  1126 V NetworkStats: performPollLocked() took 6ms
08-29 18:40:16.906  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:16.906  1631  1631 I Hs20UtilService: Starting #22
,08-29 18:40:16.916  1631  1727 I Hs20UtilService: Message received 5007
,08-29 18:40:16.916  6901  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 18:40:16.916  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 18:40:16.916  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 18:40:16.916  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 18:40:16.916  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 18:40:16.916  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 18:40:16.916  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 18:40:16.916  6901  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 18:40:16.916  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:40:16.916  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 18:40:16.916  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.916  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.916  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.916  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:16.916  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 18:40:16.916  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 18:40:16.916  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 18:40:16.916  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-29 18:40:16.916  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-29 18:40:16.916  6901  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 18:40:16.916  6901  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 18:40:16.916  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 18:40:16.916  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20cfef9c added. We now have 3 listener(s)
,08-29 18:40:16.916  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:16.926  6901  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 18:40:16.926  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 18:40:16.926  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-29 18:40:16.926  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:16.936  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.936  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.936  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:16.936  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 18:40:16.936  3901  3901 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 18:40:16.936  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:16.936  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.936  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-29 18:40:16.936  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:40:16.936  1015  1126 E ConnectivityService: updateNetworkInfo()
08-29 18:40:16.936  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 18:40:16.936  1015  1126 V NetworkStats: updateIfacesLocked()
,08-29 18:40:16.936  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
08-29 18:40:16.936  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:16.946  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:40:16.946  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 18:40:16.946  1015  1126 V NetworkStats: performPollLocked() took 6ms
,08-29 18:40:16.946  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:16.946  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 18:40:16.946  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 18:40:16.946  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 18:40:16.946  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 18:40:16.946  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232bda5 added. We now have 10 listener(s)
08-29 18:40:16.946  6901  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 18:40:16.946  6901  6955 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 18:40:16.946  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:16.946  6901  6955 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 18:40:16.946  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:16.946  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.946  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 18:40:16.946  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.946  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0a4be9 removed from the list
08-29 18:40:16.946  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.946  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b9806e removed from the list
08-29 18:40:16.946  6901  6955 D io.jxcore.node.ConnectivityMonitor: stop
08-29 18:40:16.946  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:16.946  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.946  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.946  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.956  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:16.956  1015  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-29 18:40:16.956  1015  7838 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:16.956  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-29 18:40:16.956  1015  7838 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-29 18:40:16.956  1015  7838 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 18:40:16.956  1015  7838 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-29 18:40:16.956  1015  7838 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 18:40:16.956  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 18:40:16.956  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:16.956  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.956  6901  6955 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b9806e not in the list
08-29 18:40:16.956  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.956  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 18:40:16.956   276   950 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 18:40:16.956   276   950 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-29 18:40:16.956  1015  1126 D ConnectivityService:    accepting network in place of null
08-29 18:40:16.956  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 18:40:16.956  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 18:40:16.956  1451  1451 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 18:40:16.956  1451  1451 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 18:40:16.956  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 18:40:16.956  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 18:40:16.956  6901  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 18:40:16.956  6901  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232bda5 removed from the list
08-29 18:40:16.956  6901  6955 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 18:40:16.956  6901  6955 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 18:40:16.956  6901  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 18:40:16.956  6901  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 18:40:16.956  6901  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20cfef9c removed from the list
,08-29 18:40:16.956  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 18:40:16.956  1015  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-29 18:40:16.956  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 18:40:16.956  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 18:40:16.956  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 18:40:16.956  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 18:40:16.956  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 18:40:16.956  6901  6955 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 18:40:16.956  1015  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-29 18:40:16.966  1015  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-29 18:40:16.966  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-29 18:40:16.966  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,08-29 18:40:16.966  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-29 18:40:16.966  1015  1121 V NetworkStats: updateIfacesLocked()
08-29 18:40:16.966  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.966  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 18:40:16.966  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-29 18:40:16.966  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:40:16.966  1172  1749 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 18:40:16.966  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 18:40:16.966  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:40:16.966  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 18:40:16.966  4737  7027 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 18:40:16.966  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
08-29 18:40:16.966  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 18:40:16.966  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 18:40:16.966  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-29 18:40:16.966  1172  1172 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 18:40:16.966  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-29 18:40:16.966  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:16.966  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:16.966  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 18:40:16.976  6901  7876 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1394, name: My test thread name)
,08-29 18:40:16.976  6901  7876 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1394, thread name: My test thread name)
08-29 18:40:16.976  6901  7876 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1394, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 18:40:16.976  1631  1631 I Hs20UtilService: Starting #23
,08-29 18:40:16.976  1631  1727 I Hs20UtilService: Message received 5007
,08-29 18:40:16.976  1015  1121 V NetworkStats: performPollLocked() took 8ms
08-29 18:40:16.976  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.976  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 18:40:16.976  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 18:40:16.976  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 18:40:16.976  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.976  6901  7877 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1396, name: My test thread name)
08-29 18:40:16.976  6901  7877 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1396, thread name: My test thread name)
08-29 18:40:16.976  6901  7877 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1396, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 18:40:16.976  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:40:16.976  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 18:40:16.976  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.976  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.976  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:16.976  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:16.976  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.976  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.976  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 18:40:16.976  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:16.976  6901  6955 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 18:40:16.976  6901  6955 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 18:40:16.976  6901  6955 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 18:40:16.976  6901  6955 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 18:40:16.976  6901  6955 D com.test.thalitest.ThaliTestRunner: Total duration: 24501 ms
,08-29 18:40:16.976  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 18:40:16.976  6901  6955 I jxcore-log: *Native tests were executed*
08-29 18:40:16.976  6901  6955 I jxcore-log: 
08-29 18:40:16.986  6901  6955 I jxcore-log: Total number of executed tests:  80
08-29 18:40:16.986  6901  6955 I jxcore-log: 
08-29 18:40:16.986  6901  6955 I jxcore-log: Number of passed tests:  80
08-29 18:40:16.986  6901  6955 I jxcore-log: 
08-29 18:40:16.986  3901  3901 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 18:40:16.986  6901  6955 I jxcore-log: Number of failed tests:  0
08-29 18:40:16.986  6901  6955 I jxcore-log: 
08-29 18:40:16.986  6901  6955 I jxcore-log: Number of ignored tests:  0
08-29 18:40:16.986  6901  6955 I jxcore-log: 
,08-29 18:40:16.986  6901  6955 I jxcore-log: Total duration:  24501
08-29 18:40:16.986  6901  6955 I jxcore-log: 
08-29 18:40:16.986  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-29 18:40:16.986  6901  6955 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 18:40:16.986  6901  6955 I jxcore-log: 
,08-29 18:40:16.986  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.986  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 18:40:16.986  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:16.986  6901  6955 I jxcore-log: 
08-29 18:40:16.986  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:16.986  6901  6955 I jxcore-log: 
08-29 18:40:16.986  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:16.996  3901  3901 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-29 18:40:16.996  3901  3901 I NearbySettings: MountReceiver.onReceive - Keep current state
08-29 18:40:16.996  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:16.996  6901  6955 I jxcore-log: 
08-29 18:40:16.996  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:16.996  6901  6955 I jxcore-log: 
08-29 18:40:16.996  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:16.996  6901  6955 I jxcore-log: 
08-29 18:40:16.996  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:16.996  6901  6955 I jxcore-log: 
,08-29 18:40:17.006  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 18:40:17.006  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 18:40:17.006  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:17.006  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:17.006  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 18:40:17.006  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 18:40:17.006  6901  6955 I jxcore-log: 
,08-29 18:40:17.006  1631  1631 I Hs20UtilService: Starting #24
,08-29 18:40:17.006  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 18:40:17.006  6901  6955 I jxcore-log: 
08-29 18:40:17.006  1631  1727 I Hs20UtilService: Message received 5007
,08-29 18:40:17.006  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.006  6901  6955 I jxcore-log: 
08-29 18:40:17.006  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.006  6901  6955 I jxcore-log: 
,08-29 18:40:17.006  3901  3901 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 18:40:17.006  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:17.006  6901  6955 I jxcore-log: 
08-29 18:40:17.006  3901  3901 I NearbySettings: MountReceiver.onReceive - Keep current state
08-29 18:40:17.006  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 18:40:17.006  6901  6955 I jxcore-log: 
,08-29 18:40:17.006  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.006  6901  6955 I jxcore-log: 
,08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
,08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
,08-29 18:40:17.016  6901  6901 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
,08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
,08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
,08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
,08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
,08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
08-29 18:40:17.016  1015  1748 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-29 18:40:17.016  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:17.016  6901  6955 I jxcore-log: 
,08-29 18:40:17.026  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:17.026  6901  6955 I jxcore-log: 
,08-29 18:40:17.026  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:17.026  6901  6955 I jxcore-log: 
,08-29 18:40:17.026  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 18:40:17.026  6901  6955 I jxcore-log: 
,08-29 18:40:17.026  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-29 18:40:17.026  1015  1027 D SecContentProvider2: mCursor = null
,08-29 18:40:17.026  1015  1479 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-29 18:40:17.026  1015  1479 D SecContentProvider2: mCursor = null
,08-29 18:40:17.026  1015  1476 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-29 18:40:17.026  1015  1476 D SecContentProvider2: mCursor = null
,08-29 18:40:17.026  1015  1495 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-29 18:40:17.026  1015  1495 D SecContentProvider2: mCursor = null
,08-29 18:40:17.036  1015  1538 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-29 18:40:17.036  1015  1538 D SecContentProvider2: mCursor = null
,08-29 18:40:17.036  1015  1218 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-29 18:40:17.036  1015  1218 D SecContentProvider2: mCursor = null
,08-29 18:40:17.056  1015  7838 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 18:40:17.066   258   258 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-29 18:40:17.076  1015  1027 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015,
,08-29 18:40:17.086  6901  6901 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 18:40:17.086  1172  1172 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 18:40:17.096  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 18:40:17.096  6901  6955 I jxcore-log: 
,08-29 18:40:17.126  1015  7838 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 16:40:17 GMT], X-Android-Received-Millis=[1472488817134], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472488817096]}
08-29 18:40:17.126  1015  7838 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 18:40:17.126  1015  7838 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-29 18:40:17.126  1015  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-29 18:40:17.126  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-29 18:40:17.126  1015  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-29 18:40:17.126  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-29 18:40:17.126  1172  1749 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 18:40:17.126  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
08-29 18:40:17.126  4737  7027 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 18:40:17.136  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
,08-29 18:40:17.136  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 18:40:17.136  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 18:40:17.136  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-29 18:40:17.136  1172  1172 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 18:40:17.136  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 18:40:17.146  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 18:40:17.146  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 18:40:17.146  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 18:40:17.146  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 18:40:17.146  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-29 18:40:17.146  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:17.146  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:17.146  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 18:40:17.146  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 18:40:17.236  6901  6901 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 18:40:17.236  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 18:40:17.236  6901  6955 I jxcore-log: 
,08-29 18:40:17.276  7878  7878 D AndroidRuntime: 
08-29 18:40:17.276  7878  7878 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 18:40:17.286  7878  7878 D AndroidRuntime: CheckJNI is OFF,
08-29 18:40:17.286  7878  7878 D AndroidRuntime: readGMSProperty: start
08-29 18:40:17.286  7878  7878 D AndroidRuntime: readGMSProperty: already setted!!
,08-29 18:40:17.286  7878  7878 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 18:40:17.286  7878  7878 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 18:40:17.286  7878  7878 D AndroidRuntime: readGMSProperty: end
,08-29 18:40:17.286  7878  7878 D AndroidRuntime: addProductProperty: start
,08-29 18:40:17.356  6901  6901 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 18:40:17.356  6901  6955 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 18:40:17.356  6901  6955 I jxcore-log: 
,08-29 18:40:17.406  7878  7878 E AffinityControl: AffinityControl: registerfunction enter,
,08-29 18:40:17.436  7878  7878 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 18:40:17.456  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-29 18:40:17.456  1015  1028 D PackageManager: START PACKAGE DELETE: observer{195806858}
08-29 18:40:17.456  1015  1028 D PackageManager: pkg{<packageName>}
08-29 18:40:17.456  1015  1028 D PackageManager: user{0}
,08-29 18:40:17.456  1015  1028 D PackageManager: caller{2000}
08-29 18:40:17.456  1015  1028 D PackageManager: flags{2}
,08-29 18:40:17.456  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-29 18:40:17.456  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-29 18:40:17.456  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 18:40:17.456  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-29 18:40:17.456  1015  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-29 18:40:17.456  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-29 18:40:17.456  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-29 18:40:17.456  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-29 18:40:17.456  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-29 18:40:17.456  1015  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,08-29 18:40:17.466  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:17.486  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-29 18:40:17.486  1015  1041 I ActivityManager: Killing 6901:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-29 18:40:17.546  1015  1056 W PackageSettings: Skipping PackageSetting{3775dc64 com.example.hello/10168} due to missing metadata
,08-29 18:40:17.586  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{3aa1e72 u0 com.test.thalitest/.MainActivity t2}
,08-29 18:40:17.606  1015  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 18:40:17.606  1015  1041 D InputDispatcher: Focus left window: 6901
,08-29 18:40:17.606   258   446 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-29 18:40:17.616   258  1037 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-29 18:40:17.616  1015  1041 D InputDispatcher: Focused application released
,08-29 18:40:17.616  1015  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 18:40:17.616  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 18:40:17.616  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 18:40:17.616  1015  1041 D FocusedStackFrame: Set to : 0
,08-29 18:40:17.626  1015  1041 W ActivityManager: mDVFSHelper.acquire()
,08-29 18:40:17.636  1015  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-29 18:40:17.636  1015  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-29 18:40:17.636  1015  1015 V ActivityManager: Display changed displayId=0
,08-29 18:40:17.646  1015  1046 W DisplayManagerService: Failed to notify process 6901 that displays changed, assuming it died.
08-29 18:40:17.646  1015  1046 W DisplayManagerService: android.os.TransactionTooLargeException
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 18:40:17.646  1015  1046 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 18:40:17.646  1015  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-29 18:40:17.666  1015  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
08-29 18:40:17.666  1480  1480 D Launcher: onRestart, Launcher: 592651011
,08-29 18:40:17.686  1480  1480 D Launcher: onStart, Launcher: 592651011
,08-29 18:40:17.686  1480  1480 D Launcher.HomeView: onStart
,08-29 18:40:17.686  1480  1480 D Launcher: onResume, Launcher: 592651011
,08-29 18:40:17.686  1015  1495 D SettingsProvider: name = kids_home_mode
08-29 18:40:17.686  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 18:40:17.686  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 18:40:17.686  1015  1495 D SettingsProvider: selectionArgs: false
08-29 18:40:17.686  1015  1495 D SettingsProvider: selectionArgs: 10006
08-29 18:40:17.686  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 18:40:17.686  1015  1495 D SettingsProvider: ret = -1
,08-29 18:40:17.696  1480  1480 D Launcher.HomeView: onResume
,08-29 18:40:17.706  2639  2639 I art     : Explicit concurrent mark sweep GC freed 19556(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 805us total 41.399ms
,08-29 18:40:17.706  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-29 18:40:17.726  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:17.746  2003  2156 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 18:40:17.746  1872  1872 E SamsungIME: mOCRHelper is null
,08-29 18:40:17.756  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 18:40:17.756  4737  4737 I art     : Explicit concurrent mark sweep GC freed 23569(1412KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 12MB/17MB, paused 1.409ms total 99.001ms
,08-29 18:40:17.756  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 18:40:17.756  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:17.756  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:17.756  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:17.756  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:17.796  7891  7891 E Zygote  : MountEmulatedStorage(),
08-29 18:40:17.796  7891  7891 I libpersona: KNOX_SDCARD checking this for 1000
08-29 18:40:17.796  7891  7891 E Zygote  : v2,
08-29 18:40:17.796  7891  7891 I libpersona: KNOX_SDCARD not a persona
08-29 18:40:17.796  7891  7891 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 18:40:17.796  7891  7891 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 18:40:17.796  7891  7891 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 18:40:17.796  1015  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7891 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 18:40:17.806  1480  1480 D MenuAppsGridFragment: onResume
,08-29 18:40:17.826  1433  1433 D PersonaManager: isKioskContainerExistOnDevice
,08-29 18:40:17.846  7891  7891 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:40:17.846  7891  7891 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:17.846  1433  1433 D RegisteredServicesCache: empty dynamic service
,08-29 18:40:17.856  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-29 18:40:17.856  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:17.856  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
,08-29 18:40:17.856  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-29 18:40:17.856  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 18:40:17.856  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 18:40:17.856  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-29 18:40:17.856  1015  1040 W TextServicesManagerService: no available spell checker services found
08-29 18:40:17.856  1015  1335 D ActivityManager: handle home activity for 0
08-29 18:40:17.856  1015  1335 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-29 18:40:17.856  1015  1335 D KnoxTimeoutHandler: post home show event for user 0
08-29 18:40:17.856  1015  1335 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-29 18:40:17.856  1015  1335 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 18:40:17.856  1015  1335 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-29 18:40:17.856  1480  1480 D Launcher.HomeView: onPause
08-29 18:40:17.856  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-29 18:40:17.866  1015  1121 V NetworkStats: performPollLocked() took 14ms
08-29 18:40:17.866  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:17.876  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 18:40:17.876  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 18:40:17.876  1015  1015 I art     : Explicit concurrent mark sweep GC freed 82351(4MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 25MB/38MB, paused 10.757ms total 212.323ms
,08-29 18:40:17.876  1015  1056 I art     : WaitForGcToComplete blocked for 46.482ms for cause Explicit
,08-29 18:40:17.876   258   258 I SurfaceFlinger: id=16 createSurf (540x960),1 flag=4, Mauncher
,08-29 18:40:17.876  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 18:40:17.886  1433  1433 D RegisteredComponentCache: Collect Tech packages for Knox
,08-29 18:40:17.886  1433  1433 D PersonaManager: isKioskContainerExistOnDevice
,08-29 18:40:17.906  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 18:40:17.916  1015  1479 D InputDispatcher: Focus entered window: 1480
,08-29 18:40:17.916  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 18:40:17.916  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 18:40:17.916  1480  1480 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 18:40:17.916  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 18:40:17.916  1015  1027 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 18:40:17.916  1015  1027 D SecContentProvider2: mCursor = null
,08-29 18:40:17.926  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{27a85d5e token=android.os.BinderProxy@1c495b97 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-29 18:40:17.926  1480  1480 D Launcher.HomeView: onStop
,08-29 18:40:17.936  1015  1538 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 18:40:17.936  1015  7907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 18:40:17.946  7891  7891 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-29 18:40:17.946  7891  7891 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 18:40:17.946  7891  7891 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 18:40:17.946  1015  1538 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6901 uid 10171
,08-29 18:40:17.966  7891  7891 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-29 18:40:17.966  7891  7891 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-29 18:40:17.966  7891  7891 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 18:40:17.966  7891  7891 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:17.966  1015  1538 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 6 r.nextReceiver= 1 receivers.size=28
,08-29 18:40:17.966  1015  1538 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-29 18:40:17.976  1015  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-29 18:40:17.976  1872  1872 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-29 18:40:17.976  1015  1538 I ActivityManager: Killing 7257:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-29 18:40:17.976  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 18:40:18.006  1768  1768 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 18:40:18.016  1015  1479 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-29 18:40:18.016  1015  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-29 18:40:18.016  1015  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:18.016  1015  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 18:40:18.016  1015  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-29 18:40:18.016  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 18:40:18.016  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-29 18:40:18.016  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 18:40:18.026  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-29 18:40:18.026  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 18:40:18.026  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.026  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.026  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.026  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:18.026  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-29 18:40:18.026  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-29 18:40:18.026  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-29 18:40:18.046  7910  7910 E Zygote  : MountEmulatedStorage(),
,08-29 18:40:18.046  7910  7910 I libpersona: KNOX_SDCARD checking this for 10121
08-29 18:40:18.046  7910  7910 E Zygote  : v2
,08-29 18:40:18.046  7910  7910 I libpersona: KNOX_SDCARD not a persona
08-29 18:40:18.046  7910  7910 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:40:18.046  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter,
08-29 18:40:18.046  1015  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7910 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 18:40:18.046  7910  7910 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:40:18.056  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-29 18:40:18.056  7910  7910 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:40:18.066  1015  1475 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.soagent/com.sec.android.soagent.RegisterReceiver}
08-29 18:40:18.066  1015  1475 W BroadcastQueue: android.os.DeadObjectException
08-29 18:40:18.066  1015  1475 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 18:40:18.066  1015  1475 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 18:40:18.066  1015  1475 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-29 18:40:18.066  1015  1475 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-29 18:40:18.066  1015  1475 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-29 18:40:18.066  1015  1475 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-29 18:40:18.066  1015  1475 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-29 18:40:18.066  1015  1475 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-29 18:40:18.066  1015  1475 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 18:40:18.066  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 18:40:18.076  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:18.076  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.076  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.076  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:18.076  1015  1478 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 18:40:18.076  1015  1478 D SecContentProvider2: mCursor = null
,08-29 18:40:18.086  7925  7925 E Zygote  : MountEmulatedStorage()
08-29 18:40:18.086  7925  7925 I libpersona: KNOX_SDCARD checking this for 10031
08-29 18:40:18.086  7925  7925 E Zygote  : v2
08-29 18:40:18.086  7925  7925 I libpersona: KNOX_SDCARD not a persona
08-29 18:40:18.086  7925  7925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:40:18.096  7910  7910 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:40:18.096  7910  7910 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:18.096  7925  7925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 18:40:18.096  1015  1475 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7925 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-29 18:40:18.096  7925  7925 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:40:18.106  1015  1046 W ActivityManager: mDVFSHelper.release()
08-29 18:40:18.106  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2bacdde2 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:148722
,08-29 18:40:18.106  1015  1495 W ActivityManager: Spurious death for ProcessRecord{1690f860 7925:com.sec.android.soagent/u0a31}, curProc for 7257: null
,08-29 18:40:18.116  2471  2482 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-29 18:40:18.116  1768  1768 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 18:40:18.126  1768  1768 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-29 18:40:18.126  1768  1768 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-29 18:40:18.126  1768  1768 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 18:40:18.136  7910  7910 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 18:40:18.136  7910  7910 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 18:40:18.136  7910  7910 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 18:40:18.136  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-29 18:40:18.136  7925  7925 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:40:18.136  7925  7925 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:18.146  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 18:40:18.156  7910  7910 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:18.156  1015  1056 I art     : Explicit concurrent mark sweep GC freed 17285(1369KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 25MB/38MB, paused 3.590ms total 274.947ms
,08-29 18:40:18.156  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 18:40:18.166  7910  7910 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 18:40:18.166  1768  1768 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 18:40:18.176  1768  1768 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 18:40:18.176  7910  7910 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 18:40:18.196  1015  1477 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:40:18.196  1015  1748 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-29 18:40:18.196  1015  1748 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-29 18:40:18.196  1015  1748 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:18.196  1015  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:40:18.196  1015  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-29 18:40:18.206  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 18:40:18.206  1015  1056 D PackageManager: delete codoeFile: 
,08-29 18:40:18.206  1015  1476 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 18:40:18.216  1015  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-29 18:40:18.216  1015  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-29 18:40:18.226  1015  1056 D PackageManager: result of delete: 1{195806858}
,08-29 18:40:18.226  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 18:40:18.226  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 18:40:18.226  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 18:40:18.226  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 18:40:18.236  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 18:40:18.236  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 18:40:18.236  7878  7878 D AndroidRuntime: Shutting down VM
,08-29 18:40:18.236  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:18.236  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 18:40:18.236  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 18:40:18.246  7422  7422 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-29 18:40:18.266  1015  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-29 18:40:18.266  1015  1056 D PackageManager: userId{-1}
08-29 18:40:18.266  1015  1056 D PackageManager: andCode{true}
,08-29 18:40:18.276  1015  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-29 18:40:18.276  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 18:40:18.276  7154  7942 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-29 18:40:18.276  7154  7942 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 18:40:18.276  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 18:40:18.276  7154  7942 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 18:40:18.276  7154  7942 I System.out: (HTTPLog)-Thread-1300-878505782: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 18:40:18.276  7154  7942 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 18:40:18.276  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.276  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.276  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.276  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 18:40:18.276  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-29 18:40:18.276  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-29 18:40:18.276  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 18:40:18.276  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-29 18:40:18.276  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 18:40:18.276  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 18:40:18.276  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 18:40:18.276  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-29 18:40:18.276  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 18:40:18.286   276   950 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 18:40:18.286   276   950 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-29 18:40:18.286  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 18:40:18.286  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 18:40:18.286  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 18:40:18.286  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 18:40:18.296  7948  7948 E Zygote  : MountEmulatedStorage()
08-29 18:40:18.296  7948  7948 E Zygote  : v2
08-29 18:40:18.296  7948  7948 I libpersona: KNOX_SDCARD checking this for 10003
08-29 18:40:18.296  7948  7948 I libpersona: KNOX_SDCARD not a persona
,08-29 18:40:18.296  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 18:40:18.296  7948  7948 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 18:40:18.296  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 18:40:18.296  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 18:40:18.296  7948  7948 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:40:18.296  7948  7948 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:40:18.296  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 18:40:18.296  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 18:40:18.306  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 18:40:18.306  1015  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7948 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 18:40:18.306  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 18:40:18.306  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-29 18:40:18.306  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-29 18:40:18.306  1015  1158 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-29 18:40:18.306  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-29 18:40:18.306  1015  3354 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-29 18:40:18.306  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 18:40:18.306  1015  1158 D TaskPersister: removeObsoleteFile: deleting file=2_task_thumbnail.png
08-29 18:40:18.306  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-29 18:40:18.306  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 18:40:18.306  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 18:40:18.306  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 18:40:18.306  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-29 18:40:18.306  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 18:40:18.316  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-29 18:40:18.316  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-29 18:40:18.316  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-29 18:40:18.316  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-29 18:40:18.316  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-29 18:40:18.326  7948  7948 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 18:40:18.326  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-29 18:40:18.326  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
08-29 18:40:18.326  7948  7948 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:18.336  1172  1172 I StatusBar: Icon Only
,08-29 18:40:18.336  1172  1172 D PanelView: There is/are notification(s) ,
,08-29 18:40:18.336  1015  1040 W libprocessgroup: failed to open /acct/uid_10031/pid_7257/cgroup.procs: No such file or directory
08-29 18:40:18.336  7321  7321 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
08-29 18:40:18.336  2757  7960 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-29 18:40:18.336  2757  7960 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-29 18:40:18.346  7154  7942 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 18:40:18.346  2757  7960 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 18:40:18.356  7339  7339 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 18:40:18.356  7339  7339 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-29 18:40:18.356  7339  7339 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 18:40:18.366  7339  7339 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-29 18:40:18.366  7339  7339 I SA      : [OR] == isSIMCardReady false ==
,08-29 18:40:18.366  7339  7339 I SA      : [SCU] == networkStateCheck == true
,08-29 18:40:18.376  7339  7339 I SA      : [DM] getCountryCodeFromCSC : PL
08-29 18:40:18.376  7339  7339 I SA      : isChinaCountryCode : false
08-29 18:40:18.376  7339  7339 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-29 18:40:18.376  7339  7339 I SA      : [OR] == networkStateCheck true ==
,08-29 18:40:18.376  7725  7741 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 18:40:18.386  7339  7339 I SA      : [OR] GetMyCountryZoneTask
,08-29 18:40:18.386  7339  7339 I SA      : [OR] onReceive END
08-29 18:40:18.386  2757  7960 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-29 18:40:18.386  2757  7960 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-29 18:40:18.386  1015  1218 I ActivityManager: Killing 7305:com.sec.android.diagmonagent/1000 (adj 15): empty #21
08-29 18:40:18.386  2757  7960 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
08-29 18:40:18.386  2757  7960 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-29 18:40:18.396  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 18:40:18.396  1015  1478 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-29 18:40:18.396  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-29 18:40:18.396  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:18.396  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 18:40:18.396  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-29 18:40:18.396  2757  7960 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-29 18:40:18.406  2757  7960 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-29 18:40:18.406  2757  7960 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-29 18:40:18.406  2757  7960 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-29 18:40:18.416  2757  7960 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-29 18:40:18.416  7339  7965 I SA      : [SRS] prepareGetMyCountryZone
,08-29 18:40:18.426  7154  7942 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 18:40:18.426  1015  1218 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-29 18:40:18.426   288   288 E SMD     : DCD OFF
,08-29 18:40:18.426  1015  1218 D SecContentProvider2: mCursor = null
,08-29 18:40:18.436  1015  1335 I ActivityManager: Killing 7356:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 18:40:18.436  2757  7960 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-29 18:40:18.446  7878  7878 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 18:40:18.446  7339  7965 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-29 18:40:18.446  7339  7965 I SA      : [SSP] query invoked
,08-29 18:40:18.446  7339  7965 I SA      : [TPMU] GetMccFromDB : null
,08-29 18:40:18.456  7339  7965 I SA      : [SCU] getMccFromPreferece mcc = 260
08-29 18:40:18.456  7339  7965 I SA      : [LBE] isSupportCheckDomainRegion : false
08-29 18:40:18.456  7339  7965 I SA      : [TPM] isNoProxy(default) : true
,08-29 18:40:18.456  1015  1476 D PersonaManager: isKioskContainerExistOnDevice
,08-29 18:40:18.466  7339  7965 E File    : fail readDirectory() errno=2
,08-29 18:40:18.476  1480  1480 I Choreographer: Skipped 30 frames!  The application may be doing too much work on its main thread.
,08-29 18:40:18.476  1480  1480 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1c495b97 time:149095
,08-29 18:40:18.556  1015  1015 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850,
08-29 18:40:18.556  1015  1015 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM AppFreezer WHERE package_name='com.test.thalitest'] disk I/O error
08-29 18:40:18.556  1015  1015 E LpnetManagerService: Exception on handling DB : disk I/O error (code 3850)
08-29 18:40:18.556  1015  1015 W System.err: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850),
,08-29 18:40:18.556  1015  1015 W System.err: ,	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 18:40:18.556  1015  1015 W System.err: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-29 18:40:18.556  1015  1015 W System.err: ,	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 18:40:18.556  1015  1015 W System.err: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 18:40:18.556  1015  1015 W System.err: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
,08-29 18:40:18.556  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
08-29 18:40:18.556  1015  1015 W System.err: 	at com.android.server.LpnetManagerService$DBManager.dbDelete(LpnetManagerService.java:2312)
08-29 18:40:18.556  1015  1015 W System.err: 	at com.android.server.LpnetManagerService$2$1.run(LpnetManagerService.java:725)
08-29 18:40:18.556  1015  1015 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-29 18:40:18.556  1015  1015 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 18:40:18.556  1015  1015 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-29 18:40:18.556  1015  1015 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:445)
08-29 18:40:18.556  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 18:40:18.556  1015  1015 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:329)
08-29 18:40:18.556  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.556  1015  1015 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 18:40:18.556  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.556  1015  1015 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 18:40:18.556  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 18:40:18.556  1015  1015 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 18:40:18.556  1015  1015 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 18:40:18.566  7970  7970 E Zygote  : MountEmulatedStorage(),
,08-29 18:40:18.576  7970  7970 E Zygote  : v2
08-29 18:40:18.576  7970  7970 I libpersona: KNOX_SDCARD checking this for 10001
08-29 18:40:18.576  7970  7970 I libpersona: KNOX_SDCARD not a persona
,08-29 18:40:18.576  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7970 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 18:40:18.576  7970  7970 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 18:40:18.586  7970  7970 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 18:40:18.586  7970  7970 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 18:40:18.596  7970  7970 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 18:40:18.596  7970  7970 D ActivityThread: Added TimaKeyStore provider
,08-29 18:40:18.616  1015  1218 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-29 18:40:18.616  1015  1218 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-29 18:40:18.616  1015  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-29 18:40:18.616  1015  1218 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 18:40:18.616  1015  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-29 18:40:18.626  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 18:40:18.626  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 18:40:18.626  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 18:40:18.626  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 18:40:18.626  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 18:40:18.636   276   950 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 18:40:18.636   276   950 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-29 18:40:18.646  4737  4737 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 18:40:18.646  7422  7422 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-29 18:40:18.646  7422  7422 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-29 18:40:18.646  7422  7422 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-29 18:40:18.646  7422  7422 D InitializeManagerStateMachine: exit::IDLE
,08-29 18:40:18.656  7422  7422 D InitializeManagerStateMachine: entry::NETWORK_CHECK

```
