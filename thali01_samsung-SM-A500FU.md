#### Test 75789268eab05ed_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
07-05 11:07:58.080  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:07:58.080  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:07:58.080  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
--------- beginning of system
07-05 11:07:58.080  1014  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-05 11:07:58.120  1014  1209 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:07:58.120  1014  1209 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:07:58.120  1014  1209 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 11:07:58.120  1014  1209 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:07:58.120  1014  1209 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
07-05 11:07:58.140  6157  6191 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 213 ms] updated apps [took 212 ms] 
07-05 11:07:58.140  1014  2956 I ActivityManager: Killing 5218:com.google.android.gm/u0a101 (adj 15): empty #31
07-05 11:07:58.200  1014  1039 W libprocessgroup: failed to kill pid 5218: No such process
07-05 11:07:58.290  2088  3544 I Icing   : Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
07-05 11:07:58.380  2088  3544 I Icing   : Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
07-05 11:07:58.380  1014  1093 V AlarmManager: waitForAlarm result :4
07-05 11:07:58.600   287   287 E SMD     : DCD OFF
,07-05 11:07:59.130  2088  3544 I Icing   : Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
07-05 11:07:59.160  5868  5868 I Mms/MmsApp:  start initViewCache mms
07-05 11:07:59.160  5868  5868 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1904.842395
07-05 11:07:59.160  5868  5868 D Mms/ComposeMessageFragment: fillCache, easy = false
07-05 11:07:59.220  2088  3544 I Icing   : Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
07-05 11:07:59.240  1014  2956 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-05 11:07:59.240  1014  2956 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:07:59.240  1014  2956 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:07:59.240  1014  2956 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 11:07:59.250  5868  5868 D AbsListView: Get MotionRecognitionManager
07-05 11:07:59.250  1014  1676 D MotionRecognitionService:  ssp status : false
07-05 11:07:59.260  5868  5868 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 101.362344
07-05 11:07:59.290  5868  5883 W art     : Suspending all threads took: 7.490ms
07-05 11:07:59.330  6210  6210 D AndroidRuntime: 
07-05 11:07:59.330  6210  6210 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 11:07:59.340  6210  6210 D AndroidRuntime: CheckJNI is OFF
07-05 11:07:59.340  6210  6210 D AndroidRuntime: readGMSProperty: start
07-05 11:07:59.340  6210  6210 D AndroidRuntime: readGMSProperty: already setted!!
07-05 11:07:59.340  6210  6210 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 11:07:59.340  6210  6210 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 11:07:59.340  6210  6210 D AndroidRuntime: readGMSProperty: end
07-05 11:07:59.340  6210  6210 D AndroidRuntime: addProductProperty: start
07-05 11:07:59.350  5868  5868 D Mms/BubbleViewCache: fillCache bubble = 1
07-05 11:07:59.460  6210  6210 E AffinityControl: AffinityControl: registerfunction enter
07-05 11:07:59.490  6210  6210 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 11:07:59.500  1014  1027 E PersonaManagerService: inState():  stateMachine is null !!
07-05 11:07:59.500  1014  1027 I PersonaManagerService: PersonaId don't exist
07-05 11:07:59.500  1014  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 11:07:59.500  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 11:07:59.520  1014  1027 W ActivityManager: mDVFSHelper.acquire()
07-05 11:07:59.520  1014  1027 D FocusedStackFrame: Set to : 0
07-05 11:07:59.520  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-05 11:07:59.520  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-05 11:07:59.530  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:07:59.530  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:07:59.530  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:07:59.530  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:07:59.540  6222  6222 E Zygote  : MountEmulatedStorage()
07-05 11:07:59.540  6222  6222 E Zygote  : v2
07-05 11:07:59.540  6222  6222 I libpersona: KNOX_SDCARD checking this for 10155
07-05 11:07:59.540  6222  6222 I libpersona: KNOX_SDCARD not a persona
07-05 11:07:59.540  6222  6222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 11:07:59.540  1014  1027 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6222 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 11:07:59.540  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-05 11:07:59.540  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 11:07:59.540  1014  1027 D InputDispatcher: Focused application set to: xxxx
07-05 11:07:59.540  1014  1027 D InputDispatcher: Focus left window: 1477
07-05 11:07:59.550  6210  6210 D AndroidRuntime: Shutting down VM
07-05 11:07:59.550  6222  6222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 11:07:59.550  6222  6222 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 11:07:59.550  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-05 11:07:59.550  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-05 11:07:59.550   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-05 11:07:59.560  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 11:07:59.560  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 11:07:59.570  6222  6222 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 11:07:59.570  6222  6222 D ActivityThread: Added TimaKeyStore provider
07-05 11:07:59.570  1014  2958 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-05 11:07:59.580  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 11:07:59.590  1014  2958 D PersonaManager: isKioskContainerExistOnDevice
07-05 11:07:59.640   257  1036 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-05 11:07:59.640   257   439 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-05 11:07:59.640  1477  1477 V ActivityThread: updateVisibility : ActivityRecord{29aaec46 token=android.os.BinderProxy@1f96e849 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 11:07:59.640  1477  1477 D Launcher: onTrimMemory. Level: 20
07-05 11:07:59.700  6222  6222 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 11:07:59.720  6222  6222 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2938-2940)
07-05 11:07:59.720  6222  6222 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 11:07:59.730  6222  6222 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8a9b43f}
07-05 11:07:59.740  6222  6222 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 11:07:59.740  6222  6222 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 11:07:59.750  6210  6210 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-05 11:07:59.770  6222  6222 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 11:07:59.770  6222  6222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:07:59.770  6222  6222 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 11:07:59.790  6222  6222 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-05 11:07:59.800  6222  6222 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-05 11:07:59.800  6222  6222 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-05 11:07:59.800  6222  6222 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-05 11:07:59.800  6222  6222 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 11:07:59.800  6222  6222 I Adreno-EGL: Build Date: 04/06/15 Mon
07-05 11:07:59.800  6222  6222 I Adreno-EGL: Local Branch: 
07-05 11:07:59.800  6222  6222 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-05 11:07:59.800  6222  6222 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-05 11:07:59.800  6222  6222 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
07-05 11:07:59.920  6222  6248 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-05 11:07:59.970  6222  6222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:07:59.980  6222  6222 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 11:07:59.990  6222  6222 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-05 11:07:59.990  6222  6222 D PhoneWindow: *FMB* installDecor flags : -2139027200
07-05 11:07:59.990  1014  1093 V AlarmManager: waitForAlarm result :8
07-05 11:08:00.000  6222  6222 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-05 11:08:00.000  6222  6222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:00.000  6222  6222 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 11:08:00.040  6222  6261 D OpenGLRenderer: Render dirty regions requested: true
07-05 11:08:00.050  1014  2957 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 11:08:00.050  1014  2957 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 11:08:00.050  1014  2957 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 11:08:00.050  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 11:08:00.050  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 11:08:00.060  6222  6222 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-05 11:08:00.060  6222  6222 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-05 11:08:00.070   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
07-05 11:08:00.080  1014  1027 D InputDispatcher: Focus entered window: 6222
07-05 11:08:00.080  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 11:08:00.080  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 11:08:00.080  6222  6222 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-05 11:08:00.080  6222  6261 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 11:08:00.090  6222  6261 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-05 11:08:00.090  6222  6261 D OpenGLRenderer: Enabling debug mode 0
07-05 11:08:00.140  6222  6222 V ActivityThread: updateVisibility : ActivityRecord{2c9f77e6 token=android.os.BinderProxy@2d2f1928 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 11:08:00.160  1014  1232 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-05 11:08:00.160  1176  1176 I StatusBar: Icon Only
07-05 11:08:00.160  1176  1176 D PanelView: There is/are notification(s) 
07-05 11:08:00.170  1014  6264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 11:08:00.170  6222  6222 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-05 11:08:00.170  6222  6222 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d2f1928 time:123397
07-05 11:08:00.170  1784  1784 I SamsungIME: getCurrentCandidateView
07-05 11:08:00.180  1014  1045 I ActivityManager: Displayed Component not be shown by security: +583ms (total +8s455ms)
07-05 11:08:00.180  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{28dd0ff0 u0 com.test.thalitest/.MainActivity t24} time:123400
07-05 11:08:00.180  1014  1045 W ActivityManager: mDVFSHelper.release()
07-05 11:08:00.180   257   436 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
07-05 11:08:00.180   257   439 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
07-05 11:08:00.230  6222  6222 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6222
07-05 11:08:00.280  1784  1784 D SamsungIME: Dismiss ExpandCandiate
07-05 11:08:00.380  6222  6222 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-05 11:08:00.410  1784  1784 I SamsungIME: getDebugLevel  : 0x4f4c
07-05 11:08:00.440  6222  6222 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-05 11:08:00.450  1784  1784 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 11:08:00.460  1784  1784 I SamsungIME: KeybaordView init() : load resources
,07-05 11:08:00.480  6222  6265 D jxcore_app_log: JniHelper::setJavaVM(0xb8b6f328), pthread_self() = -1190313616
,07-05 11:08:00.490  1784  1784 I SamsungIME: getCurrentKeyboard
07-05 11:08:00.490  1784  1784 I SamsungIME: getTextKeyboard
,07-05 11:08:00.490  6222  6265 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 11:08:00.490  6222  6265 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 11:08:00.490  6222  6265 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 11:08:00.490  6222  6265 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 11:08:00.490  6222  6265 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 11:08:00.490  6222  6265 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22aba696 added. We now have 1 listener(s)
,07-05 11:08:00.500  6222  6265 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,07-05 11:08:00.500  6222  6265 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,07-05 11:08:00.500  6222  6265 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 11:08:00.500  6222  6265 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 11:08:00.500  1784  1784 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff517ed added. We now have 1 listener(s)
,07-05 11:08:00.510  6222  6265 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 11:08:00.510  6222  6265 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-05 11:08:00.510  6222  6265 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 11:08:00.510  6222  6265 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 11:08:00.510  6222  6265 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-05 11:08:00.510  6222  6265 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 11:08:00.520  6222  6265 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 11:08:00.520  6222  6265 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,07-05 11:08:00.530  6222  6265 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 11:08:00.530  6222  6265 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 11:08:00.530  6222  6265 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 11:08:00.530  6222  6265 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 11:08:00.530  6222  6265 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 11:08:00.530  6222  6265 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 11:08:00.530  6222  6265 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 11:08:00.530  6222  6265 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 11:08:00.530  6222  6265 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 11:08:00.530  6222  6265 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 11:08:00.530  6222  6265 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 11:08:00.530  6222  6222 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 11:08:00.530  6222  6222 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 11:08:00.550  6222  6222 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 11:08:00.590   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:08:00.980  1784  6270 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-05 11:08:01.090  6222  6274 W jxcore-log: Initializing JXcore engine,
07-05 11:08:01.090  6222  6274 W jxcore-log: JXcore engine is ready
,07-05 11:08:01.140  1911  1911 E audit   : type=1400 msg=audit(1467709681.140:205): avc:  denied  { ioctl } for  pid=6274 comm="Thread-1083" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 11:08:01.140  1911  1911 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
07-05 11:08:01.140  1911  1911 E audit   : type=1300 msg=audit(1467709681.140:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ea008f8 items=0 ppid=303 ppcomm=main pid=6274 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1083" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-05 11:08:01.140  1911  1911 E audit   : type=1320 msg=audit(1467709681.140:205): 
,07-05 11:08:01.160  6222  6274 W jxcore-log: Starting JXcore engine
,07-05 11:08:01.260  6222  6274 W jxcore-log: Platform android
07-05 11:08:01.260  6222  6274 W jxcore-log: 
07-05 11:08:01.260  6222  6274 W jxcore-log: Process ARCH arm
07-05 11:08:01.260  6222  6274 W jxcore-log: 
,07-05 11:08:01.460  6222  6274 I jxcore-log: JXcore Cordova bridge is ready!
07-05 11:08:01.460  6222  6274 I jxcore-log: 
,07-05 11:08:01.460  6222  6274 W jxcore-log: JXcore engine is started
,07-05 11:08:01.590   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:01.600   287   287 E SMD     : DCD OFF,
,07-05 11:08:02.590   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:08:03.140  1014  2957 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:08:03.140  1014  2957 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-05 11:08:03.140  1014  2957 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:08:03.140  1014  2957 D BatteryService: stay LED for fully charged
07-05 11:08:03.140  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:08:03.140  1014  1014 I MotionRecognitionService: Plugged
07-05 11:08:03.140  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 11:08:03.150  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:08:03.150  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:08:03.150  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
07-05 11:08:03.150  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,07-05 11:08:03.150  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:03.160  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:03.160  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:08:03.160  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:08:03.170  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:03.590   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:03.780  1014  2951 I ActivityManager: Killing 5338:com.dropbox.android/u0a92 (adj 15): empty #31
,07-05 11:08:04.590   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:04.600   287   287 E SMD     : DCD OFF
,07-05 11:08:05.590   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 11:08:05.960  1014  1047 I PowerManagerService: [PWL] Off : 50s ago
,07-05 11:08:06.070  1014  2746 D SSRM:n  : SIOP:: AP = 340
,07-05 11:08:07.550  1014  1055 D PackageManager: [MSG] MCS_UNBIND,
,07-05 11:08:07.550  1014  1476 I ActivityManager: Killing 5303:com.google.android.talk/u0a104 (adj 15): empty #31
,07-05 11:08:07.600   287   287 E SMD     : DCD OFF
,07-05 11:08:09.540  1014  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 11:08:10.610   287   287 E SMD     : DCD OFF
,07-05 11:08:11.600  1014  1093 V AlarmManager: waitForAlarm result :4
,07-05 11:08:11.620  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,07-05 11:08:11.630  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,07-05 11:08:11.640  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,07-05 11:08:11.640  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
07-05 11:08:11.640  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,07-05 11:08:11.640  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 11:08:11.640  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:08:11.650  5554  5590 I Finsky  : [951] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-05 11:08:11.670  1945  1945 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,07-05 11:08:11.670  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 11:08:11.680  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 11:08:11.700  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:08:11.700  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 11:08:11.700  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:08:11.700  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 11:08:11.700  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,07-05 11:08:11.710  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
07-05 11:08:11.710  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:11.710  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:11.740  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:08:11.740  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:08:11.740  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,07-05 11:08:11.760  1014  1040 I ActivityManager: Waited long enough for: ServiceRecord{3cb36873 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,07-05 11:08:11.770  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:08:11.820  1014  1540 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 11:08:11.830  1014  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,07-05 11:08:11.830  1014  1540 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:11.830  1014  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:11.830  1014  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:11.840  1014  2957 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,07-05 11:08:11.840  1014  2957 D ActivityManager: com.google.android.gms, Starting
07-05 11:08:11.840  1014  2957 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,07-05 11:08:11.870  1014  1540 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 11:08:11.870  1014  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,07-05 11:08:11.870  1014  1540 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:11.870  1014  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:11.870  1014  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:11.900  2088  6283 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-05 11:08:11.900  2088  6283 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-05 11:08:11.910  1945  1945 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:08:11.940  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:11.940  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-05 11:08:11.940  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.050  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 11:08:12.050  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,07-05 11:08:12.050  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:12.050  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.050  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.080  5554  5590 I Finsky  : [951] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-05 11:08:12.080  5554  5554 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-05 11:08:12.090  1014  3206 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 11:08:12.090  1014  3206 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,07-05 11:08:12.090  1014  3206 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:12.090  1014  3206 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.090  1014  3206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.130  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:12.130  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:12.130  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.130  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.140  1014  2958 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:12.150  1014  2958 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:12.150  1014  2958 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.150  1014  2958 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.180  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:12.190  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:12.190  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.190  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.190  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 11:08:12.190  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:08:12.190  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:08:12.190  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 11:08:12.200  6287  6287 E Zygote  : MountEmulatedStorage()
07-05 11:08:12.200  6287  6287 I libpersona: KNOX_SDCARD checking this for 10012
07-05 11:08:12.200  6287  6287 E Zygote  : v2
07-05 11:08:12.200  6287  6287 I libpersona: KNOX_SDCARD not a persona
,07-05 11:08:12.210  6287  6287 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-05 11:08:12.210  1014  1026 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6287 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,07-05 11:08:12.210  6287  6287 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-05 11:08:12.210  6287  6287 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-05 11:08:12.250  6287  6287 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 11:08:12.250  6287  6287 D ActivityThread: Added TimaKeyStore provider
,07-05 11:08:12.260  6287  6287 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 11:08:12.260  6287  6287 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 11:08:12.310  6287  6287 I MultiDex: VM with version 2.1.0 has multidex support
07-05 11:08:12.310  6287  6287 I MultiDex: install
07-05 11:08:12.310  6287  6287 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 11:08:12.350  6287  6287 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 11:08:12.410  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,07-05 11:08:12.410  6287  6287 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-05 11:08:12.410  6287  6287 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@140e4b88: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 11:08:12.410  6287  6287 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 11:08:12.410  1014  3206 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:12.420  1014  3206 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:12.420  1014  3206 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.420  1014  3206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.430  1014  2958 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:12.430  1014  2958 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:12.430  1014  2958 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.430  1014  2958 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.440  6287  6287 D ChimeraCfgMgr: Reading stored module config
,07-05 11:08:12.470  1945  1945 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=2548d646-ba53-4124-a0a3-79b99d65e7ae
,07-05 11:08:12.480  1014  2958 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-05 11:08:12.480  1014  2958 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,07-05 11:08:12.480  1014  2958 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:08:12.480  1014  2958 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.480  1014  2958 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.490  1945  1945 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:08:12.490  1945  1945 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:08:12.510  1014  1540 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-05 11:08:12.510  1014  1540 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:08:12.510  1014  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.510  1014  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 11:08:12.520  6287  6306 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 11:08:12.540  6287  6287 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-05 11:08:12.540  6287  6287 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-05 11:08:12.610   282   282 D WVCdm   : Instantiating CDM.
,07-05 11:08:12.620   282   788 I WVCdm   : CdmEngine::OpenSession
07-05 11:08:12.620   282   788 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,07-05 11:08:12.640   282   788 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 11:08:12.640  1945  2116 W GCoreFlp: No location to return for getLastLocation()
,07-05 11:08:12.670   282   788 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
07-05 11:08:12.670   282   788 D DrmWidevineDash: Service_Initialize: starts!
07-05 11:08:12.670   282   788 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,07-05 11:08:12.670   282   788 D QSEECOMAPI: : App is not loaded in QSEE
07-05 11:08:12.670   282   788 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
07-05 11:08:12.670   282   788 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-05 11:08:12.670   282   788 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 11:08:12.670   282   788 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 11:08:12.670   282   788 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
07-05 11:08:12.670   282   788 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-05 11:08:12.670   282   788 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 11:08:12.670   282   788 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 11:08:12.700  2088  6284 D UdcContextInitService: registered all accounts: true
,07-05 11:08:12.700   282   788 D QSEECOMAPI: : Loaded image: APP id = 11
,07-05 11:08:12.700   282   788 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-05 11:08:12.710   282   788 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
07-05 11:08:12.710   282   788 D QSAPPSVER: qsapps_get_capabilities: returns 0
07-05 11:08:12.710   282   788 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1707000
07-05 11:08:12.710   282   788 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1707000
07-05 11:08:12.710   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:08:12.710  1945  2122 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 11:08:12.710   427   435 D DrmLibTime: got the req here! ret=0
07-05 11:08:12.710   427   435 D DrmLibTime: command id, time_cmd_id = 770
07-05 11:08:12.710   427   435 D DrmLibTime: time_getutcsec starts!
07-05 11:08:12.710   427   435 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-05 11:08:12.710   427   435 D DrmLibTime: QSEE Time Listener: get_utc_seconds
07-05 11:08:12.710   427   435 D DrmLibTime: QSEE Time Listener: time_get_modem_time
07-05 11:08:12.710   427   435 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
07-05 11:08:12.720   427   435 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
07-05 11:08:12.720   427   435 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
07-05 11:08:12.720   427   435 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
,07-05 11:08:12.720  6287  6296 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
07-05 11:08:12.720  6287  6296 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 11:08:12.720  6287  6296 I System.out: (HTTPLog)-Static: isShipBuild true
07-05 11:08:12.720  6287  6296 I System.out: (HTTPLog)-Thread-1063-46072618: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
07-05 11:08:12.720  6287  6296 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 11:08:12.720   427   435 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-05 11:08:12.720   317   556 D QC-time-services: Daemon: Connection accepted:time_genoff
,07-05 11:08:12.720   317  6313 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
07-05 11:08:12.720   317  6313 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
07-05 11:08:12.720   317  6313 D QC-time-services: offset is: 0 for base: 0
07-05 11:08:12.720   317   556 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-05 11:08:12.720   427   435 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
07-05 11:08:12.720   427   435 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
07-05 11:08:12.720   427   435 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1467709692
07-05 11:08:12.720   427   435 D DrmLibTime: time_getutcsec returns 0, sec = 1467709692; nsec = 0
07-05 11:08:12.720   427   435 D DrmLibTime: time_getutcsec finished! 
07-05 11:08:12.720   427   435 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-05 11:08:12.720   427   435 D DrmLibTime: before calling ioctl to read the next time_cmd
,07-05 11:08:12.720   277   964 D EnterpriseController: uids 10012
07-05 11:08:12.720   277   964 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
07-05 11:08:12.720   277   964 D Netd    : getNetworkForDns: using netid 502 for uid 10012
07-05 11:08:12.720   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 11:08:12.730  6287  6296 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-05 11:08:12.730   282   788 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-05 11:08:12.730   282   788 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 11:08:12.730   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:08:12.730   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.730   282   788 D DrmWidevineDash: hlos api version =  9
07-05 11:08:12.730   282   788 D DrmWidevineDash: tz api version =  9
07-05 11:08:12.730   282   788 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 11:08:12.730   282   788 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
07-05 11:08:12.730   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:08:12.730  1945  2132 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-05 11:08:12.730  6287  6296 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6287, getuid(): 10012
,07-05 11:08:12.740  1945  2116 I art     : Explicit concurrent mark sweep GC freed 61078(3MB) AllocSpace objects, 7(352KB) LOS objects, 39% free, 14MB/24MB, paused 1.848ms total 83.384ms
,07-05 11:08:12.750   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 11:08:12.750   282   788 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 11:08:12.750   282   788 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 11:08:12.750   282   788 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1929960
07-05 11:08:12.750   282   788 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
07-05 11:08:12.750   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:08:12.750   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.750   282   788 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 11:08:12.750   282   788 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 11:08:12.750   282   788 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb809e078, dataLength=8
07-05 11:08:12.750   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:08:12.750   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.750   282   788 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 11:08:12.750   282   788 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb802a620, wrapped_rsa_key_length=1280
07-05 11:08:12.750   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:08:12.760   282   788 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.760   282   788 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 11:08:12.760   282   788 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 11:08:12.760   282   282 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 11:08:12.760   282   282 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-05 11:08:12.760   282   282 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 11:08:12.760   282   282 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8037550, idLength=0xbec91f80
07-05 11:08:12.760   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:08:12.770  1014  1232 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:12.770  1014  1232 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:12.770  1014  1232 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,07-05 11:08:12.770  1014  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.780  1014  1209 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:12.780  1014  1209 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:08:12.780  1014  1209 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.780  1014  1209 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:12.780  1014  1232 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:08:12.790  1014  1232 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:08:12.790  1014  1232 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:12.790  1014  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xbec91f96, maximum = 0xbec91f97
07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.790   282   282 D DrmWidevineDash: hlos api version =  9
07-05 11:08:12.790   282   282 D DrmWidevineDash: tz api version =  9
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xbec92004
07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 11:08:12.790   282   282 D WVCdm   : PrepareKeyRequest: nonce=919294882
07-05 11:08:12.790   282   282 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8037b58
07-05 11:08:12.790   282   282 D DrmWidevineDash: message_length=1599, signature=0xb8063668, signature_length=0xbec91f64
07-05 11:08:12.790   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:08:12.940   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.940   282   282 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 11:08:12.940   282   789 I WVCdm   : CdmEngine::CloseSession
,07-05 11:08:12.940   282   789 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,07-05 11:08:12.940   282   789 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:08:12.940   282   789 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.940   282   789 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 11:08:12.940   282   789 I WVCdm   : L3 Terminate.
07-05 11:08:12.940   282   789 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-05 11:08:12.940   282   789 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 11:08:12.940   282   789 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 11:08:12.940   282   789 D DrmWidevineDash: Service_Uninitialize: starts!
07-05 11:08:12.940   282   789 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 11:08:12.940   282   789 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,07-05 11:08:12.940   282   789 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,07-05 11:08:12.940   282   789 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 11:08:12.980  6287  6296 I qtaguid : Untagging socket 33
,07-05 11:08:13.020  1014  1323 I art     : Explicit concurrent mark sweep GC freed 25404(1305KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 28MB/42MB, paused 2.458ms total 140.276ms
,07-05 11:08:13.060  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-05 11:08:13.060  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,07-05 11:08:13.060  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:13.060  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:13.060  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:13.200  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:08:13.200  1014  1209 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,07-05 11:08:13.210  1014  1209 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:08:13.210  1014  1209 D BatteryService: stay LED for fully charged
,07-05 11:08:13.210  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:08:13.210  1014  1014 I MotionRecognitionService: Plugged
,07-05 11:08:13.210  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 11:08:13.210  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:08:13.210  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:08:13.210  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 11:08:13.210  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:08:13.230  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:08:13.230  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:08:13.240  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:13.240  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:13.240  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:13.300  6318  6318 I dex2oat : ----------------------------------------------------
07-05 11:08:13.300  6318  6318 I dex2oat : <SS>: S T A R T I N G . . .
07-05 11:08:13.300  6318  6318 I dex2oat : <SS>: Zip is absent. Canceled.
,07-05 11:08:13.300  6318  6318 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-05 11:08:13.330  6318  6318 I dex2oat : dex2oat took 23.620ms (threads: 4)
,07-05 11:08:13.340  6287  6296 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-05 11:08:13.340  6287  6296 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 11:08:13.340  6287  6296 I Adreno-EGL: Build Date: 04/06/15 Mon
07-05 11:08:13.340  6287  6296 I Adreno-EGL: Local Branch: 
07-05 11:08:13.340  6287  6296 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-05 11:08:13.340  6287  6296 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-05 11:08:13.340  6287  6296 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-05 11:08:13.430  6287  6296 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-05 11:08:13.430  6287  6296 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 11:08:13.430  6287  6296 I Adreno-EGL: Build Date: 04/06/15 Mon
07-05 11:08:13.430  6287  6296 I Adreno-EGL: Local Branch: 
07-05 11:08:13.430  6287  6296 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-05 11:08:13.430  6287  6296 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-05 11:08:13.430  6287  6296 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-05 11:08:13.610   287   287 E SMD     : DCD OFF
,07-05 11:08:13.630  6287  6296 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-05 11:08:13.630  6287  6296 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 11:08:13.630  6287  6296 I Adreno-EGL: Build Date: 04/06/15 Mon
07-05 11:08:13.630  6287  6296 I Adreno-EGL: Local Branch: 
07-05 11:08:13.630  6287  6296 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-05 11:08:13.630  6287  6296 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-05 11:08:13.630  6287  6296 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-05 11:08:13.740  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-05 11:08:13.740  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,07-05 11:08:13.740  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:08:13.740  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:13.740  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:13.750  1945  6285 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 11:08:13.750   277   964 D EnterpriseController: uids 10012
07-05 11:08:13.750   277   964 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
07-05 11:08:13.750   277   964 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,07-05 11:08:13.760  1945  6285 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-05 11:08:13.760  1945  6285 I qtaguid : Tagging socket 66 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1945, getuid(): 10012
,07-05 11:08:13.810  1945  6285 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1945, getuid(): 10012
,07-05 11:08:14.010  1945  2132 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-07-05 11:08:12.825+0200, stopTime=2016-07-05 11:08:14.010+0200, duration=1185ms
,07-05 11:08:14.010  1945  5307 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 11:08:14.010  1945  5307 I qtaguid : Tagging socket 60 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1945, getuid(): 10012
,07-05 11:08:14.070  1014  1209 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,07-05 11:08:14.080  2088  3544 V UdcCtxListenerSrv: handle intent
,07-05 11:08:14.110  1650  1667 I art     : Explicit concurrent mark sweep GC freed 1709(61KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 809us total 30.312ms
,07-05 11:08:14.150  1945  5307 I qtaguid : Untagging socket 60
,07-05 11:08:14.180  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:08:14.190  1014  2951 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 11:08:14.190  1014  2951 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,07-05 11:08:14.190  1014  2951 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:14.190  1014  2951 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-05 11:08:14.190  1014  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:14.230  1945  2132 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-05 11:08:14.290  1014  3206 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:14.300  1014  3206 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:14.300  1014  3206 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:14.300  1014  3206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:14.320  1014  1324 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:14.330  1014  1324 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:14.330  1014  1324 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-05 11:08:14.330  1014  1324 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:14.370  1014  1676 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:14.370  1014  1676 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:14.370  1014  1676 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:14.370  1014  1676 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:14.370  1945  6330 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 11:08:14.370  1945  6328 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 11:08:14.370  1014  1678 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:14.370  1014  1678 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:14.370  1014  1678 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:14.370  1014  1678 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:14.400  1014  2958 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:14.400  1014  2958 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:14.400  1014  2958 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-05 11:08:14.400  1014  2958 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:14.400  1945  6330 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 11:08:14.400  1945  6328 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 11:08:14.400  1014  1209 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:14.400  1014  1209 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:14.400  1014  1209 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:14.400  1014  1209 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:14.430  1014  2951 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:08:14.430  1014  2951 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:08:14.430  1014  2951 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:08:14.430  1014  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:08:14.430  1945  6330 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 11:08:14.430  1945  6328 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 11:08:14.430  1945  6328 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-05 11:08:14.450  1945  6328 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 11:08:14.500  1014  2958 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 11:08:14.530  1945  6328 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 11:08:14.530   277   964 D EnterpriseController: uids 10012
07-05 11:08:14.530   277   964 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
07-05 11:08:14.530   277   964 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,07-05 11:08:14.530  1945  6328 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-05 11:08:14.530  1945  6328 I qtaguid : Tagging socket 78 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1945, getuid(): 10012
,07-05 11:08:14.580  1945  6328 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1945, getuid(): 10012
,07-05 11:08:14.820  1014  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 11:08:14.830  1945  6328 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 11:08:14.830  1945  6328 I qtaguid : Tagging socket 78 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1945, getuid(): 10012
,07-05 11:08:14.960  1014  3206 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 11:08:14.970  1945  6328 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 11:08:14.970  1945  6328 I qtaguid : Tagging socket 78 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1945, getuid(): 10012
,07-05 11:08:15.050  1014  1335 E Watchdog: !@Sync 4
,07-05 11:08:15.110  1014  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 11:08:15.140  1945  6328 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 11:08:15.140  1945  6328 I qtaguid : Tagging socket 78 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1945, getuid(): 10012
,07-05 11:08:15.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:08:16.100  1014  2746 D SSRM:n  : SIOP:: AP = 330
,07-05 11:08:16.140  1945  5308 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 11:08:16.140  1945  5308 I qtaguid : Tagging socket 60 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1945, getuid(): 10012
,07-05 11:08:16.300  1945  5308 I qtaguid : Untagging socket 60
,07-05 11:08:16.300  1945  2132 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-05 11:08:16.330  1014  1676 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,07-05 11:08:16.340  2088  3544 V UdcCtxListenerSrv: handle intent
,07-05 11:08:16.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:08:16.610   287   287 E SMD     : DCD OFF
,07-05 11:08:17.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:08:18.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:18.740  1014  1678 I ActivityManager: Killing 5694:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,07-05 11:08:19.360  1014  2002 V SAMP_SPCM_test: CSC File load.. 
,07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
07-05 11:08:19.370  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering,
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
,07-05 11:08:19.400  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm,
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
,07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
07-05 11:08:19.410  1014  2002 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,07-05 11:08:19.430  1014  2002 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,07-05 11:08:19.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:19.610   287   287 E SMD     : DCD OFF
,07-05 11:08:20.600   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,07-05 11:08:22.610   287   287 E SMD     : DCD OFF
,07-05 11:08:23.280  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:08:25.610   287   287 E SMD     : DCD OFF
,07-05 11:08:26.140  1014  2746 D SSRM:n  : SIOP:: AP = 320
,07-05 11:08:28.610   287   287 E SMD     : DCD OFF,
,07-05 11:08:30.980  1014  1047 I PowerManagerService: [PWL] Off : 75s ago
,07-05 11:08:31.620   287   287 E SMD     : DCD OFF
,07-05 11:08:33.350  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:08:34.180  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:08:34.620   287   287 E SMD     : DCD OFF,
,07-05 11:08:35.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:36.170  1014  2746 D SSRM:n  : SIOP:: AP = 310
,07-05 11:08:36.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:08:37.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:08:37.620   287   287 E SMD     : DCD OFF
,07-05 11:08:38.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:08:39.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:08:40.600   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,07-05 11:08:40.620   287   287 E SMD     : DCD OFF
,07-05 11:08:43.430  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:08:43.620   287   287 E SMD     : DCD OFF,
,07-05 11:08:45.050  1014  1335 E Watchdog: !@Sync 5
,07-05 11:08:45.820  1945  2576 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 11:08:46.210  1014  2746 D SSRM:n  : SIOP:: AP = 300
,07-05 11:08:46.620   287   287 E SMD     : DCD OFF
,07-05 11:08:49.620   287   287 E SMD     : DCD OFF
,07-05 11:08:52.620   287   287 E SMD     : DCD OFF,
,07-05 11:08:53.510  1014  2951 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:08:53.510  1014  2951 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-05 11:08:53.510  1014  2951 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:08:53.510  1014  2951 D BatteryService: stay LED for fully charged
07-05 11:08:53.510  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:08:53.510  1014  1014 I MotionRecognitionService: Plugged,
07-05 11:08:53.510  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 11:08:53.510  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
07-05 11:08:53.510  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:08:53.520  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 11:08:53.520  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:08:53.530  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:08:53.530  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:08:53.540  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 11:08:53.540  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:08:53.540  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:08:54.180  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:08:55.630   287   287 E SMD     : DCD OFF
,07-05 11:08:56.230  1014  2746 D SSRM:n  : SIOP:: AP = 300
,07-05 11:08:58.630   287   287 E SMD     : DCD OFF,
,07-05 11:08:59.990  1014  1093 V AlarmManager: waitForAlarm result :8
,07-05 11:09:00.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:00.990  1014  1047 I PowerManagerService: [PWL] Off : 105s ago
,07-05 11:09:01.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:01.630   287   287 E SMD     : DCD OFF
,07-05 11:09:02.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:03.580  1014  2958 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:09:03.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:04.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:04.630   287   287 E SMD     : DCD OFF,
,07-05 11:09:05.600   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,07-05 11:09:06.250  1014  2746 D SSRM:n  : SIOP:: AP = 300
,07-05 11:09:07.630   287   287 E SMD     : DCD OFF,
,07-05 11:09:10.630   287   287 E SMD     : DCD OFF
,07-05 11:09:13.630   287   287 E SMD     : DCD OFF,
,07-05 11:09:13.660  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:09:14.180  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:09:15.050  1014  1335 E Watchdog: !@Sync 6
,07-05 11:09:16.290  1014  2746 D SSRM:n  : SIOP:: AP = 300
,07-05 11:09:16.640   287   287 E SMD     : DCD OFF
,07-05 11:09:19.640   287   287 E SMD     : DCD OFF
,07-05 11:09:22.640   287   287 E SMD     : DCD OFF
,07-05 11:09:23.730  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 11:09:23.730  1014  1676 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-05 11:09:23.730  1014  1676 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:09:23.730  1014  1676 D BatteryService: stay LED for fully charged
,07-05 11:09:23.730  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 11:09:23.740  1014  1014 I MotionRecognitionService: Plugged
07-05 11:09:23.740  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 11:09:23.740  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:09:23.740  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:09:23.740  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 11:09:23.740  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:09:23.750  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:09:23.750  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:09:23.760  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:09:23.770  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:09:23.770  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:09:25.640   287   287 E SMD     : DCD OFF
,07-05 11:09:26.310  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:09:28.640   287   287 E SMD     : DCD OFF
,07-05 11:09:30.600   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
07-05 11:09:30.600   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 11:09:31.640   287   287 E SMD     : DCD OFF
,07-05 11:09:33.810  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:09:34.180  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:09:34.640   287   287 E SMD     : DCD OFF
,07-05 11:09:35.990  1014  1047 I PowerManagerService: [PWL] Off : 140s ago
,07-05 11:09:36.320  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:09:37.640   287   287 E SMD     : DCD OFF
,07-05 11:09:40.600   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:40.650   287   287 E SMD     : DCD OFF,
,07-05 11:09:41.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:42.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:43.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:43.650   287   287 E SMD     : DCD OFF
,07-05 11:09:43.880  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:09:44.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:45.050  1014  1335 E Watchdog: !@Sync 7,
,07-05 11:09:45.610   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,07-05 11:09:46.340  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:09:46.650   287   287 E SMD     : DCD OFF,
,07-05 11:09:49.650   287   287 E SMD     : DCD OFF
,07-05 11:09:50.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:51.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:52.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:52.650   287   287 E SMD     : DCD OFF
,07-05 11:09:53.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:09:53.960  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:09:54.180  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:09:54.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:09:55.610   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,07-05 11:09:55.650   287   287 E SMD     : DCD OFF
,07-05 11:09:56.370  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:09:58.570  1014  1093 V AlarmManager: waitForAlarm result :4
,07-05 11:09:58.570  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 11:09:58.570  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:09:58.580  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 11:09:58.580  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 11:09:58.590  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:09:58.590  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 11:09:58.590  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:09:58.630  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:09:58.630  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:09:58.640  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:09:58.650   287   287 E SMD     : DCD OFF
,07-05 11:09:58.660  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:09:59.990  1014  1093 V AlarmManager: waitForAlarm result :8
,07-05 11:10:01.650   287   287 E SMD     : DCD OFF
,07-05 11:10:04.040  1014  3206 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:04.660   287   287 E SMD     : DCD OFF
,07-05 11:10:05.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:06.390  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:10:06.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:10:07.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:10:07.660   287   287 E SMD     : DCD OFF
,07-05 11:10:08.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:10:09.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:10.610   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 11:10:10.660   287   287 E SMD     : DCD OFF,
,07-05 11:10:13.660   287   287 E SMD     : DCD OFF,
,07-05 11:10:14.110  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:14.110  1014  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-05 11:10:14.110  1014  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:10:14.110  1014  1027 D BatteryService: stay LED for fully charged
07-05 11:10:14.110  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:10:14.120  1014  1014 I MotionRecognitionService: Plugged
07-05 11:10:14.120  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
07-05 11:10:14.120  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:10:14.120  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:10:14.120  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 11:10:14.120  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:10:14.130  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:10:14.130  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:10:14.140  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 11:10:14.140  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:10:14.140  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:10:14.180  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:10:15.050  1014  1335 E Watchdog: !@Sync 8
,07-05 11:10:15.990  1014  1047 I PowerManagerService: [PWL] Off : 180s ago
,07-05 11:10:16.400  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:10:16.660   287   287 E SMD     : DCD OFF
,07-05 11:10:19.660   287   287 E SMD     : DCD OFF
,07-05 11:10:22.660   287   287 E SMD     : DCD OFF
,07-05 11:10:24.190  1014  1324 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:25.610   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:25.670   287   287 E SMD     : DCD OFF
,07-05 11:10:26.440  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:10:26.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:27.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:28.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:10:28.670   287   287 E SMD     : DCD OFF,
,07-05 11:10:29.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:30.620   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 11:10:31.670   287   287 E SMD     : DCD OFF,
,07-05 11:10:34.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:10:34.270  1014  2956 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:34.670   287   287 E SMD     : DCD OFF,
,07-05 11:10:36.450  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:10:37.670   287   287 E SMD     : DCD OFF,
,07-05 11:10:40.670   287   287 E SMD     : DCD OFF,
,07-05 11:10:43.670   287   287 E SMD     : DCD OFF,
,07-05 11:10:44.340  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:10:45.050  1014  1335 E Watchdog: !@Sync 9,
,07-05 11:10:46.460  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:10:46.680   287   287 E SMD     : DCD OFF
,07-05 11:10:49.680   287   287 E SMD     : DCD OFF,
,07-05 11:10:50.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:51.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:52.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:52.680   287   287 E SMD     : DCD OFF,
,07-05 11:10:53.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:10:54.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:10:54.420  1014  1232 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:10:54.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:10:55.620   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 11:10:55.680   287   287 E SMD     : DCD OFF
,07-05 11:10:56.500  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:10:58.680   287   287 E SMD     : DCD OFF,
,07-05 11:11:01.040  1014  1047 I PowerManagerService: [PWL] Off : 225s ago
,07-05 11:11:01.680   287   287 E SMD     : DCD OFF
,07-05 11:11:04.500  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:04.680   287   287 E SMD     : DCD OFF
,07-05 11:11:06.520  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:11:07.690   287   287 E SMD     : DCD OFF
,07-05 11:11:10.690   287   287 E SMD     : DCD OFF,
,07-05 11:11:11.940  1014  1084 I TLC_TIMA_PKM_initialize: initializing...
07-05 11:11:11.940  1014  1084 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 11:11:11.940  1014  1084 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-05 11:11:11.940  1014  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-05 11:11:11.940  1014  1084 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
07-05 11:11:11.940  1014  1083 D TimaService: TimaServiceHandler.handleMessage what =1
07-05 11:11:11.940  1014  1084 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-05 11:11:11.940  1014  1084 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
07-05 11:11:11.940  1014  1084 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
07-05 11:11:11.940  1014  1084 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
07-05 11:11:11.940  1014  1084 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
07-05 11:11:11.940  1014  1084 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
07-05 11:11:11.940  1014  1084 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 11:11:11.960  1014  1084 D QSEECOMAPI: : Loaded image: APP id = 12
,07-05 11:11:11.970  1014  1084 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 11:11:11.980  1014  1084 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 11:11:13.690   287   287 E SMD     : DCD OFF
,07-05 11:11:13.840  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:11:13.840  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:11:13.850  1014  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:11:13.850  1014  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:11:14.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:11:14.570  1014  2958 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:15.050  1014  1335 E Watchdog: !@Sync 10
,07-05 11:11:16.530  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:11:16.690   287   287 E SMD     : DCD OFF
,07-05 11:11:19.690   287   287 E SMD     : DCD OFF
,07-05 11:11:20.620   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 11:11:20.620   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 11:11:22.690   287   287 E SMD     : DCD OFF
,07-05 11:11:24.650  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:11:25.690   287   287 E SMD     : DCD OFF
,07-05 11:11:26.570  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:11:28.690   287   287 E SMD     : DCD OFF,
,07-05 11:11:31.700   287   287 E SMD     : DCD OFF
,07-05 11:11:34.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:11:34.700   287   287 E SMD     : DCD OFF
,07-05 11:11:34.720  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:35.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:36.580  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:11:36.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:37.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:37.700   287   287 E SMD     : DCD OFF
,07-05 11:11:38.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:11:39.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:40.620   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 11:11:40.700   287   287 E SMD     : DCD OFF
,07-05 11:11:43.700   287   287 E SMD     : DCD OFF,
,07-05 11:11:44.800  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:44.800  1014  1209 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,07-05 11:11:44.800  1014  1209 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:11:44.800  1014  1209 D BatteryService: stay LED for fully charged
07-05 11:11:44.800  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 11:11:44.800  1014  1014 I MotionRecognitionService: Plugged
07-05 11:11:44.800  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
07-05 11:11:44.810  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 11:11:44.810  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 11:11:44.810  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:11:44.810  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:11:44.820  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:11:44.820  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:11:44.830  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:44.830  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:44.830  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:11:45.050  1014  1335 E Watchdog: !@Sync 11
,07-05 11:11:45.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:46.600  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:11:46.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:46.700   287   287 E SMD     : DCD OFF
,07-05 11:11:47.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:48.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:11:49.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:11:49.700   287   287 E SMD     : DCD OFF
,07-05 11:11:50.620   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 11:11:51.040  1014  1047 I PowerManagerService: [PWL] Off : 275s ago
,07-05 11:11:52.710   287   287 E SMD     : DCD OFF
,07-05 11:11:53.620  1014  1540 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,07-05 11:11:53.630  1014  1540 D ActivityManager: com.google.android.gms, Starting,
07-05 11:11:53.630  1014  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,07-05 11:11:53.640  1945  1945 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 11:11:53.650  1014  1232 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-05 11:11:53.650  1014  1232 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,07-05 11:11:53.650  1014  1232 W ActivityManager: userId = 0, bbcId = -10000,
07-05 11:11:53.650  1014  1232 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:11:53.650  1014  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:11:53.660  1945  1945 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,07-05 11:11:53.660  1945  1945 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,07-05 11:11:53.680  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:11:53.680  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:11:53.690  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:11:53.690  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:11:53.700  5554  5587 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 11:11:53.700   277   964 D EnterpriseController: uids 10028
07-05 11:11:53.700   277   964 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
07-05 11:11:53.700   277   964 D Netd    : getNetworkForDns: using netid 502 for uid 10028
,07-05 11:11:53.750  5554  5587 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-05 11:11:54.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:11:54.870  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:11:55.710   287   287 E SMD     : DCD OFF
,07-05 11:11:56.640  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:11:58.710   287   287 E SMD     : DCD OFF
,07-05 11:12:00.620   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:01.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:01.710   287   287 E SMD     : DCD OFF
,07-05 11:12:02.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:03.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:04.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:12:04.710   287   287 E SMD     : DCD OFF,
,07-05 11:12:04.950  1014  2951 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:12:05.630   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 11:12:06.660  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:12:07.710   287   287 E SMD     : DCD OFF
,07-05 11:12:10.710   287   287 E SMD     : DCD OFF
,07-05 11:12:13.710   287   287 E SMD     : DCD OFF,
,07-05 11:12:14.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:12:15.030  1014  2957 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:15.050  1014  1335 E Watchdog: !@Sync 12
,07-05 11:12:16.700  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:12:16.720   287   287 E SMD     : DCD OFF
,07-05 11:12:19.720   287   287 E SMD     : DCD OFF
,07-05 11:12:20.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:21.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:22.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:22.720   287   287 E SMD     : DCD OFF
,07-05 11:12:23.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:24.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:12:25.100  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:25.630   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 11:12:25.720   287   287 E SMD     : DCD OFF
,07-05 11:12:26.730  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:12:28.720   287   287 E SMD     : DCD OFF
,07-05 11:12:31.720   287   287 E SMD     : DCD OFF,
,07-05 11:12:34.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:12:34.720   287   287 E SMD     : DCD OFF
,07-05 11:12:35.180  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:12:36.740  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:12:37.720   287   287 E SMD     : DCD OFF
,07-05 11:12:40.730   287   287 E SMD     : DCD OFF
,07-05 11:12:43.730   287   287 E SMD     : DCD OFF
,07-05 11:12:45.050  1014  1335 E Watchdog: !@Sync 13,
,07-05 11:12:45.260  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:45.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:46.100  1014  1047 I PowerManagerService: [PWL] Off : 330s ago
,07-05 11:12:46.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:12:46.730   287   287 E SMD     : DCD OFF,
,07-05 11:12:46.760  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:12:47.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:48.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:49.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:12:49.730   287   287 E SMD     : DCD OFF
,07-05 11:12:50.630   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 11:12:52.730   287   287 E SMD     : DCD OFF
,07-05 11:12:54.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:12:55.330  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:12:55.730   287   287 E SMD     : DCD OFF
,07-05 11:12:56.790  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:12:58.730   287   287 E SMD     : DCD OFF
,07-05 11:12:59.990  1014  1093 V AlarmManager: waitForAlarm result :8
07-05 11:12:59.990  1014  1093 V AlarmManager: No more alarm at this time.nowELAPSED=423217 batch.start=798134
,07-05 11:13:00.000  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 11:13:00.000  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:13:00.010  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 11:13:00.010  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 11:13:00.020  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
07-05 11:13:00.020  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 11:13:00.020  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:13:00.050  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:13:00.060  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:13:00.060  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:13:00.080  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:13:01.730   287   287 E SMD     : DCD OFF
,07-05 11:13:04.740   287   287 E SMD     : DCD OFF
,07-05 11:13:05.410  1014  1324 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:06.800  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:13:07.740   287   287 E SMD     : DCD OFF
,07-05 11:13:10.740   287   287 E SMD     : DCD OFF
,07-05 11:13:13.740   287   287 E SMD     : DCD OFF
,07-05 11:13:14.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:13:15.050  1014  1335 E Watchdog: !@Sync 14
,07-05 11:13:15.480  1014  2956 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:15.630   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 11:13:15.630   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 11:13:16.740   287   287 E SMD     : DCD OFF,
,07-05 11:13:16.840  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:13:19.740   287   287 E SMD     : DCD OFF
,07-05 11:13:22.740   287   287 E SMD     : DCD OFF
,07-05 11:13:25.560  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:25.750   287   287 E SMD     : DCD OFF,
,07-05 11:13:26.880  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:13:28.750   287   287 E SMD     : DCD OFF
,07-05 11:13:31.750   287   287 E SMD     : DCD OFF
,07-05 11:13:34.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:13:34.750   287   287 E SMD     : DCD OFF,
,07-05 11:13:35.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:35.640  1014  1232 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:13:35.640  1014  1232 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-05 11:13:35.640  1014  1232 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:13:35.640  1014  1232 D BatteryService: stay LED for fully charged
,07-05 11:13:35.640  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:13:35.640  1014  1014 I MotionRecognitionService: Plugged,
07-05 11:13:35.640  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
07-05 11:13:35.650  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 11:13:35.650  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:13:35.650  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 11:13:35.650  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:13:35.660  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:13:35.660  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:13:35.670  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:35.670  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:35.670  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:13:36.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:36.900  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:13:37.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:37.750   287   287 E SMD     : DCD OFF
,07-05 11:13:38.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:13:39.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:40.630   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 11:13:40.750   287   287 E SMD     : DCD OFF
,07-05 11:13:43.750   287   287 E SMD     : DCD OFF,
,07-05 11:13:45.050  1014  1335 E Watchdog: !@Sync 15
,07-05 11:13:45.630   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:45.720  1014  2958 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:13:46.100  1014  1047 I PowerManagerService: [PWL] Off : 390s ago,
,07-05 11:13:46.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:46.750   287   287 E SMD     : DCD OFF
,07-05 11:13:46.940  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:13:47.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:48.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:49.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:13:49.760   287   287 E SMD     : DCD OFF
,07-05 11:13:50.640   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 11:13:52.760   287   287 E SMD     : DCD OFF
,07-05 11:13:54.190  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:13:55.760   287   287 E SMD     : DCD OFF
,07-05 11:13:55.790  1014  2951 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:13:56.980  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:13:58.760   287   287 E SMD     : DCD OFF
,07-05 11:13:59.990  1014  1093 V AlarmManager: waitForAlarm result :8,
,07-05 11:14:00.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:01.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:01.760   287   287 E SMD     : DCD OFF
,07-05 11:14:02.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:03.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:03.690   310   310 I bootchecker: bootchecker wake up!!
,07-05 11:14:04.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:04.760   287   287 E SMD     : DCD OFF
,07-05 11:14:05.640   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 11:14:05.870  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:14:07.020  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:14:07.760   287   287 E SMD     : DCD OFF
,07-05 11:14:10.770   287   287 E SMD     : DCD OFF
,07-05 11:14:13.770   287   287 E SMD     : DCD OFF
,07-05 11:14:14.200  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:14:15.050  1014  1335 E Watchdog: !@Sync 16,
,07-05 11:14:15.950  1014  3206 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:16.770   287   287 E SMD     : DCD OFF
,07-05 11:14:17.060  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:14:19.770   287   287 E SMD     : DCD OFF,
,07-05 11:14:20.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:14:21.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:14:22.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:22.770   287   287 E SMD     : DCD OFF
,07-05 11:14:23.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:24.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:25.640   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 11:14:25.770   287   287 E SMD     : DCD OFF
,07-05 11:14:26.020  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:27.070  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:14:28.770   287   287 E SMD     : DCD OFF,
,07-05 11:14:31.770   287   287 E SMD     : DCD OFF
,07-05 11:14:34.200  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:14:34.780   287   287 E SMD     : DCD OFF
,07-05 11:14:36.090  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:37.110  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:14:37.780   287   287 E SMD     : DCD OFF
,07-05 11:14:40.780   287   287 E SMD     : DCD OFF
,07-05 11:14:43.780   287   287 E SMD     : DCD OFF,
,07-05 11:14:45.050  1014  1335 E Watchdog: !@Sync 17
,07-05 11:14:45.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:14:46.170  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:46.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:46.780   287   287 E SMD     : DCD OFF
,07-05 11:14:47.160  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:14:47.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:48.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 11:14:49.640   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 11:14:49.780   287   287 E SMD     : DCD OFF
,07-05 11:14:50.640   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 11:14:51.140  1014  1047 I PowerManagerService: [PWL] Off : 455s ago
,07-05 11:14:52.780   287   287 E SMD     : DCD OFF
,07-05 11:14:54.200  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:14:55.780   287   287 E SMD     : DCD OFF
,07-05 11:14:56.240  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:14:57.200  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:14:58.790   287   287 E SMD     : DCD OFF,
,07-05 11:15:01.790   287   287 E SMD     : DCD OFF
,07-05 11:15:04.790   287   287 E SMD     : DCD OFF
,07-05 11:15:06.320  1014  2958 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:15:07.240  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:15:07.790   287   287 E SMD     : DCD OFF
,07-05 11:15:10.790   287   287 E SMD     : DCD OFF
,07-05 11:15:13.790   287   287 E SMD     : DCD OFF
,07-05 11:15:14.200  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-05 11:15:15.060  1014  1335 E Watchdog: !@Sync 18
,07-05 11:15:15.640   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 11:15:15.640   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 11:15:16.400  1014  2951 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:15:16.790   287   287 E SMD     : DCD OFF
,07-05 11:15:17.280  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:15:19.790   287   287 E SMD     : DCD OFF
,07-05 11:15:22.800   287   287 E SMD     : DCD OFF
,07-05 11:15:25.800   287   287 E SMD     : DCD OFF,
,07-05 11:15:26.470  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:15:27.300  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:15:28.800   287   287 E SMD     : DCD OFF,
,07-05 11:15:31.800   287   287 E SMD     : DCD OFF
,07-05 11:15:34.200  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:15:34.800   287   287 E SMD     : DCD OFF
,07-05 11:15:36.550  1014  3206 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:15:37.310  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:15:37.800   287   287 E SMD     : DCD OFF,
,07-05 11:15:40.650   315   315 I Atfwd_Daemon: Stop the daemon....,
,07-05 11:15:40.800   287   287 E SMD     : DCD OFF,
,07-05 11:15:43.800   287   287 E SMD     : DCD OFF,
,07-05 11:15:45.060  1014  1335 E Watchdog: !@Sync 19,
,07-05 11:15:46.630  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:15:46.810   287   287 E SMD     : DCD OFF
,07-05 11:15:47.330  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:15:49.810   287   287 E SMD     : DCD OFF
,07-05 11:15:52.810   287   287 E SMD     : DCD OFF,
,07-05 11:15:54.200  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:15:55.810   287   287 E SMD     : DCD OFF
,07-05 11:15:56.700  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:15:57.370  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:15:58.810   287   287 E SMD     : DCD OFF,
,07-05 11:16:01.180  1014  1047 I PowerManagerService: [PWL] Off : 525s ago
,07-05 11:16:01.810   287   287 E SMD     : DCD OFF
,07-05 11:16:04.810   287   287 E SMD     : DCD OFF
,07-05 11:16:06.780  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:07.410  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:16:07.820   287   287 E SMD     : DCD OFF
,07-05 11:16:10.820   287   287 E SMD     : DCD OFF,
,07-05 11:16:11.940  1014  1084 D TimaService: TIMA: TimaService scheduler is intialized. 
07-05 11:16:11.940  1014  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-05 11:16:11.940  1014  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 11:16:12.750  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:16:12.750  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:16:12.760  1014  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:16:12.760  1014  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:16:13.820   287   287 E SMD     : DCD OFF,
,07-05 11:16:14.200  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:16:15.060  1014  1335 E Watchdog: !@Sync 20
,07-05 11:16:16.820   287   287 E SMD     : DCD OFF
,07-05 11:16:16.860  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 11:16:16.860  1014  1026 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-05 11:16:16.860  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:16:16.860  1014  1026 D BatteryService: stay LED for fully charged
07-05 11:16:16.860  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:16:16.860  1014  1014 I MotionRecognitionService: Plugged
,07-05 11:16:16.860  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 11:16:16.870  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:16:16.870  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:16:16.870  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 11:16:16.870  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:16:16.880  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:16:16.880  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:16:16.890  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 11:16:16.890  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:16:16.890  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:16:17.420  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:16:19.820   287   287 E SMD     : DCD OFF
,07-05 11:16:22.820   287   287 E SMD     : DCD OFF
,07-05 11:16:25.820   287   287 E SMD     : DCD OFF
,07-05 11:16:26.940  1014  2951 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:16:27.440  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:16:28.820   287   287 E SMD     : DCD OFF
,07-05 11:16:31.830   287   287 E SMD     : DCD OFF
,07-05 11:16:34.200  1014  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 11:16:34.830   287   287 E SMD     : DCD OFF
,07-05 11:16:37.010  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:37.450  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:16:37.830   287   287 E SMD     : DCD OFF
,07-05 11:16:40.830   287   287 E SMD     : DCD OFF
,07-05 11:16:43.830   287   287 E SMD     : DCD OFF
,07-05 11:16:45.060  1014  1335 E Watchdog: !@Sync 21
,07-05 11:16:46.830   287   287 E SMD     : DCD OFF,
,07-05 11:16:47.090  1014  3206 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:47.470  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:16:49.830   287   287 E SMD     : DCD OFF
,07-05 11:16:52.830   287   287 E SMD     : DCD OFF,
,07-05 11:16:55.840   287   287 E SMD     : DCD OFF
,07-05 11:16:57.160  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:16:57.480  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:16:58.840   287   287 E SMD     : DCD OFF,
,07-05 11:17:01.840   287   287 E SMD     : DCD OFF
,07-05 11:17:04.840   287   287 E SMD     : DCD OFF
,07-05 11:17:07.240  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:07.520  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:17:07.840   287   287 E SMD     : DCD OFF
,07-05 11:17:10.840   287   287 E SMD     : DCD OFF
,07-05 11:17:13.840   287   287 E SMD     : DCD OFF
,07-05 11:17:15.060  1014  1335 E Watchdog: !@Sync 22
,07-05 11:17:16.180  1014  1047 I PowerManagerService: [PWL] Off : 600s ago
,07-05 11:17:16.850   287   287 E SMD     : DCD OFF
,07-05 11:17:17.320  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:17.560  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:17:19.850   287   287 E SMD     : DCD OFF,
,07-05 11:17:22.850   287   287 E SMD     : DCD OFF
,07-05 11:17:25.850   287   287 E SMD     : DCD OFF
,07-05 11:17:27.390  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:17:27.570  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:17:28.850   287   287 E SMD     : DCD OFF
,07-05 11:17:31.850   287   287 E SMD     : DCD OFF
,07-05 11:17:34.850   287   287 E SMD     : DCD OFF
,07-05 11:17:37.470  1014  1324 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:17:37.580  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:17:37.850   287   287 E SMD     : DCD OFF
,07-05 11:17:40.860   287   287 E SMD     : DCD OFF
,07-05 11:17:43.860   287   287 E SMD     : DCD OFF,
,07-05 11:17:45.060  1014  1335 E Watchdog: !@Sync 23
,07-05 11:17:46.860   287   287 E SMD     : DCD OFF
,07-05 11:17:47.550  1014  2956 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:47.600  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:17:49.860   287   287 E SMD     : DCD OFF
,07-05 11:17:52.860   287   287 E SMD     : DCD OFF
,07-05 11:17:55.860   287   287 E SMD     : DCD OFF,
,07-05 11:17:57.620  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:17:57.640  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:17:58.860   287   287 E SMD     : DCD OFF,
,07-05 11:18:01.870   287   287 E SMD     : DCD OFF,
,07-05 11:18:04.870   287   287 E SMD     : DCD OFF
,07-05 11:18:07.680  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:18:07.700  1014  1232 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:07.870   287   287 E SMD     : DCD OFF,
,07-05 11:18:10.870   287   287 E SMD     : DCD OFF
,07-05 11:18:13.870   287   287 E SMD     : DCD OFF,
,07-05 11:18:15.060  1014  1335 E Watchdog: !@Sync 24
,07-05 11:18:16.870   287   287 E SMD     : DCD OFF
,07-05 11:18:17.710  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:18:17.780  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:19.870   287   287 E SMD     : DCD OFF
,07-05 11:18:22.880   287   287 E SMD     : DCD OFF
,07-05 11:18:25.880   287   287 E SMD     : DCD OFF
,07-05 11:18:27.750  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:18:27.860  1014  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:28.880   287   287 E SMD     : DCD OFF,
,07-05 11:18:31.880   287   287 E SMD     : DCD OFF
,07-05 11:18:34.880   287   287 E SMD     : DCD OFF
,07-05 11:18:36.210  1014  1047 I PowerManagerService: [PWL] Off : 680s ago
,07-05 11:18:37.800  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:18:37.880   287   287 E SMD     : DCD OFF
,07-05 11:18:37.930  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:18:40.880   287   287 E SMD     : DCD OFF
,07-05 11:18:43.880   287   287 E SMD     : DCD OFF
,07-05 11:18:45.060  1014  1335 E Watchdog: !@Sync 25,
,07-05 11:18:46.890   287   287 E SMD     : DCD OFF,
,07-05 11:18:47.820  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:18:48.010  1014  2957 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:49.890   287   287 E SMD     : DCD OFF
,07-05 11:18:52.890   287   287 E SMD     : DCD OFF
,07-05 11:18:55.890   287   287 E SMD     : DCD OFF
,07-05 11:18:57.870  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:18:58.090  1014  1324 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:18:58.890   287   287 E SMD     : DCD OFF
,07-05 11:19:01.890   287   287 E SMD     : DCD OFF
,07-05 11:19:04.890   287   287 E SMD     : DCD OFF
,07-05 11:19:07.890   287   287 E SMD     : DCD OFF,
,07-05 11:19:07.910  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:19:08.160  1014  2956 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:10.900   287   287 E SMD     : DCD OFF
,07-05 11:19:13.900   287   287 E SMD     : DCD OFF,
,07-05 11:19:14.910  1014  1093 V AlarmManager: waitForAlarm result :4
,07-05 11:19:14.920  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 11:19:14.920  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 11:19:14.930  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 11:19:14.930  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 11:19:14.940  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
07-05 11:19:14.940  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-05 11:19:14.940  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 11:19:14.980  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:19:14.990  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:19:15.000  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:19:15.000  1014  1232 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:19:15.000  1014  1232 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,07-05 11:19:15.000  1014  1232 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:19:15.000  1014  1232 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-05 11:19:15.000  1014  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:19:15.030  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 11:19:15.030  1014  2957 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:19:15.040  1014  2957 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:19:15.040  1014  2957 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:19:15.040  1014  2957 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:19:15.060  2088  6610 I EventLogChimeraService: Aggregate from 1467708118316 (log), 1467708118316 (data)
,07-05 11:19:15.060  1014  1335 E Watchdog: !@Sync 26
,07-05 11:19:15.160  1014  1232 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:19:15.160  1014  1232 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:19:15.160  1014  1232 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:19:15.160  1014  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:19:15.180  1014  2958 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:19:15.180  1014  2958 W ActivityManager: userId = 0, bbcId = -10000,
07-05 11:19:15.180  1014  2958 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:19:15.180  1014  2958 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:19:15.210  1014  2951 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:19:15.220  1014  2951 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:19:15.220  1014  2951 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:19:15.220  1014  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:19:15.220  1014  1676 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 11:19:15.220  1014  1676 W ActivityManager: userId = 0, bbcId = -10000
,07-05 11:19:15.220  1014  1676 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:19:15.220  1014  1676 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 11:19:15.260  2088  6611 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 11:19:15.270  2088  6611 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 11:19:16.900   287   287 E SMD     : DCD OFF
,07-05 11:19:17.950  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:19:18.240  1014  2956 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:19.900   287   287 E SMD     : DCD OFF
,07-05 11:19:22.900   287   287 E SMD     : DCD OFF
,07-05 11:19:25.900   287   287 E SMD     : DCD OFF
,07-05 11:19:28.000  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:19:28.320  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:28.900   287   287 E SMD     : DCD OFF,
,07-05 11:19:31.910   287   287 E SMD     : DCD OFF
,07-05 11:19:34.910   287   287 E SMD     : DCD OFF
,07-05 11:19:37.910   287   287 E SMD     : DCD OFF
,07-05 11:19:38.040  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:19:38.400  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:40.910   287   287 E SMD     : DCD OFF
,07-05 11:19:43.910   287   287 E SMD     : DCD OFF
,07-05 11:19:45.060  1014  1335 E Watchdog: !@Sync 27
,07-05 11:19:46.910   287   287 E SMD     : DCD OFF
,07-05 11:19:48.090  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:19:48.470  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:19:49.910   287   287 E SMD     : DCD OFF
,07-05 11:19:52.920   287   287 E SMD     : DCD OFF
,07-05 11:19:55.920   287   287 E SMD     : DCD OFF
,07-05 11:19:58.130  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:19:58.550  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:19:58.920   287   287 E SMD     : DCD OFF
,07-05 11:19:59.990  1014  1093 V AlarmManager: waitForAlarm result :8
,07-05 11:20:01.220  1014  1047 I PowerManagerService: [PWL] Off : 765s ago
,07-05 11:20:01.920   287   287 E SMD     : DCD OFF,
,07-05 11:20:04.920   287   287 E SMD     : DCD OFF
,07-05 11:20:07.920   287   287 E SMD     : DCD OFF
,07-05 11:20:08.180  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:20:08.620  1014  1324 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:08.620  1014  1324 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-05 11:20:08.620  1014  1324 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:20:08.620  1014  1324 D BatteryService: stay LED for fully charged
,07-05 11:20:08.630  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:20:08.630  1014  1014 I MotionRecognitionService: Plugged
07-05 11:20:08.630  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 11:20:08.630  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:20:08.630  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
07-05 11:20:08.630  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 11:20:08.630  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:20:08.640  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 11:20:08.640  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:20:08.650  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:08.650  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:20:08.650  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:10.920   287   287 E SMD     : DCD OFF
,07-05 11:20:13.920   287   287 E SMD     : DCD OFF
,07-05 11:20:15.060  1014  1335 E Watchdog: !@Sync 28
,07-05 11:20:16.930   287   287 E SMD     : DCD OFF
,07-05 11:20:18.220  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:20:18.700  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:19.930   287   287 E SMD     : DCD OFF
,07-05 11:20:22.930   287   287 E SMD     : DCD OFF
,07-05 11:20:25.930   287   287 E SMD     : DCD OFF
,07-05 11:20:28.260  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:20:28.770  1014  2957 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-05 11:20:28.770  1014  2957 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,07-05 11:20:28.770  1014  2957 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:20:28.770  1014  2957 D BatteryService: stay LED for fully charged
07-05 11:20:28.770  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 11:20:28.780  1014  1014 I MotionRecognitionService: Plugged
07-05 11:20:28.780  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 11:20:28.780  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 11:20:28.780  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 11:20:28.780  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 11:20:28.780  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:20:28.790  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:20:28.790  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:20:28.800  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:28.800  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:20:28.800  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:28.930   287   287 E SMD     : DCD OFF
,07-05 11:20:31.930   287   287 E SMD     : DCD OFF
,07-05 11:20:34.930   287   287 E SMD     : DCD OFF
,07-05 11:20:37.930   287   287 E SMD     : DCD OFF,
,07-05 11:20:38.290  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:20:38.850  1014  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:38.850  1014  1678 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
07-05 11:20:38.850  1014  1678 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
07-05 11:20:38.850  1014  1678 D BatteryService: stay LED for fully charged
,07-05 11:20:38.850  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 11:20:38.860  1014  1014 I MotionRecognitionService: Plugged
07-05 11:20:38.860  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 11:20:38.860  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 11:20:38.860  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 11:20:38.860  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-05 11:20:38.860  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-05 11:20:38.870  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 11:20:38.870  2654  2744 D HeadsetStateMachine: Disconnected process message: 10
,07-05 11:20:38.880  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:38.890  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 11:20:38.890  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 11:20:40.940   287   287 E SMD     : DCD OFF
,07-05 11:20:43.940   287   287 E SMD     : DCD OFF,
,07-05 11:20:45.060  1014  1335 E Watchdog: !@Sync 29
,07-05 11:20:46.940   287   287 E SMD     : DCD OFF
,07-05 11:20:48.310  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:20:48.930  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:20:49.940   287   287 E SMD     : DCD OFF
,07-05 11:20:52.940   287   287 E SMD     : DCD OFF
,07-05 11:20:55.940   287   287 E SMD     : DCD OFF
,07-05 11:20:58.330  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:20:58.940   287   287 E SMD     : DCD OFF,
,07-05 11:20:59.010  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:21:01.950   287   287 E SMD     : DCD OFF
,07-05 11:21:04.950   287   287 E SMD     : DCD OFF,
,07-05 11:21:07.950   287   287 E SMD     : DCD OFF
,07-05 11:21:08.350  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:21:09.080  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:10.950   287   287 E SMD     : DCD OFF,
,07-05 11:21:11.940  1014  1084 D TimaService: TIMA: TimaService scheduler is intialized. ,
07-05 11:21:11.940  1014  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-05 11:21:11.940  1014  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 11:21:13.810  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:21:13.810  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:21:13.820  1014  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:21:13.820  1014  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:21:13.950   287   287 E SMD     : DCD OFF
,07-05 11:21:15.070  1014  1335 E Watchdog: !@Sync 30
,07-05 11:21:16.950   287   287 E SMD     : DCD OFF
,07-05 11:21:18.400  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:21:19.160  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:19.950   287   287 E SMD     : DCD OFF
,07-05 11:21:22.960   287   287 E SMD     : DCD OFF
,07-05 11:21:25.960   287   287 E SMD     : DCD OFF
,07-05 11:21:28.420  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:21:28.960   287   287 E SMD     : DCD OFF
,07-05 11:21:29.230  1014  1324 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:31.220  1014  1047 I PowerManagerService: [PWL] Off : 855s ago
,07-05 11:21:31.960   287   287 E SMD     : DCD OFF
,07-05 11:21:34.960   287   287 E SMD     : DCD OFF
,07-05 11:21:37.960   287   287 E SMD     : DCD OFF
,07-05 11:21:38.470  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:21:39.310  1014  1232 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:40.960   287   287 E SMD     : DCD OFF
,07-05 11:21:43.960   287   287 E SMD     : DCD OFF
,07-05 11:21:45.070  1014  1335 E Watchdog: !@Sync 31,
,07-05 11:21:46.970   287   287 E SMD     : DCD OFF
,07-05 11:21:48.510  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:21:49.380  1014  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:21:49.970   287   287 E SMD     : DCD OFF
,07-05 11:21:52.970   287   287 E SMD     : DCD OFF
,07-05 11:21:55.970   287   287 E SMD     : DCD OFF
,07-05 11:21:58.530  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:21:58.970   287   287 E SMD     : DCD OFF
,07-05 11:21:59.450  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:01.970   287   287 E SMD     : DCD OFF
,07-05 11:22:04.970   287   287 E SMD     : DCD OFF
,07-05 11:22:07.970   287   287 E SMD     : DCD OFF
,07-05 11:22:08.580  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:22:09.530  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:10.980   287   287 E SMD     : DCD OFF
,07-05 11:22:13.980   287   287 E SMD     : DCD OFF,
,07-05 11:22:15.070  1014  1335 E Watchdog: !@Sync 32,
,07-05 11:22:16.980   287   287 E SMD     : DCD OFF
,07-05 11:22:18.630  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:22:19.610  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:19.980   287   287 E SMD     : DCD OFF
,07-05 11:22:22.980   287   287 E SMD     : DCD OFF
,07-05 11:22:25.980   287   287 E SMD     : DCD OFF
,07-05 11:22:28.650  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:22:28.980   287   287 E SMD     : DCD OFF,
,07-05 11:22:29.690  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:31.980   287   287 E SMD     : DCD OFF
,07-05 11:22:34.990   287   287 E SMD     : DCD OFF
,07-05 11:22:37.990   287   287 E SMD     : DCD OFF
,07-05 11:22:38.700  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:22:39.760  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:22:40.990   287   287 E SMD     : DCD OFF
,07-05 11:22:43.990   287   287 E SMD     : DCD OFF
,07-05 11:22:45.070  1014  1335 E Watchdog: !@Sync 33
,07-05 11:22:46.990   287   287 E SMD     : DCD OFF
,07-05 11:22:48.750  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:22:49.840  1014  1324 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:22:49.990   287   287 E SMD     : DCD OFF
,07-05 11:22:52.990   287   287 E SMD     : DCD OFF
,07-05 11:22:56.000   287   287 E SMD     : DCD OFF
,07-05 11:22:58.790  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:22:59.000   287   287 E SMD     : DCD OFF
,07-05 11:22:59.910  1014  1232 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:02.000   287   287 E SMD     : DCD OFF
,07-05 11:23:05.000   287   287 E SMD     : DCD OFF
,07-05 11:23:06.270  1014  1047 I PowerManagerService: [PWL] Off : 950s ago
,07-05 11:23:08.000   287   287 E SMD     : DCD OFF,
,07-05 11:23:08.840  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:23:09.990  1014  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:11.000   287   287 E SMD     : DCD OFF
,07-05 11:23:14.000   287   287 E SMD     : DCD OFF
,07-05 11:23:15.070  1014  1335 E Watchdog: !@Sync 34
,07-05 11:23:17.000   287   287 E SMD     : DCD OFF,
,07-05 11:23:18.850  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:23:20.010   287   287 E SMD     : DCD OFF
,07-05 11:23:20.060  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:23.010   287   287 E SMD     : DCD OFF,
,07-05 11:23:26.010   287   287 E SMD     : DCD OFF
,07-05 11:23:28.860  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:23:29.010   287   287 E SMD     : DCD OFF
,07-05 11:23:30.140  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:32.010   287   287 E SMD     : DCD OFF
,07-05 11:23:35.010   287   287 E SMD     : DCD OFF
,07-05 11:23:38.010   287   287 E SMD     : DCD OFF,
,07-05 11:23:38.910  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:23:40.210  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:41.020   287   287 E SMD     : DCD OFF
,07-05 11:23:44.020   287   287 E SMD     : DCD OFF
,07-05 11:23:45.070  1014  1335 E Watchdog: !@Sync 35
,07-05 11:23:47.020   287   287 E SMD     : DCD OFF
,07-05 11:23:48.960  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:23:50.020   287   287 E SMD     : DCD OFF,
,07-05 11:23:50.290  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:23:53.020   287   287 E SMD     : DCD OFF,
,07-05 11:23:56.020   287   287 E SMD     : DCD OFF
,07-05 11:23:59.000  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:23:59.020   287   287 E SMD     : DCD OFF,
,07-05 11:24:00.360  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:24:02.020   287   287 E SMD     : DCD OFF
,07-05 11:24:05.030   287   287 E SMD     : DCD OFF
,07-05 11:24:08.030   287   287 E SMD     : DCD OFF,
,07-05 11:24:09.040  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:24:10.440  1014  1324 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:11.030   287   287 E SMD     : DCD OFF
,07-05 11:24:14.030   287   287 E SMD     : DCD OFF
,07-05 11:24:15.070  1014  1335 E Watchdog: !@Sync 36,
,07-05 11:24:17.030   287   287 E SMD     : DCD OFF,
,07-05 11:24:19.050  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:24:20.030   287   287 E SMD     : DCD OFF
,07-05 11:24:20.510  1014  1232 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:23.030   287   287 E SMD     : DCD OFF
,07-05 11:24:26.040   287   287 E SMD     : DCD OFF,
,07-05 11:24:29.040   287   287 E SMD     : DCD OFF
,07-05 11:24:29.100  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:24:30.590  1014  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:32.040   287   287 E SMD     : DCD OFF
,07-05 11:24:35.040   287   287 E SMD     : DCD OFF,
,07-05 11:24:38.040   287   287 E SMD     : DCD OFF
,07-05 11:24:39.150  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:24:40.670  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:24:41.040   287   287 E SMD     : DCD OFF
,07-05 11:24:44.040   287   287 E SMD     : DCD OFF
,07-05 11:24:45.070  1014  1335 E Watchdog: !@Sync 37,
,07-05 11:24:46.370  1014  1047 I PowerManagerService: [PWL] Off : 1051s ago,
,07-05 11:24:47.040   287   287 E SMD     : DCD OFF,
,07-05 11:24:49.200  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:24:50.050   287   287 E SMD     : DCD OFF
,07-05 11:24:50.740  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:24:53.050   287   287 E SMD     : DCD OFF
,07-05 11:24:56.050   287   287 E SMD     : DCD OFF
,07-05 11:24:59.050   287   287 E SMD     : DCD OFF
,07-05 11:24:59.210  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:25:00.820  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:25:02.050   287   287 E SMD     : DCD OFF
,07-05 11:25:05.050   287   287 E SMD     : DCD OFF
,07-05 11:25:08.050   287   287 E SMD     : DCD OFF
,07-05 11:25:09.260  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:25:10.900  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:25:11.050   287   287 E SMD     : DCD OFF
,07-05 11:25:14.060   287   287 E SMD     : DCD OFF
,07-05 11:25:15.070  1014  1335 E Watchdog: !@Sync 38
,07-05 11:25:17.060   287   287 E SMD     : DCD OFF
,07-05 11:25:19.270  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:25:20.060   287   287 E SMD     : DCD OFF
,07-05 11:25:20.970  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:25:23.060   287   287 E SMD     : DCD OFF
,07-05 11:25:26.060   287   287 E SMD     : DCD OFF
,07-05 11:25:29.060   287   287 E SMD     : DCD OFF
,07-05 11:25:29.290  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:25:31.050  1014  2957 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:25:32.060   287   287 E SMD     : DCD OFF,
,07-05 11:25:35.070   287   287 E SMD     : DCD OFF
,07-05 11:25:38.070   287   287 E SMD     : DCD OFF
,07-05 11:25:39.300  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:25:41.070   287   287 E SMD     : DCD OFF
,07-05 11:25:41.130  1014  2956 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:25:44.070   287   287 E SMD     : DCD OFF
,07-05 11:25:45.070  1014  1335 E Watchdog: !@Sync 39
,07-05 11:25:47.070   287   287 E SMD     : DCD OFF
,07-05 11:25:49.310  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:25:50.070   287   287 E SMD     : DCD OFF
,07-05 11:25:51.210  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:25:53.070   287   287 E SMD     : DCD OFF
,07-05 11:25:56.070   287   287 E SMD     : DCD OFF
,07-05 11:25:59.080   287   287 E SMD     : DCD OFF
,07-05 11:25:59.330  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:26:01.280  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:02.080   287   287 E SMD     : DCD OFF
,07-05 11:26:05.080   287   287 E SMD     : DCD OFF
,07-05 11:26:08.080   287   287 E SMD     : DCD OFF
,07-05 11:26:09.370  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:26:11.080   287   287 E SMD     : DCD OFF,
,07-05 11:26:11.360  1014  2951 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:11.940  1014  1084 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 11:26:11.940  1014  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-05 11:26:11.940  1014  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 11:26:12.670  1014  1039 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 11:26:12.710  1014  1099 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-05 11:26:12.710  1014  1099 I ApplicationUsage: Updating Usage Statistics in DB @ 1467710772714
,07-05 11:26:12.710  1014  1099 I ApplicationPolicy: updateDataUsageMap
,07-05 11:26:12.760  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:26:12.760  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:26:12.760  1014  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:26:12.760  1014  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:26:13.180  1014  1099 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,07-05 11:26:13.180  1014  1099 I NetworkDataUsageDb: ::isTableExists: Table exists 
,07-05 11:26:13.200  1014  1099 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467710773208
,07-05 11:26:14.080   287   287 E SMD     : DCD OFF,
,07-05 11:26:15.070  1014  1335 E Watchdog: !@Sync 40
,07-05 11:26:17.080   287   287 E SMD     : DCD OFF
,07-05 11:26:19.420  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:26:20.080   287   287 E SMD     : DCD OFF
,07-05 11:26:21.430  1014  3206 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:23.090   287   287 E SMD     : DCD OFF
,07-05 11:26:26.090   287   287 E SMD     : DCD OFF
,07-05 11:26:29.090   287   287 E SMD     : DCD OFF
,07-05 11:26:29.440  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:26:31.390  1014  1047 I PowerManagerService: [PWL] Off : 1156s ago
,07-05 11:26:31.510  1014  2958 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:26:32.090   287   287 E SMD     : DCD OFF
,07-05 11:26:35.090   287   287 E SMD     : DCD OFF
,07-05 11:26:38.090   287   287 E SMD     : DCD OFF
,07-05 11:26:39.450  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:26:41.090   287   287 E SMD     : DCD OFF
,07-05 11:26:41.580  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:26:44.100   287   287 E SMD     : DCD OFF
,07-05 11:26:45.070  1014  1335 E Watchdog: !@Sync 41
,07-05 11:26:47.100   287   287 E SMD     : DCD OFF
,07-05 11:26:49.460  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:26:50.100   287   287 E SMD     : DCD OFF
,07-05 11:26:51.660  1014  2957 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:26:53.100   287   287 E SMD     : DCD OFF
,07-05 11:26:56.100   287   287 E SMD     : DCD OFF
,07-05 11:26:59.100   287   287 E SMD     : DCD OFF,
,07-05 11:26:59.470  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:27:01.740  1014  2956 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:27:02.100   287   287 E SMD     : DCD OFF
,07-05 11:27:05.100   287   287 E SMD     : DCD OFF
,07-05 11:27:08.110   287   287 E SMD     : DCD OFF
,07-05 11:27:09.520  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:27:11.110   287   287 E SMD     : DCD OFF
,07-05 11:27:11.810  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:14.110   287   287 E SMD     : DCD OFF
,07-05 11:27:15.070  1014  1335 E Watchdog: !@Sync 42
,07-05 11:27:17.110   287   287 E SMD     : DCD OFF
,07-05 11:27:19.540  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:27:20.110   287   287 E SMD     : DCD OFF
,07-05 11:27:21.890  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:23.110   287   287 E SMD     : DCD OFF
,07-05 11:27:26.110   287   287 E SMD     : DCD OFF
,07-05 11:27:29.110   287   287 E SMD     : DCD OFF,
,07-05 11:27:29.560  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:27:31.960  1014  2951 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:32.120   287   287 E SMD     : DCD OFF
,07-05 11:27:35.120   287   287 E SMD     : DCD OFF
,07-05 11:27:38.120   287   287 E SMD     : DCD OFF
,07-05 11:27:39.570  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:27:41.120   287   287 E SMD     : DCD OFF
,07-05 11:27:42.040  1014  3206 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:27:44.120   287   287 E SMD     : DCD OFF,
,07-05 11:27:45.070  1014  1335 E Watchdog: !@Sync 43
,07-05 11:27:47.120   287   287 E SMD     : DCD OFF
,07-05 11:27:49.620  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:27:50.120   287   287 E SMD     : DCD OFF,
,07-05 11:27:52.120  1014  2958 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:27:53.130   287   287 E SMD     : DCD OFF
,07-05 11:27:56.130   287   287 E SMD     : DCD OFF
,07-05 11:27:59.130   287   287 E SMD     : DCD OFF,
,07-05 11:27:59.640  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:28:02.130   287   287 E SMD     : DCD OFF
,07-05 11:28:02.200  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:05.130   287   287 E SMD     : DCD OFF
,07-05 11:28:08.130   287   287 E SMD     : DCD OFF
,07-05 11:28:09.690  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:28:11.130   287   287 E SMD     : DCD OFF,
,07-05 11:28:12.270  1014  2957 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:14.130   287   287 E SMD     : DCD OFF,
,07-05 11:28:15.080  1014  1335 E Watchdog: !@Sync 44
,07-05 11:28:17.140   287   287 E SMD     : DCD OFF
,07-05 11:28:19.700  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:28:20.140   287   287 E SMD     : DCD OFF
,07-05 11:28:21.490  1014  1047 I PowerManagerService: [PWL] Off : 1266s ago
,07-05 11:28:22.350  1014  2956 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:23.140   287   287 E SMD     : DCD OFF
,07-05 11:28:26.140   287   287 E SMD     : DCD OFF
,07-05 11:28:29.140   287   287 E SMD     : DCD OFF,
,07-05 11:28:29.720  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:28:32.140   287   287 E SMD     : DCD OFF
,07-05 11:28:32.430  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:35.140   287   287 E SMD     : DCD OFF
,07-05 11:28:38.140   287   287 E SMD     : DCD OFF
,07-05 11:28:39.730  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:28:41.150   287   287 E SMD     : DCD OFF
,07-05 11:28:42.500  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:28:44.150   287   287 E SMD     : DCD OFF,
,07-05 11:28:45.080  1014  1335 E Watchdog: !@Sync 45
,07-05 11:28:47.150   287   287 E SMD     : DCD OFF
,07-05 11:28:49.780  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:28:50.150   287   287 E SMD     : DCD OFF
,07-05 11:28:52.570  1014  2951 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:28:53.150   287   287 E SMD     : DCD OFF
,07-05 11:28:56.150   287   287 E SMD     : DCD OFF
,07-05 11:28:59.150   287   287 E SMD     : DCD OFF,
,07-05 11:28:59.800  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:29:02.150   287   287 E SMD     : DCD OFF,
,07-05 11:29:02.650  1014  3206 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:29:05.160   287   287 E SMD     : DCD OFF
,07-05 11:29:08.160   287   287 E SMD     : DCD OFF,
,07-05 11:29:09.810  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:29:11.160   287   287 E SMD     : DCD OFF
,07-05 11:29:12.730  1014  2958 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:29:14.160   287   287 E SMD     : DCD OFF
,07-05 11:29:15.080  1014  1335 E Watchdog: !@Sync 46
,07-05 11:29:17.160   287   287 E SMD     : DCD OFF
,07-05 11:29:19.860  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:29:20.160   287   287 E SMD     : DCD OFF
,07-05 11:29:22.810  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:29:23.170   287   287 E SMD     : DCD OFF,
,07-05 11:29:26.170   287   287 E SMD     : DCD OFF
,07-05 11:29:29.170   287   287 E SMD     : DCD OFF
,07-05 11:29:29.880  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:29:32.170   287   287 E SMD     : DCD OFF
,07-05 11:29:32.890  1014  2957 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:29:35.170   287   287 E SMD     : DCD OFF,
,07-05 11:29:38.170   287   287 E SMD     : DCD OFF,
,07-05 11:29:39.890  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:29:41.170   287   287 E SMD     : DCD OFF
,07-05 11:29:42.970  1014  2956 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:29:44.170   287   287 E SMD     : DCD OFF
,07-05 11:29:45.080  1014  1335 E Watchdog: !@Sync 47
,07-05 11:29:47.180   287   287 E SMD     : DCD OFF
,07-05 11:29:49.940  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:29:50.180   287   287 E SMD     : DCD OFF,
,07-05 11:29:53.040  1014  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:29:53.180   287   287 E SMD     : DCD OFF,
,07-05 11:29:56.180   287   287 E SMD     : DCD OFF
,07-05 11:29:59.180   287   287 E SMD     : DCD OFF
,07-05 11:29:59.960  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:30:02.180   287   287 E SMD     : DCD OFF
,07-05 11:30:03.120  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:05.180   287   287 E SMD     : DCD OFF
,07-05 11:30:08.180   287   287 E SMD     : DCD OFF,
,07-05 11:30:09.980  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:30:11.190   287   287 E SMD     : DCD OFF
,07-05 11:30:13.200  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:14.190   287   287 E SMD     : DCD OFF
,07-05 11:30:15.080  1014  1335 E Watchdog: !@Sync 48
,07-05 11:30:16.490  1014  1047 I PowerManagerService: [PWL] Off : 1381s ago
,07-05 11:30:17.190   287   287 E SMD     : DCD OFF
,07-05 11:30:19.990  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:30:20.190   287   287 E SMD     : DCD OFF
,07-05 11:30:23.190   287   287 E SMD     : DCD OFF
,07-05 11:30:23.270  1014  1324 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:26.190   287   287 E SMD     : DCD OFF
,07-05 11:30:29.190   287   287 E SMD     : DCD OFF
,07-05 11:30:30.010  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:30:32.190   287   287 E SMD     : DCD OFF
,07-05 11:30:33.350  1014  1232 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:30:35.200   287   287 E SMD     : DCD OFF,
,07-05 11:30:38.200   287   287 E SMD     : DCD OFF
,07-05 11:30:40.060  1014  2746 D SSRM:n  : SIOP:: AP = 290,
,07-05 11:30:41.200   287   287 E SMD     : DCD OFF,
,07-05 11:30:43.430  1014  1678 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:44.200   287   287 E SMD     : DCD OFF
,07-05 11:30:45.080  1014  1335 E Watchdog: !@Sync 49
,07-05 11:30:47.200   287   287 E SMD     : DCD OFF
,07-05 11:30:50.070  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:30:50.200   287   287 E SMD     : DCD OFF
,07-05 11:30:53.200   287   287 E SMD     : DCD OFF,
,07-05 11:30:53.500  1014  1209 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:30:56.210   287   287 E SMD     : DCD OFF
,07-05 11:30:59.210   287   287 E SMD     : DCD OFF
,07-05 11:31:00.090  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:31:02.210   287   287 E SMD     : DCD OFF
,07-05 11:31:03.580  1014  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:31:05.210   287   287 E SMD     : DCD OFF
,07-05 11:31:08.210   287   287 E SMD     : DCD OFF,
,07-05 11:31:10.100  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:31:11.210   287   287 E SMD     : DCD OFF
,07-05 11:31:11.940  1014  1084 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 11:31:11.940  1014  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 11:31:11.940  1014  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 11:31:13.660  1014  1676 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 11:31:13.830  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 11:31:13.830  1014  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 11:31:13.840  1014  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:31:13.840  1014  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 11:31:14.210   287   287 E SMD     : DCD OFF
,07-05 11:31:15.080  1014  1335 E Watchdog: !@Sync 50
,07-05 11:31:17.210   287   287 E SMD     : DCD OFF
,07-05 11:31:20.110  1014  2746 D SSRM:n  : SIOP:: AP = 290
,07-05 11:31:20.220   287   287 E SMD     : DCD OFF
,07-05 11:31:23.220   287   287 E SMD     : DCD OFF,
,07-05 11:31:23.740  1014  1323 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,07-05 11:31:26.220   287   287 E SMD     : DCD OFF
,07-05 11:31:29.220   287   287 E SMD     : DCD OFF
,07-05 11:31:30.130  1014  2746 D SSRM:n  : SIOP:: AP = 290
,TIME-OUT KILL (timeout was 1400000ms),07-05 11:31:32.220   287   287 E SMD     : DCD OFF
07-05 11:31:33.820  1014  2955 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 11:31:34.740  6911  6911 D AndroidRuntime: 
07-05 11:31:34.740  6911  6911 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 11:31:34.740  6911  6911 D AndroidRuntime: CheckJNI is OFF
07-05 11:31:34.740  6911  6911 D AndroidRuntime: readGMSProperty: start
07-05 11:31:34.740  6911  6911 D AndroidRuntime: readGMSProperty: already setted!!
07-05 11:31:34.740  6911  6911 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 11:31:34.740  6911  6911 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 11:31:34.740  6911  6911 D AndroidRuntime: readGMSProperty: end
07-05 11:31:34.740  6911  6911 D AndroidRuntime: addProductProperty: start
07-05 11:31:34.870  6911  6911 E AffinityControl: AffinityControl: registerfunction enter
07-05 11:31:34.890  6911  6911 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 11:31:34.900  1014  1678 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 11:31:34.900  1014  1678 D PackageManager: START PACKAGE DELETE: observer{927605454}
07-05 11:31:34.900  1014  1678 D PackageManager: pkg{<packageName>}
07-05 11:31:34.900  1014  1678 D PackageManager: user{0}
07-05 11:31:34.900  1014  1678 D PackageManager: caller{2000}
07-05 11:31:34.900  1014  1678 D PackageManager: flags{2}
07-05 11:31:34.900  1014  1678 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 11:31:34.900  1014  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 11:31:34.900  1014  1678 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 11:31:34.910  1014  1055 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
07-05 11:31:34.900  1014  1678 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 11:31:34.910  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
07-05 11:31:34.900  1014  1678 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 11:31:34.910  1014  1040 I ActivityManager: Killing 6222:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 11:31:34.900  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 11:31:34.910  1014  1040 I ActivityManager:   Force finishing activity ActivityRecord{28dd0ff0 u0 com.test.thalitest/.MainActivity t24}
07-05 11:31:34.900  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 11:31:34.900  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 11:31:34.900  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 11:31:34.920  1014  1040 D InputDispatcher: Focus left window: 6222
07-05 11:31:34.920   257   439 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
07-05 11:31:34.920   257   436 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
07-05 11:31:34.940  1014  1040 D InputDispatcher: Focused application released
07-05 11:31:34.940  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 11:31:34.940  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 11:31:35.050  1014  1055 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
07-05 11:31:35.070  1014  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
07-05 11:31:35.110  5623  5623 I art     : Explicit concurrent mark sweep GC freed 1979(113KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 837us total 32.941ms
07-05 11:31:35.110  6157  6157 I art     : Explicit concurrent mark sweep GC freed 598(34KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 1.271ms total 51.872ms
07-05 11:31:35.120  5715  5715 I art     : Explicit concurrent mark sweep GC freed 103(15KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 743us total 58.904ms
07-05 11:31:35.130  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 11:31:35.140  1945  2122 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 11:31:35.140  2088  2088 I art     : Explicit concurrent mark sweep GC freed 19989(1247KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 15MB/21MB, paused 1.309ms total 85.238ms
07-05 11:31:35.140  1784  1784 E SamsungIME: mOCRHelper is null
07-05 11:31:35.150  3688  3688 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jul 05 11:31:35 GMT+02:00 2016
07-05 11:31:35.160  1014  3206 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-05 11:31:35.160  1014  3206 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
07-05 11:31:35.160  1014  3206 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.160  1014  3206 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 11:31:35.160  1014  3206 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
07-05 11:31:35.160  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
07-05 11:31:35.170  1439  1439 D RegisteredServicesCache: empty dynamic service
07-05 11:31:35.180  3688  3688 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
07-05 11:31:35.180  2088  2098 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-05 11:31:35.190  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
07-05 11:31:35.190  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
07-05 11:31:35.190  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 11:31:35.190  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
07-05 11:31:35.190  1014  2956 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
07-05 11:31:35.190  1014  2956 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
07-05 11:31:35.190  1014  2956 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-05 11:31:35.190  1014  2956 D ActivityManager: com.sec.esdk.elm, Starting
07-05 11:31:35.200  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
07-05 11:31:35.200  1014  2956 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.200  1014  2956 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.200  1014  2956 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.200  1014  2956 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.210  1014  1122 V NetworkStats: performPollLocked() took 21ms
07-05 11:31:35.210  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 11:31:35.210  6923  6923 E Zygote  : MountEmulatedStorage()
07-05 11:31:35.210  6923  6923 E Zygote  : v2
07-05 11:31:35.210  6923  6923 I libpersona: KNOX_SDCARD checking this for 10094
07-05 11:31:35.210  6923  6923 I libpersona: KNOX_SDCARD not a persona
07-05 11:31:35.220  3688  3688 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
07-05 11:31:35.220  6923  6923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 11:31:35.220  1014  2956 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6923 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
07-05 11:31:35.220  6923  6923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 11:31:35.220  6923  6923 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 11:31:35.220   287   287 E SMD     : DCD OFF
07-05 11:31:35.230  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
07-05 11:31:35.240  4998  4998 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
07-05 11:31:35.240  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
07-05 11:31:35.250  3688  3688 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-05 11:31:35.260  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
07-05 11:31:35.260  1014  1040 D ActivityManager: com.sec.android.app.themechooser, Starting
07-05 11:31:35.260  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.260  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.260  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.260  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.260  6923  6923 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 11:31:35.260  6923  6923 D ActivityThread: Added TimaKeyStore provider
07-05 11:31:35.270  3688  3688 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-05 11:31:35.270  3688  6922 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
07-05 11:31:35.280  6938  6938 E Zygote  : MountEmulatedStorage()
07-05 11:31:35.280  6938  6938 I libpersona: KNOX_SDCARD checking this for 10149
07-05 11:31:35.280  6938  6938 E Zygote  : v2
07-05 11:31:35.280  6938  6938 I libpersona: KNOX_SDCARD not a persona
07-05 11:31:35.280  6938  6938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 11:31:35.280  6938  6938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 11:31:35.280  6938  6938 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 11:31:35.280  1014  1040 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6938 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 11:31:35.300  3688  6922 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
07-05 11:31:35.310  6938  6938 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 11:31:35.310  6938  6938 D ActivityThread: Added TimaKeyStore provider
07-05 11:31:35.310  5715  6940 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
07-05 11:31:35.320  3688  6922 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
07-05 11:31:35.320  1014  1014 I art     : Explicit concurrent mark sweep GC freed 40629(4MB) AllocSpace objects, 176(2MB) LOS objects, 33% free, 29MB/44MB, paused 6.159ms total 253.055ms
07-05 11:31:35.320  1014  1055 I art     : WaitForGcToComplete blocked for 147.296ms for cause Explicit
07-05 11:31:35.320  3688  6922 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
07-05 11:31:35.330  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 11:31:35.330  1014  2957 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 11:31:35.330  1014  2957 D SecContentProvider2: mCursor = null
07-05 11:31:35.340  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 11:31:35.360  5715  6940 I art     : Explicit concurrent mark sweep GC freed 623(35KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 731us total 25.060ms
07-05 11:31:35.380  5868  5868 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
07-05 11:31:35.400  1014  1324 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-05 11:31:35.400  1014  1324 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
07-05 11:31:35.400  1014  1324 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.400  1014  1324 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 11:31:35.400  1014  1324 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
07-05 11:31:35.410  6084  6098 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-05 11:31:35.410  6084  6098 D BadgeProvider: sendNotify, [notify] : null
07-05 11:31:35.410  6084  6098 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-05 11:31:35.410  6084  6098 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-05 11:31:35.410  6084  6098 D BadgeProvider: update, [UpdateCount] : 1
07-05 11:31:35.420  6923  6923 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-05 11:31:35.430  3688  6922 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
07-05 11:31:35.430  6923  6923 D elm:15183: ELMEngine.ELMEngine( context ).
07-05 11:31:35.430  6923  6923 D elm:15183: MDMBridge.setEnterpriseBridge()
07-05 11:31:35.430  5102  5102 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
07-05 11:31:35.440  1014  1027 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-05 11:31:35.440  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
07-05 11:31:35.440  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.440  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 11:31:35.440  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
07-05 11:31:35.440  1014  2956 I TactileAssist: enable value -1
07-05 11:31:35.440  1014  2956 I TactileAssist: internal enable value -1
07-05 11:31:35.440  1014  2956 I TactileAssist: intensity value -1
07-05 11:31:35.440  1014  2956 I TactileAssist: saveAppList value true
07-05 11:31:35.440  1014  2956 I TactileAssist: List of disabled apps :
07-05 11:31:35.450  5868  6954 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-05 11:31:35.450  5868  6954 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
07-05 11:31:35.450  6923  6923 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-05 11:31:35.450  1014  2955 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-05 11:31:35.450  1014  2955 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
07-05 11:31:35.450  1014  2955 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.450  1014  2955 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 11:31:35.450  1014  2955 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
07-05 11:31:35.460  3366  3366 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-05 11:31:35.460  3366  3366 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 11:31:35.460  3366  3366 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-05 11:31:35.460  3366  3366 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-05 11:31:35.460  3366  3366 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-05 11:31:35.460  3366  3366 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-05 11:31:35.460  3366  3366 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-05 11:31:35.460  3366  3366 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 11:31:35.460  3366  3366 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 11:31:35.460  3366  3366 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 11:31:35.460  3366  3366 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 11:31:35.460  3366  3366 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 11:31:35.460  3366  3366 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 11:31:35.460  3366  3366 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 11:31:35.460  6923  6923 D elm:15183: ElmAgentService : onCreate()
07-05 11:31:35.460  6923  6955 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-05 11:31:35.460  6923  6955 D elm:15183: MainReceiver.listeningToPackageRemoved()
07-05 11:31:35.460  6923  6955 D elm:15183: MDMBridge.getInstance()
07-05 11:31:35.460  6923  6955 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
07-05 11:31:35.460  3688  6922 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-05 11:31:35.470  6938  6938 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-05 11:31:35.470  6938  6938 D ThemeInfoUtil: isCurrentFestival = false
07-05 11:31:35.470  6923  6955 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
07-05 11:31:35.480  3688  6922 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
07-05 11:31:35.480  5499  5499 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
07-05 11:31:35.480  1014  2957 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
07-05 11:31:35.480  1014  2957 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
07-05 11:31:35.480  6923  6923 D elm:15183: ElmAgentService : onDestroy().
07-05 11:31:35.490  1014  1014 D RCPManagerService: PackageReceiver onReceive()
07-05 11:31:35.490  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-05 11:31:35.490  1014  2951 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
07-05 11:31:35.490  3688  3688 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
07-05 11:31:35.490  1014  2951 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
07-05 11:31:35.490  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-05 11:31:35.490  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-05 11:31:35.490  1014  2951 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.490  1014  2951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 11:31:35.490  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
07-05 11:31:35.490  1014  2951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
07-05 11:31:35.490  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
07-05 11:31:35.500  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
07-05 11:31:35.500  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
07-05 11:31:35.500  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
07-05 11:31:35.500  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 11:31:35.500  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 11:31:35.500  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 11:31:35.500  1014  1014 V EnterpriseBillingPolicy: uID is 10155
07-05 11:31:35.500  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 11:31:35.500  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 11:31:35.500  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-05 11:31:35.500  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 11:31:35.500  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 11:31:35.500  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 11:31:35.500  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 11:31:35.510  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 11:31:35.510  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-05 11:31:35.510  1014  1014 V EnterpriseBillingPolicy: uID is 10155
07-05 11:31:35.510  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 11:31:35.510  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 11:31:35.510  1014  2746 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-05 11:31:35.510  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-05 11:31:35.510  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 11:31:35.510  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 11:31:35.510  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 11:31:35.510  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 11:31:35.520  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
07-05 11:31:35.520  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=24_task.xml
07-05 11:31:35.520  5951  5951 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
07-05 11:31:35.520  5951  5951 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
07-05 11:31:35.520  5951  5951 I TapandpayWidget:Utils: Clear T&P info.
07-05 11:31:35.520  5951  5951 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
07-05 11:31:35.530  5888  5888 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-05 11:31:35.530  5888  5888 I PCWCLIENTTRACE_PushUtil: sales region : global
07-05 11:31:35.530  5888  5888 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-05 11:31:35.530  5888  5888 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-05 11:31:35.540  6140  6140 D Compatibility: onReceive() it will make start service
07-05 11:31:35.540  1014  1678 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
07-05 11:31:35.540  1014  1678 D ActivityManager: com.sec.enterprise.knox.cloudmdm.smdms, Starting
07-05 11:31:35.540  1014  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.540  1014  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.540  1014  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.540  1014  1678 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.550  6959  6959 E Zygote  : MountEmulatedStorage()
07-05 11:31:35.550  6959  6959 E Zygote  : v2
07-05 11:31:35.550  6959  6959 I libpersona: KNOX_SDCARD checking this for 10160
07-05 11:31:35.550  6959  6959 I libpersona: KNOX_SDCARD not a persona
07-05 11:31:35.550  6959  6959 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 11:31:35.550  6959  6959 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 11:31:35.560  1014  1678 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6959 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
07-05 11:31:35.560  6959  6959 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 11:31:35.560  1014  2956 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-05 11:31:35.560  1014  2956 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
07-05 11:31:35.560  1014  2956 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.560  1014  2956 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 11:31:35.560  1014  2956 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
07-05 11:31:35.570  1014  1476 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
07-05 11:31:35.570  1014  1476 D ActivityManager: com.android.keychain, Starting
07-05 11:31:35.580  6140  6970 D Compatibility: onHandleIntent()
07-05 11:31:35.580  6140  6970 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
07-05 11:31:35.580  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.580  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.580  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.580  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.580  6140  6970 D Compatibility: found: 2
07-05 11:31:35.580  6140  6970 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-05 11:31:35.580  6140  6970 D Compatibility: skipping ResolveInfo{2a21dc6a com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-05 11:31:35.580  6140  6970 D Compatibility: considering ResolveInfo{258f555b com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-05 11:31:35.580  6140  6970 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
07-05 11:31:35.590  6959  6959 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 11:31:35.590  6959  6959 D ActivityThread: Added TimaKeyStore provider
07-05 11:31:35.590  6975  6975 E Zygote  : MountEmulatedStorage()
07-05 11:31:35.590  6975  6975 E Zygote  : v2
07-05 11:31:35.590  6975  6975 I libpersona: KNOX_SDCARD checking this for 1000
07-05 11:31:35.590  6975  6975 I libpersona: KNOX_SDCARD not a persona
07-05 11:31:35.600  6140  6970 D Compatibility: enabling receiver ResolveInfo{96b41f8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
07-05 11:31:35.600  6975  6975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 11:31:35.600  1014  1476 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6975 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
07-05 11:31:35.600  6975  6975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 11:31:35.600  6975  6975 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 11:31:35.610  6140  6970 D Compatibility: enabling receiver ResolveInfo{2e94d6d1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
07-05 11:31:35.630  1014  1476 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-05 11:31:35.630  1014  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-05 11:31:35.630  1014  1476 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.630  1014  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:31:35.630  1014  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
07-05 11:31:35.630  6140  6970 D Compatibility: enabling receiver ResolveInfo{25795536 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
07-05 11:31:35.630  6975  6975 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 11:31:35.630  6975  6975 D ActivityThread: Added TimaKeyStore provider
07-05 11:31:35.640  1014  1055 I art     : Explicit concurrent mark sweep GC freed 20020(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 4.550ms total 315.447ms
07-05 11:31:35.640  6140  6970 D Compatibility: enabling receiver ResolveInfo{a63ec37 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
07-05 11:31:35.650  6157  6990 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-05 11:31:35.660  6959  6959 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
07-05 11:31:35.660  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-05 11:31:35.660  1014  1026 D ActivityManager: com.sec.spp.push, Starting
07-05 11:31:35.670  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.670  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.670  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.670  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.670  6140  6970 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
07-05 11:31:35.680  6991  6991 E Zygote  : MountEmulatedStorage()
07-05 11:31:35.680  6991  6991 E Zygote  : v2
07-05 11:31:35.680  6991  6991 I libpersona: KNOX_SDCARD checking this for 10035
07-05 11:31:35.680  6991  6991 I libpersona: KNOX_SDCARD not a persona
07-05 11:31:35.680  6991  6991 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 11:31:35.680  6991  6991 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 11:31:35.680  6991  6991 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-05 11:31:35.690  1014  1026 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6991 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 11:31:35.700  6959  6959 D [0]UMC:UMCContentProvider: @onCreate
07-05 11:31:35.700  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-05 11:31:35.700  1014  1026 D ActivityManager: com.samsung.android.intelligenceservice, Starting
07-05 11:31:35.700  6959  6959 D [0]UMC:Core: onCreate(): 
07-05 11:31:35.700  6959  6959 D [0]UMC:Core: @isManagedProfileUser
07-05 11:31:35.700  6959  6959 D [0]UMC:Core: userId: 0
07-05 11:31:35.700  6959  6959 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
07-05 11:31:35.700  6959  6959 D [0]UMC:Core: userInfo.isManagedProfile() : false
07-05 11:31:35.700  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.700  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.700  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.700  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.720  7006  7006 E Zygote  : MountEmulatedStorage()
07-05 11:31:35.720  7006  7006 E Zygote  : v2
07-05 11:31:35.720  7006  7006 I libpersona: KNOX_SDCARD checking this for 10003
07-05 11:31:35.720  7006  7006 I libpersona: KNOX_SDCARD not a persona
07-05 11:31:35.720  1014  1026 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7006 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
07-05 11:31:35.730  7006  7006 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 11:31:35.730  6975  6975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
07-05 11:31:35.730  6991  6991 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 11:31:35.730  1014  1026 I ActivityManager: Killing 5734:com.google.android.gms:car/u0a12 (adj 15): empty #31
07-05 11:31:35.730  6991  6991 D ActivityThread: Added TimaKeyStore provider
07-05 11:31:35.730  1014  1232 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
07-05 11:31:35.730  1014  1232 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
07-05 11:31:35.730  1014  1232 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.730  1014  1232 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 11:31:35.730  1014  1232 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
07-05 11:31:35.740  7006  7006 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 11:31:35.740  7006  7006 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 11:31:35.750  1014  1476 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
07-05 11:31:35.750  1014  1476 D ActivityManager: com.samsung.android.app.mirrorlink, Starting
07-05 11:31:35.750  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.750  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.750  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.750  1014  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 11:31:35.760  6959  6959 D [0]UMC:DeviceInfo: USA==US==
07-05 11:31:35.770  7018  7018 E Zygote  : MountEmulatedStorage()
07-05 11:31:35.770  7018  7018 I libpersona: KNOX_SDCARD checking this for 1000
07-05 11:31:35.770  7018  7018 E Zygote  : v2
07-05 11:31:35.770  7018  7018 I libpersona: KNOX_SDCARD not a persona
07-05 11:31:35.770  7018  7018 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-05 11:31:35.770  7018  7018 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-05 11:31:35.770  7018  7018 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 11:31:35.770  7006  7006 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 11:31:35.780  7006  7006 D ActivityThread: Added TimaKeyStore provider
07-05 11:31:35.780  1014  1476 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7018 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
07-05 11:31:35.780  1014  2958 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-05 11:31:35.780  1014  2958 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.780  1014  2958 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:31:35.780  1014  2958 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
07-05 11:31:35.800  1014  2956 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 11:31:35.800  1014  2956 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-05 11:31:35.800  1014  2956 W ActivityManager: userId = 0, bbcId = -10000
07-05 11:31:35.800  1014  2956 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 11:31:35.800  1014  2956 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms

```
