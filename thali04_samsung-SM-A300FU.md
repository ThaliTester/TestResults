#### Test 79763830f325397_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
,08-22 12:03:23.105  4823  4823 D FactoryTest: Not factory mode
08-22 12:03:23.105  4823  4823 D FactoryTest: Not factory mode. isFactoryMode() returend false
08-22 12:03:23.115  4823  4823 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-22 12:03:23.115  4823  4823 D MTPRx   : still no open session command from host, so toast
--------- beginning of system
08-22 12:03:23.125  4823  4823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-22 12:03:23.125  4823  4823 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:105974
08-22 12:03:23.125  4823  4823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
08-22 12:03:23.135  1018  1471 E PersonaManagerService: inState():  stateMachine is null !!
08-22 12:03:23.135  1018  1471 I PersonaManagerService: PersonaId don't exist
08-22 12:03:23.135  1018  1471 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-22 12:03:23.145  1018  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-22 12:03:23.145  1018  1471 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:23.145  1018  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:23.145  1018  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
08-22 12:03:23.155  1018  1471 W ActivityManager: mDVFSHelper.acquire()
08-22 12:03:23.165   259   259 I SurfaceFlinger: id=9 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-22 12:03:23.185   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(An
08-22 12:03:23.195  1018  1471 D FocusedStackFrame: Set to : 0
08-22 12:03:23.205  1018  1018 V ActivityManager: Display changed displayId=0
08-22 12:03:23.205  1018  1471 D PersonaManager: isKioskContainerExistOnDevice
08-22 12:03:23.215  1018  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-22 12:03:23.215  1018  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-22 12:03:23.215  1018  1471 D InputDispatcher: Focused application set to: xxxx
08-22 12:03:23.215  1018  1471 D InputDispatcher: Focus left window: 1478
08-22 12:03:23.215  4823  4823 E MTPRx   : started activity for popup
08-22 12:03:23.235  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-22 12:03:23.235  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:23.235  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 12:03:23.275  4823  4823 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-22 12:03:23.275  4823  4823 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 12:03:23.275  4823  4823 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 12:03:23.275  4823  4823 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 12:03:23.275  4823  4823 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 12:03:23.275  4823  4823 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-22 12:03:23.295  4823  4823 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
08-22 12:03:23.305  1018  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-22 12:03:23.305  1018  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 12:03:23.305  1018  1476 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 12:03:23.305  1018  1476 D BatteryService: stay LED for fully charged
08-22 12:03:23.305  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-22 12:03:23.315  1018  1471 D FocusedStackFrame: Set to : 0
08-22 12:03:23.315  1018  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-22 12:03:23.315  1018  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-22 12:03:23.315  1018  1471 D InputDispatcher: Focused application set to: xxxx
08-22 12:03:23.315  1018  1471 D InputDispatcher: Focus entered window: 1478
08-22 12:03:23.315  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:23.315  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 12:03:23.315  1018  1136 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-22 12:03:23.315  1018  1136 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3ad7cd1e attribute=android.view.inputmethod.EditorInfo@1195a9ff, token = android.os.BinderProxy@3e1cd2b1
08-22 12:03:23.325  1774  1774 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-22 12:03:23.325  1018  1018 I MotionRecognitionService: Plugged
08-22 12:03:23.325  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-22 12:03:23.325  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-22 12:03:23.325  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-22 12:03:23.325  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
08-22 12:03:23.325  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-22 12:03:23.345  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 12:03:23.345  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 12:03:23.345  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 12:03:23.365  4823  4823 D SettingsReceiverActivity: dev.kiessupport is : TRUE
08-22 12:03:23.365  4823  4823 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-22 12:03:23.365  4823  4823 D PhoneWindow: *FMB* installDecor flags : 8388610
08-22 12:03:23.375  5778  5778 D AndroidRuntime: 
08-22 12:03:23.375  5778  5778 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 12:03:23.375  5778  5778 D AndroidRuntime: CheckJNI is OFF
08-22 12:03:23.385  5778  5778 D AndroidRuntime: readGMSProperty: start
08-22 12:03:23.385  5778  5778 D AndroidRuntime: readGMSProperty: already setted!!
08-22 12:03:23.385  5778  5778 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 12:03:23.385  5778  5778 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 12:03:23.385  5778  5778 D AndroidRuntime: readGMSProperty: end
08-22 12:03:23.385  5778  5778 D AndroidRuntime: addProductProperty: start
08-22 12:03:23.415  1018  1096 V AlarmManager: waitForAlarm result :4
08-22 12:03:23.525  5778  5778 E AffinityControl: AffinityControl: registerfunction enter
08-22 12:03:23.545  5778  5778 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-22 12:03:23.555  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
08-22 12:03:23.555  1018  1030 I PersonaManagerService: PersonaId don't exist
08-22 12:03:23.555  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-22 12:03:23.565  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 12:03:23.575  1018  1030 W ActivityManager: mDVFSHelper.acquire()
08-22 12:03:23.575  1018  1030 D FocusedStackFrame: Set to : 0
08-22 12:03:23.585  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 12:03:23.585  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-22 12:03:23.585  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:23.585  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:23.585  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:23.585  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:23.595  5792  5792 E Zygote  : MountEmulatedStorage()
08-22 12:03:23.595  5792  5792 E Zygote  : v2
08-22 12:03:23.595  5792  5792 I libpersona: KNOX_SDCARD checking this for 10171
08-22 12:03:23.595  5792  5792 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:23.595  1018  1030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5792 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 12:03:23.595  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-22 12:03:23.595  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 12:03:23.595  1018  1030 D InputDispatcher: Focused application set to: xxxx
08-22 12:03:23.595  1018  1030 D InputDispatcher: Focus left window: 1478
08-22 12:03:23.595  5792  5792 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:23.595  5778  5778 D AndroidRuntime: Shutting down VM
08-22 12:03:23.605  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 12:03:23.605  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 12:03:23.605  5792  5792 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:23.605   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
08-22 12:03:23.605  5792  5792 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-22 12:03:23.625  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:23.625  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 12:03:23.625  5792  5792 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:23.625  5792  5792 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:23.625  1018  1464 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-22 12:03:23.625  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 12:03:23.645  1018  1464 D PersonaManager: isKioskContainerExistOnDevice
08-22 12:03:23.675   259   446 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-22 12:03:23.675   259   449 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-22 12:03:23.685  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{1780197 token=android.os.BinderProxy@d780d1b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-22 12:03:23.685  1478  1478 D Launcher: onTrimMemory. Level: 20
08-22 12:03:23.785  5792  5792 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-22 12:03:23.805  5778  5778 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 12:03:23.835  5792  5792 I cr.library_loader: Time to load native libraries: 13 ms (timestamps 6675-6688)
,08-22 12:03:23.835  5792  5792 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 12:03:23.865  5792  5792 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {38dc548}
,08-22 12:03:23.865  5792  5792 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 12:03:23.875  5792  5792 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 12:03:23.915  5792  5792 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-22 12:03:23.925  5792  5792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:23.925  5792  5792 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 12:03:23.975  5792  5810 W chromium: [WARNING:dns_config_service_posix.cc(298)] Failed to read DnsConfig.
,08-22 12:03:23.985  5792  5792 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 12:03:23.985  5792  5792 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 12:03:23.985  5792  5792 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 12:03:23.985  5792  5792 I Adreno-EGL: Local Branch: 
08-22 12:03:23.985  5792  5792 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 12:03:23.985  5792  5792 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 12:03:23.985  5792  5792 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 12:03:24.065  5792  5821 D BluetoothAdapter: 457802695: getState() :  mService = null. Returning STATE_OFF
,08-22 12:03:24.075  5792  5792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 12:03:24.085  5792  5792 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-22 12:03:24.085  5792  5792 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-22 12:03:24.095  5792  5792 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-22 12:03:24.095  5792  5792 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-22 12:03:24.145   289   289 E SMD     : DCD OFF
,08-22 12:03:24.145  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{3d9b1e91 u0 com.test.thalitest/.MainActivity t3}
,08-22 12:03:24.225  5792  5792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:24.235  5792  5792 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-22 12:03:24.245  5792  5792 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-22 12:03:24.245  5792  5792 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-22 12:03:24.255  5792  5792 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-22 12:03:24.265  5792  5792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:24.265  5792  5792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:24.305  5792  5832 D OpenGLRenderer: Render dirty regions requested: true
,08-22 12:03:24.315  1018  1475 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-22 12:03:24.315  1018  1475 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 12:03:24.315  1018  1475 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-22 12:03:24.315  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-22 12:03:24.315  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-22 12:03:24.315  5792  5819 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-22 12:03:24.325  5792  5792 V ActivityThread: updateVisibility : ActivityRecord{27d022c1 token=android.os.BinderProxy@b265e9a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-22 12:03:24.325  5792  5792 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 12:03:24.325  5792  5792 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-22 12:03:24.355   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-22 12:03:24.365  1018  1136 D InputDispatcher: Focus entered window: 5792
,08-22 12:03:24.375  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 12:03:24.375  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 12:03:24.375  5792  5792 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-22 12:03:24.375  5792  5832 I OpenGLRenderer: Initialized EGL, version 1.4
,08-22 12:03:24.375  5792  5832 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-22 12:03:24.385  5792  5832 D OpenGLRenderer: Enabling debug mode 0
,08-22 12:03:24.395  1018  2953 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 12:03:24.405  1173  1173 I StatusBar: Icon Only
,08-22 12:03:24.405  1173  1173 D PanelView: There is/are notification(s) 
,08-22 12:03:24.415  1018  5836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 12:03:24.415  1018  1048 I ActivityManager: Displayed Component not be shown by security: +773ms (total +1s223ms)
,08-22 12:03:24.415  1018  1048 W ActivityManager: mDVFSHelper.release()
08-22 12:03:24.415  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d9b1e91 u0 com.test.thalitest/.MainActivity t3} time:107269
,08-22 12:03:24.425  5792  5792 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-22 12:03:24.425  5792  5792 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b265e9a time:107275
,08-22 12:03:24.425   259   449 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
,08-22 12:03:24.435   259   446 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
,08-22 12:03:24.475  1774  1774 I SamsungIME: getCurrentCandidateView
,08-22 12:03:24.565  1774  1774 D SamsungIME: Dismiss ExpandCandiate
,08-22 12:03:24.565  5792  5792 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5792
,08-22 12:03:24.725  1774  1774 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 12:03:24.735  5792  5792 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 12:03:24.775  1774  1774 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 12:03:24.785  1774  1774 I SamsungIME: KeybaordView init() : load resources
,08-22 12:03:24.815  1774  1774 I SamsungIME: getCurrentKeyboard
08-22 12:03:24.815  1774  1774 I SamsungIME: getTextKeyboard
,08-22 12:03:24.825  5792  5838 D jxcore_app_log: JniHelper::setJavaVM(0xb85be2b0), pthread_self() = -1196118280
,08-22 12:03:24.835  5792  5838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 12:03:24.835  5792  5838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 12:03:24.835  5792  5838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 12:03:24.835  5792  5838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 12:03:24.835  5792  5838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-22 12:03:24.835  5792  5838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@181bee9f added. We now have 1 listener(s)
08-22 12:03:24.835  1774  1774 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-22 12:03:24.845  5792  5838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-22 12:03:24.845  5792  5838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 12:03:24.845  5792  5838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 12:03:24.845  5792  5838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-22 12:03:24.845  5792  5838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a3a24a added. We now have 1 listener(s)
08-22 12:03:24.845  5792  5838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 12:03:24.855  5792  5838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 12:03:24.855  5792  5838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-22 12:03:24.855  5792  5838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 12:03:24.855  5792  5838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 12:03:24.855  5792  5838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 12:03:24.855  5792  5838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 12:03:24.855  5792  5838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-22 12:03:24.865  5792  5838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:24.865  5792  5838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:24.865  5792  5838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:24.865  5792  5838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:03:24.865  5792  5838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:24.865  5792  5838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:24.865  5792  5838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:24.865  5792  5838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:24.865  5792  5838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 12:03:24.865  5792  5838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-22 12:03:24.865  5792  5838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 12:03:24.865  5792  5838 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 12:03:24.895  5792  5792 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 12:03:25.075  1018  1301 E Watchdog: !@Sync 3
,08-22 12:03:25.435  5792  5845 W jxcore-log: Initializing JXcore engine
08-22 12:03:25.435  5792  5845 W jxcore-log: JXcore engine is ready
,08-22 12:03:25.485  1908  1908 E audit   : type=1400 msg=audit(1471860205.485:203): avc:  denied  { ioctl } for  pid=5845 comm="Thread-1050" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-22 12:03:25.485  1908  1908 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:25.485  1908  1908 E audit   : type=1300 msg=audit(1471860205.485:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f2fb8f8 items=0 ppid=306 ppcomm=main pid=5845 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1050" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-22 12:03:25.485  1908  1908 E audit   : type=1320 msg=audit(1471860205.485:203): 
,08-22 12:03:25.495  5792  5845 W jxcore-log: Starting JXcore engine
,08-22 12:03:25.605  5792  5845 W jxcore-log: Platform android
08-22 12:03:25.605  5792  5845 W jxcore-log: 
08-22 12:03:25.605  5792  5845 W jxcore-log: Process ARCH arm
08-22 12:03:25.605  5792  5845 W jxcore-log: 
,08-22 12:03:25.805  5792  5845 I jxcore-log: JXcore Cordova bridge is ready!
08-22 12:03:25.805  5792  5845 I jxcore-log: 
,08-22 12:03:25.805  5792  5845 W jxcore-log: JXcore engine is started
,08-22 12:03:25.815  5792  5838 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-22 12:03:25.815  5792  5792 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 12:03:26.145   319   319 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-22 12:03:26.145   319   319 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-22 12:03:27.145   289   289 E SMD     : DCD OFF,
,08-22 12:03:28.465  1018  1043 W ProcessCpuTracker: Skipping unknown process pid 5846,
,08-22 12:03:30.145   289   289 E SMD     : DCD OFF
,08-22 12:03:30.825  1018  2604 D SSRM:n  : SIOP:: AP = 340
,08-22 12:03:31.145   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 12:03:31.895  1018  2617 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-22 12:03:32.145   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 12:03:33.145   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 12:03:33.145   289   289 E SMD     : DCD OFF
,08-22 12:03:33.365  1018  2952 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 12:03:33.365  1018  2952 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 12:03:33.365  1018  2952 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-22 12:03:33.365  1018  2952 D BatteryService: stay LED for fully charged,
08-22 12:03:33.365  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 12:03:33.365  1018  1018 I MotionRecognitionService: Plugged,
08-22 12:03:33.365  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 12:03:33.375  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-22 12:03:33.375  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 12:03:33.375  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 12:03:33.375  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 12:03:33.385  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 12:03:33.385  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 12:03:33.395  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 12:03:33.635  1018  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-22 12:03:34.145   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 12:03:35.145   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 12:03:36.145   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-22 12:03:36.155   289   289 E SMD     : DCD OFF,
,08-22 12:03:38.205  5792  5845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-22 12:03:38.205  5792  5845 I jxcore-log: 
,08-22 12:03:38.205  5792  5845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-22 12:03:38.205  5792  5845 I jxcore-log: 
,08-22 12:03:38.215  5792  5845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-22 12:03:38.215  5792  5845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:38.215  5792  5845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:38.215  5792  5845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:03:38.215  5792  5845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:38.215  5792  5845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:38.215  5792  5845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:38.215  5792  5845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:38.215  5792  5845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
08-22 12:03:38.215  5792  5845 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:38.215  5792  5845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 12:03:38.215  5792  5845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-22 12:03:38.215  5792  5845 I jxcore-log: 
,08-22 12:03:38.215  5792  5845 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-22 12:03:38.215  5792  5845 I jxcore-log: 
,08-22 12:03:38.865  5792  5845 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests,
08-22 12:03:38.865  5792  5845 I jxcore-log: Failed to execute UT.
08-22 12:03:38.865  5792  5845 I jxcore-log: 
08-22 12:03:38.865  5792  5845 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-22 12:03:38.865  5792  5845 I jxcore-log: 
,08-22 12:03:38.875  5792  5845 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 12:03:38.875  5792  5845 I jxcore-log: 
08-22 12:03:38.875  5792  5792 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-22 12:03:39.145  5852  5852 D AndroidRuntime: 
08-22 12:03:39.145  5852  5852 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-22 12:03:39.155   289   289 E SMD     : DCD OFF,
08-22 12:03:39.155  5852  5852 D AndroidRuntime: CheckJNI is OFF
08-22 12:03:39.155  5852  5852 D AndroidRuntime: readGMSProperty: start
08-22 12:03:39.155  5852  5852 D AndroidRuntime: readGMSProperty: already setted!!
08-22 12:03:39.155  5852  5852 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 12:03:39.155  5852  5852 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 12:03:39.155  5852  5852 D AndroidRuntime: readGMSProperty: end
08-22 12:03:39.155  5852  5852 D AndroidRuntime: addProductProperty: start
,08-22 12:03:39.265  5852  5852 E AffinityControl: AffinityControl: registerfunction enter,
,08-22 12:03:39.295  5852  5852 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-22 12:03:39.305  1018  1030 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-22 12:03:39.305  1018  1030 D PackageManager: START PACKAGE DELETE: observer{169276261}
08-22 12:03:39.305  1018  1030 D PackageManager: pkg{<packageName>}
08-22 12:03:39.305  1018  1030 D PackageManager: user{0}
08-22 12:03:39.305  1018  1030 D PackageManager: caller{2000}
08-22 12:03:39.305  1018  1030 D PackageManager: flags{2}
08-22 12:03:39.305  1018  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-22 12:03:39.305  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-22 12:03:39.305  1018  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-22 12:03:39.305  1018  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-22 12:03:39.305  1018  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-22 12:03:39.305  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-22 12:03:39.305  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-22 12:03:39.305  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-22 12:03:39.305  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-22 12:03:39.305  1018  1058 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-22 12:03:39.315  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg,
08-22 12:03:39.315  1018  1043 I ActivityManager: Killing 5792:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
08-22 12:03:39.315  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{3d9b1e91 u0 com.test.thalitest/.MainActivity t3}
,08-22 12:03:39.325  1018  1043 D InputDispatcher: Focus left window: 5792
,08-22 12:03:39.325   259   717 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
08-22 12:03:39.325   259   449 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-22 12:03:39.325  1018  1043 D InputDispatcher: Focused application released
08-22 12:03:39.325  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:39.325  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 12:03:39.325  1018  1043 D FocusedStackFrame: Set to : 0
,08-22 12:03:39.335  1018  1043 W ActivityManager: mDVFSHelper.acquire()
,08-22 12:03:39.405  1018  1058 W PackageSettings: Skipping PackageSetting{1e19eb98 com.example.hello/10168} due to missing metadata
,08-22 12:03:39.425  1018  1043 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-22 12:03:39.435  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-22 12:03:39.445  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-22 12:03:39.475  5498  5498 I art     : Explicit concurrent mark sweep GC freed 18084(988KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 702us total 30.049ms
,08-22 12:03:39.485  1478  1478 D Launcher: onRestart, Launcher: 457802695
,08-22 12:03:39.505  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 12:03:39.505  5636  5636 I art     : Explicit concurrent mark sweep GC freed 329(24KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 759us total 68.792ms
,08-22 12:03:39.515  1774  1774 E SamsungIME: mOCRHelper is null
,08-22 12:03:39.515  3977  3977 I art     : Explicit concurrent mark sweep GC freed 1776(79KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 11MB/15MB, paused 1.212ms total 77.423ms
,08-22 12:03:39.515  1918  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 12:03:39.535  1478  1478 D Launcher: onStart, Launcher: 457802695
08-22 12:03:39.535  1478  1478 D Launcher.HomeView: onStart
,08-22 12:03:39.535  1478  1478 D Launcher: onResume, Launcher: 457802695
,08-22 12:03:39.535  1018  1464 D SettingsProvider: name = kids_home_mode
08-22 12:03:39.535  1018  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 12:03:39.535  1018  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 12:03:39.535  1018  1464 D SettingsProvider: selectionArgs: false
08-22 12:03:39.535  1018  1464 D SettingsProvider: selectionArgs: 10006
08-22 12:03:39.535  1018  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 12:03:39.535  1018  1464 D SettingsProvider: ret = -1
,08-22 12:03:39.535  1478  1478 D Launcher.HomeView: onResume
08-22 12:03:39.535  1431  1431 D PersonaManager: isKioskContainerExistOnDevice
,08-22 12:03:39.545  1018  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-22 12:03:39.545  1018  1123 V NetworkStats: performPollLocked(flags=0x3)
08-22 12:03:39.545  1018  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 12:03:39.545  1018  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 12:03:39.545  3696  3696 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 12:03:39 GMT+02:00 2016
,08-22 12:03:39.545  1018  1123 V NetworkStats: performPollLocked() took 4ms
,08-22 12:03:39.555  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-22 12:03:39.555  1431  1431 D RegisteredServicesCache: empty dynamic service
,08-22 12:03:39.555  1018  2953 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-22 12:03:39.555  1018  2953 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 12:03:39.555  1018  2953 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:39.555  1018  2953 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:39.555  1018  2953 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 12:03:39.565  1478  1478 D MenuAppsGridFragment: onResume
,08-22 12:03:39.565  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-22 12:03:39.565  1478  1478 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-22 12:03:39.575  3696  3696 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 12:03:39.575  1018  2952 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-22 12:03:39.575  1018  2952 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-22 12:03:39.575  1018  2952 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-22 12:03:39.575  1018  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:39.575  1018  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.575  1018  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.575  1018  2952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:39.595  5865  5865 E Zygote  : MountEmulatedStorage()
08-22 12:03:39.595  5865  5865 I libpersona: KNOX_SDCARD checking this for 10090
08-22 12:03:39.595  5865  5865 E Zygote  : v2
08-22 12:03:39.595  5865  5865 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:39.595  5865  5865 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:39.595  1018  2952 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5865 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-22 12:03:39.595  5865  5865 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:39.595  5865  5865 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:39.595  1431  1431 D RegisteredComponentCache: Collect Tech packages for Knox
08-22 12:03:39.605  1018  2951 D ActivityManager: handle home activity for 0
08-22 12:03:39.605  1018  2951 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-22 12:03:39.605  1018  2951 D KnoxTimeoutHandler: post home show event for user 0
08-22 12:03:39.605  1018  2951 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-22 12:03:39.605  1018  2951 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 12:03:39.605  1018  2951 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-22 12:03:39.605  1431  1431 D PersonaManager: isKioskContainerExistOnDevice
,08-22 12:03:39.605  1478  1478 D Launcher.HomeView: onPause
08-22 12:03:39.605  3696  3696 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-22 12:03:39.605  1478  1478 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-22 12:03:39.615  3696  3696 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 12:03:39.635  1018  1136 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-22 12:03:39.635  1018  1136 D SecContentProvider2: mCursor = null
,08-22 12:03:39.645   259   259 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,08-22 12:03:39.645  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-22 12:03:39.645  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-22 12:03:39.655  1018  1030 D InputDispatcher: Focus entered window: 1478
,08-22 12:03:39.655  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:39.655  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 12:03:39.655  1478  1478 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-22 12:03:39.655  1018  1018 I art     : Explicit concurrent mark sweep GC freed 40660(2MB) AllocSpace objects, 25(400KB) LOS objects, 33% free, 24MB/36MB, paused 2.964ms total 208.255ms
,08-22 12:03:39.655  1018  1058 I art     : WaitForGcToComplete blocked for 122.846ms for cause Explicit
,08-22 12:03:39.665  5865  5865 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:39.665  5865  5865 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:39.665  3696  3696 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 12:03:39.675  1018  2951 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 12:03:39.695  3696  5864 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-22 12:03:39.695  1018  2951 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5792 uid 10171
,08-22 12:03:39.695  1018  1124 D NtpTrustedTime: forceRefresh() from cache miss
,08-22 12:03:39.695   279   993 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 12:03:39.695   279   993 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-22 12:03:39.705  1018  5881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-22 12:03:39.705  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-22 12:03:39.705  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.705  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.705  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.705  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:39.705   279   993 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 12:03:39.705   279   993 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-22 12:03:39.715  1018  1124 D NtpTrustedTime: forceRefresh Fail.,
,08-22 12:03:39.715  1018  1018 D RCPManagerService: PackageReceiver onReceive(),
08-22 12:03:39.715  1018  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5884 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 12:03:39.725  3696  5864 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-22 12:03:39.725  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-22 12:03:39.725  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-22 12:03:39.725  5884  5884 E Zygote  : MountEmulatedStorage()
08-22 12:03:39.725  5884  5884 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:39.725  5884  5884 E Zygote  : v2
,08-22 12:03:39.725  5884  5884 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:39.725  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-22 12:03:39.725  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-22 12:03:39.725  3696  5864 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-22 12:03:39.725  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
08-22 12:03:39.725  1774  1774 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-22 12:03:39.725  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.725  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.725  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.725  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.735  1018  1136 I TactileAssist: enable value -1
08-22 12:03:39.735  1018  1136 I TactileAssist: internal enable value -1
08-22 12:03:39.735  1018  1136 I TactileAssist: intensity value -1
08-22 12:03:39.735  1018  1136 I TactileAssist: saveAppList value true
08-22 12:03:39.735  5884  5884 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:39.735  5884  5884 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:39.735  3696  5864 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-22 12:03:39.735  5884  5884 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:39.745  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-22 12:03:39.755  5892  5892 E Zygote  : MountEmulatedStorage()
08-22 12:03:39.755  5892  5892 E Zygote  : v2
08-22 12:03:39.755  5892  5892 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:39.755  5892  5892 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:39.755  5892  5892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:39.755  5892  5892 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:39.755  5892  5892 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:39.755  1018  1136 I TactileAssist: List of disabled apps :
08-22 12:03:39.765  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-22 12:03:39.765  1018  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5892 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-22 12:03:39.785  5884  5884 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:39.785  5884  5884 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:39.795  1018  1048 W ActivityManager: mDVFSHelper.release()
08-22 12:03:39.795  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2282836a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:122645
,08-22 12:03:39.805  5865  5865 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-22 12:03:39.805  5865  5865 D elm:15121: ELMEngine.ELMEngine( context ).
,08-22 12:03:39.805  5865  5865 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-22 12:03:39.815  5620  5620 D Compatibility: onReceive() it will make start service
,08-22 12:03:39.825  1018  1471 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-22 12:03:39.825  1018  1471 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-22 12:03:39.825  5892  5892 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:39.825  5892  5892 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:39.835  1018  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:39.835  1018  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:39.835  1018  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-22 12:03:39.835  1018  2951 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-22 12:03:39.835  5865  5865 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-22 12:03:39.835  1018  2951 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-22 12:03:39.835  1018  2951 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:39.835  1018  2951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:39.835  1018  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-22 12:03:39.855  5865  5865 D elm:15121: ElmAgentService : onCreate()
,08-22 12:03:39.855  5865  5915 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-22 12:03:39.855  5865  5915 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-22 12:03:39.855  5865  5915 D elm:15121: MDMBridge.getInstance()
08-22 12:03:39.855  5865  5915 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 12:03:39.865  5620  5916 D Compatibility: onHandleIntent()
,08-22 12:03:39.865  5620  5916 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-22 12:03:39.865  1018  1218 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-22 12:03:39.865  1018  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 12:03:39.865  1018  1218 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:39.865  1018  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:39.865  1018  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-22 12:03:39.865  5884  5884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-22 12:03:39.865  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-22 12:03:39.865  5865  5915 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 12:03:39.865  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-22 12:03:39.875  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-22 12:03:39.875  1018  1018 V EnterpriseBillingPolicy: uID is 10171
08-22 12:03:39.875  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 12:03:39.875  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-22 12:03:39.875  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-22 12:03:39.875  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 12:03:39.875  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 12:03:39.875  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 12:03:39.875  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-22 12:03:39.875  1018  2951 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-22 12:03:39.875  1018  2951 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-22 12:03:39.875  5620  5916 D Compatibility: found: 2
08-22 12:03:39.875  5620  5916 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-22 12:03:39.875  5620  5916 D Compatibility: skipping ResolveInfo{393f5106 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-22 12:03:39.875  5620  5916 D Compatibility: considering ResolveInfo{1b4983c7 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-22 12:03:39.875  5620  5916 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-22 12:03:39.875  1018  2951 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:39.875  1018  2951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:39.875  1018  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-22 12:03:39.875  3696  5864 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-22 12:03:39.875  5620  5916 D Compatibility: enabling receiver ResolveInfo{375dedf4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-22 12:03:39.885  1018  1471 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-22 12:03:39.885  1018  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 12:03:39.885  5620  5916 D Compatibility: enabling receiver ResolveInfo{3036d91d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-22 12:03:39.885  1018  1471 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:39.885  1018  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:39.885  1018  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-22 12:03:39.885  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-22 12:03:39.885  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-22 12:03:39.885  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-22 12:03:39.885  1018  1018 V EnterpriseBillingPolicy: uID is 10171
08-22 12:03:39.885  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 12:03:39.885  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-22 12:03:39.885  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 12:03:39.885  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 12:03:39.885  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 12:03:39.885  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 12:03:39.885  1018  1161 D TaskPersister: removeObsoleteFile: deleting file=3_task.xml
,08-22 12:03:39.895  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-22 12:03:39.895  1018  2604 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-22 12:03:39.895  1018  1464 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-22 12:03:39.895  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-22 12:03:39.895  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-22 12:03:39.895  5620  5916 D Compatibility: enabling receiver ResolveInfo{6ef7792 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-22 12:03:39.895  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-22 12:03:39.895  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-22 12:03:39.895  1018  1018 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-22 12:03:39.895  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.895  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.895  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.895  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:39.905  5620  5916 D Compatibility: enabling receiver ResolveInfo{37509563 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-22 12:03:39.915  5920  5920 E Zygote  : MountEmulatedStorage(),
08-22 12:03:39.915  5920  5920 E Zygote  : v2
08-22 12:03:39.915  5920  5920 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:39.915  5920  5920 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:39.915  5920  5920 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:39.915  5920  5920 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:39.915  1018  1464 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5920 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 12:03:39.915  5920  5920 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:39.915  1173  1173 I StatusBar: Icon Only
08-22 12:03:39.915  1173  1173 D PanelView: There is/are notification(s) 
,08-22 12:03:39.925  5620  5916 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-22 12:03:39.925  1018  1464 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-22 12:03:39.935  5865  5865 D elm:15121: ElmAgentService : onDestroy().
,08-22 12:03:39.935  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:39.935  5892  5892 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-22 12:03:39.935  3696  5864 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-22 12:03:39.935  3696  5864 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-22 12:03:39.935  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.935  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:39.945  1018  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:39.955  5920  5920 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:39.955  5920  5920 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:39.965  1018  1058 I art     : Explicit concurrent mark sweep GC freed 17861(1522KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 8.108ms total 301.272ms
,08-22 12:03:39.965  5935  5935 E Zygote  : MountEmulatedStorage(),
08-22 12:03:39.965  5935  5935 E Zygote  : v2
08-22 12:03:39.965  5935  5935 I libpersona: KNOX_SDCARD checking this for 10055
08-22 12:03:39.965  5935  5935 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:39.975  5935  5935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:39.975  1018  1464 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5935 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-22 12:03:39.975  5935  5935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 12:03:39.975  5935  5935 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:39.985  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-22 12:03:39.985  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:39.985  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.985  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:39.985  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:40.005   306   306 I art     : Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 28.589ms
08-22 12:03:40.005  1018  1058 D PackageManager: delete codoeFile: 
08-22 12:03:40.005  5935  5935 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:40.005  5935  5935 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:40.015   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 569us total 16.279ms
,08-22 12:03:40.015  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest,
08-22 12:03:40.015  1018  1058 I AASA_removePackage: UID=10171 Target=com.test.thalitest
08-22 12:03:40.025  1018  1058 D PackageManager: result of delete: 1{169276261}
,08-22 12:03:40.035  5852  5852 D AndroidRuntime: Shutting down VM
,08-22 12:03:40.035   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.371ms
,08-22 12:03:40.035  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-22 12:03:40.035  1018  1058 D PackageManager: userId{-1}
08-22 12:03:40.035  1018  1058 D PackageManager: andCode{true}
,08-22 12:03:40.045  5950  5950 E Zygote  : MountEmulatedStorage(),
,08-22 12:03:40.045  5950  5950 E Zygote  : v2
08-22 12:03:40.045  5950  5950 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:40.045  5950  5950 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:40.045  5950  5950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:40.045  1018  1018 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5950 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 12:03:40.055  5636  5918 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
08-22 12:03:40.055  5950  5950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:40.055  5950  5950 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:40.055  3696  3696 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 12:03:40.065  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-22 12:03:40.085  1018  1030 D SecContentProvider2: uri = -1 selection = getSealedState
08-22 12:03:40.085  1018  1030 D SecContentProvider2: mCursor = null
,08-22 12:03:40.085  5892  5892 I PopupuiReceiver_KNOX: getSealedState : true
08-22 12:03:40.085  1018  1445 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-22 12:03:40.085  1018  1445 D SecContentProvider2: mCursor = null
08-22 12:03:40.085  5892  5892 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-22 12:03:40.085  1018  2951 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-22 12:03:40.085  1018  2951 D SecContentProvider2: mCursor = null
08-22 12:03:40.085  5950  5950 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:40.085  5950  5950 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:40.085  5892  5892 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-22 12:03:40.085  5892  5892 D PopupuiReceiver: Action package removed
,08-22 12:03:40.095  5920  5920 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 12:03:40.095  1018  1476 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-22 12:03:40.105  1018  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.105  1018  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.105  1018  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.105  1018  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:40.115  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-22 12:03:40.115  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-22 12:03:40.115  5935  5935 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-22 12:03:40.115  1018  1042 W TextServicesManagerService: no available spell checker services found
,08-22 12:03:40.115  5966  5966 E Zygote  : MountEmulatedStorage()
08-22 12:03:40.115  5966  5966 E Zygote  : v2
08-22 12:03:40.115  5966  5966 I libpersona: KNOX_SDCARD checking this for 10145
08-22 12:03:40.115  5966  5966 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:40.125  5966  5966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:40.125  1018  1476 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5966 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 12:03:40.125  5966  5966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:40.125  1018  1476 I ActivityManager: Killing 5408:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-22 12:03:40.125  5966  5966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:40.125  1018  1475 I ActivityManager: Killing 5426:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-22 12:03:40.145  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.145  5950  5950 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-22 12:03:40.145  5950  5950 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-22 12:03:40.145  5950  5950 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-22 12:03:40.145  5920  5920 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0,
08-22 12:03:40.145  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.155  5950  5950 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-22 12:03:40.155  5950  5950 I PCWCLIENTTRACE_PushUtil: sales region : global
08-22 12:03:40.155  5950  5950 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-22 12:03:40.155  5950  5950 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-22 12:03:40.165  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.165  1478  1478 V ActivityThread: updateVisibility : ActivityRecord{1780197 token=android.os.BinderProxy@d780d1b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-22 12:03:40.165  1478  1478 D Launcher.HomeView: onStop
08-22 12:03:40.165  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.165  5935  5935 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-22 12:03:40.165  1478  1478 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d780d1b time:123016
,08-22 12:03:40.165  5935  5935 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-22 12:03:40.165  5935  5935 D UserAnalysis: Create SecureDbHelper
08-22 12:03:40.165  5966  5966 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:40.165  5966  5966 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:40.175  1018  2951 D PersonaManager: isKioskContainerExistOnDevice
,08-22 12:03:40.185  1018  1030 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-22 12:03:40.185  1018  1030 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-22 12:03:40.185  5935  5935 D IntelligenceServiceApplication: onCreate()
,08-22 12:03:40.195  5935  5935 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-22 12:03:40.195  1018  1475 I ActivityManager: Killing 5463:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-22 12:03:40.195  1018  1475 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.apps.docs/com.google.android.apps.docs.receivers.AppPackageAddRemoveReceiver}
08-22 12:03:40.195  1018  1475 W BroadcastQueue: android.os.DeadObjectException
08-22 12:03:40.195  1018  1475 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-22 12:03:40.195  1018  1475 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-22 12:03:40.195  1018  1475 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-22 12:03:40.195  1018  1475 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-22 12:03:40.195  1018  1475 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-22 12:03:40.195  1018  1475 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-22 12:03:40.195  1018  1475 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-22 12:03:40.195  1018  1475 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-22 12:03:40.195  1018  1475 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-22 12:03:40.195  1018  1475 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-22 12:03:40.195  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.195  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.195  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.195  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.205  5935  5935 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-22 12:03:40.215  5982  5982 E Zygote  : MountEmulatedStorage()
08-22 12:03:40.215  5982  5982 E Zygote  : v2
08-22 12:03:40.215  5982  5982 I libpersona: KNOX_SDCARD checking this for 10087
08-22 12:03:40.215  5982  5982 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:40.215  1018  1475 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5982 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,08-22 12:03:40.225  1018  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:40.225  5982  5982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:40.225  1018  1471 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.225  1018  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:40.225  1018  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-22 12:03:40.225  5982  5982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 12:03:40.225  1018  2952 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
08-22 12:03:40.225  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-22 12:03:40.225  1018  1352 W ActivityManager: Spurious death for ProcessRecord{329cc667 5982:com.google.android.apps.docs/u0a87}, curProc for 5408: null
08-22 12:03:40.225  1018  2951 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-22 12:03:40.235  5982  5982 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-22 12:03:40.225  1018  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.235  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-22 12:03:40.225  1018  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.235  5852  5852 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-22 12:03:40.225  1018  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.225  1018  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:40.255  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-22 12:03:40.255  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.255  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.255  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-22 12:03:40.255  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-22 12:03:40.265  1018  2951 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5996 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-22 12:03:40.275  1018  2951 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,08-22 12:03:40.275  5996  5996 I libpersona: KNOX_SDCARD checking this for 10032,
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
08-22 12:03:40.275  5996  5996 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:40.265  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false,
08-22 12:03:40.275  1018  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-22 12:03:40.275  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:40.275  1018  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.275  5996  5996 E Zygote  : MountEmulatedStorage(),
08-22 12:03:40.275  1018  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.275  5996  5996 E Zygote  : v2
08-22 12:03:40.275  1018  2951 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:40.275  5982  5982 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:40.275  5982  5982 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:40.275  5996  5996 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:40.275  5935  5935 D BluetoothAdapter: 571046622: getState() :  mService = null. Returning STATE_OFF
08-22 12:03:40.275  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 12:03:40.275  5935  5935 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
08-22 12:03:40.275  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 12:03:40.275  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 12:03:40.285  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:40.285  5996  5996 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 12:03:40.285  5996  5996 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-22 12:03:40.295  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.295  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.295  6008  6008 E Zygote  : MountEmulatedStorage()
08-22 12:03:40.295  6008  6008 E Zygote  : v2
,08-22 12:03:40.295  6008  6008 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:40.295  6008  6008 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:40.295  6008  6008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 12:03:40.295  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:40.295  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-22 12:03:40.295  1018  2951 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 12:03:40.295  6008  6008 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:40.295  1018  2951 I ActivityManager: Killing 5483:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-22 12:03:40.295  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.305  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:40.305  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-22 12:03:40.305  6008  6008 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:40.305  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:40.305  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-22 12:03:40.305  5966  5966 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-22 12:03:40.305  5966  5966 D ThemeInfoUtil: isCurrentFestival = false
,08-22 12:03:40.305  1018  1471 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-22 12:03:40.305  1018  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.305  1018  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.305  1018  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.305  1018  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.305  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:40.315  5996  5996 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:40.315  5996  5996 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:40.325  6028  6028 E Zygote  : MountEmulatedStorage(),
08-22 12:03:40.325  6028  6028 E Zygote  : v2
08-22 12:03:40.325  6028  6028 I libpersona: KNOX_SDCARD checking this for 10148
08-22 12:03:40.325  6028  6028 I libpersona: KNOX_SDCARD not a persona,
08-22 12:03:40.325  6028  6028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:40.325  1018  1471 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6028 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,08-22 12:03:40.335  1018  1471 I ActivityManager: Killing 5324:com.android.mms/u0a41 (adj 15): empty #21
,08-22 12:03:40.335  6028  6028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:40.335  1018  1464 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-22 12:03:40.335  6028  6028 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:40.335  1018  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:40.335  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 12:03:40.345  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.345  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:40.345  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:40.345  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 12:03:40.345  5935  5935 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 12:03:40.345  6008  6008 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:40.345  6008  6008 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:40.355  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-22 12:03:40.355  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-22 12:03:40.355  1018  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:40.355  1018  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 12:03:40.355  1018  1475 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.355  1018  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:40.355  1018  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:40.365  1018  1042 W libprocessgroup: failed to open /acct/uid_10087/pid_5408/cgroup.procs: No such file or directory
,08-22 12:03:40.375  1018  2951 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 12:03:40.375  1018  2951 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.375  1018  2951 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:40.375  1018  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:40.375  6028  6028 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:40.375  6028  6028 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:40.375  6008  6008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 12:03:40.375  1018  1352 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:40.375  1018  1352 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 12:03:40.385  1018  1352 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.385  1018  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:40.385  1018  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:40.395  1018  1445 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-22 12:03:40.405  1018  1352 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-22 12:03:40.435  1018  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:40.435  6008  6008 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)
08-22 12:03:40.435  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.435  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:40.435  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db'.
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2443)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(DataStore.java:85)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider.onCreate(LowpowerContextProvider.java:303)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:40.435  6008  6008 E S,QLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 12:03:40.435  6008  6008 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 12:03:40.445  6008  6008 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131138) and mode_t (0) due to error (30)
08-22 12:03:40.445  3977  6045 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 12:03:40.445  3977  6045 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 12:03:40.445  6008  6008 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 12:03:40.445  6008  6008 D AndroidRuntime: Shutting down VM
08-22 12:03:40.445  6008  6008 E AndroidRuntime: FATAL EXCEPTION: main
08-22 12:03:40.445  6008  6008 E AndroidRuntime: Process: com.samsung.android.sm, PID: 6008
08-22 12:03:40.445  6008  6008 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.sm.database.SmProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 12:03:40.445  6008  6008 E AndroidRuntime: 	... 11 more
08-22 12:03:40.445  1018  1031 D CountryDetector: No listener is left
08-22 12:03:40.455  6028  6028 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 12:03:40.455  6028  6028 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 12:03:40.455  6028  6028 D AndroidRuntime: Shutting down VM
08-22 12:03:40.455  6028  6028 E AndroidRuntime: FATAL EXCEPTION: main
08-22 12:03:40.455  6028  6028 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 6028
08-22 12:03:40.455  6028  6028 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 12:03:40.455  6028  6028 E AndroidRuntime: 	... 11 more
08-22 12:03:40.455  5996  6047 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-22 12:03:40.455  5996  6047 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-22 12:03:40.465  1018  1464 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-22 12:03:40.465  1018  1464 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
08-22 12:03:40.465  1018  1218 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
08-22 12:03:40.465  1018  1464 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.465  1018  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:40.465  1018  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
08-22 12:03:40.465  1018  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,08-22 12:03:40.475  5996  6047 D SPPClientService: PushLog.txt file is not deleted.
08-22 12:03:40.475  5996  6047 D SPPClientService: PushLog.txt file is not deleted.
08-22 12:03:40.475  5996  6047 D SPPClientService: ============PushLog. stop!
08-22 12:03:40.475  1018  1445 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-22 12:03:40.485  3977  6045 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQstg5Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
08-22 12:03:40.485  3977  6045 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjQgKDMwNTE3NzQtMDM0KRji-eAR
08-22 12:03:40.485  3977  6045 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQwPngEQ
08-22 12:03:40.485  3977  6045 I GCore-Chimera-Crash: ==
08-22 12:03:40.485  3977  6045 I GCore-Chimera-Crash: GCore-Chimera-Crash
08-22 12:03:40.485  3977  6045 I DeviceDoctorDatabaseHelper: Cleaning stale data from database!
08-22 12:03:40.485  1018  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.485  1018  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.485  1018  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.485  1018  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.485  3977  6045 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131138) and mode_t (0) due to error (30)
08-22 12:03:40.485  3977  6045 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131072) and mode_t (0) due to error (2)
08-22 12:03:40.485  3977  6045 E SQLiteLog: (14) cannot open file at line 32510 of [b3bb660af9]
08-22 12:03:40.485  3977  6045 E SQLiteLog: (14) os_unix.c:32510: (2) open(/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db) - 
08-22 12:03:40.495  5996  5996 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
08-22 12:03:40.495  6050  6050 E Zygote  : MountEmulatedStorage()
08-22 12:03:40.495  6050  6050 E Zygote  : v2
08-22 12:03:40.495  6050  6050 I libpersona: KNOX_SDCARD checking this for 10039
08-22 12:03:40.495  6050  6050 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:40.495  6050  6050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:40.495  1018  1445 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6050 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db'.
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1508)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:22519)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at iiq.c(:com.google.android.gms:207)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at ifm.uncaughtException(:com.google.android.gms:2111)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at ifs.uncaughtException(:com.google.android.gms:54)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at ifl.uncaughtException(:com.google.android.gms:62)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-22 12:03:40.505  3977  6045 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-22 12:03:40.505  6050  6050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:40.505  6050  6050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:40.505  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-22 12:03:40.505  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
08-22 12:03:40.505  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.515  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:40.515  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-22 12:03:40.515  5996  5996 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.b(Unknown Source)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.a(Unknown Source)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.i.handleMessage(Unknown Source)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 12:03:40.515  5996  5996 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 12:03:40.515  5996  5996 E LNoti   : [b] open fail. SQLException occured
,08-22 12:03:40.515  1018  1352 I ActivityManager: Killing 5561:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-22 12:03:40.515  1018  2951 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:40.525  1018  2951 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.525  1018  2951 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:40.525  1018  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:40.525  1018  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 12:03:40.535  1018  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,08-22 12:03:40.535  1018  1471 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:40.535  1018  1471 I ActivityManager: Killing 5596:com.wsomacp/u0a23 (adj 15): empty #21
08-22 12:03:40.535  1018  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:40.535  1018  1471 I ActivityManager: Killing 5578:com.sec.android.app.myfiles/u0a42 (adj 15): empty #22
08-22 12:03:40.535  1018  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:40.535  3977  6045 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-22 12:03:40.535  3977  6045 E AndroidRuntime: Process: com.google.android.gms, PID: 3977
08-22 12:03:40.535  3977  6045 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at pgd.a(:com.google.android.gms:290)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at pgd.b(:com.google.android.gms:138)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at phk.a(:com.google.android.gms:382)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.InternalIcingCorporaChimeraProvider.update(:com.google.android.gms:247)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at com.google.android.chimera.container.ContentProviderProxy.update(:com.google.android.gms:462)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at pih.call(:com.google.android.gms:1333)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at pii.call(:com.google.android.gms:1266)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.UpdateIcingCorporaChimeraService.a(:com.google.android.gms:244)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.UpdateIcingCorporaChimeraService.onHandleIntent(:com.google.android.gms:2177)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at bhe.handleMessage(:com.google.android.gms:65)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:40.535  3977  6045 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 12:03:40.535  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-22 12:03:40.535  6050  6050 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:40.545  6050  6050 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:40.545  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.545  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.545  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:40.545  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:40.555  1018  6062 E DropBoxManagerService: Can't write: system_app_crash
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop166.tmp: open failed: EROFS (Read-only file system)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 12:03:40.555  1018  6062 E DropBoxManagerService: 	... 5 more
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: Can't write: system_app_crash
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop167.tmp: open failed: EROFS (Read-only file system)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 12:03:40.555  1018  6065 E DropBoxManagerService: 	... 5 more
,08-22 12:03:40.565  6067  6067 E Zygote  : MountEmulatedStorage(),
08-22 12:03:40.565  6067  6067 E Zygote  : v2
08-22 12:03:40.565  6067  6067 I libpersona: KNOX_SDCARD checking this for 10152
08-22 12:03:40.565  6067  6067 I libpersona: KNOX_SDCARD not a persona,
,08-22 12:03:40.565  6067  6067 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:40.565  6028  6028 I Process : Sending signal. PID: 6028 SIG: 9
,08-22 12:03:40.565  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6067 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-22 12:03:40.565  6067  6067 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:40.565   256   256 E lowmemorykiller: Error writing /proc/6028/oom_score_adj; errno=22
08-22 12:03:40.565  6067  6067 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 12:03:40.575  1018  1464 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,08-22 12:03:40.575  6008  6008 I Process : Sending signal. PID: 6008 SIG: 9
,08-22 12:03:40.585  1018  6075 E DropBoxManagerService: Can't write: system_app_crash
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop168.tmp: open failed: EROFS (Read-only file system)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 12:03:40.585  1018  6075 E DropBoxManagerService: 	... 5 more
,08-22 12:03:40.585  3977  6045 I Process : Sending signal. PID: 3977 SIG: 9
,08-22 12:03:40.605  6067  6067 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:40.605  6067  6067 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:40.605  6050  6050 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 12:03:40.605  6050  6050 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 12:03:40.605  6050  6050 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 12:03:40.605  6050  6050 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-22 12:03:40.605  6050  6050 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-22 12:03:40.605  6050  6050 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 12:03:40.605  6050  6050 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.

```
