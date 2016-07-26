#### Test 757892686f45c73_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
07-26 15:20:54.276  1012  2760 D SSRM:n  : SIOP:: AP = 330
07-26 15:20:54.296  1012  2804 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
07-26 15:20:54.496   288   288 E SMD     : DCD OFF
,07-26 15:20:55.866  1012  1336 E Watchdog: !@Sync 4
07-26 15:20:56.066  6300  6300 D AndroidRuntime: 
07-26 15:20:56.066  6300  6300 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-26 15:20:56.076  6300  6300 D AndroidRuntime: CheckJNI is OFF
07-26 15:20:56.076  6300  6300 D AndroidRuntime: readGMSProperty: start
07-26 15:20:56.076  6300  6300 D AndroidRuntime: readGMSProperty: already setted!!
07-26 15:20:56.076  6300  6300 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-26 15:20:56.076  6300  6300 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-26 15:20:56.076  6300  6300 D AndroidRuntime: readGMSProperty: end
07-26 15:20:56.076  6300  6300 D AndroidRuntime: addProductProperty: start
07-26 15:20:56.216  6300  6300 E AffinityControl: AffinityControl: registerfunction enter
07-26 15:20:56.246  6300  6300 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-26 15:20:56.256  1012  1025 E PersonaManagerService: inState():  stateMachine is null !!
07-26 15:20:56.256  1012  1025 I PersonaManagerService: PersonaId don't exist
07-26 15:20:56.256  1012  1025 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-26 15:20:56.266  1012  1025 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-26 15:20:56.276  1012  1025 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1012  pkgName : ACTIVITY_RESUME_BOOSTER@7
07-26 15:20:56.276  1012  1025 W ActivityManager: mDVFSHelper.acquire()
07-26 15:20:56.276  1012  1025 D FocusedStackFrame: Set to : 0
07-26 15:20:56.286  1012  1042 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-26 15:20:56.286  1012  1042 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-26 15:20:56.286  1012  1025 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-26 15:20:56.286  1012  1025 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-26 15:20:56.286  1012  1025 D InputDispatcher: Focused application set to: xxxx
07-26 15:20:56.286  1482  1482 D Launcher.HomeView: onPause
07-26 15:20:56.286  1012  1025 D InputDispatcher: Focus left window: 1482
07-26 15:20:56.286  6300  6300 D AndroidRuntime: Shutting down VM
07-26 15:20:56.286  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-26 15:20:56.286  1012  1037 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:56.286  1012  1037 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:56.286  1012  1037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-26 15:20:56.296  1012  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:56.296  5650  5650 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
07-26 15:20:56.296  1012  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:56.296  1012  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:56.296  1012  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:56.296  1012  1042 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-26 15:20:56.296  1012  1042 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-26 15:20:56.296   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-26 15:20:56.306  6311  6311 E Zygote  : MountEmulatedStorage()
07-26 15:20:56.306  6311  6311 E Zygote  : v2
07-26 15:20:56.306  6311  6311 I libpersona: KNOX_SDCARD checking this for 10155
07-26 15:20:56.306  6311  6311 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:56.316  6311  6311 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-26 15:20:56.316  1012  1132 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6311 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-26 15:20:56.316  1012  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-26 15:20:56.316  1012  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
07-26 15:20:56.316  6311  6311 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-26 15:20:56.326  6311  6311 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-26 15:20:56.336  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{9be75a0 token=android.os.BinderProxy@2453b726 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-26 15:20:56.356  6311  6311 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:56.356  6311  6311 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:56.356  1012  1024 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
07-26 15:20:56.356  1012  1024 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-26 15:20:56.356  1012  1024 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
07-26 15:20:56.366  1012  1012 V ActivityManager: Display changed displayId=0
07-26 15:20:56.366  1012  1040 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:20:56.366  1482  1482 D Launcher.HomeView: onStop
07-26 15:20:56.376  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{9be75a0 token=android.os.BinderProxy@2453b726 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-26 15:20:56.376  1012  1024 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:20:56.386  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-26 15:20:56.386  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-26 15:20:56.386  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-26 15:20:56.386  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-26 15:20:56.386  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-26 15:20:56.386  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-26 15:20:56.406  1012  1012 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-26 15:20:56.406  1012  1012 D SensorService: [SO] activate (ident=0xb818a418, enabled=0)
07-26 15:20:56.406  1012  1012 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
07-26 15:20:56.416  1012  1012 D SensorManager: unregisterListener ::   
07-26 15:20:56.416  1012  1012 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
07-26 15:20:56.416  1482  1482 D Launcher: onTrimMemory. Level: 20
07-26 15:20:56.416  1012  1012 D SensorService: [SO] changed settle time [1]
07-26 15:20:56.416  1012  1012 D SensorService: [SO] setDelay [66000000]
07-26 15:20:56.416  1012  1012 D SensorService: [SO] activate (ident=0xb83f8dd0, enabled=1)
07-26 15:20:56.416  1012  1012 D SensorService: [SO] AR_init
07-26 15:20:56.416  1012  1012 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
07-26 15:20:56.416  1012  1012 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
07-26 15:20:56.486  1012  1034 D SensorService: [SO] Reset Rotation Old [100], Init [1]
07-26 15:20:56.496  6300  6300 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-26 15:20:56.506  6311  6311 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-26 15:20:56.516   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:20:56.526  6311  6311 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8820-8822)
,07-26 15:20:56.526  6311  6311 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-26 15:20:56.546  6311  6311 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1bd5737}
,07-26 15:20:56.546  6311  6311 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-26 15:20:56.546  6311  6311 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-26 15:20:56.556  1012  1034 D SensorService: [SO] currT = 138850555726, prevT = 138540241716, diff = 310314010, [0.144 -0.306 10.199]
,07-26 15:20:56.556  1012  1034 D SensorService: [SO] 0.144 -0.306 10.199
,07-26 15:20:56.556  1012  1034 D SensorService: [SO] [100 -> 255]
,07-26 15:20:56.576  6311  6311 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-26 15:20:56.586  6311  6311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:56.586  6311  6311 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-26 15:20:56.606  6311  6311 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-26 15:20:56.606  6311  6311 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-26 15:20:56.606  6311  6311 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-26 15:20:56.606  6311  6311 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-26 15:20:56.606  6311  6311 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-26 15:20:56.606  6311  6311 I Adreno-EGL: Build Date: 04/06/15 Mon
07-26 15:20:56.606  6311  6311 I Adreno-EGL: Local Branch: 
07-26 15:20:56.606  6311  6311 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-26 15:20:56.606  6311  6311 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-26 15:20:56.606  6311  6311 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-26 15:20:56.736  6311  6337 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-26 15:20:56.786  6311  6311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:56.796  6311  6311 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-26 15:20:56.806  6311  6311 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-26 15:20:56.806  6311  6311 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-26 15:20:56.816  6311  6311 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-26 15:20:56.816   257  1093 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,07-26 15:20:56.816   257   452 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,07-26 15:20:56.826  6311  6311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:56.826  6311  6311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:56.866  6311  6350 D OpenGLRenderer: Render dirty regions requested: true
,07-26 15:20:56.876  1012  1477 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-26 15:20:56.876  1012  1477 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-26 15:20:56.876  1012  1477 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-26 15:20:56.876  1012  1012 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-26 15:20:56.876  1012  1012 D PersonaManagerService: getPersonasForUser(): returning null!
,07-26 15:20:56.886  6311  6311 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-26 15:20:56.886  6311  6311 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-26 15:20:56.886   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-26 15:20:56.896  1012  1527 D InputDispatcher: Focus entered window: 6311
,07-26 15:20:56.906  1012  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-26 15:20:56.906  1012  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
07-26 15:20:56.906  6311  6311 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-26 15:20:56.906  6311  6350 I OpenGLRenderer: Initialized EGL, version 1.4
,07-26 15:20:56.916  6311  6350 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,07-26 15:20:56.916  6311  6350 D OpenGLRenderer: Enabling debug mode 0
,07-26 15:20:56.996  1012  1477 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-26 15:20:56.996  1012  6353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-26 15:20:57.006  1176  1176 I StatusBar: Icon Only
,07-26 15:20:57.006  1176  1176 D PanelView: There is/are notification(s) 
,07-26 15:20:57.006  1012  1042 I ActivityManager: Displayed Component not be shown by security: +711ms (total +25s404ms)
,07-26 15:20:57.006  1012  1042 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1012  tag : ACTIVITY_RESUME_BOOSTER@7
,07-26 15:20:57.006  1012  1042 W ActivityManager: mDVFSHelper.release()
07-26 15:20:57.006  1012  1042 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c84d4c5 u0 com.test.thalitest/.MainActivity t66} time:139306
07-26 15:20:57.006  1012  1037 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1012  pkgName : ACTIVITY_RESUME_BOOSTER@11
,07-26 15:20:57.026  1770  1770 I SamsungIME: getCurrentCandidateView
,07-26 15:20:57.026  6311  6311 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a262440 time:139320
,07-26 15:20:57.096  1770  1770 D SamsungIME: Dismiss ExpandCandiate
,07-26 15:20:57.096  6311  6311 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6311
,07-26 15:20:57.206   257  1093 I SurfaceFlinger: id=12 Removed uhalitest (7/8)
,07-26 15:20:57.206   257   452 I SurfaceFlinger: id=12 Removed uhalitest (-2/8)
,07-26 15:20:57.236  6311  6311 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,07-26 15:20:57.246  1770  1770 I SamsungIME: getDebugLevel  : 0x4f4c
,07-26 15:20:57.286  1770  1770 I SamsungIME: getDebugLevel  : 0x4f4c
,07-26 15:20:57.306  1770  1770 I SamsungIME: KeybaordView init() : load resources
,07-26 15:20:57.306  1012  1012 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1012  tag : ACTIVITY_RESUME_BOOSTER@11
,07-26 15:20:57.346  1770  1770 I SamsungIME: getCurrentKeyboard
07-26 15:20:57.346  1770  1770 I SamsungIME: getTextKeyboard
,07-26 15:20:57.366  1770  1770 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-26 15:20:57.376  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-26 15:20:57.376  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-26 15:20:57.376  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-26 15:20:57.376  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-26 15:20:57.376  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-26 15:20:57.376  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-26 15:20:57.416  6311  6356 D jxcore_app_log: JniHelper::setJavaVM(0xb7b82328), pthread_self() = -1207049640
,07-26 15:20:57.426  6311  6356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 15:20:57.426  6311  6356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:20:57.426  6311  6356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:20:57.426  6311  6356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:20:57.426  6311  6356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-26 15:20:57.436  6311  6356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a20896e added. We now have 1 listener(s)
,07-26 15:20:57.436  6311  6356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,07-26 15:20:57.436  6311  6356 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,07-26 15:20:57.456  6311  6356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:20:57.456  6311  6356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-26 15:20:57.466  6311  6356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fa81aa5 added. We now have 1 listener(s)
,07-26 15:20:57.466  6311  6356 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:20:57.486  6311  6356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:20:57.486  6311  6356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2,
07-26 15:20:57.486  6311  6356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3,
07-26 15:20:57.486  6311  6356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-26 15:20:57.486  6311  6356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:20:57.496  6311  6356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,07-26 15:20:57.496   288   288 E SMD     : DCD OFF
,07-26 15:20:57.506  6311  6356 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,07-26 15:20:57.506  6311  6356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:57.506  6311  6356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:57.506  6311  6356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:20:57.506  6311  6356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:57.506  6311  6356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:57.506  6311  6356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:57.506  6311  6356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:57.506  6311  6356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:57.506  6311  6356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-26 15:20:57.506  6311  6356 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:20:57.506  6311  6356 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-26 15:20:57.516   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:20:57.606  6311  6311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:57.606  6311  6311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:57.606  6311  6311 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-26 15:20:57.836  1012  1044 D PowerManagerService: [s] UserActivityState : 1 -> 2
,07-26 15:20:57.836  1012  1044 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,07-26 15:20:57.836  1012  1044 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-26 15:20:57.836  1012  1044 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,07-26 15:20:57.846  1012  1156 D lights  : lcd : 33 +
,07-26 15:20:57.866  1012  1044 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,07-26 15:20:57.866  1012  1044 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-26 15:20:57.866  1012  1156 D lights  : lcd : 33 -
,07-26 15:20:57.866  1012  1156 D lights  : lcd : 19 +
,07-26 15:20:57.886  1012  1156 D lights  : lcd : 19 -
,07-26 15:20:57.886  1012  1044 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,07-26 15:20:57.886  1012  1044 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-26 15:20:57.936  1770  6362 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-26 15:20:58.066  6311  6368 W jxcore-log: Initializing JXcore engine
07-26 15:20:58.066  6311  6368 W jxcore-log: JXcore engine is ready
,07-26 15:20:58.116  1928  1928 E audit   : type=1400 msg=audit(1469539258.116:205): avc:  denied  { ioctl } for  pid=6368 comm="Thread-1095" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-26 15:20:58.116  1928  1928 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
07-26 15:20:58.116  1928  1928 E audit   : type=1300 msg=audit(1469539258.116:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9bf028f8 items=0 ppid=311 ppcomm=main pid=6368 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1095" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-26 15:20:58.116  1928  1928 E audit   : type=1320 msg=audit(1469539258.116:205): 
,07-26 15:20:58.126  6311  6368 W jxcore-log: Starting JXcore engine
,07-26 15:20:58.246  6311  6368 W jxcore-log: Platform android
07-26 15:20:58.246  6311  6368 W jxcore-log: 
07-26 15:20:58.246  6311  6368 W jxcore-log: Process ARCH arm
07-26 15:20:58.246  6311  6368 W jxcore-log: 
,07-26 15:20:58.436  6311  6368 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:20:58.436  6311  6368 I jxcore-log: 
,07-26 15:20:58.436  6311  6368 W jxcore-log: JXcore engine is started
,07-26 15:20:58.446  6311  6356 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:20:58.446  6311  6311 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 15:20:58.466  6311  6368 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-26 15:20:58.466  6311  6368 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-26 15:20:58.476  6311  6311 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-26 15:20:58.476  6311  6311 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-26 15:20:58.476  1012  1471 D FocusedStackFrame: Set to : 0
07-26 15:20:58.476  1012  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-26 15:20:58.476  1012  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-26 15:20:58.476  1012  1471 D InputDispatcher: Focused application set to: xxxx
07-26 15:20:58.476  1012  1471 D InputDispatcher: Focus left window: 6311
07-26 15:20:58.486  1012  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-26 15:20:58.486  1012  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-26 15:20:58.516   322   322 I ServiceManager: Waiting for service AtCmdFwd...
07-26 15:20:58.536  6311  6356 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 57ms. Plugin should use CordovaInterface.getThreadPool().
07-26 15:20:58.536  6311  6311 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-26 15:20:58.536  6311  6311 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-26 15:20:58.536  1012  1528 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1012  pkgName : ACTIVITY_RESUME_BOOSTER@7
,07-26 15:20:58.546  1012  1528 W ActivityManager: mDVFSHelper.acquire()
,07-26 15:20:58.546  1012  1528 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
07-26 15:20:58.546  1012  1528 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-26 15:20:58.546  1012  1528 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,07-26 15:20:58.566  1482  1482 D Launcher: onRestart, Launcher: 260452307
,07-26 15:20:58.566  1482  1482 D Launcher: onStart, Launcher: 260452307
,07-26 15:20:58.566  1482  1482 D Launcher.HomeView: onStart
,07-26 15:20:58.566  1482  1482 D Launcher: onResume, Launcher: 260452307
07-26 15:20:58.566  1012  1245 D SettingsProvider: name = kids_home_mode
07-26 15:20:58.566  1012  1245 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-26 15:20:58.566  1012  1245 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-26 15:20:58.566  1012  1245 D SettingsProvider: selectionArgs: false
07-26 15:20:58.566  1012  1245 D SettingsProvider: selectionArgs: 10007
07-26 15:20:58.566  1012  1245 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
07-26 15:20:58.566  1012  1245 D SettingsProvider: ret = -1
07-26 15:20:58.576  1482  1482 D Launcher.HomeView: onResume
,07-26 15:20:58.576  1012  1012 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200,
07-26 15:20:58.576  1012  1012 D SensorService: [SO] activate (ident=0xb83f8dd0, enabled=0)
07-26 15:20:58.576  1012  1012 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,07-26 15:20:58.576  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-26 15:20:58.576  1482  1482 D MenuAppsGridFragment: onResume
,07-26 15:20:58.586  1012  1037 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:58.586  1012  1037 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.586  1012  1037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-26 15:20:58.586  1012  1024 D ActivityManager: handle home activity for 0
07-26 15:20:58.586  1012  1528 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
07-26 15:20:58.586  1012  1024 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-26 15:20:58.586  1012  1528 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
07-26 15:20:58.586  1012  1024 D KnoxTimeoutHandler: post home show event for user 0
07-26 15:20:58.586  1012  1024 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-26 15:20:58.586  1012  1024 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-26 15:20:58.586  1012  1024 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-26 15:20:58.586   257   257 I SurfaceFlinger: id=14 createSurf (720x1280),1 flag=4, Mauncher
,07-26 15:20:58.586  1012  1528 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.586  1012  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.586  1012  1040 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:20:58.586  1012  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-26 15:20:58.596  1012  1245 D InputDispatcher: Focus entered window: 1482
07-26 15:20:58.596  1012  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-26 15:20:58.596  1012  1040 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:20:58.596  1012  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
07-26 15:20:58.596  1482  1482 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-26 15:20:58.596  1012  1012 D SensorManager: unregisterListener ::   
,07-26 15:20:58.596  1012  1037 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.596  1012  1037 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.596  1012  1037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-26 15:20:58.596  1012  1012 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
07-26 15:20:58.596  4995  4995 D GalleryCacheReady: Receive : home resume
07-26 15:20:58.596  1012  1012 D SensorService: [SO] changed settle time [0]
07-26 15:20:58.596  1012  1012 D SensorService: [SO] setDelay [200000000]
07-26 15:20:58.596  1012  1012 D SensorService: [SO] activate (ident=0xb83f8dd0, enabled=1)
07-26 15:20:58.596  1012  1012 D SensorService: [SO] AR_init
07-26 15:20:58.596  1012  1012 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,07-26 15:20:58.606  1012  1012 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
07-26 15:20:58.606  1012  1012 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-26 15:20:58.606  1012  1012 D PersonaManagerService: getPersonasForUser(): returning null!
07-26 15:20:58.606  1012  1012 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-26 15:20:58.606  1012  1012 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-26 15:20:58.606  1012  1037 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.606  1012  1037 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.606  1012  1037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-26 15:20:58.616  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
07-26 15:20:58.616  1012  1132 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-26 15:20:58.616  1012  1528 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:58.616  1012  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.616  1012  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-26 15:20:58.616  1012  6373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-26 15:20:58.616  1176  1176 I StatusBar: Icon Only
07-26 15:20:58.626  1176  1176 D PanelView: There is/are notification(s) 
,07-26 15:20:58.626  1012  1037 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.626  1012  1037 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.626  1012  1037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-26 15:20:58.626  6311  6311 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-26 15:20:58.626  5794  5794 D Mms/UIEventReceiver: ui event
07-26 15:20:58.626  1770  1770 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-26 15:20:58.636  1012  1528 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:58.636  1012  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.636  1012  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-26 15:20:58.646  5650  5650 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-26 15:20:58.656  1012  1528 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.656  1012  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.656  1012  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-26 15:20:58.656  1012  1528 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1482, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,07-26 15:20:58.656  1482  1482 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2453b726 time:140952
,07-26 15:20:58.656  1012  1037 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.656  1012  1037 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.656  1012  1037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
07-26 15:20:58.656  1012  1042 D PersonaManager: isKioskContainerExistOnDevice
,07-26 15:20:58.656  2520  2520 D Recents_RecreateReceiver: onReceive by home
,07-26 15:20:58.656  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.656  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.656  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-26 15:20:58.676  1012  1042 I ActivityManager: Displayed Component not be shown by security: +130ms (total +24s838ms)
,07-26 15:20:58.676  1012  1347 I splitIntent: Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,07-26 15:20:58.776  6369  6369 D AndroidRuntime: ,
07-26 15:20:58.776  6369  6369 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-26 15:20:58.776  6369  6369 D AndroidRuntime: CheckJNI is OFF,
,07-26 15:20:58.776  6369  6369 D AndroidRuntime: readGMSProperty: start
07-26 15:20:58.776  6369  6369 D AndroidRuntime: readGMSProperty: already setted!!
07-26 15:20:58.776  6369  6369 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-26 15:20:58.776  6369  6369 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-26 15:20:58.776  6369  6369 D AndroidRuntime: readGMSProperty: end
,07-26 15:20:58.776  6369  6369 D AndroidRuntime: addProductProperty: start
,07-26 15:20:58.806  1012  1034 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,07-26 15:20:58.916  6369  6369 E AffinityControl: AffinityControl: registerfunction enter
,07-26 15:20:58.936  6369  6369 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-26 15:20:58.956  1012  1471 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
07-26 15:20:58.956  1012  1471 D PackageManager: START PACKAGE DELETE: observer{1042399332}
07-26 15:20:58.956  1012  1471 D PackageManager: pkg{<packageName>}
07-26 15:20:58.956  1012  1471 D PackageManager: user{0}
07-26 15:20:58.956  1012  1471 D PackageManager: caller{2000}
07-26 15:20:58.956  1012  1471 D PackageManager: flags{2}
07-26 15:20:58.956  1012  1471 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-26 15:20:58.956  1012  1471 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-26 15:20:58.956  1012  1471 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-26 15:20:58.956  1012  1471 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-26 15:20:58.956  1012  1052 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-26 15:20:58.956  1012  1052 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-26 15:20:58.956  1012  1052 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-26 15:20:58.956  1012  1052 D ApplicationPolicy: getApplicationUninstallationEnabled
07-26 15:20:58.956  1012  1052 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-26 15:20:58.956  1012  1052 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,07-26 15:20:58.956  1012  1037 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
07-26 15:20:58.956  1012  1037 I ActivityManager: Killing 6311:com.test.thalitest/u0a155 (adj 1): stop com.test.thalitest cause uninstall pkg
,07-26 15:20:59.006  1012  1034 D SensorService: [SO] currT = 141300063538, prevT = 140810201923, diff = 489861615, [0.144 -0.306 10.247]
,07-26 15:20:59.006  1012  1034 D SensorService: [SO] 0.144 -0.306 10.247
07-26 15:20:59.006  1012  1034 D SensorService: [SO] [100 -> 255]
,07-26 15:20:59.036  1012  1025 I WindowState: WIN DEATH: Window{b1dab21 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,07-26 15:20:59.036  1012  1037 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1012  tag : ACTIVITY_RESUME_BOOSTER@7,
,07-26 15:20:59.036  1012  1037 W ActivityManager: mDVFSHelper.release()
07-26 15:20:59.036  1012  1037 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1012  pkgName : ACTIVITY_RESUME_BOOSTER@11
,07-26 15:20:59.076  1012  1052 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,07-26 15:20:59.086  1012  1052 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-26 15:20:59.106   257   448 I SurfaceFlinger: id=13 Removed NainActivit (7/8)
,07-26 15:20:59.106   257  1093 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-26 15:20:59.106   257  1093 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-26 15:20:59.126  5672  5672 I art     : Explicit concurrent mark sweep GC freed 13273(745KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 6MB/9MB, paused 673us total 34.507ms
,07-26 15:20:59.136  5596  5596 I art     : Explicit concurrent mark sweep GC freed 1964(113KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 705us total 41.472ms
,07-26 15:20:59.136  6049  6049 I art     : Explicit concurrent mark sweep GC freed 595(34KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 12.259ms total 47.150ms
,07-26 15:20:59.146  1800  2044 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:20:59.146  1770  1770 E SamsungIME: mOCRHelper is null
,07-26 15:20:59.156  3737  3737 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jul 26 15:20:59 GMT+02:00 2016
,07-26 15:20:59.166  1012  1042 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26e42fc8 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t64} time:141464
,07-26 15:20:59.166  1012  1527 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-26 15:20:59.166  1012  1527 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.176  1012  1527 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.176  1012  1527 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.176  1012  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-26 15:20:59.176  3802  3802 I art     : Explicit concurrent mark sweep GC freed 21053(1297KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 15MB/21MB, paused 1.316ms total 93.852ms
,07-26 15:20:59.176  1435  1435 D PersonaManager: isKioskContainerExistOnDevice
,07-26 15:20:59.186  1012  1119 V NetworkStats: removeUidsLocked() for UIDs [10155]
07-26 15:20:59.186  1012  1119 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:20:59.186  1012  1119 V NetworkStats: performPollLocked(flags=0x3)
,07-26 15:20:59.196  1012  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
07-26 15:20:59.196  1012  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-26 15:20:59.196  3737  3737 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,07-26 15:20:59.206  3802  3814 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-26 15:20:59.206  1012  1119 V NetworkStats: performPollLocked() took 15ms
07-26 15:20:59.206  1012  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:20:59.206  1012  1095 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-26 15:20:59.206  1012  1478 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
07-26 15:20:59.206  1435  1435 D RegisteredServicesCache: empty dynamic service
07-26 15:20:59.206  1012  1478 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-26 15:20:59.206  1012  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-26 15:20:59.216  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.216  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.216  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.216  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.226  6385  6385 E Zygote  : MountEmulatedStorage()
07-26 15:20:59.226  6385  6385 E Zygote  : v2
07-26 15:20:59.226  6385  6385 I libpersona: KNOX_SDCARD checking this for 10094
07-26 15:20:59.226  6385  6385 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.226  6385  6385 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-26 15:20:59.236  1012  1478 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6385 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,07-26 15:20:59.236  6385  6385 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,07-26 15:20:59.236  3737  3737 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,07-26 15:20:59.236  6385  6385 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:20:59.246  1012  1037 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,07-26 15:20:59.246  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.246  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.246  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.246  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.256  4995  4995 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,07-26 15:20:59.256  3737  3737 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-26 15:20:59.266  6392  6392 E Zygote  : MountEmulatedStorage()
07-26 15:20:59.266  6392  6392 E Zygote  : v2
07-26 15:20:59.266  6392  6392 I libpersona: KNOX_SDCARD checking this for 10149
07-26 15:20:59.266  6392  6392 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.266  6392  6392 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-26 15:20:59.266  6392  6392 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-26 15:20:59.276  6392  6392 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,07-26 15:20:59.276  1012  1037 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6392 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:20:59.276  1435  1435 D RegisteredComponentCache: Collect Tech packages for Knox
,07-26 15:20:59.286  1435  1435 D PersonaManager: isKioskContainerExistOnDevice
,07-26 15:20:59.296  3737  3737 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-26 15:20:59.306  6392  6392 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:20:59.306  6385  6385 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:20:59.306  6392  6392 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:59.306  6385  6385 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:59.316  1012  1471 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-26 15:20:59.316  1012  1471 D SecContentProvider2: mCursor = null
,07-26 15:20:59.316  5794  5794 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,07-26 15:20:59.326  3737  6384 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-26 15:20:59.336  1012  1012 I art     : Explicit concurrent mark sweep GC freed 58088(4MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 31MB/47MB, paused 5.303ms total 244.726ms
,07-26 15:20:59.336  1012  1052 I art     : WaitForGcToComplete blocked for 150.459ms for cause Explicit
07-26 15:20:59.336  1012  1025 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,07-26 15:20:59.336  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.336  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:59.336  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.346  1012  1036 D EnterpriseDeviceManagerService: Package has changed for user 0
07-26 15:20:59.346  1012  1036 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-26 15:20:59.346  1012  1036 W TextServicesManagerService: no available spell checker services found
07-26 15:20:59.346  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,07-26 15:20:59.346  3737  6384 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,07-26 15:20:59.356  3737  6384 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,07-26 15:20:59.356  3737  6384 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-26 15:20:59.366  5794  6417 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,07-26 15:20:59.366  5794  6417 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,07-26 15:20:59.376  1012  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:20:59.376  1012  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:20:59.376  5672  5672 I art     : Explicit concurrent mark sweep GC freed 885(39KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 1.898ms total 36.655ms
,07-26 15:20:59.406  1012  1527 I TactileAssist: enable value -1
07-26 15:20:59.406  1012  1527 I TactileAssist: internal enable value -1
07-26 15:20:59.406  1012  1527 I TactileAssist: intensity value -1
07-26 15:20:59.406  1012  1527 I TactileAssist: saveAppList value true
,07-26 15:20:59.406  5672  6411 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,07-26 15:20:59.416  1012  1527 I TactileAssist: List of disabled apps :
,07-26 15:20:59.436  6385  6385 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-26 15:20:59.436  6385  6385 D elm:15183: ELMEngine.ELMEngine( context ).
,07-26 15:20:59.436  6385  6385 D elm:15183: MDMBridge.setEnterpriseBridge()
,07-26 15:20:59.446  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.456  1012  1525 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-26 15:20:59.456  1012  1525 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.456  1012  1525 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:59.456  1012  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.456  1012  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-26 15:20:59.456  5970  5978 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-26 15:20:59.456  5970  5978 D BadgeProvider: sendNotify, [notify] : null
07-26 15:20:59.456  5970  5978 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-26 15:20:59.456  5970  5978 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-26 15:20:59.456  5970  5978 D BadgeProvider: update, [UpdateCount] : 1
,07-26 15:20:59.466  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,07-26 15:20:59.466  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.466  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.466  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.466  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.476  6385  6385 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-26 15:20:59.486  6419  6419 E Zygote  : MountEmulatedStorage()
,07-26 15:20:59.486  6419  6419 E Zygote  : v2
07-26 15:20:59.486  6419  6419 I libpersona: KNOX_SDCARD checking this for 1000
07-26 15:20:59.486  6419  6419 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.486  6419  6419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,07-26 15:20:59.486  1012  1025 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6419 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,07-26 15:20:59.486  6419  6419 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,07-26 15:20:59.496  6419  6419 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:20:59.506  3367  3367 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-26 15:20:59.506  1012  1012 D RCPManagerService: PackageReceiver onReceive()
07-26 15:20:59.506  1012  1012 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-26 15:20:59.506  3367  3367 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-26 15:20:59.506  3367  3367 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
,07-26 15:20:59.506  3367  3367 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
,07-26 15:20:59.506  3367  3367 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-26 15:20:59.506  3367  3367 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-26 15:20:59.506  1012  1012 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-26 15:20:59.506  1012  1012 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,07-26 15:20:59.516  3367  3367 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-26 15:20:59.516  3367  3367 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:59.516  3367  3367 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:20:59.516  3367  3367 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-26 15:20:59.516  3367  3367 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:59.516  3367  3367 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:20:59.516  3367  3367 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-26 15:20:59.516  3367  3367 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-26 15:20:59.516  1012  1012 D OTPFW   : OtpDbHelper::getInstance New instance created
,07-26 15:20:59.516  6385  6385 D elm:15183: ElmAgentService : onCreate()
,07-26 15:20:59.516  6385  6418 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-26 15:20:59.516  6385  6418 D elm:15183: MainReceiver.listeningToPackageRemoved()
07-26 15:20:59.516  6385  6418 D elm:15183: MDMBridge.getInstance()
07-26 15:20:59.516  6385  6418 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,07-26 15:20:59.516  6392  6392 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-26 15:20:59.516  6392  6392 D ThemeInfoUtil: isCurrentFestival = false
,07-26 15:20:59.516  1012  1012 D OTPFW   : DBIntegrity::getInstance - New instance created
07-26 15:20:59.516   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:20:59.526  3737  6384 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-26 15:20:59.526  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.526  6385  6418 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,07-26 15:20:59.526  6020  6020 D Compatibility: onReceive() it will make start service
,07-26 15:20:59.536  1012  1012 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,07-26 15:20:59.536  3737  6384 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-26 15:20:59.536  1012  1012 I OTPFW   : ProvisionData::getAllEntries Enter
,07-26 15:20:59.536  1012  1012 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-26 15:20:59.536  1012  1012 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-26 15:20:59.536  6419  6419 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:59.536  1012  1012 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-26 15:20:59.536  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-26 15:20:59.536  1012  1012 V EnterpriseBillingPolicy: uID is 10155
07-26 15:20:59.536  1012  1012 V EnterpriseBillingPolicy: Removed Packageuid is0
07-26 15:20:59.536  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-26 15:20:59.536  3737  6384 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
07-26 15:20:59.536  6419  6419 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:59.546  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,07-26 15:20:59.546  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-26 15:20:59.546  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-26 15:20:59.546  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-26 15:20:59.546  1012  1025 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-26 15:20:59.546  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-26 15:20:59.546  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.546  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.546  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
07-26 15:20:59.546  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-26 15:20:59.546  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.556  1012  1012 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-26 15:20:59.556  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-26 15:20:59.556  1012  1012 V EnterpriseBillingPolicy: uID is 10155
07-26 15:20:59.556  1012  1012 V EnterpriseBillingPolicy: Removed Packageuid is0
07-26 15:20:59.556  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-26 15:20:59.556  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-26 15:20:59.556  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-26 15:20:59.556  1012  2760 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-26 15:20:59.556  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-26 15:20:59.556  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest,
,07-26 15:20:59.556  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-26 15:20:59.556  6020  6435 D Compatibility: onHandleIntent()
07-26 15:20:59.556  6020  6435 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,07-26 15:20:59.566  1012  1012 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1012  tag : ACTIVITY_RESUME_BOOSTER@11
,07-26 15:20:59.586  1012  1012 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,07-26 15:20:59.586  6020  6435 D Compatibility: found: 2
07-26 15:20:59.586  6020  6435 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-26 15:20:59.586  6020  6435 D Compatibility: skipping ResolveInfo{3ca35c2 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-26 15:20:59.586  6020  6435 D Compatibility: considering ResolveInfo{f862fd3 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-26 15:20:59.586  6020  6435 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,07-26 15:20:59.596  1012  1524 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
07-26 15:20:59.596  1012  1524 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.596  6385  6385 D elm:15183: ElmAgentService : onDestroy().
,07-26 15:20:59.596  1012  1524 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.596  1012  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.596  1012  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,07-26 15:20:59.596  3737  3737 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,07-26 15:20:59.596  6020  6435 D Compatibility: enabling receiver ResolveInfo{ee6d710 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-26 15:20:59.606  1012  1132 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,07-26 15:20:59.606  1012  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.606  6020  6435 D Compatibility: enabling receiver ResolveInfo{1430a209 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-26 15:20:59.616  1012  1132 W ActivityManager: userId = 0, bbcId = -10000,
07-26 15:20:59.616  1012  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.616  1012  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-26 15:20:59.626  6020  6435 D Compatibility: enabling receiver ResolveInfo{609ec0e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-26 15:20:59.626  6049  6437 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-26 15:20:59.636  1012  1052 I art     : Explicit concurrent mark sweep GC freed 19300(1674KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 31MB/47MB, paused 5.919ms total 305.684ms,
,07-26 15:20:59.656  5860  5860 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,07-26 15:20:59.656  5860  5860 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,07-26 15:20:59.656  5860  5860 I TapandpayWidget:Utils: Clear T&P info.
,07-26 15:20:59.656  6020  6435 D Compatibility: enabling receiver ResolveInfo{38f9f62f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-26 15:20:59.656  5860  5860 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,07-26 15:20:59.666  6020  6435 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,07-26 15:20:59.676  5843  5843 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-26 15:20:59.676  5843  5843 I PCWCLIENTTRACE_PushUtil: sales region : global
07-26 15:20:59.686  1012  1528 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,07-26 15:20:59.686  1012  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.686  1012  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.686  1012  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.686  1012  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.686  5843  5843 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-26 15:20:59.686  6419  6419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,07-26 15:20:59.686  5843  5843 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-26 15:20:59.696  6440  6440 E Zygote  : MountEmulatedStorage()
07-26 15:20:59.696  6440  6440 E Zygote  : v2
07-26 15:20:59.696  6440  6440 I libpersona: KNOX_SDCARD checking this for 10003
07-26 15:20:59.696  6440  6440 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.696  6440  6440 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-26 15:20:59.706  6440  6440 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-26 15:20:59.706  1012  1528 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6440 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
07-26 15:20:59.706  6440  6440 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:20:59.706  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,07-26 15:20:59.706  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.706  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.706  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.706  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,07-26 15:20:59.726  1012  1025 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6455 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a,
07-26 15:20:59.726  1012  1036 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-26 15:20:59.726  1012  1024 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-26 15:20:59.726  1012  1024 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.736  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.736  1012  1024 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.736  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,07-26 15:20:59.736  6455  6455 E Zygote  : MountEmulatedStorage()
07-26 15:20:59.736  6455  6455 I libpersona: KNOX_SDCARD checking this for 10160
07-26 15:20:59.736  6455  6455 E Zygote  : v2
07-26 15:20:59.736  6455  6455 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.736  6455  6455 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-26 15:20:59.736  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.736  6440  6440 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:20:59.736  6440  6440 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:59.746  6455  6455 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-26 15:20:59.746  6455  6455 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:59.746  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.756  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.786  6440  6440 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-26 15:20:59.806  6455  6455 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:20:59.806  6455  6455 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:59.816  1012  1158 D TaskPersister: removeObsoleteFile: deleting file=66_task.xml
,07-26 15:20:59.816  1012  1158 D TaskPersister: removeObsoleteFile: deleting file=66_task_thumbnail.png
,07-26 15:20:59.816  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-26 15:20:59.816  5466  5466 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,07-26 15:20:59.816  1012  1528 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
07-26 15:20:59.816  1012  1528 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-26 15:20:59.826  1012  1036 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-26 15:20:59.826  1012  1036 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:20:59.826  1012  1036 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-26 15:20:59.826  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.826  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.826  6440  6440 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,07-26 15:20:59.826  6440  6440 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-26 15:20:59.826  6440  6440 D UserAnalysis: Create SecureDbHelper
,07-26 15:20:59.836  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.836  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.846  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.846  6471  6471 E Zygote  : MountEmulatedStorage()
07-26 15:20:59.846  6471  6471 E Zygote  : v2
07-26 15:20:59.846  6471  6471 I libpersona: KNOX_SDCARD checking this for 10035
07-26 15:20:59.846  6471  6471 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.846  6471  6471 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-26 15:20:59.846  6455  6455 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
07-26 15:20:59.846  1012  1025 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6471 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-26 15:20:59.846  1012  1025 I ActivityManager: Killing 5777:com.google.android.partnersetup/u0a15 (adj 15): empty #31
07-26 15:20:59.846  6471  6471 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-26 15:20:59.846  1012  1528 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-26 15:20:59.856  6471  6471 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-26 15:20:59.856  1012  1052 D PackageManager: delete codoeFile: 
,07-26 15:20:59.866  1012  1528 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.866  1012  1528 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.866  1012  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
07-26 15:20:59.866  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.866  1012  1052 I AASA_removePackage: UID=10155 Target=com.test.thalitest
07-26 15:20:59.866  1012  1052 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,07-26 15:20:59.866  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.876  6440  6440 D IntelligenceServiceApplication: onCreate()
,07-26 15:20:59.876  1012  1052 D PackageManager: result of delete: 1{1042399332}
,07-26 15:20:59.876  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:20:59.876  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-26 15:20:59.876  1012  1347 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:20:59.876  6455  6455 D [0]UMC:UMCContentProvider: @onCreate
,07-26 15:20:59.876  1012  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.876  1012  1347 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.876  1012  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.876  1012  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-26 15:20:59.876  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:20:59.876  6440  6440 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,07-26 15:20:59.886  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:20:59.886  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-26 15:20:59.886  6455  6455 D [0]UMC:Core: onCreate(): 
,07-26 15:20:59.886  6455  6455 D [0]UMC:Core: @isManagedProfileUser
07-26 15:20:59.886  6455  6455 D [0]UMC:Core: userId: 0
,07-26 15:20:59.886  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.886  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-26 15:20:59.886  6455  6455 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
07-26 15:20:59.886  6455  6455 D [0]UMC:Core: userInfo.isManagedProfile() : false
,07-26 15:20:59.896  6440  6440 D IntelligenceServiceApplication: no applications having user consent for prediction
,07-26 15:20:59.896  6369  6369 D AndroidRuntime: Shutting down VM
,07-26 15:20:59.906  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:59.906  6471  6471 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:20:59.906  6471  6471 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:59.906  1012  1036 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-26 15:20:59.906  1012  1036 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-26 15:20:59.906  1012  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-26 15:20:59.906  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-26 15:20:59.906  1482  1482 D Launcher.Model: reloadBadges entered.
,07-26 15:20:59.916  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-26 15:20:59.916  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-26 15:20:59.926  1012  1528 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:20:59.926  1012  1528 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.926  5672  5672 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
07-26 15:20:59.926  1012  1528 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.926  1012  1528 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.926  1012  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:59.936  1012  1245 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.936  1012  1245 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:59.936  1012  1245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-26 15:20:59.936  1012  1245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:59.936  6455  6455 D [0]UMC:DeviceInfo: USA==US==
07-26 15:20:59.936  1012  1471 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
07-26 15:20:59.936  1012  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.936  1012  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.936  1012  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.936  1012  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.946  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-26 15:20:59.956  6487  6487 E Zygote  : MountEmulatedStorage(),
07-26 15:20:59.956  6487  6487 I libpersona: KNOX_SDCARD checking this for 1000
07-26 15:20:59.956  6487  6487 E Zygote  : v2
07-26 15:20:59.956  6487  6487 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.956  6487  6487 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-26 15:20:59.956  6487  6487 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
07-26 15:20:59.956  6487  6487 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:59.956  1012  1471 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6487 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,07-26 15:20:59.966  1482  1482 D Launcher.Model: reloadBadges entered.
07-26 15:20:59.966  1012  1524 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:20:59.966  5970  5978 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-26 15:20:59.966  1012  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-26 15:20:59.966  5970  5978 D BadgeProvider: sendNotify, [notify] : null
07-26 15:20:59.966  5970  5978 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-26 15:20:59.966  5970  5978 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-26 15:20:59.966  5970  5978 D BadgeProvider: update, [UpdateCount] : 1
,07-26 15:20:59.976  1012  1524 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.976  1012  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.976  1012  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:59.976   311   311 I art     : Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 22.995ms
,07-26 15:20:59.986  1012  1090 V AlarmManager: waitForAlarm result :8
,07-26 15:20:59.996  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-26 15:20:59.996  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,07-26 15:20:59.996   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 18.648ms
,07-26 15:21:00.006  6487  6487 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:00.006  6487  6487 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:00.006  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-26 15:21:00.006  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,07-26 15:21:00.016   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.580ms
,07-26 15:21:00.016  1012  1525 I ActivityManager: Killing 5812:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,07-26 15:21:00.016  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-26 15:21:00.016  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-26 15:21:00.016  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,07-26 15:21:00.026  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
,07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,07-26 15:21:00.036  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,07-26 15:21:00.066  6440  6440 D BluetoothAdapter: cancelDiscovery
,07-26 15:21:00.076  2653  2949 D BluetoothAdapterProperties: mDiscovering is false
07-26 15:21:00.076  2653  2949 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,07-26 15:21:00.076  6471  6505 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-26 15:21:00.076  6471  6505 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-26 15:21:00.086  6440  6440 D BluetoothAdapter: cancelDiscovery = true
,07-26 15:21:00.086  6440  6440 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,07-26 15:21:00.086  1012  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-26 15:21:00.086  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-26 15:21:00.086  6049  6437 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 463 ms] updated apps [took 463 ms] 
,07-26 15:21:00.086  6074  6074 I SA      : [SUR] onReceive called
07-26 15:21:00.086  6074  6074 I SA      : [SUR] Not SA Package.. finish
,07-26 15:21:00.096  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-26 15:21:00.096  6471  6505 D SPPClientService: PushLog.txt file is not deleted.
07-26 15:21:00.096  6471  6505 D SPPClientService: PushLog.txt file is not deleted.
07-26 15:21:00.096  6471  6505 D SPPClientService: ============PushLog. stop!
,07-26 15:21:00.096  3802  6501 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-26 15:21:00.096  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
07-26 15:21:00.096  1012  1527 I ActivityManager: Killing 5939:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,07-26 15:21:00.096  6440  6440 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-26 15:21:00.096  6455  6455 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,07-26 15:21:00.106  6369  6369 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,07-26 15:21:00.116  1012  1245 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,07-26 15:21:00.116  1012  1245 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0,
,07-26 15:21:00.116  1012  1245 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:21:00.116  6487  6487 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
07-26 15:21:00.116  1012  1245 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-26 15:21:00.116  1012  1245 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
07-26 15:21:00.116  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
07-26 15:21:00.116  6455  6455 D [0]UMC:AdminManager: init - start
,07-26 15:21:00.116  1012  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-26 15:21:00.126  1012  1471 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:21:00.126  1012  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:21:00.126  1012  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:21:00.126  1012  1052 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-26 15:21:00.126  1012  1052 D PackageManager: userId{-1}
07-26 15:21:00.126  1012  1052 D PackageManager: andCode{true}
,07-26 15:21:00.136  1012  1525 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
,07-26 15:21:00.136  1012  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,07-26 15:21:00.136  1012  1525 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:21:00.136  1012  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:21:00.136  1012  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,07-26 15:21:00.146  1012  1956 V SAMP_SPCM_test: CSC File load.. 
,07-26 15:21:00.146  6455  6455 D [0]UMC:AdminManager: loadAdmins
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings,
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,07-26 15:21:00.156  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
07-26 15:21:00.166  6455  6455 D [0]UMC:AdminManager: init - end
07-26 15:21:00.166  6455  6455 D GSLBManager: migrateStoredUrlFromOldPref
,07-26 15:21:00.166  6455  6455 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,07-26 15:21:00.166  6455  6455 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,07-26 15:21:00.176  6455  6455 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,07-26 15:21:00.176  6455  6455 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
07-26 15:21:00.176  6455  6455 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
07-26 15:21:00.176  6455  6455 D [0]UMC:UMCAdmin: isContainer : 0
,07-26 15:21:00.176  1012  1471 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,07-26 15:21:00.176  6455  6455 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
07-26 15:21:00.176  6455  6455 D [0]UMC:UMCAdmin: isContainer : 0
,07-26 15:21:00.186  6455  6455 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
07-26 15:21:00.196  1012  1052 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
07-26 15:21:00.186  1012  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
07-26 15:21:00.216  1012  1477 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
07-26 15:21:00.216  1012  1477 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
07-26 15:21:00.216  1531  1539 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-26 15:21:00.216  1531  1539 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-26 15:21:00.216  1531  1539 E DatabaseUtils: Writing exception to parcel
07-26 15:21:00.216  1531  1539 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850),
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at com.sec.android.provider.logsprovider.LogsProvider.delete(LogsProvider.java:3550)
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
07-26 15:21:00.216  1531  1539 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
07-26 15:21:00.216  1012  1477 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:21:00.216  1012  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:21:00.216  1012  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
07-26 15:21:00.226  1012  1525 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-26 15:21:00.226  1012  1525 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
07-26 15:21:00.226  6455  6455 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
07-26 15:21:00.226  6455  6455 D [0]UMC:CoreReceiver: Intent : android.intent.action.PACKAGE_REMOVED
07-26 15:21:00.226  6455  6455 D [0]UMC:CoreReceiver: PackageName : com.test.thalitest
07-26 15:21:00.226  6455  6455 D [0]UMC:CoreReceiver: Intent Replacing : false
07-26 15:21:00.226  1012  1525 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:21:00.226  1012  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:21:00.226  1012  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
07-26 15:21:00.226  1694  6507 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-26 15:21:00.226  1694  6507 E AndroidRuntime: Process: android.process.acore, PID: 1694
07-26 15:21:00.226  1694  6507 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:543)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:476)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:00.226  1694  6507 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-26 15:21:00.236  6455  6455 D [0]UMC:CoreReceiver: bulk enrolled package: null
07-26 15:21:00.236  1012  1528 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
07-26 15:21:00.236  6455  6455 V [0]UMC:ProfileStorage: Enter loadList
07-26 15:21:00.236  1012  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:00.236  1012  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:00.236  1012  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:00.236  1012  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:00.236  6455  6455 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
07-26 15:21:00.236  6455  6455 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
07-26 15:21:00.246  6455  6455 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
07-26 15:21:00.246  6455  6455 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
07-26 15:21:00.246  6455  6455 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
07-26 15:21:00.246  6455  6455 D [0]UMC:UMCAdmin: isContainer : 0
07-26 15:21:00.246  1012  1478 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
07-26 15:21:00.246  6455  6455 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
07-26 15:21:00.246  6455  6455 D [0]UMC:UMCAdmin: isContainer : 0
07-26 15:21:00.256  6455  6455 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
07-26 15:21:00.256  6455  6455 D [0]UMC:GuardService: @GuardService oncreate()
07-26 15:21:00.256  6455  6455 D [0]UMC:GuardService: @GuardService onStartCommand()
,07-26 15:21:00.256  6514  6514 E Zygote  : MountEmulatedStorage()
07-26 15:21:00.256  6514  6514 I libpersona: KNOX_SDCARD checking this for 1000
07-26 15:21:00.256  6514  6514 E Zygote  : v2
07-26 15:21:00.256  6514  6514 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:00.256  6514  6514 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-26 15:21:00.256  1012  1528 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6514 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,07-26 15:21:00.256  6514  6514 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-26 15:21:00.266  6514  6514 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:21:00.266  1012  1956 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,07-26 15:21:00.266  1012  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname android.process.acore
,07-26 15:21:00.266  1012  1527 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:21:00.266  1012  1527 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
07-26 15:21:00.266  1012  1527 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:21:00.266  1012  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:21:00.266  1012  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:21:00.286  1012  1528 I ActivityManager: Killing 5986:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,07-26 15:21:00.286  1012  6525 E DropBoxManagerService: Can't write: system_app_crash
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop177.tmp: open failed: EROFS (Read-only file system)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-26 15:21:00.286  1012  6525 E DropBoxManagerService: 	... 5 more
,07-26 15:21:00.296  6514  6514 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-26 15:21:00.296  6514  6514 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:00.306  1012  1037 D PhoneWindow: *FMB* installDecor mIsFloating : true,
07-26 15:21:00.306  1012  1037 D PhoneWindow: *FMB* installDecor flags : 8519682
,07-26 15:21:00.306  1012  6530 E android.os.Debug: ro.product_ship = true
07-26 15:21:00.306  1012  6530 E android.os.Debug: ro.debug_level = 0x4f4c

```
